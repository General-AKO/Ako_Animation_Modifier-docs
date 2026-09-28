# Layered Blend Per Bone

## What It Does

Creates a **new Animation Sequence** by baking a selected bone branch from a second animation into the current base animation.

The selected branch contains the selected bone and all of its children.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FTdjeC3Ov5zivnydlRuKm%2Fblend_per_bone.mp4?alt=media&token=ae6d6f9a-3c84-41a8-88a9-fc1e392165bc" %}

## Requirements

The two Animation Sequences must use the **same Skeleton**.

## Workflow

1. Confirm the current Animation Sequence as the **Base Animation**.
2. Select the **Animation To Blend**.
3. Select the bone branch in the Skeleton Tree.
4. Choose the **Output Path**.
5. Enter the **New Animation Name**.
6. Click **Bake Layered Blend**.

## Common Problems

The operation can be blocked when the source animations, Skeletons, selected bone branch, Animation Data Model, frame rate, or output destination is invalid.
