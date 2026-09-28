---
icon: swap
---

# Snap Animation To Floor

## <mark style="background-color:$success;">What It Does</mark>

Snap Animation To Floor moves the selected height bone so the lowest skinned mesh vertex reaches the floor, with an optional vertical correction.<br>

#### 🟢 **VIDEO TUTORIAL:**

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FKBo8QiglWaJDuZFIv4R6%2Fsnap_to_floor.mp4?alt=media&token=f7686835-cd8d-4c9a-81ed-9af10679e679" %}

## <mark style="color:cyan;">Height Bone</mark>

Choose the bone that receives the vertical correction. The tool can detect a suitable height bone automatically, or you can select another bone from the Skeleton.

## <mark style="color:cyan;">Mesh Sampling</mark>

Choose the **LOD used for vertex sampling**.

Lower LOD numbers normally represent more detailed mesh data. **LOD 0** is generally the highest-detail option and is typically the most accurate for floor-contact sampling.

## <mark style="color:blue;">Frame Mode</mark>

Choose how the frames to process are defined:

* <mark style="color:violet;">**All Frames**</mark>\
  &#x20; 1-  Selects all frames by **default**. You can adjust the range to process fewer frames, but only **one continuous range** can be selected.



* &#x20;<mark style="color:pink;">**Selected Frame Ranges**</mark>\
  &#x20; Allows you to define **multiple separate frame ranges**. For example, you can process frames <mark style="color:$primary;">**10–20**</mark> and <mark style="color:$primary;">**40–60**</mark>, leaving the frames between them <mark style="color:$success;">**untouched**</mark>. Each range can be defined independently, without requiring the ranges to be continuous.

## <mark style="color:blue;">Vertical Correction</mark>

Use the vertical correction setting when the floor-contact result needs an additional offset.

Click **Snap To Floor** to apply the operation.

## Common Problems

The operation may fail when the Animation Sequence, selected bone, Preview Skeletal Mesh, LOD, or selected frame range is invalid or cannot be evaluated.
