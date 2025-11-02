---
icon: book-open
---

# First Circuit: Output, LEDs, Variables

{% hint style="info" %}
## LEDs

LEDs, or Light Emitting Diodes, are semiconductor devices that emit light when an electrical current passes through them. They are energy-efficient and have a long lifespan, often used in a variety of applications such as indicators, displays, and lighting. LEDs come in different colors and brightness levels and are valued for their durability and low power consumption.
{% endhint %}

Work your way through the videos, then complete the additional activities at the bottom of the page. Make sure you follow **EVERY STEP** from each video.

### 1.0 - First Circuit: Setup Circuit in TinkerCAD

The following video will show you how to setup an Arduino, Breadboard and LEDs in TinkerCAD.&#x20;

{% embed url="https://drive.google.com/file/d/1oHbuEAP6Q-_FnvB0Ay-TQH0-_kdddfJZ/view?usp=sharing" %}

### 1.1 - First Circuit: OUTPUT and Programming LEDs

We're now going to learn how to use C++ to program the Arduino and make the LEDs light up. LEDs are an **output** device, as the Arduino is **sending** a signal to the LED.

{% embed url="https://drive.google.com/file/d/1ZuRGOe2je-JMJkPJtNB0tBK-nf4ROYDu/view?usp=sharing" %}

{% hint style="info" %}
## Output

The output of an algorithm refers to the results produced after the execution of its process. This is the final data obtained after the algorithm processes the input according to its defined sequence of operations. Each algorithm may have different types of outputs, ranging from numerical values, textual data, or even complex data structures, depending on its purpose and design.

In the video above, the **output is LEDs lighting up.**&#x20;
{% endhint %}

{% hint style="info" %}
## Iteration / Loops

Let's think back for a second to when we looked at algorithms. Do you notice here that the Arduino continually loops in the **void loop?**

Iteration is a fundamental concept in programming that refers to the repetition of a block of code a certain number of times or until a specified condition is met. It allows for efficient handling of tasks that need to be repeated, minimising redundancy in code. Iteration is commonly implemented using loops, such as `for`, `while`, and `do-while` loops.&#x20;
{% endhint %}

### 1.2 First Circuit: Variables and Constants

Working with the pin numbers can quickly get a bit confusing, especially if you use more than 3 output pins. We can help in this by using **variables** and **constants** to store our data.&#x20;

{% embed url="https://drive.google.com/file/d/1mmBEsoAt8SkqaVfkq_kch92aAKo_c2PX/view?usp=sharing" %}

{% hint style="info" %}
## Variables vs Constants

Variables are fundamental components in programming that act as storage locations for data. They are used to hold information that can be referenced and manipulated by a program. Each variable is associated with a specific type of data, such as integers, floating-point numbers or strings (raw text). The choice of variable names should be descriptive to improve readability and maintainability of the code. Variables enable dynamic input handling, allowing algorithms to operate flexibly with varying data.

Constants are similar to variables, but their values are fixed once they are defined and cannot be altered during the execution of a program. They are used to represent fixed values that might appear multiple times throughout a codebase, improving readability and maintainability. By using constants, programmers can ensure that certain values remain consistent and protect critical data from being accidentally modified.

In the above video, we use **constants.**&#x20;
{% endhint %}

## Student Activities

1. Make sure you have completed EVERYTHING from the above videos.



2. You now will create a new pattern performance with the LEDs. Before we do that in the code, let's plan it out with pseudocode. Here's an example of mine to get you started:

```
BEGIN
    SET greenLed to 11
    SET yellowLed to 12
    SET redLed to 13
    
    SET pinMode(redLed) to OUTPUT
    SET pinMode(yellowLed) TO OUTPUT
    SET pinMode(greenLed) TO OUTPUT
    
    WHILE true DO
        TURN ON greenLed
        WAIT 1 second
        TURN OFF greenLed
        WAIT 1 second

        TURN ON yellowLed
        WAIT 1 second
        TURN OFF yellowLed
        WAIT 1 second

        TURN ON redLed
        WAIT 1 second
        TURN OFF redLed
        WAIT 1 second
    ENDWHILE
    
END
```

**Note:** The 'WHILE true DO' will have the program keep going until it is terminated.&#x20;

3. Make a copy of your TinkerCAD simulation and program the new pattern performance with the LEDs
