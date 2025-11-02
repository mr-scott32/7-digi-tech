---
icon: book-open
---

# Branching with a Potentiometer

{% hint style="info" %}
## Potentiometer

A potentiometer is a three-terminal resistor with a sliding or rotating contact that forms an adjustable voltage divider. It can be used to control electrical devices like volume controls on audio equipment. By adjusting the knob or slider, you can vary the resistance and hence the voltage output.
{% endhint %}

### 4.0 IF, ELSE IF and ELSE with a Potentiometer

{% embed url="https://drive.google.com/file/d/1vZrYv-JS8XmNmPf_XuMmkE9yEL7M0Vvd/view?usp=sharing" %}

{% hint style="info" %}
## Branching

Branching in programming allows a program to take different paths based on certain conditions. When using a potentiometer, branching can be implemented to perform different actions based on the resistance or voltage level read from the potentiometer. For example, if the voltage is below a certain threshold, a program could execute a specific block of code, like dimming an LED. If the voltage is higher, it might execute a different block, such as brightening the LED. This decision-making process uses IF, ELSE IF, and ELSE statements to evaluate the potentiometer's input and determine the appropriate response.
{% endhint %}

### Student Activities

1. Program a potentiometer to create a simple traffic light system like the video.



2. Can you add your buzzer so that it mimics the buzzer that rings for pedestrians crossing? I.e. buzzer beeps slowly with yellow and green, but rings loudly and continuously when red?
   1. Plan this out with a pseudocode algorithm.
   2. Make a copy of your TinkerCAD project, then implement your algorithm using code.



3. Can you add another green and red LED to make pedestrian crossing?
   1. Plan this out with a pseudocode algorithm.
   2. Make a copy of your TinkerCAD project, then implement your algorithm using code.

#### Example of Pseudocode with a Potentiometer

```
BEGIN

    SET greenLed TO 11
    SET yellowLed TO 12
    SET redLed TO 13
    SET pot TO A0

    SET pinMode(greenLed) TO OUTPUT
    SET pinMode(yellowLed) TO OUTPUT
    SET pinMode(redLed) TO OUTPUT
    SET pinMode(pot) TO INPUT

    WHILE TRUE DO

        GET value FROM pot

        IF value < 341 THEN
            TURN ON greenLed
            TURN OFF yellowLed
            TURN OFF redLed

        ELSEIF value < 682 THEN
            TURN OFF greenLed
            TURN ON yellowLed
            TURN OFF redLed

        ELSE
            TURN OFF greenLed
            TURN OFF yellowLed
            TURN ON redLed
        ENDIF

    ENDWHILE

END
```
