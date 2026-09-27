# Make Animation In Place

## What It Does

Make Animation In Place prepares an animation to become In Place while preserving the required Pelvis rotation information through a staged workflow.

## Stage 1

The original Pelvis local rotations are saved for all animation frames. No animation data is modified during this stage.

## Stage 2

The Pelvis location is adjusted so the animation becomes In Place.

## Stage 3

The Pelvis rotations saved in Stage 1 are applied back to the animation.

## Important

The stages remain locked until the previous required stage has completed. Changing the Root or Pelvis selection after Stage 1 requires the initial stage to be run again.
