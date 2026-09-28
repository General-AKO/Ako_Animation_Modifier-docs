---
icon: object-exclude
---

# Combine Animation Sequences

## <mark style="background-color:$success;">What It Does</mark>

Creates a **new Animation Sequence** by placing Animation Sequence B after Animation Sequence A.

<mark style="color:green;">**The source sequences are not modified.**</mark>

#### 🟢 **VIDEO TUTORIAL:**

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FRNeJTgSU0RK2rNx0buzU%2Fcombine%20aniamtion.mp4?alt=media&token=e386e181-efbb-489e-9a3d-0158e78e47c9" %}

## <mark style="color:cyan;">Source Sequences</mark>

Choose:

* **Sequence A** — the first animation.
* **Sequence B** — the animation placed after A.

Both must be valid Animation Sequences with usable Skeleton information and a length greater than zero.

## <mark style="color:cyan;">Output</mark>

Choose the destination asset through **Choose Output...**.

The tool does not overwrite an existing output package.

## <mark style="color:cyan;">Combine Method</mark>

The tool provides **two ways** to combine two animations, depending on whether you want a <mark style="color:$success;">**direct connection**</mark> or a <mark style="color:$success;">**smoother transition.**</mark>

#### <mark style="color:$primary;">Standard Append</mark>

Places animation **B** directly after animation **A**, with <mark style="color:$warning;">**no transition**</mark> between them.

#### <mark style="color:$primary;">Smooth Transition</mark>

Creates a <mark style="color:green;">**smooth transition**</mark> from animation **A** into animation **B** using the selected number of transition frames. This blends the two animations together instead of switching directly from one to the other.

<mark style="color:$warning;">**Tip:**</mark> See the video example for a visual demonstration of the difference between the two modes.

### <mark style="color:cyan;">**Data Options**</mark>

Choose which types of **animation data** should be included when creating the result. Each option can be <mark style="color:$success;">**enabled independently**</mark> depending on what you need to preserve or generate.



* <mark style="color:blue;">**Bone Tracks (required)**</mark> — Includes bone animation data such as position, rotation, and scale keys.
* <mark style="color:blue;">**Curves**</mark> — Includes animation curve data.
* <mark style="color:blue;">**Continue Root Motion**</mark> — Continues the Root Motion movement smoothly from the previous animation.
* <mark style="color:blue;">**Notifies**</mark> — Includes Animation Notifies from the source animations.
* <mark style="color:blue;">**Sync Markers**</mark> — Includes authored Sync Marker data.

### <mark style="color:cyan;">Sampling Rate</mark>

Choose the sampling rate used when generating the resulting animation:

* **30 FPS**
* **50 FPS**
* **60 FPS**

A higher sampling rate can provide more precise animation sampling and smoother results, depending on the source animations.

## <mark style="color:cyan;">Workflow</mark>

1. Select Sequence A.
2. Select Sequence B.
3. Choose the output asset.
4. Select the combine method.
5. Set transition frames when using **Smooth Transition.**
6. Choose the data options.
7. Choose the sampling rate.
8. Click **Combine into New Animation Sequence**.
