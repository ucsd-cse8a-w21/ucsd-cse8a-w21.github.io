---
layout: page
title: "UCSD CSE8A W21 – PA3 (Programming Assessment)"
doodle: "/doodle.png"
---

# PA6 (Programming Assessment)

**Due Tuesday, February 16, 4pm Pacific Time**

This assessment is to be completed entirely on your own. You can ask
_private_ questions about the assignment on Edstem, but it's likely that we
won't give detailed answers and won't help you debug your program. The intent
of this assessment is to give a grade to your understanding of the material
from the course so far.

You can use any course resources, videos, Google searches, and so on to
complete this assessment. You _cannot_ communicate with anyone else or get
staff help to complete it. You can ask staff questions about making your
video or submission logistics, but they have been instructed to not help with
your program.

You will also complete a video screencast demonstrating part of the PA for
grading, which is detailed at the end of this description.


## Programming Tasks

### Task 1 - Checking Usernames

Complete this task in the first slide of the lesson.

A standard restriction on usernames is that they contain only characters from
a-z or digits 0-9, and have length at least 4

Write a program that prompts a user for input with the message `"Enter a
username: "`. If they enter a valid username, it should print `"Thanks,
username saved"`, and the program should end. If they enter an invalid
username, it should print one of the following strings:

- `"Too short"` if the string is shorter than 4 characters
- `"Invalid character"` if the string is 4 or more characters and has invalid
characters

Then it should prompt them to enter the username again, and repeat until
something valid is entered, then print the `"Thanks, username saved."`
message and end.

### Task 2 – Functions

Complete this task in the second slide of the lesson. For each function,
implement it in the file corresponding to the name of the function
(`average_of_prefix.py` for the first one, and so on).

For at least _one_ of these functions, you _must_ use `map` or `filter` in
order to demonstrate your understanding in a video task below. Other than
that constraint, you are free to choose which strategies you use for
implementing the functions below.

- Write a function `average_of_prefix` that takes a list of numbers and a
non-negative number `n` and produces the average (mean) of the numbers in the
list up to, but not including, index `n`. If the list has fewer than `n`
numbers, return the average of the whole list. If there are no numbers to
average, return `0`.

    Example:

    ```
    >>> average_of_prefix([5, 6, 7, 100, 200], 3)
    6
    ```

- Write a function `longest_s_word` that takes a list of strings and returns
the longest string in the list that starts with `"s"` or `"S"`. If there is a
tie, it should return the one at the earliest index. If there is no word that
starts with `"s"` or `"S"`, it should return the empty string.

    Example:

    ```
    >>> longest_s_word(["surf", "salad", "agree"])
    'salad'
    ```

- Write a function `truncate_all`, that takes a list of strings and a
positive number `n`, and produces a new list of strings, where each string in
the resulting list is _truncated_ (or shortened) to length `n`. To truncate a
string, if it is longer than `n`, take only the first `n` characters. If it's
shorter, leave it unchanged.

    Example:

    ```
    >>> truncate_all(["surf", "salad", "agree"], 2)
    ["su", "sa", "ag"]
    ```

- Write a function `sum_larger` that takes a list of numbers and a number
`n`, and produces a number that's the sum of numbers in the list that are
larger than `n`.

    Example: 

    ```
    >>> sum_larger([5, 6, 1, 2, 7], 4)
    18
    ```

## Video Tasks

1. For task 1, show your program running for at least 2 unsuccessful inputs,
one of each type of invalid username, followed by a successful input. Present
a loop trace of the program for all the variables that changed during the
loop. [Watch a sample loop video](https://drive.google.com/file/d/1dGySNMB23fW0V8fjJBWZw5hmM8kAdY6A/view?usp=sharing) to see what we have in mind.
2. Choose an example from Task 2 where you used either map or
filter. Show a meaningful example at interactions of calling a function you wrote
that calls map/filter on a list of length at least 4. Then show a trace of
the use of map or filter. If the function you chose
uses multiple of map/filter, choose
just one map or filter call to demonstrate. Watch a [sample map
video](https://drive.google.com/file/d/1KqHhi0u-So3sz6cAr57mEPjGfK1f8bGf/view?usp=sharing)
or a [sample filter
video](https://drive.google.com/file/d/12aJeouO9IWdiBAQ1fbXKEko4T7ITf6Uc/view?usp=sharing) to see what we have in mind.

## Submission

Make sure to click ✔️**Mark** on both slides (Task 1 and Task 2) before the
deadline.

Upload your video here: 

[Google Form Video Upload](https://docs.google.com/forms/d/e/1FAIpQLSd5v1z_Xjnu1kyMGMVFnmvlZkxCJqxZ1p6AOZ2bpSAQTs1cNQ/viewform)
