---
icon: book-open
---

# WHILE Loops

## 6.1 WHILE Loops

{% embed url="https://drive.google.com/file/d/1HSq6oA8mwlnUdymLz4idremxZBE0Nuf2/view?usp=sharing" %}

{% hint style="info" %}
## WHILE Loops (Pre-Test)

A while loop is a control flow statement that allows code to be executed repeatedly based on a given boolean condition. The loop continues to execute as long as the specified condition evaluates to true. Iteration in the context of while loops refers to the repeated execution of the loop's block of statements. Each execution cycle of a while loop is called an iteration, allowing the program to repeatedly execute a sequence of instructions until the condition becomes false. While loops are particularly useful when the number of iterations is not known beforehand and depends on dynamic runtime conditions. They are a **pre-test** loop.
{% endhint %}

{% hint style="info" %}
## DO WHILE Loops (Post-Test)

A do-while loop is similar to a while loop, but it guarantees that the code block will be executed at least once. The condition is evaluated after the code block has been executed, meaning the loop's block of statements will run once before the condition is checked. This makes do-while loops particularly useful when the loop body needs to execute at least once regardless of the condition. They are a **post-test** loop.
{% endhint %}

### Student Activities

1. Make a duplicate of your first circuit. Complete the 'While' and 'Do While' activities involving LEDs in the video.



2. Make a duplicate of your FUNCTIONS circuit (with the buzzer and button). Complete the 'While' activities from the video which involve the button and buzzer.



3. Write a program that plays a tune 1 note at a time when you press the button. It must play at least 5 different notes, 1 each time you press the button.
   1. Plan your design with a pseudocode algorithm first
   2. Implement your algorithm in a new TinkerCAD project



#### Example of While and Do-While in Pseudocode

#### While Loop Pseudocode (Pre-Test)

```
BEGIN

    SET greenLed TO 11
    SET redLed TO 12
    SET yellowLed TO 13

    SET pinMode(greenLed) TO OUTPUT
    SET pinMode(redLed) TO OUTPUT
    SET pinMode(yellowLed) TO OUTPUT

    WHILE TRUE DO
        SET counter TO 0
        WHILE counter < 5 DO
            TURN ON greenLed
            WAIT 500ms
            TURN OFF greenLed
            WAIT 500ms
            SET counter to counter + 1
        ENDWHILE

        TURN ON yellowLed
        WAIT 500ms
        TURN OFF yellowLed
        WAIT 500ms

        TURN ON redLed
        WAIT 500ms
        TURN OFF redLed
        WAIT 500ms

    ENDWHILE
END
```

#### Do While Loop Pseudocode (Post-Test)

```
BEGIN

    SET greenLed TO 11
    SET redLed TO 12
    SET yellowLed TO 13

    SET pinMode(greenLed) TO OUTPUT
    SET pinMode(redLed) TO OUTPUT
    SET pinMode(yellowLed) TO OUTPUT

    WHILE TRUE DO

        SET counter TO 0
        REPEAT
            TURN ON greenLed
            WAIT 500ms
            TURN OFF greenLed
            WAIT 500ms
            SET counter to counter + 1
        UNTIL counter = 5

        TURN ON yellowLed
        WAIT 500ms
        TURN OFF yellowLed
        WAIT 500ms

        TURN ON redLed
        WAIT 500ms
        TURN OFF redLed
        WAIT 500ms

    ENDWHILE
END
```
