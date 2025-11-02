---
icon: book-open
---

# Simplifying Code with Functions

{% hint style="warning" %}
## IMPORTANT

Make a copy of your TinkerCAD file from the 'Music with a Piezo Buzzer' for this particular task.
{% endhint %}

### 5.0 Simplifying Code with Functions

{% embed url="https://drive.google.com/file/d/1Xq-n9CAPbB8bWIqfazQPLXf0e9ob5CqM/view?usp=sharing" %}

{% hint style="info" %}
## Functions

Functions are reusable blocks of code designed to perform a specific task. They help in simplifying code by reducing repetition and improving readability. A function can take inputs, called parameters, and may return a result or simply execute actions. By using functions, you can write more organised and maintainable code.

In our pseudocode algorithms, they are called **subroutines.**
{% endhint %}

### Student Activities

1. Make a duplicate of your Music + Button program (IF statements). Complete all activities in the above video.



2.  Make a duplicate of your Traffic Light System (potentiometer). Add three functions to your traffic light system (one for IF, one of ELIF, one for ELSE).&#x20;

    1. Plan this out with a pseudocode algorithm first
    2. Implement this in the copied TinkerCAD project


3. **Extension:** Program a button and potentiometer that plays a different note each time you press the button depending on where the potentiometer is turned to. Make it play at least one octave (C, C#, D, D#, E, F, F#, G, G#, A, A#, B, C).
   1. Plan this out with pseudocode first
   2. Implement this in a new TinkerCAD project.



#### Example of Pseudocode for Functions

```
START music
    PLAY TONE buzzer AT 440Hz FOR 500ms
    STOP TONE buzzer
END music


BEGIN

    SET buzzer TO 8
    SET button TO 2
    SET buttonState to 0

    SET pinMode(buzzer) TO OUTPUT
    SET pinMode(button) TO INPUT

    WHILE TRUE DO
        GET buttonState FROM button
        IF buttonState = PRESSED THEN
            CALL music
        ENDIF
    ENDWHILE
END
```
