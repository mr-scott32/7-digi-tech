---
icon: book-open
---

# Music with the Piezo Buzzer

{% hint style="info" %}
## Piezo Buzzer

A piezo buzzer is an electronic device that uses the piezoelectric effect to generate sound. It consists of a thin piezoelectric material that vibrates when an electric signal is applied, producing audible tones. Piezo buzzers are commonly used in electronic projects and systems for sound alerts due to their simple construction, reliability, and ability to produce a wide range of frequencies.
{% endhint %}

### 2.0 - Setup the Arduino and Piezo Buzzer

{% embed url="https://drive.google.com/file/d/1kUjapYjdtpIA2Iix6QF1Uw_pU-dJLhND/view?usp=sharing" %}

### 2.1 - Music with the Piezo Buzzer

{% embed url="https://drive.google.com/file/d/1ArjLLLcr5-5E9S2cvwBv-mJlJhAzlEBF/view?usp=sharing" %}

{% embed url="https://noobnotes.net/?authuser=0" %}

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

## Student Activities

1. Complete the activities in the video to simulate a pop song of your choosing.



2. **Extension:** Can you program the LEDs to turn on and off in a sequence after each note plays? At least one LED should turn on each time a note plays.&#x20;
   1. Plan out this algorithm with pseudocode.
   2. Make a copy of your TinkerCAD project and try to do this.

#### Example of Pseudocode for Buzzer:

I have **NOT** included the setup - that is up to you.

```
BEGIN loop
    WHILE TRUE DO
        
        PLAY TONE buzzer AT 440Hz FOR 500ms
        WAIT 1 second
        
        PLAY TONE buzzer AT 523Hz FOR 300ms
        WAIT 1 second
        
        PLAY TONE buzzer AT 659Hz FOR 700ms
        WAIT 1 second
        
    ENDWHILE
END loop
```
