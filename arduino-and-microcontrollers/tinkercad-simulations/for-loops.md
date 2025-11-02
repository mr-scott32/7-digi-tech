---
icon: book-open
---

# FOR Loops

### 6.0 FOR Loops

{% embed url="https://drive.google.com/file/d/1w5zkts3-ulH__F_6Eqa1mUUUiyLwSZGV/view?usp=sharing" %}

{% hint style="info" %}
## Iteration and FOR Loops

Iteration refers to the process of repeating a set of instructions in a program until a specific condition is met. FOR loops are a common construct used for iteration in programming. They allow you to execute a block of code multiple times, typically with a counter or variable that changes with each iteration. FOR loops are useful when the number of iterations is known beforehand, making them ideal for tasks such as traversing arrays or lists.
{% endhint %}

### Student Activities

1. Make a duplicate of your first circuit. Complete all activities in the attached video.



2. Make a duplicate of your button / piezo buzzer circuit. Can you use a for loop to make the song play more than once when the button is pressed?
   1. Plan this out using a pseudocode algorithm first
   2. Implement your algorithm in your TinkerCAD project



3. **Extension:** Make a duplicate of your first circuit (LEDs).  Can you setup three pins for output to LEDs using 1 line of code inside of a for loop?  You'll do this in the _void setup()_ function. Do NOT add your pins to variables (i.e. remove _const int greenLed = 10_ and such).
   1. Plan this out using a pseudocode algorithm first
   2. Implement your algorithm in your TinkerCAD project



#### Example of FOR Loop Pseudocode

```
BEGIN

    SET greenLed TO 11
    SET redLed TO 12
    SET yellowLed TO 13

    SET pinMode(greenLed) TO OUTPUT
    SET pinMode(redLed) TO OUTPUT
    SET pinMode(yellowLed) TO OUTPUT

    WHILE TRUE DO
        FOR count FROM 1 TO 5 STEP 1
            TURN ON greenLed
            WAIT 500ms
            TURN OFF greenLed
            WAIT 500ms
        NEXT count

        FOR count FROM 1 TO 5 STEP 1
            TURN ON redLed
            WAIT 500ms
            TURN OFF redLed
            WAIT 500ms
        NEXT count

        FOR count FROM 1 TO 5 STEP 1
            TURN ON yellowLed
            WAIT 500ms
            TURN OFF yellowLed
            WAIT 500ms
        NEXT count
    ENDWHILE

END
```
