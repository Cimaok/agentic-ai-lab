# 06 — Multi-Agent Systems

This folder is for systems where more than one agent works on a task. Each agent has a narrower job, such as researching, drafting, or checking, and they pass work to one another.

This is a practice space alongside Ed Donner's course. It does not replace the course materials.

## What you will learn

- Why you might split one big prompt into several specialized agents.
- How agents hand work off: one agent's output becomes the next agent's input.
- Common patterns, such as a coordinator that assigns tasks, or a reviewer that checks another agent's work.
- What goes wrong when roles overlap or instructions conflict.
- How to keep a readable trace of which agent did what.

## What you will practise

- Two agents with different instructions working on the same short task.
- A simple handoff, where agent A produces a draft and agent B reviews it.
- Writing a one-paragraph role description for each agent before you write code.

## How to use this folder

Start with two agents. Add a third only when you can explain what the first two are each responsible for. Save the message each agent receives and returns so you can debug the handoff.
