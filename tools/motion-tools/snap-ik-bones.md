# Snap IK Bones

## What It Does

Snap IK Bones finds IK bones and their target bones, then makes the IK tracks follow the target positions across the animation.

## Detection Source

Choose:

- **Preview Skeletal Mesh**
- **Skeleton**

## Options

### Use Virtual Bones

Allows Virtual Bone relationships to participate in automatic target detection.

### Include Root Bone IK

Allows the immediate parent of an automatically detected leaf IK bone to be considered as an IK candidate. The Skeleton root itself remains excluded from automatic IK detection.

## Workflow

1. Choose the Detection Source.
2. Set the detection options.
3. Click **Detect IK Bones**.
4. Review each detected **IK Bone / Target Bone** pair.
5. Change the detected pairs when required.
6. Use **+ Add IK Pair** to create a pair manually.
7. Remove unwanted pairs or use **Remove All IK Pairs**.
8. Click **Snap** for one pair or **Snap all IK Bones** for all prepared pairs.

## Virtual Bone Limitation

Virtual Bones cannot receive normal animation tracks. If the selected IK bone or target is virtual when a real animatable bone is required, select the corresponding real Skeleton bone instead.
