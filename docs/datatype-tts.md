---
tags:
  - datatype
---
# `TTS`

<!--dt-desc-start-->
Holds several members for MQTextToSpeech
<!--dt-desc-end-->

## Members
<!--dt-members-start-->
/// member | string Voice
Which voice is being used (additional voices must be installed)
///

/// member | int Volume
The current set volume
///

/// member | int Speed
The speed of the speech
///

<!--dt-members-end-->

## Examples
<!--dt-examples-start-->
- `/tts say The current voice is ${TTS.Voice}.`
<!--dt-examples-end-->

<!--dt-linkrefs-start-->
[int]: ../macroquest/reference/data-types/datatype-int.md
[string]: ../macroquest/reference/data-types/datatype-string.md
<!--dt-linkrefs-end-->
