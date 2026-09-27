# Combine Animation Sequences

## What It Does

Creates a **new Animation Sequence** by placing Animation Sequence B after Animation Sequence A.

The source sequences are not modified.

## Source Sequences

Choose:

- **Sequence A** — the first animation.
- **Sequence B** — the animation placed after A.

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

- **Bone Tracks (required)**
- **Curves**
- **Continue Root Motion**
- **Notifies**
- **Sync Markers**

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
