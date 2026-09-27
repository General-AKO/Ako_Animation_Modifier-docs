# Errors and Messages

## No Animation Sequence is available

The current tool requires an Animation Sequence, but none is available.

<mark style="color:$success;">**Fix**</mark>**:** Open a valid Animation Sequence in the Animation Editor and run the tool again.

## The Animation Sequence has no Skeleton

The Animation Sequence does not have a valid Skeleton assigned.

<mark style="color:$success;">**Fix**</mark>**:** Verify the Skeleton assigned to the Animation Sequence.

## The Animation Sequence data model is unavailable

The tool needs Unreal's Animation Data Model, but it is not available for the current asset.

<mark style="color:$success;">**Fix**</mark>**:** Reopen the asset and confirm that it is a valid Animation Sequence. If the message persists, the asset may not be in a usable state.

## The selected bone does not exist in the Skeleton

A Root, Pelvis, height, IK, target, or branch bone selected by the tool is not present in the current Skeleton.

<mark style="color:$success;">**Fix**</mark>**:** Re-select the bone from the current Skeleton.

## Root Bone and Pelvis Bone must be different bones

The same bone was selected for both roles.

<mark style="color:$success;">**Fix:**</mark> Select a separate Root and Pelvis bone.

## The selected Pelvis must be a descendant of the selected Root

The Skeleton hierarchy does not place the selected Pelvis below the selected Root.

<mark style="color:$success;">**Fix:**</mark> Select bones that follow the intended Root → Pelvis relationship.

## The two Animation Sequences must use the same Skeleton

The source animations are not compatible for the requested per-bone layered operation.

<mark style="color:$success;">**Fix:**</mark> Use Animation Sequences that share the same Skeleton.

## The output package already exists

The chosen destination already contains an asset with the same path or name.

<mark style="color:$success;">**Fix**</mark>**:** Choose a different destination or asset name.

## The selected output location is not a valid Unreal asset path

The destination is not a valid Content Browser asset path.

<mark style="color:$success;">**Fix**</mark>**:** Choose the output location through the asset picker or use a valid Unreal asset path.

## No bone tracks were removed

No valid bone tracks matched the removal request.

<mark style="color:$success;">**Fix**</mark>**:** Check the selected bones or run the automatic detection again.

## No IK bone pairs were detected

Automatic detection did not find usable IK/target pairs with the current settings.

<mark style="color:$success;">**Fix**</mark>**:** Change the Detection Source or detection options, or add a pair manually.

## The IK bone is a Virtual Bone

Virtual Bones cannot receive normal animation tracks.

<mark style="color:$success;">**Fix**</mark>**:** Select a real, animatable IK bone.

## The target bone is a Virtual Bone

The target selected for the IK operation is not a real Skeleton bone.

<mark style="color:$success;">**Fix**</mark>**:** Select the actual Skeleton bone that should provide the target location.

## Enable at least one mirror option before running the tool

No mirror operation is enabled.

<mark style="color:$success;">**Fix**</mark>**:** Enable at least one Mirror option.

## No bone tracks are available

The requested operation has no compatible bone tracks to process.

<mark style="color:$success;">**Fix**</mark>**:** Verify the Skeleton and the Animation Sequence data being processed.

## No bone tracks covered by the Mirror Data Table were found

The selected Mirror Data Table does not provide compatible relationships for the current animation tracks.

<mark style="color:$success;">**Fix**</mark>**:** Verify the Skeleton, Mirror Data Table, and Animation Sequence.

## Select at least one transfer axis

A Root Motion or In Place transfer operation was started without a translation axis.

<mark style="color:$success;">**Fix**</mark>**:** Enable at least one of X, Y, or Z.

## Select a valid sampling rate: 30, 50, or 60 FPS

A bake or conversion tool does not currently have a valid sampling rate.

<mark style="color:$success;">**Fix**</mark>**:** Select 30, 50, or 60 FPS.

## Invalid range

A selected frame range is not valid for the current Animation Sequence.

<mark style="color:$success;">**Fix**</mark>**:** Make sure the start and end frames are valid and inside the animation's frame range.
