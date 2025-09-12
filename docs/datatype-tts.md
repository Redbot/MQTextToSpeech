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
### {{ renderMember(type='string', name='Voice') }}

:   Which voice is being used (additional voices must be installed)

### {{ renderMember(type='int', name='Volume') }}

:   The current set volume

### {{ renderMember(type='int', name='Speed') }}

:   The speed of the speech

<!--dt-members-end-->

## Examples
<!--dt-examples-start-->
- `/tts say The current voice is ${TTS.Voice}.`
<!--dt-examples-end-->

<!--dt-linkrefs-start-->
[int]: ../macroquest/reference/data-types/datatype-int.md
[string]: ../macroquest/reference/data-types/datatype-string.md
<!--dt-linkrefs-end-->
