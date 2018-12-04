---
title: 'Creating an output'
description: 'How to use the print function to create an output using Python'
---

## Example 1

```yaml
type: NormalExercise
key: e8c1edbe67
lang: python
xp: 100
skills: 2
```

The example below demonstrates how to code a very simple output using Python

`@instructions`
All you have to do here is take a look at the code and then click on RUN

`@hint`
You just click on the run button!

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}
print("Hi")
```

`@solution`
```{python}
print("Hi")
```

`@sct`
```{python}
Ex().has_output(r'Hi')
success_msg("Well Done!")
```

---

## Insert exercise title here

```yaml
type: NormalExercise
key: ffc6e00c2d
xp: 100
```

Outputting text using the print function.

`@instructions`
Python uses the `print()` function to output information to the screen.
Anything between the parenthesis will appear on the screen. Anything you add between the parenthesis is called _an argument_.
When we want the computer output text, we must also use quotation marks surrounding out text like in the previous example.
`"hi"`
Try to print out your name in the windows below.
The output should be in this format:
`My name is _name_.`

`@hint`
You must write `print` in lower case and put and your argument between the parenthesis.

`@pre_exercise_code`
```{python}

```

`@sample_code`
```{python}

```

`@solution`
```{python}

```

`@sct`
```{python}
Ex().has_output(r'[H|h]i,\s+my name is \w+')
success_msg("Well Done!")
```
