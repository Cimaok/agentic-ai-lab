# 07 — Agentic Workflows

This folder is for workflows: a defined series of steps an agent system follows to finish a job. A workflow can mix model calls, tools, checks, and human review so the same kind of task can be run again reliably.

This is a practice space alongside Ed Donner's course. It does not replace the course materials.

## What you will learn

- The difference between a free-form agent and a workflow with named steps.
- How to break a task into steps such as plan, gather, draft, check, and finish.
- Where a human should approve a step before the workflow continues.
- How to record inputs and outputs so you can rerun a workflow and compare results.
- How failures in one step should stop or retry instead of silently continuing.

## What you will practise

- Writing a workflow as a short list of steps in Markdown before coding it.
- A small workflow with two or three steps and a clear final output.
- Adding one check, such as "stop if the draft is empty," so you can see a workflow fail safely.

## How to use this folder

Describe the workflow in plain language first. Then implement only the steps you can test. Keep each workflow in its own file or subfolder once it grows beyond a single script.
