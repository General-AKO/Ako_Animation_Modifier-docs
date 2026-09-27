# FAQ

## Does the plugin replace my source animation?

It depends on the tool. Combine Animation Sequences, Layered Blend Per Bone, and Convert Animation Composite to Animation Sequence create new Animation Sequences. Other editing tools operate on the current Animation Sequence.

## Why does a tool ask me to analyze first?

Analysis-first workflows are designed to let you inspect the detected state before committing the edit.

## Why can I select a bone but nothing changes?

Selecting a bone is usually only preparation. The actual animation edit happens when the tool's final action is run.

## Why does my tool say that two Skeletons are incompatible?

Some tools require the source animations to use the same Skeleton. Use compatible Animation Sequences for those workflows.

## Can Virtual Bones receive animation tracks?

No. The Snap IK Bones workflow requires real animatable Skeleton bones when a track must be written.

## Which sampling rates are available?

The relevant bake/combination tools expose **30, 50, and 60 FPS**.

## What should I include when asking for support?

Include the Unreal Engine version, plugin version, tool name, asset type, exact error/result message, and a short description of what you selected before the problem occurred.
