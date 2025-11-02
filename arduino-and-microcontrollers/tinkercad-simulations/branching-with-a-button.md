---
icon: book-open
---

# Branching with a Button

{% hint style="info" %}
## Push Button

A push button is a simple switch used to control the flow of electricity in a circuit. When pressed, it completes the circuit, allowing current to flow, and when released, it breaks the circuit, stopping the current. Push buttons are commonly used for user inputs, such as turning a device on or off, or triggering specific actions in an electronic system.
{% endhint %}

### 3.0 IF Statements and Buttons

Work through the following video to get a sense of how you can program a button press in C++.

{% embed url="https://drive.google.com/file/d/1fGmZJyXOBvcFjGt-AR_givduwAfnv-K3/view?usp=sharing" %}

{% hint style="info" %}
## Input

In programming, input refers to the data or signals received by the program from external sources to influence its behavior. For example, in a C++ program, a button press event can serve as an input. When a user presses a button, the program receives an input signal indicating this event, which can trigger specific functions or actions coded to respond to such inputs. This process allows interactive applications to react in real-time, providing a dynamic user experience.
{% endhint %}

{% hint style="info" %}
## Branching

Branching in programming refers to the ability to change the flow of execution based on certain conditions. It allows your program to decide which code to execute based on the outcomes of expressions, typically using `if`, `else if`, and `else` statements. This enables more complex decision-making processes, allowing the software to adapt its behavior dynamically in response to different inputs or states.

In short, it allows you to **make decisions depending on user input.**&#x20;
{% endhint %}

### Student Activities

1. Follow the steps in the above video to play your pop song. Make sure to **make a duplicate** of your buzzer file first.



2. **Extension:** Can you make a program where the buzzer rings constantly, but turns off when you hold the button? **Note:** Do NOT add a delay to your buzzer.
   1. Plan out this algorithm using pseudocode first.
   2. Create a new TinkerCAD file, setup the button and buzzer, then program it based on your algorithm and try it out.

#### Example of Pseudocode for Button

```
BEGIN loop

    SET buzzer TO 8
    SET button TO 2
    SET buttonState to 0

    SET pinMode(buzzer) TO OUTPUT
    SET pinMode(button) TO INPUT

    WHILE TRUE DO
        GET buttonState FROM button
        IF buttonState = PRESSED THEN
            PLAY TONE buzzer AT 440Hz FOR 500ms
        ELSE
            STOP TONE buzzer
        ENDIF
    ENDWHILE
END loop
```
