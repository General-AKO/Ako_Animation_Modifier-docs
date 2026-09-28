# Mirror Animation

## What It Does

Mirror Animation bakes Unreal's animation mirroring setup directly into the current Animation Sequence.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FCvgcVNwnFzyEnxfts80J%2Fmirore.mp4?alt=media&token=840e4b99-f2fd-4f8a-ab93-5b66179173d6" %}

## Mirror Data Source

Choose:

* **Auto**
* **Custom Mirror Data Table**

## Mirror Axis

Choose X, Y, or Z.

## Options

### Mirror Bones

Mirrors bone transforms using the relationships defined by the Mirror Data Table.

### Mirror Curves

Mirrors float animation curves using the curve relationships in the Mirror Data Table.

### Mirror Notifies

Renames animation notify events to their mirrored names.

### Mirror Sync Markers

Renames authored sync markers to their mirrored names while preserving their timing.

### Mirror Root Motion

Includes the Root transform in the mirror operation.

### Reverse the Original Direction

After successful Root Motion mirroring, applies the same +180° World Reverse Direction operation used by the Root Motion orientation workflow. When Root Motion mirroring is disabled, this option is automatically enabled.

## Requirements

* A valid Animation Sequence and Skeleton
* A valid Mirror Data Table when using the custom source
* At least one mirror operation enabled
* Compatible mirror relationships for the content being processed
