# Debugging Report Template   now 

After forking this project on GitHub, edit this file to replace where it says `Your answer here...` under each section below with your actual answers to each prompt while you strategically hunt for bugs!

<br/>
<hr/>

### 1. Your hypothesis: what do you think is causing the bug?

Even if you feel like you have *no idea*, take a guess! What are some possible issues that might cause our bug (and that, if fixed, would lead to our game working correctly)? ***Be as specific as possible here, and focus on just ONE small idea for each of your debugging reports.***

**Example:** *"It could be a typo in the line of code (line #28) that displays the "you win!" message."*

<br/>

```
The problem appears to be the computer cannot "see" the correct answer, "a". When you type in the correct response, you are told your wrong and to guess again until you run out of guesses. 
```

<br/>

### 2. Log your questions: what do you need to find out?

Write down a list of questions that you have related to your specific hypothesis above.

**Example:** *"What is this textContent thing? Is the C supposed to be capitalized? Is it missing a letter?"*

<br/>

```
First thing I would check is the syntax of the program... are all the parenthesis, semicolons, etc. in the right places?
Do the spellings of the variables match throughout the program?
Are the variables with two-word names camel-cased in all instances?
Does the spelling of the variable and ID  names in the html and CSS  match in the javascript?

If nothing is found wrong in the above, then I focused on the parts of the program that deal with the answer itself, how it is pulled out of the html, how the function is written. 





```

<br/>

### 3. Research and review: what answers can you find?

This step isn't needed for every hypothesis (depends what it is!), but if applicable in your case, do a little research on your questions! Write down a list of ***what*** you found, ***where*** you found it, and ***how*** you found it -- for example, what was the phrase you searched for on Google or StackOverflow? Did you ask on Slack or ask a friend? What did you discover?

**Example:** *"I searched for "textContent" on Google and found out from this page on MDN (https://developer.mozilla.org/en-US/docs/Web/API/Node/textContent) that it's a "property" that contains the text of an HTML element."*

<br/>

```

```

<br/>


### 4. Run your experiment: what are the exact steps you'll take to test your prediction?

For most hypotheses, research won't be enough; you'll need to test out some changes to the code! A real experiment!

If applicable to your hypothesis, write a **list of steps** for how you changed and testing your code to check if your hypothesis is correct. These steps should be specific enough that somebody else can *replicate* them, like following a recipe.

**Example** (for a different example hypotheses): *"Because I thought maybe my JavaScript file wasn't loading, I added console.log("test") on line #1. Then I refreshed the page for the app and opened the browser console to see if it appeared."*

<br/>

```
Your list of steps to run your experiment...
```

<br/>

### 5. Report your results: what happened?

What was the result of your experiment? Did it solve the bug or not? Did it create a *new* bug? Were there any error messages in the browser console? Did the app behave incorrectly (not as expected)? Write down your findings.

**Example:** *"I saw "test" appear in the browser console. No errors appeared. But it didn't solve the bug."*

<br/>

```
I created a new bug where the program now says "you've won!" all the time,  no wrong answer.
didn't solve the original bug. 
```

<br/>

### 6. Conclusion: what did you learn?

Did this experiment *confirm* your hypothesis? Or would you say this result is inconclusive and you still don't know if your hypothesis is correct? Did this experiment bring up any followup questions or ideas for new hypotheses?

**Example:** *"This experiment confirmed that my JavaScript file is loading, without a doubt! My next hypothesis that I'd like to test later on is this: maybe I forgot to initialize the guessesRemaining variable."*

<br/>

```
The javascript file does load but I have to undo my new bug.  
```

<br/>

#### 7. Iterate: Repeat the steps above!

Think of another hypothesis and/or another way to research or test it, and see what happens. (You don't need to do this whole process for *every tiny thing* you try, but do it at least a couple times, especially for anything that surprised you or led to you learning something new.)

This will be a familiar mantra when designing *anything*, software apps included: *Iterate, iterate, iterate!*
