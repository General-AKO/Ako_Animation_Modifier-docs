---
icon: reflect-horizontal
---

# Mirror Animation

## <mark style="background-color:$success;">What It Does</mark>

Mirror Animation bakes Unreal's animation mirroring setup directly into the current Animation Sequence.

#### 🟢 **VIDEO TUTORIAL:**

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FCvgcVNwnFzyEnxfts80J%2Fmirore.mp4?alt=media&token=840e4b99-f2fd-4f8a-ab93-5b66179173d6" %}

## Mirror Data Source

Choose the mirror mapping used to determine how elements are mirrored:

* <mark style="color:blue;">**Auto**</mark>\
  Automatically uses the appropriate Mirror Data Table available for the animation.
* <mark style="color:blue;">**Custom Mirror Data Table**</mark>\
  Allows you to select a specific Mirror Data Table to use for the operation.

## Mirror Axis

* Choose the axis used for the mirroring operation:

&#x20;            Choose X, Y, or Z.

## <mark style="color:$success;">Mirror Support:</mark>

The tool <mark style="background-color:$success;">**supports**</mark> mirroring <mark style="color:blue;">**Bones**</mark>**,&#x20;**<mark style="color:blue;">**Animation Curves**</mark>**,**<mark style="color:blue;">**Animation Notifies**</mark>,<mark style="color:blue;">**Mirror Sync Markers**</mark>,  <mark style="color:blue;">**Mirror Root Motion**</mark> — <mark style="color:$success;">**allowing these elements to be mirrored together during the operation**</mark>.\
each type can be <mark style="color:$success;">**mirrored independently**</mark>. This allows you to <mark style="color:$primary;">**mirror only**</mark> the required data without mirroring the entire animation.

### <mark style="color:cyan;">Mirror Bones</mark>

Mirrors bone transforms using the relationships defined by the Mirror Data Table.

### <mark style="color:cyan;">Mirror Curves</mark>

Mirrors float animation curves using the curve relationships in the Mirror Data Table.

### <mark style="color:cyan;">Mirror Notifies</mark>

Renames animation notify events to their mirrored names.

### <mark style="color:cyan;">Mirror Sync Markers</mark>

Renames authored sync markers to their mirrored names while preserving their timing.

### <mark style="color:cyan;">Mirror Root Motion</mark>

Includes the Root transform in the mirror operation.

### <mark style="color:cyan;">Reverse the Original Direction</mark>

After successful Root Motion mirroring, applies the same +180° World Reverse Direction operation used by the Root Motion orientation workflow. When Root Motion mirroring is disabled, this option is automatically enabled.

