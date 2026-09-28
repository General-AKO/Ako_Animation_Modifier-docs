# Combine Animation Sequences

## What It Does

Creates a **new Animation Sequence** by placing Animation Sequence B after Animation Sequence A.

The source sequences are not modified.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FRNeJTgSU0RK2rNx0buzU%2Fcombine%20aniamtion.mp4?alt=media&token=e386e181-efbb-489e-9a3d-0158e78e47c9" %}

## Source Sequences

Choose:

* **Sequence A** — the first animation.
* **Sequence B** — the animation placed after A.

Both must be valid Animation Sequences with usable Skeleton information and a length greater than zero.

## Output

Choose the destination asset through **Choose Output...**.

The tool does not overwrite an existing output package.

## Combine Method

### Standard Append

Places B directly after A.

### Smooth Transition

Creates a transition between A and B using the selected number of transition frames.

## Data Options

* **Bone Tracks (required)**
* **Curves**
* **Continue Root Motion**
* **Notifies**
* **Sync Markers**

## Sampling Rate

Choose 30, 50, or 60 FPS.

## Workflow

1. Select Sequence A.
2. Select Sequence B.
3. Choose the output asset.
4. Select the combine method.
5. Set transition frames when using Smooth Transition.
6. Choose the data options.
7. Choose the sampling rate.
8. Click **Combine into New Animation Sequence**.
