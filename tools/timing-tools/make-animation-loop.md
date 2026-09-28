# Make Animation Loop

## What It Does

Make Animation Loop adds new frames to the end of an Animation Sequence to create an end-to-start transition back to frame 0.

The original last frame remains unchanged. The added frames transition toward frame 0, and the final added frame is frame 0.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FQEpFo2hEnu5fnvKkQSNQ%2Floop.mp4?alt=media&token=55db4b3e-95e0-4dd6-9cc9-5987024ed479" %}

## Frames to Add

Choose how many transition frames should be added.

## Interpolation

Available modes:

* Auto
* User
* Break
* Linear
* Constant

## Transition Curve

The curve controls how the transition progresses:

* **0.0 = Last Frame**
* **1.0 = Frame 0**

The middle control points shape the transition between those endpoints.

## Workflow

1. Set **Frames to Add**.
2. Choose the interpolation mode.
3. Adjust the transition curve when needed.
4. Click **Apply Loop Transition**.

Use **Reset Curve** to restore the default transition shape.
