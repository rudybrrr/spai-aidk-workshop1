# AI Don’t Know Workshop 1: Python Foundations — Speaker Script

This script follows the exact order of the 32 slides and the Workshop 1 starter notebook.

## Slide 1: AI Don’t Know — Workshop 1: Python Foundations

**Main Script:**  
“Hey everyone, thanks for coming. This is Workshop 1, so we’re starting with the basics of Python. Some of you may have used JavaScript before, and some of you may be completely new to coding. Both are fine. We’ll go slowly, try the examples together, and help you out if you get stuck.”

**Additional Notes:**  
- Let everyone know that questions are welcome.
- Remind them that getting errors is a normal part of learning.

**Transition to next slide:**  
“Before we start, just a quick intro to SPAI.”

## Slide 2: About SPAI

**Main Script:**  
“SPAI is a student group here in SP. We run AI workshops and events, mostly for people who want to try things out without needing much experience first. You can come in, ask questions, and learn with everyone else. That’s basically what today is for as well.”

**Additional Notes:**  
- Keep this short so there is more time for the workshop.
- Make sure beginners know they are welcome.

**Transition to next slide:**  
“A bit more about what we do.”

## Slide 3: Who We Are

**Main Script:**  
“We’re students too, so we know AI can look quite overwhelming from the outside. Our events are open to students from any course or school. We try to keep things practical, explain them normally, and make it easy to ask for help.”

**Additional Notes:**  
- Briefly point out the four areas on the slide: workshops, events, community, and projects.
- Avoid turning this into a long club introduction.

**Transition to next slide:**  
“These are some things we’ve run before.”

## Slide 4: Previous Events

**Main Script:**  
“Just to give you an idea, these are a few of our past events. We’ve done sessions on AI tools, data visualisation, and n8n automation. They’re quite different topics, but we usually keep the format hands-on. We show you something, then you get to try it.”

**Additional Notes:**  
- If there is time, share one short memory from an earlier event.
- The event details are only background, so move on quickly.

**Transition to next slide:**  
“Today is also part one of a short series.”

## Slide 5: Workshop Series

**Main Script:**  
“This isn’t a one-off session. There are three workshops. Today is Python, the next one uses Python with data and charts, and the last one is a guided machine learning example. So today is really just getting everyone onto the same starting point.”

**Additional Notes:**  
- Make the three workshops feel connected, not like separate topics.
- Attendees do not need to master one workshop before joining the next.

**Transition to next slide:**  
“Here’s what each workshop covers.”

## Slide 6: Series Outline

**Main Script:**  
“So, today: Python basics. Next week: using data and making charts. Then in the last workshop, you’ll fill in parts of a prepared machine learning example. Don’t worry about all the tool names on the slide yet. We’ll introduce them when we actually use them.”

**Additional Notes:**  
- Point out the dates and times briefly.
- Make it clear that Workshop 3 is guided, not built from a blank page.

**Transition to next slide:**  
“What are we hoping you get out of all this?”

## Slide 7: Takeaways

**Main Script:**  
“You’re not expected to master Python today. Honestly, if you can look at a short piece of Python and roughly follow what it’s doing, that’s already a good start. The next two workshops will add data and machine learning on top of that.”

**Additional Notes:**  
- Even experienced programmers still look things up.
- Success today means being willing to read, change, and run small pieces of code.

**Transition to next slide:**  
“Okay, let’s get the notebook open first.”

## Slide 8: Python Setup Checklist

**Main Script:**  
“Quick setup check. Open the workshop folder, then open `01_AIDK_W1_Starter.ipynb`. You’ll also need the Python and Jupyter extensions in VS Code. If the notebook won’t open, or yours looks completely different from what we’re showing, just raise your hand. Someone will come over.”

**Notebook Cue:**  
Ask everyone to open `01_AIDK_W1_Starter.ipynb` and stop at the title, `# AI Don't Know Workshop 1: Python Foundations`. Do not start the TODO tasks yet.

**Additional Notes:**  
- Pause for about one minute while facilitators check the room.
- Let facilitators help people one-to-one instead of solving every setup problem from the front.

**Transition to next slide:**  
“Got it open? Let’s check that it runs.”

## Slide 9: Notebook Tools

**Main Script:**  
“You can ignore the long install command if everything is already working. In the notebook, run the quick check. You should see ‘Python is working!’ underneath the cell. If you do, you’re good. If there’s an error, raise your hand and we’ll take a look.”

**Notebook Cue:**  
Under `## Setup Check`, ask everyone to run the cell containing `print("Python is working!")`. Pause until most people see the message.

**Additional Notes:**  
- On Windows, `py` may work if the `python` command does not.
- Do not explain all the other tools yet; they are for later workshops.

**Transition to next slide:**  
“Alright, setup’s out of the way.”

## Slide 10: Workshop 1 Flow

**Main Script:**  
“For the rest of today, we’ll keep moving between the slides and the notebook. We’ll explain one idea, run a small example, then move on. Near the end, you’ll put a few of those ideas together yourself.”

**Additional Notes:**  
- Give everyone a moment to look back at the slides after the setup check.
- It is okay if a facilitator is still quietly helping someone.

**Transition to next slide:**  
“This is the rough order for today.”

## Slide 11: Workshop 1 Flow

**Main Script:**  
“We’ll start with a quick look at Python, compare it with JavaScript, and then go through the basics. After that, there’s a short practice task. Keep the notebook open—we’ll tell you when to switch over and run a cell.”

**Notebook Cue:**  
Ask everyone to keep the starter notebook open for the next sections.

**Additional Notes:**  
- Ask attendees not to rush ahead through the TODO tasks.
- The examples are arranged in the same order as the slides.

**Transition to next slide:**  
“First up, Python compared with JavaScript.”

## Slide 12: About Python + JS vs Python

**Main Script:**  
“If you’ve done some JavaScript, you already know quite a few of the ideas we’ll use. Python just writes them differently. Try to look at what the code is doing before worrying about every bracket or symbol. If JavaScript is new to you too, that’s fine—we’ll still go through the Python examples properly.”

**Additional Notes:**  
- Programming ideas can carry from one language to another.
- Avoid making complete beginners feel behind.

**Transition to next slide:**  
“So, why Python?”

## Slide 13: Why Python

**Main Script:**  
“Mainly because Python is used a lot for AI and data, and the code is usually quite readable. It also has plenty of ready-made tools for working with data, making charts, and building models. We’re not touching all of that today. We’re just learning enough Python so those tools don’t look completely unfamiliar later.”

**Notebook Cue:**  
Open `## About Python - Why Python` and run the cell beginning `topic = "Python Foundations"`. Check that the message appears.

**Additional Notes:**  
- You can describe a library as a box of ready-made tools.
- Do not explain each library in detail here.

**Transition to next slide:**  
“Have a look at the same `if` statement in both languages.”

## Slide 14: Code Blocks

**Main Script:**  
“These two examples do the same thing: they check whether the score is at least 60. JavaScript uses curly brackets. Python uses a colon, then puts the next line slightly further in. That spacing matters. Luckily, VS Code usually adds it for you when you press Enter.”

**Notebook Cue:**  
Under `## JS vs Python - Code Blocks`, find the cell beginning `score = 72`. Ask everyone to guess the result, then run it.

**Additional Notes:**  
- Four spaces is the usual amount, but beginners can let VS Code handle it.
- A common mistake is forgetting the colon or moving `print()` too far left.

**Transition to next slide:**  
“Next, variables.”

## Slide 15: Variables

**Main Script:**  
“Variables sound more complicated than they are. It’s just a name for a value. In JavaScript, you may start with `let` or `const`. Python skips that. You can just write `score = 82`, and from then on, `score` means 82.”

**Notebook Cue:**  
Under `## JS vs Python - Variables`, run the cell beginning `name = "Ravi"`. Then let everyone try the next TODO cell: create `course` and print it. Pause for about two minutes. Facilitators should give hints without typing the answer.

**Additional Notes:**  
- Think of a variable name as a label on a container.
- If someone finishes early, ask them to change the course and run it again.

**Transition to next slide:**  
“How do we actually see that value? We print it.”

## Slide 16: Printing Output

**Main Script:**  
“This one is simple. `print()` puts something on the screen. If you’ve used JavaScript, it’s basically our `console.log()`. You can print text, numbers, or a variable. We’ll use it a lot just to check what’s happening.”

**Notebook Cue:**  
Under `## JS vs Python - Printing Output`, run the cell beginning `print("Hello SPAI!")`. Then let everyone try the next cell with `name = "Moiz"` and `print(_____)`. Give them a moment before offering a hint.

**Additional Notes:**  
- Text written directly needs quotation marks.
- A variable name does not need quotation marks.

**Transition to next slide:**  
“Two more small values before we move on.”

## Slide 17: Booleans and None

**Main Script:**  
“For a yes-or-no value, Python uses `True` and `False`. Just remember the capital letters. `None` means there isn’t a value yet. So here, the student passed, but nobody has written any remarks.”

**Notebook Cue:**  
Under `## JS vs Python - Booleans and None`, run the cell beginning `passed = True`. Ask everyone to notice the capital letters.

**Additional Notes:**  
- `None` without quotation marks means no value yet.
- A common mistake is writing `true` or `false` with small letters.

**Transition to next slide:**  
“That’s the quick JavaScript comparison done.”

## Slide 18: Python Basics

**Main Script:**  
“That’s my part done. We’ve covered the main differences you’ll notice straight away: spacing, variables, `print()`, and a few special values. Murugan’s going to take over from here and run through the rest with you.”

**Additional Notes:**  
- Enzo closes with: “I’ll hand over to Murugan, who will guide us through the next examples and the practice.”
- Pause briefly for the speaker change.

**Transition to next slide:**  
“I’ll pass it over to Murugan.”

> **Speaker handover — Enzo to Murugan:** Enzo closes Slide 18. Murugan starts from Slide 19 and leads the hands-on Python section.

## Slide 19: Data Types

**Main Script:**  
“Thanks, Enzo. Quick recap: Python can store different kinds of values. A name is text, 88 is a whole number, 2.50 is a decimal, and `True` or `False` is a yes-or-no value. You don’t need to memorise every name on this slide. Just know that Python treats these values differently.”

**Notebook Cue:**  
Under `## Python Basics - Data Types`, run the cell beginning `name = "Aisha"` and look at the results from `type(...)`. Then let everyone try the next cell with `student_score = 95`. Pause before helping.

**Additional Notes:**  
- The notebook shows the names `string`, `integer`, `float`, `boolean`, and `None`.
- The text `"95"` and the number `95` may look alike, but Python treats them differently.

**Transition to next slide:**  
“Now for a few tools Python already gives us.”

## Slide 20: Built-in Functions

**Main Script:**  
“You’ve already used `print()`. `sum()` and `len()` work in a similar way. `sum()` adds the numbers, and `len()` counts how many there are. Put the list inside the brackets, and Python does the job for you. We’ll use both to get an average.”

**Notebook Cue:**  
Under `## Python Basics - Built-in Functions`, run the cell beginning `scores = [72, 85, 60, 91]`. Then let everyone try the cell with `total = _____(scores)` and `count = _____(scores)`. Let them use the example above. Do not reveal both answers immediately.

**Additional Notes:**  
- “Built-in” only means Python already gives us the tool.
- A common mistake is forgetting the brackets after the tool’s name.

**Transition to next slide:**  
“There’s one small catch when someone types a number.”

## Slide 21: Input and Conversion

**Main Script:**  
“`input()` lets someone type something in. The small catch is that Python reads it as text—even if they typed 75. So before we do maths with it, we use `int()` to change it into a number. Then adding 5 works normally.”

**Notebook Cue:**  
Under `## Python Basics - Input and Conversion`, run the cell beginning `score_text = "75"`. Then let everyone try the next TODO cell: ask for a score, change it into a number, and add 10. Pause for about three minutes. Remind them that the cell waits for them to type a score.

**Additional Notes:**  
- If someone types letters instead of a number, an error may appear. That is okay for today.
- Facilitators should use the hint in the notebook before giving more help.

**Transition to next slide:**  
“Once we have the score, we can make a choice with it.”

## Slide 22: Conditionals

**Main Script:**  
“This is how the program chooses between a few messages. It checks `if` first. If that doesn’t match, it tries `elif`. If neither matches, it goes to `else`. The score here is 72. Take a second—what do you think it will print?”

**Notebook Cue:**  
Under `## Python Basics - Conditionals`, run the cell beginning `score = 72` after everyone predicts the result. Change the score once and run it again. Then let them try the next incomplete cell beginning `score = 58`. Give them time before helping.

**Additional Notes:**  
- Only one of the three messages will be shown.
- Check for missing colons and lines that are not moved to the right.
- After it works, try a score of exactly 60.

**Transition to next slide:**  
“Next up: repeating something without writing it five times.”

## Slide 23: For Loops

**Main Script:**  
“That’s what a loop is for. Instead of writing `print()` five times, we write it once and let Python repeat it. The first example prints 0 to 4. The second one goes through the names and greets each person.”

**Notebook Cue:**  
Under `## Python Basics - For Loops`, run the cell beginning `for i in range(5):`, including the names example. Then let everyone try the next TODO cell with the `students` list. Pause for two to three minutes. Facilitators should check the spacing first.

**Additional Notes:**  
- `range(5)` stops before 5, so the last number is 4.
- A common mistake is placing the repeated line too far left.

**Transition to next slide:**  
“Those groups of names and scores are lists.”

## Slide 24: Lists

**Main Script:**  
“This square-bracket thing is a list. It keeps a group of values together. Python counts from zero, so the first score is at position zero. `len()` counts the items, and `append()` adds one more at the end. You’ll see lists a lot when working with groups of data.”

**Notebook Cue:**  
Under `## Python Basics - Lists`, run the cell beginning `scores = [72, 85, 60, 91]`. Then let everyone try the next TODO cell with `student_names = ["Aisha", "Ben"]`: add one name, show the first name, and show the full list. Do not give the finished cell.

**Additional Notes:**  
- A common mistake is using position 1 for the first item. Python starts from 0.
- Point back to `append()` in the example if someone gets stuck.

**Transition to next slide:**  
“A dictionary stores things a little differently.”

## Slide 25: Dictionaries

**Main Script:**  
“A dictionary is more like a small profile. Instead of finding something by position, we use a label such as `name`, `course`, or `score`. So if we ask for `name`, Python gives us Aisha. It’s useful when each value has a clear meaning.”

**Notebook Cue:**  
Under `## Python Basics - Dictionaries`, run the cell with Aisha’s details. Then let everyone try the next cell with Ben’s details and `print(student[_____])`. Ask them to choose one label that already exists. Do not give the exact answer immediately.

**Additional Notes:**  
- Think of each label as the name on a drawer.
- The label must match the spelling used in the dictionary.

**Transition to next slide:**  
“Last new idea: functions.”

## Slide 26: Functions

**Main Script:**  
“A function is just a few steps grouped under one name. We make one with `def`. This function takes some numbers and works out the average. Once it’s there, we can call its name whenever we need that same calculation again.”

**Notebook Cue:**  
Under `## Python Basics - Functions`, run the cell beginning `def calculate_average(numbers):`. Then let everyone try the next cell beginning `def check_pass(score):`. Ask them what score should count as a pass, and let them test more than one score.

**Additional Notes:**  
- The lines moved to the right belong to the function.
- Keep the explanation focused on “name some steps and reuse them.”

**Transition to next slide:**  
“Okay, that’s enough new stuff. Time to try it.”

## Slide 27: Practice

**Main Script:**  
“Your turn. The code is already in the notebook—you’re just filling in the blanks. Go one TODO at a time, and use the earlier examples if you forget something. Try an answer even if you’re not completely sure. If it breaks, call one of us over and we’ll give you a hint.”

**Notebook Cue:**  
Ask everyone to scroll to `## Practice - Class Score Summary` and read the instructions. Do not fill or run the cell yet; the next slide explains the task.

**Additional Notes:**  
- Ask facilitators to spread out around the room.
- Attendees can discuss with a neighbour, but each person should type their own attempt.

**Transition to next slide:**  
“Have a look at the task first.”

## Slide 28: Practice Task

**Main Script:**  
“You’ve got five scores. First, find the average. Then fill in the check for whether that average is at least 60. There’s a hint on the slide, and everything you need is somewhere above in the notebook. We’ll give you a few minutes. Take your time.”

**Notebook Cue:**  
In `## Practice - Class Score Summary`, complete the cell beginning `scores = [72, 85, 60, 91, 45]`. Allow about five to eight minutes. Facilitators should ask helpful questions such as “What adds the scores?”, “What counts them?”, and “What does at least mean?” Do not announce or type the full solution.

**Additional Notes:**  
- Give a halfway reminder and a one-minute warning.
- If someone finishes early, ask them to change one score and guess what will happen.
- Do not move to Slide 29 until everyone has had a real chance to try.

**Transition to next slide:**  
“Alright, let’s check it together.”

## Slide 29: Practice Solution

**Main Script:**  
“Here’s the completed version. It gets the average, prints it, then checks whether it reached 60. Compare it with yours and see where they differ. If your code looks different but still works, that’s fine too. There’s often more than one way to write something.”

**Notebook Cue:**  
Return to the cell under `## Practice - Class Score Summary`. Ask everyone to compare it with the slide, fix only what they need to, and run it again. Do not copy and paste or read out the whole answer. If time remains, point out `## Practice - Your Turn` as an extra attendance task, but do not solve it for them.

**Additional Notes:**  
- Only show this slide after the practice time is over.
- Help attendees understand their mistake instead of reading the answer character by character.
- Let attendees make the final changes themselves.

**Transition to next slide:**  
“That’s the practice done. Just a quick recap.”

## Slide 30: Summary of Today

**Main Script:**  
“That’s the coding part finished. You’ve read some Python, changed it, run it, and fixed a few blanks. Some of it may still feel new—that’s normal. At least when you see these things again, they won’t be completely new anymore.”

**Notebook Cue:**  
Ask everyone to scroll to `## Summary - Before Workshop 2`. There is no new code to run here.

**Additional Notes:**  
- Give everyone a moment to save their notebook.
- Allow a little extra time if many people are still finishing the task.

**Transition to next slide:**  
“So, what did we actually cover?”

## Slide 31: Summary

**Main Script:**  
“We used variables to keep values, `print()` to show them, lists for groups, and dictionaries for labelled information. We also tried `if`, loops, and a small function. That sounds like a lot, but you don’t need to memorise it tonight. The notebook is there if you want to look back.”

**Notebook Cue:**  
At `## Summary - Before Workshop 2`, ask everyone to read the recap. No new cell needs to be run.

**Additional Notes:**  
- Take one or two quick questions if time allows.
- Remind everyone that they can return to the notebook and rerun the examples later.

**Transition to next slide:**  
“And that’s Workshop 1.”

## Slide 32: Thank You

**Main Script:**  
“That’s it from us. Thanks for coming and actually trying the exercises. Keep the notebook—you can always rerun the examples later. Next time, we’ll use Python with data and make some charts. If anything from today still doesn’t make sense, come and ask us before you go.”

**Additional Notes:**  
- Remind everyone of the next workshop’s date and time.
- Share any feedback form or final announcement here.
- Thank the facilitators and organising team.

**Transition to next slide:**  
“Any last questions before we end?”
