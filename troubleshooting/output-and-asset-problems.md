---
icon: file-export
---

# Output and Asset Problems

## <mark style="color:$warning;">A New Asset Could Not Be Created</mark>

When a tool creates a new Animation Sequence, check that:

* the output path is valid
* the asset name is valid
* an asset with the same name does not already exist
* the source animation contains the required usable data

## <mark style="color:$warning;">An Existing Source Asset Was Changed Unexpectedly</mark>

The following tools intentionally create new Animation Sequences rather than replacing their source:

* Combine Animation Sequences
* Layered Blend Per Bone
* Convert Animation Composite to Animation Sequence

For other tools, the current Animation Sequence can be modified directly.

## Output Writes Fail

Messages such as **Failed to create**, **Failed to write**, or **The animation could not be written** mean the tool passed its earlier input checks but Unreal could not complete the requested asset-data operation.

When reporting the issue, include the complete message, including any asset, bone, curve, or track name shown in it.
