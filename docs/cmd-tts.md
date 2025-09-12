---
tags:
  - command
---

# /tts

## Syntax

<!--cmd-syntax-start-->
```eqcommand
/tts loglevel | reload | say | sayxml | speed | voice | volume [argument]
```
<!--cmd-syntax-end-->

## Description

<!--cmd-desc-start-->
Primarily the command /tts say is used to speak text. Other commands are primarily for settings, which is best controlled via the settings menu.
<!--cmd-desc-end-->

```txt
Usage:
    /tts loglevel|reload|say|sayxml|speed|voice|volume [argument]
Available Verbs:
    LogLevel - Set the log level (default is 'info')
    Reload - Reload the settings from the ini file
    Say - Speak a line of text
    SayXML - Speak a line of text using XML formatting for pattern changes
    Speed - Set the speech speed (-10 to 10)
    Voice - Change the voice (must be installed)
    Volume - Set the volume of speech (0 to 100)
  NOTE: All settings are available in the settings menu.
Example:
    /tts say Some people juggle geese.
```

!!! example "Examples"
    - `/tts say If you give a man a fire he's warm for a day.  But if you set a man on fire, he's warm for the rest of his life.`
    - `/tts say Some people juggle geese.`