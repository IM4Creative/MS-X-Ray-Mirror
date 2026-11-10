# X-Ray Mirror, Makerspace edition

A camera mirror that runs in your browser.

- **Stand close** (an arm's length): see the skull, brain and face muscles inside your head.
- **Step back** (about 8 ft): see your whole skeleton, heart, lungs and gut.
- **Hold up a hand** to see its bones.

**Try it:** https://im4creative.github.io/MS-X-Ray-Mirror/

Press **Start camera** and allow it. Use Chrome or Edge on a computer with a webcam.

## Your picture stays with you

Everything runs in your browser. Nothing from the camera is saved or sent anywhere. The page loads its own files from this site and nothing else.

## It is a model, not a scan

The anatomy is a real 3D dataset of one adult, scaled and pinned to your head and body by face, hand and pose trackers. It shows where structures typically sit. It is not a scan of you and not a medical tool.

## Keys

`1` Bones · `2` Organs · `3` Muscles · `4` Everything · `N` names · `F` full screen · `S` settings

## Credits and licenses

- **Anatomy models:** BodyParts3D, © The Database Center for Life Science, licensed under [CC Attribution-Share Alike 2.1 Japan](https://creativecommons.org/licenses/by-sa/2.1/jp/deed.en). Models were simplified and re-aligned. The simplified mesh data in this page is shared under the same license.
- **Head engine:** built on the original **X-Ray Mirror**, [shared on r/ClaudeAI](https://www.reddit.com/r/ClaudeAI/comments/1xstews/i_built_a_webcam_xray_mirror_with_claude_fable_52/). Thank you to its author. The idea, the head and hand anatomy and the face-fitting engine are theirs.
- **Makerspace edition:** page design, the walk-up tour, whole-body bones and organs, the far-away skull.
- **[three.js](https://threejs.org/)** (MIT license) and **[MediaPipe](https://developers.google.com/mediapipe)** (Apache 2.0 license). License files are in `vendor/`.
