---
icon: book
---

# Pseudocode Algorithms

{% hint style="info" %}
## Learning Intentions

* Use algorithms to solve problems and design solutions
* Develop and trace algorithms using branching, iteration and a range of data types
{% endhint %}

{% hint style="success" %}
## Success Criteria

I can use algorithms to describe processes in my daily life.

I can represent algorithms using pseudocode

I can represent branching (decision making) and iteration (loops) using pseudocode
{% endhint %}

***

## Introduction

Look through the following slides and videos for an introduction to algorithms, then complete the activity.

{% embed url="https://docs.google.com/presentation/d/1hGNIxWFSpHimPKWlhUbfct4dk4Nie-je/edit?ouid=103980595399381006248&rtpof=true&sd=true&usp=sharing" %}

{% embed url="https://docs.google.com/presentation/d/1t5u9VGgRPG7iWmp6aDysnQy7SXLa2DZa/edit?ouid=103980595399381006248&rtpof=true&sd=true&usp=sharing" %}

{% embed url="https://www.youtube.com/watch?v=Da5TOXCwLSg" %}

## Activity 1:&#x20;

Open a document. **Define** the word '**Algorithm**' in your own words.

***

{% embed url="https://www.youtube.com/watch?v=cDA3_5982h8" %}

## Activity 2:

1. Look back at the first presentation above and look through the activities / pseudocode section.
2. In the same document, create **pseudocode** for getting ready for school in the morning. Start with step-by-step instructions
3. &#x20;Add BEGIN and END to the pseudocode, then indent everything else out.&#x20;

```
BEGIN 
    Add your instructions here
    Step by step
    Line by line
    Be specific
    Use 'TAB' to indent.
    See how this code looks like it's kind of... 
    Inside the BEGIN and END block?
END
```

4. What decisions do you need to make in the morning? We need to have our algorithms make decisions. This is called 'branching', as it branches out to different possibilities in our algorithms.&#x20;

So, we're getting ready for school in the morning. What if it's raining? Then we need to bring an umbrella.

Add an IF statement to your pseudocode somewhere (don't use the example below):

```
BEGIN
    IF raining outside THEN
        Take umbrella
    ENDIF
    Go to school etc
END
    
```

5. Now, that's a simple decision. What happens if we need to decide before more than two options? Well, we can add as many IF statements as we like, using IF, ELSEIF, ELSE.&#x20;

* **IF**: We do this if the condition is true. **IF condition is true, do this.**
* **ELSEIF:** Let's say the 'IF' condition is false, but there are more options. We then move down to the ELSEIF block and check if it's true. **We can have as many of these as we like.** Instead, if **this condition is true,** we do this.&#x20;
* **ELSE:** This is what happens if **NONE** of the conditions are true. It allows us to make a decision based on **every other possibility.** It's kind of like saying **otherwise,** do this.

So we're getting ready in the morning, but what if it's Saturday? What if it's Sunday? We might have different wake-up times. Maybe we wake up for sport early on Saturday, then sleep in on Sunday, whilst for school we wake up VERY early to get the train. Let's have a look...

```
BEGIN
    GET day
    
    IF day is Saturday THEN
        Wake up at 6:30am
    ELSE IF day is Sunday THEN
        Wake up at 8:00am
    ELSE 
        Wake up at 6:00am 
    ENDIF
    
    Start getting ready by... 
END
```

So consider the above. **IF** it's Saturday, we wake up at 6:30am. **Otherwise if / ELSE IF** it's not Saturday, but it is Sunday, we wake up at 8:00am. **Otherwise or ELSE,** we wake up at 6:00am, because **all other possibilities are a school day.**&#x20;

The other difference here is I added 'GET day'. This is an **INPUT**. Whenever making a decision on a condition, an algorithm needs some kind of input data to process. To do this in pseudocode, we write **GET.** So we **GET** the day from the user, and use the **branching** algorithm (IF, ELSEIF, ELSE) to determine what time to wake up.



6. Let's do one more. This one's a bit harder. Let's get **iteration** into the algorithm. Another word for this is **repetition,** or a **loop.** We don't want to repeat ourselves in an algorithm, so it's best that we use this to save time and effort.

So we're awake, we're dressed, now we need to eat breakfast. Let's say it's cornflakes. Now to be specific without a loop, we'd need to know how many times we need to dip the spoon in the bowl and bring it up to our mouth. But instead, what we could do is keep eating **WHILE** there is cereal and milk left in the bowl. Let's have a look...

```
BEGIN
    prepare cereal
    SET finished to false
    WHILE cereal not finished
        collect cereal with spoon
        eat mouthful of cereal
        GET finished
    ENDWHILE
END
```

For the above, we prepare cereal, then SET finished to false, as the cereal is not finished. Then, WHILE cereal is not finished, we eat more cereal. We then INPUT whether or not the cereal is finished ('GET' finished). Once it is finished, we would INPUT finished as true, and the loop would end as **the condition is no longer true.**
