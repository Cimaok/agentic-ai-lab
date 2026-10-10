# 04 — Tool Calling

This folder is for teaching a model to use tools. Tool calling (also called function calling) lets the model ask your program to run a function, such as a calculator, a search, or a database lookup, and then use the result in its answer.

This is a practice space alongside Ed Donner's course. It does not replace the course materials.

## What you will learn

- What a tool is: a normal Python function with a name, a description, and typed inputs.
- How the model chooses a tool instead of inventing an answer.
- How your code runs the tool and sends the result back to the model.
- Why clear tool descriptions matter. The model only knows what you tell it.
- How to handle a tool that fails or returns nothing useful.

## What you will practise

- One or two simple tools, such as adding numbers or looking up a value in a small dictionary.
- A short agent that must call a tool to get the right answer, so you can see the call happen.
- Writing tool descriptions that a beginner (and a model) can understand.

## How to use this folder

Keep tools in their own functions so they are easy to test without a model. Add a new file when you try a new kind of tool. Leave real external services for later sections, after these local tools feel familiar.
