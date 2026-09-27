# Layered Blend Per Bone

## What It Does

Creates a **new Animation Sequence** by baking a selected bone branch from a second animation into the current base animation.

The selected branch contains the selected bone and all of its children.

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
