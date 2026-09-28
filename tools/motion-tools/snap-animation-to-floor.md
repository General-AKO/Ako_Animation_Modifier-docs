# Snap Animation To Floor

## What It Does

Snap Animation To Floor moves the selected height bone so the lowest skinned mesh vertex reaches the floor, with an optional vertical correction.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FKBo8QiglWaJDuZFIv4R6%2Fsnap_to_floor.mp4?alt=media&token=f7686835-cd8d-4c9a-81ed-9af10679e679" %}

## Height Bone

Choose the bone that receives the vertical correction. The tool can detect a suitable height bone automatically, or you can select another bone from the Skeleton.

## Mesh Sampling

Choose the **LOD used for vertex sampling**.

Lower LOD numbers normally represent more detailed mesh data. **LOD 0** is generally the highest-detail option and is typically the most accurate for floor-contact sampling.

## Frame Mode

Choose:

* **All Frames**
* **Selected Frame Ranges**

When using selected ranges, define the Start Frame and End Frame for each range.

## Vertical Correction

Use the vertical correction setting when the floor-contact result needs an additional offset.

Click **Snap To Floor** to apply the operation.

## Common Problems

The operation may fail when the Animation Sequence, selected bone, Preview Skeletal Mesh, LOD, or selected frame range is invalid or cannot be evaluated.
