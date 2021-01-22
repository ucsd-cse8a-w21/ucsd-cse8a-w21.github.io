---
layout: page
title: "UCSD CSE8A W21 – PA3 (Programming Assessment)"
doodle: "/doodle.png"
---

# UCSD CSE 8A W21 -- PA3 (Programming Assessment)

This assessment is to be completed entirely on your own. You can ask
_private_ questions about the assignment on Edstem, but it's likely that we
won't give detailed answers and won't help you debug your program. The intent
of this assessment is to give a grade to your understanding of the material
from the first part of the course.

You can use any course resources, videos, Google searches, and so on to
complete this assessment. You _cannot_ communicate with anyone else or get
staff help to complete it. You can ask staff questions about making your
video or submission logistics, but they have been instructed to not help with
your program.

You will also complete a video screencast demonstrating part of the PA for
grading, which is detailed at the end of this description.

## Tasks

### Fill in the Blanks

Write a program in the file `fill_in_blanks.py`. It should take two strings
as input from the user, and fill them into a sentence. The sentence should be
`“I ____ in shock when I found the ______ in my suitcase.”`

Here are examples of what the program should produce:

```
[ sahara ] $ python fill_in_blanks.py
Enter a past-tense verb: coughed
Enter an animal: mouse
I coughed in shock when I found the mouse in my suitcase.
[ sahara ] $ python fill_in_blanks.py
Enter a past-tense verb: danced
Enter an animal: orca
I danced in shock when I found the orca in my suitcase.
```

### Solar System

In the file `solar_system_weight.py`, write a **function** called
`weight_on`. The function should have two parameters, a string and a number,
you can choose their names. The string represents a planet name, and the
number represents a weight (assumed to be on earth). The function should
produce a number representing the weight on the given planet, using the
following values as the relative weights:

- `"earth"`: `1.0`
- `"mars"`: `0.38`
- `"venus"`: `0.91`
- `"mercury"`: `0.38`

If a value other than one of these strings is given for the planet name,
return `-1`.

Examples:

```
>>> weight_on("mars", 100)
38.0
>>> weight_on("sun", 100)
-1
```

### Checking for A Valid PID

<div class='sidenote'>Real UCSD PIDs have 9 numeric digits, but 3 is enough to see how it would be done :-)</div>

In the file `check_pid.py`, write a function `check_pid` that takes a string
and produces a boolean. It should return `True` if:

- The string is exactly 4 characters long
- The first character is `"A"`
- The remaining 3 characters are all digits (the strings `'0'`, `'1'`, and so on up to `'9'`)

It should return `False` if any of these conditions are not satisfied. The
function should never cause an _error_ as long as some string is given as
input.

Examples:

```
>>> check_pid("A123")
True
>>> check_pid("A1234")
False
>>> check_pid("AA23")
False
```

These are just examples – there are many more situations to consider that you
should consider and test yourself.

Reminders:
- Don't forget about indexing: [https://stepik.org/lesson/467751/step/3?unit=458570](https://stepik.org/lesson/467751/step/3?unit=458570)
- Don't forget the `in` and `not in` operators: [https://stepik.org/lesson/467751/step/8?unit=458570](https://stepik.org/lesson/467751/step/8?unit=458570)

## Submission

Each of the programs above will be automatically graded by EdStem; you will
be able to see the results right away.

## Video Task

You must also record and upload a screencast that demonstrates that you
understand each of the programs you wrote. You will upload it to this Google Form:

[Submit your screencast here](https://docs.google.com/forms/d/e/1FAIpQLSfIqcdj9FYtIT1yLyz2i0UMxbkQWmAa-njPxSwhLtz9yC2U3g/viewform)

You should perform each of the following tasks in the recording:

1. Show your student ID with your face showing (so we can verify that it is
you).
1. With your code file showing, run your fill in the blanks program and give
the inputs `"fled"` and `"t-rex"`. Then, for each variable in your code file,
explain what value that variable holds. You could add a comment to write it
out as you describe it, or use interactions to demonstrate it, but you must
make that information clear.
2. With your code file showing, run your solar system program. At
interactions, call the function with the arguments `"venus"`, `100`. *In
the order they evaluate*, explain which lines of code in your program
evaluate to get the result you see at interactions. You could highlight or
comment on the lines that evaluate to do this demonstration.
3. With your code file showing, run your `check_pid` program. At
interactions, call the `check_pid` function 3 times with different arguments,
each returning `False`. For each, indicate which part of your function was
responsible for making it return `False`, and choose examples so that you
demonstrate a different part of your function each time.

Your total video shouldn't be longer than about 8 minutes – spend about 2-3
minutes on each prompt.

<div class='sidenote'>The tutorial shows some code from another class – you
will want to share your EdStem window with your solution.</div>

We've made a short tutorial demonstrating how to make a screencast with Zoom:

[Screencast Tutorial](https://drive.google.com/open?id=1KROMAQuTCk40zwrEFotlYSJJQdcG_GUU)

The associated video that was created is here:

[Example Result](https://drive.google.com/open?id=1MxJN6CQcXqIbOekDYMxjh7mTt1TyRVMl)


You don't have to make your screencast with Zoom, but Zoom is UCSD-licensed
software that you have access to, so we offer the tutorials with that in
mind.

Please do reach out if you run into issues with this, and try it out early so
you know if it will work or not for you. Feel free to reach out via a private
EdStem post for help with your recording. Make sure to check that your video
looks and sounds the way you want it before uploading it to the form. An easy
way to do this is to save it to your Google Drive and make sure you can watch
it by playing it from there – that's how we will watch the video when
grading.
