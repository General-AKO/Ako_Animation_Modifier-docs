---
icon: merge
---

# Layered Blend Per Bone

## <mark style="background-color:$success;">What It Does</mark>

Creates a **new Animation Sequence** by baking a selected bone branch from a second animation into the current base animation.

The selected branch contains the selected bone and all of its children.

#### 🟢 **VIDEO TUTORIAL:**

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FTdjeC3Ov5zivnydlRuKm%2Fblend_per_bone.mp4?alt=media&token=ae6d6f9a-3c84-41a8-88a9-fc1e392165bc" %}

## <mark style="color:$danger;">Requirements</mark>

The two Animation Sequences must use the <mark style="color:$warning;">**same Skeleton**</mark>.

### <mark style="color:cyan;">Continue Blend Animation</mark>

**Continue Blend Animation** controls whether the animation used for the blend continues to affect the remaining bones outside the selected Layered Blend Per Bone hierarchy.

When <mark style="color:$success;">**enabled**</mark>, the blend animation <mark style="color:$success;">**continues**</mark> through the unaffected bone hierarchy, helping maintain continuous and consistent motion between the blended and non-blended parts of the animation.

When <mark style="color:$danger;">**disabled**</mark>, The Blend Animation **stops** when it reaches its last frame and holds that final frame for the rest of the animation.

<mark style="color:$primary;">**For example**</mark>, if the original animation is **10 frames** and the Blend Animation is only **3 frames**, disabling this option causes the blended section to play frames **1–3** and then remain on **frame 3** for frames **4–10**.

## Workflow

1. Confirm the current Animation Sequence as the **Base Animation**.
2. Select the **Animation To Blend**.
3. Select the bone branch in the Skeleton Tree.
4. Choose the **Output Path**.
5. Enter the **New Animation Name**.
6. Click **Bake Layered Blend**.

## Common Problems

The operation can be blocked when the source animations, Skeletons, selected bone branch, Animation Data Model, frame rate, or output destination is invalid.
