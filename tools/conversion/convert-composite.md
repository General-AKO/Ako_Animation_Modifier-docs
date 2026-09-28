---
icon: reply
---

# Convert Animation Composite to Animation Sequence

## <mark style="background-color:$success;">What It Does</mark>

Bakes the selected **Animation Composite** into a **new Animation Sequence**.

The source Animation Composite is not modified.

<figure><img src="../../.gitbook/assets/Cap 2026-09-28 19-16-13.jpg" alt=""><figcaption></figcaption></figure>

## Source Information

The tool shows the active Skeleton, Preview Mesh, and animation length.

## Sampling Rate

Choose 30, 50, or 60 FPS.

## Destination

Choose the output Animation Sequence with **Choose Output...**.

## Workflow

1. Open an Animation Composite.
2. Open **Convert Composite** from ako Tools.
3. Confirm the source information.
4. Choose the sampling rate.
5. Choose the output destination.
6. Click **Bake New Animation Sequence**.

<mark style="color:$warning;">**Note:**</mark> `Direct Composite Evaluation` currently writes the evaluated **Bone Transforms** and copies **Notifies** and **Sync Markers**. However, **Curves are&#x20;**<mark style="background-color:$warning;">**not yet evaluated**</mark>**&#x20;and written frame-by-frame**.

## Common Problems

The operation may fail when the Composite, Skeleton, output path, output asset, Skeleton hierarchy, bone container, or output bone tracks are invalid or unavailable.
