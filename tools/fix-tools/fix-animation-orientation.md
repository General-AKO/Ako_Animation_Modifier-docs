---
icon: compass
---

# Fix Animation Orientation

## <mark style="background-color:$success;">What It Does</mark>

Fix Animation Orientation rotates the **Root Motion** **translation** path so the animation travels in the required direction.

Use it when the animation moves correctly but its travel direction does not match your intended setup.<br>

#### 🟢 **VIDEO TUTORIAL:**

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FSDSGVumcCqN3jBe2VrcV%2Frot_fix.mp4?alt=media&token=f3bfd532-9ffa-494f-9a5c-0875045dc53a" %}

## Workflow

1. Choose the **Root Local Reference Axis**: Local X, Local Y, or Local Z. Most of the time, it is the <mark style="color:cyan;">**Z Axis**</mark>.
2. Click <mark style="color:$success;">**Analyze Root Motion**</mark><mark style="color:$success;">.</mark>
3. Review the **Direction Preview**.

<figure><img src="../../.gitbook/assets/Cap 2026-09-28 19-35-35.jpg" alt=""><figcaption></figcaption></figure>

1. Set the direction change from **-180° to +180°**.
2. Use a quick alignment button when helpful:

* WHEN YOU Choose the **Alignment Space**: <mark style="color:$success;">**Local**</mark>
  * Align to +X / -X
  * Align to +Y / -Y
* WHEN YOU Choose the **Alignment Space**: <mark style="color:$success;">**World**</mark>
  * Reverse Direction

3. Click **Apply New Direction**.

## Preview

The analysis reports the Original Direction, New Direction, and Offset so you can verify the change before applying it.
