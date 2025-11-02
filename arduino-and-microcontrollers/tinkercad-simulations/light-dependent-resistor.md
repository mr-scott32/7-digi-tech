---
icon: book-open
---

# Light Dependent Resistor

{% hint style="info" %}
## Light Dependent Resistor

Light Dependent Resistors (LDRs), also known as photoresistors, are variable resistors that adjust resistance based on the amount of light hitting their surface. Their resistance decreases as the light intensity increases, making them ideal for light-sensing applications like automatic lighting controllers, alarm systems, and various electronic projects that detect or respond to changes in light conditions.
{% endhint %}

### 7.0 Light Dependent Resistor

{% embed url="https://www.tinkercad.com/things/hKzybtglxmT?authuser=0&sharecode=Ql5NHNuEUxHy5p40Fom2R5vC1RRUsTgeDbpGdjO3gZ4" %}

### Student Activities

1. Create your own new project and create the circuit presented above. Write the code out (DON'T copy paste - write it all out!). Test your circuit to ensure it works.



2. A family always leaves their living room light on at night for security purposes. The only time this light goes out is if it has been tampered with. However, they need an alarm to sound if the light goes off so they know to go investigate. Create a circuit which will sound an alarm if the light goes off. Hint: You will need a Light Dependent Resistor to solve this problem.
   1. Plan out your algorithm using pseudocode first
   2. Implement your algorithm in a new TinkerCAD project

#### Example of Light Dependent Resistor Pseudocode

```
BEGIN

    SET ldrPin TO A0
    SET ledPin TO 11

    SET pinMode(ledPin) TO OUTPUT
    SET pinMode(ldrPin) TO INPUT

    WHILE TRUE DO
 
        SET lightLevel TO analogRead(ldrPin)

 
        IF lightLevel > 500 THEN
            TURN ON ledPin
        ELSE
            TURN OFF ledPin
        ENDIF
        
    ENDWHILE

END

```
