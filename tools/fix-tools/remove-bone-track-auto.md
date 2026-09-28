---
icon: bone-break
---

# Remove Bone Track Auto

## <mark style="background-color:$success;">What It Does</mark>

Remove Bone Track Auto analyzes the animation and its Skeletal Mesh setup to find <mark style="color:$success;">**bone tracks driven**</mark> by Post Process Animation Blueprints.

Detection is provided for convenience. The detected list remains editable before removal.

{% embed url="https://files.gitbook.com/v0/b/gitbook-x-prod.appspot.com/o/spaces%2F6sAtdsTWUp3EFn3eOTvl%2Fuploads%2FfPMT0RaDuKLQdeWL6oJ9%2Ffix_noise.mp4?alt=media&token=fc5db325-ae66-4154-90aa-1cac528d71ae" %}

## Options

### <mark style="color:cyan;">Include Driven Bones</mark>

Includes directly driven bones detected by the analysis.\
\
<mark style="color:orange;">**In most cases, enabling this option is enough. However, for more extreme cases like the one shown in the video, it is recommended to enable the next option as well:**</mark>

### <mark style="color:cyan;">Include Parent Driven Bones</mark>

Also includes the immediate parents of detected driven bones.\
\
<mark style="color:$warning;">**Enabling this option may also detect some main bones that affect the animation, such as**</mark><mark style="color:$warning;">**&#x20;**</mark><mark style="color:$warning;">**`Hand_R`**</mark><mark style="color:$warning;">**. These can be easily identified and should be removed from the selection.**</mark>

## Workflow

1. Enable the detection options you want.
2. Click **Analyze / Find Driven Bones**.
3. <mark style="color:$danger;">**Review**</mark> the detected bones and their detection source before anything.
4. Remove unwanted candidates from the pending list using <mark style="color:$danger;">**`X`**</mark>.
5. Click **Remove Detected Bone Tracks**.

## Important

* Review the detected list before applying the removal.

\
\- The analysis may report how many Skeletal Meshes, Post Process Animation Blueprints, Pose Driver nodes, and Bone Driven Controller nodes were scanned or found.
