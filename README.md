# CommTools2

> ## **This is a repository that is used for demonstration purposes only.<br>It exists only temporarily!**

Basic communication tools for the session, mainly used by user commands and test cases.

## Overview

Comes with these functions and operators: 

* `YesOrNo` for asking questions like "Are you sure?"
* `Select` for letting the user choose from a set of options
* `Pause` for printing a message to the session and asking the user to press `<enter>` to continue
* `AskForNumber` for stuff like "Number of copies"
* `AskForText` for stuff like "Enter your name"

These functions and operators have three features in common:

* They can all be interrupted by entering `∘∘∘`
* They can be automated by setting certain variables within the `CommTools` namespace

  This allows you to automate tests that would otherwise require a human to interact with.

`AskForNumber` and `AskForText` are operators that require a check function as the left operand. They allow checking the input and rejecting or accepting it.

## Documentation

You may ask for detailed documentation with

```
      ]ADoc #.CommTools
```
