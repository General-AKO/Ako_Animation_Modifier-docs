---
icon: falafel
---

# Snap IK Bones

## What It Does

Snap IK Bones finds IK bones and their target bones, then makes the IK tracks follow the target positions across the animation.

#### 🟢 **VIDEO TUTORIAL:**

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2Fgm2JShwf3pZWK6OK8X0V%2Fik_snap.mp4?alt=media&token=94c08935-9b63-4aa2-ae88-cdfd6affebde" %}

## Detection Source

Choose:

* **Preview Skeletal Mesh**

#### &#x20;                <mark style="color:$info;">**or**</mark>

* **Skeleton**

## Options

### Use Virtual Bones

Allows Virtual Bone relationships to participate in automatic target detection.

### Include Root Bone IK

Allows the immediate parent of an automatically detected leaf IK bone to be considered as an IK candidate. The Skeleton root itself remains excluded from automatic IK detection.

## Workflow

1. Choose the Detection Source.
2. Set the detection options.
3. Click **Detect IK Bones**.
4. <mark style="color:$danger;">**Review**</mark> each detected **IK Bone / Target Bone** pair.
5. Change the detected pairs when required.
6. Use **+ Add IK Pair** to create a pair manually.
7. Remove unwanted pairs or use **Remove All IK Pairs**.
8. Click **Snap** for one pair or **Snap all IK Bones** for all prepared pairs.

## <mark style="color:$warning;">Virtual Bone Limitation</mark>

Virtual Bones cannot receive normal animation tracks. If the selected IK bone or target is virtual when a real animatable bone is required, select the corresponding real Skeleton bone instead.

&#x20;-—The **IK Bone / Target Bone** pairs are detected <mark style="color:$success;">**automatically**</mark> and are correct in most cases. However, some rigs may use different bone setups, so it is <mark style="color:$danger;">**important**</mark> to <mark style="color:$danger;">**review**</mark> the detected pairs and <mark style="color:$danger;">**adjust**</mark> or <mark style="color:$danger;">**remove**</mark> any entries when needed.

