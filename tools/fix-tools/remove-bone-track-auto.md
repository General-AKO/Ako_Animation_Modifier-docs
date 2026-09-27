# Remove Bone Track Auto

## What It Does

Remove Bone Track Auto analyzes the animation and its Skeletal Mesh setup to find bone tracks driven by Post Process Animation Blueprints.

Detection is provided for convenience. The detected list remains editable before removal.

## Options

### Include Driven Bones

Includes directly driven bones detected by the analysis.

### Include Parent Driven Bones

Also includes the immediate parents of detected driven bones.

## Workflow

1. Enable the detection options you want.
2. Click **Analyze / Find Driven Bones**.
3. Review the detected bones and their detection source.
4. Remove unwanted candidates from the pending list using **X**.
5. Click **Remove Detected Bone Tracks**.

## Important

Detection alone does not remove anything. Review the detected list before applying the removal.

The analysis may report how many Skeletal Meshes, Post Process Animation Blueprints, Pose Driver nodes, and Bone Driven Controller nodes were scanned or found.
