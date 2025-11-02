---
icon: book-open
---

# MakeCode Arcade Examples

Let's see how much you understand what the block code is doing in MakeCode Arcade.&#x20;

On the previous page you have a list of examples of how to use pseudocode to represent code. Let's use this as a basis to demonstrate our understanding of our block code.

### Examples

Let's consider the examples below:

{% columns %}
{% column width="33.33333333333333%" %}
#### Makecode Arcade Block

<figure><img src="../../.gitbook/assets/image (11).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### Pseudocode Algorithm

```
BEGIN forever
    WHILE true
        GET myScoreStatus
        IF myScoreStatus > 100 THEN
            wait 500ms
            SET game_over to WIN
            DISPLAY "You win!"
            BREAK
        ENDIF
    ENDWHILE
END forever
```

With the above, 'WHILE true' is a statement we can use to run something forever until the whole program is terminated, or something breaks the loop. In this case, getting over 100 points will break the loop (you can just write BREAK), or we could have structured it as "WHILE game\_over = false" and set game\_over to true.
{% endcolumn %}
{% endcolumns %}

{% include "../../.gitbook/includes/makecode-arcade-blockpseudo....md" %}

{% columns %}
{% column width="33.33333333333333%" %}
#### MakeCode Arcade Block

<figure><img src="../../.gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### Pseudocode Algorithm

```
BEGIN start
    SET hero to sprite of kind Player
    SET invicibilityPeriod to 600
    SET pixelsToMeters to 30
    SET gravity to 9.81 * pixelsToMeters
    SET background image
    initialiseAnimations
    createPlayer(hero)
    SET levelCount to 8
    SET currentLevel to 0
    setLevelTileMap(currentLevel)
    giveIntroduction
END start
```
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column width="33.33333333333333%" %}
#### MakeCode Arcade Block

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### Pseudocode Algorithm

```
BEGIN forever
    WHILE true
        IF 60% chance THEN
            createTree
            IF 50% chance THEN
                wait for 150ms to 300ms
                createTree
            ENDIF
        ENDIF
        wait 1500ms
    ENDWHILE
END forever
```
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column width="33.33333333333333%" %}
#### MakeCode Arcade Block

<figure><img src="../../.gitbook/assets/image (14).png" alt="" width="137"><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### Pseudocode Algorithm

```
START spell2
    FOR index FROM 0 TO 4 STEP 1
        shootBulletFromSprite(boss)
    SET offset to offset + 23
END spell2
```
{% endcolumn %}
{% endcolumns %}

{% columns %}
{% column width="33.33333333333333%" %}
#### MakeCode Arcade Block

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>
{% endcolumn %}

{% column width="66.66666666666667%" %}
#### Pseudocode Algorithm

```
BEGIN startLevel
    GET currentLevel 
    IF currentLevel = 0 THEN
        set tilemap to tmlevel0
    ELSEIF currentLevel = 1 THEN
        set tilemap to tmlevel1
    ELSEIF currentLevel = 2 THEN
        set tilemap to tmlevel2
    ELSEIF currentLevel = 3 THEN
        set tilemap to tmlevel3
    ELSEIF currentLevel = 4 THEN
        set tilemap to tmlevel1
    ELSE
        SET game_over to WIN
        DISPLAY "You win!"
    ENDIF
END startLevel
```
{% endcolumn %}
{% endcolumns %}
