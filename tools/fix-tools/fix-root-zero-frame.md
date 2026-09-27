# Fix Root Zero Frame

## What It Does

Fix Root Zero Frame checks the Root at the beginning of the animation and provides a controlled Root/Pelvis correction workflow.

The tool is designed for cases where the Root is not initialized correctly or when motion needs to be reorganized between the Root and Pelvis.

## Stage 1 — Root Initial Position

Choose the **Root Bone** and review the Root position at frame 0.

Click **Check Root Position** to analyze the Root across the animation.

Depending on the analysis, the tool may provide:

- **Apply Additive Layer Fix**
- **Ignore / Continue**
- **Fix Root Position to 0, 0, 0**

The next stage remains locked until the required checks and decisions are resolved.

## Stage 2 — Motion Transfer

Choose:

- Root Bone
- Pelvis Bone
- Transfer axes: X, Y, Z
- Transfer direction: Root → Pelvis or Pelvis → Root
- Transfer method

### Full Motion

Transfers the Pelvis's complete component-space displacement from frame 0.

### Component Space

Transfers Pelvis motion relative to the Root.

## Requirements

- Root and Pelvis must be different bones.
- The Pelvis must be a descendant of the selected Root.
- At least one transfer axis must be selected when the workflow asks for axes.

## Important

This is a staged workflow. Changing the selected Root or Pelvis after the initial analysis can require the first stage to be run again.
