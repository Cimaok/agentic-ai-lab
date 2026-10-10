# 02 — LLM Fundamentals

This folder is for learning how a large language model (LLM) behaves before you wrap it in an agent. An agent is only as reliable as the model calls underneath it, so this section focuses on prompts, responses, and the settings that change them.

This is a practice space alongside Ed Donner's course. It does not replace the course materials.

## What you will learn

- What a prompt, a system message, and a user message are.
- How to send a request to a model and read the text it returns.
- How settings such as temperature change how varied the answers are.
- Why the same prompt can produce different answers, and how to make instructions more specific.
- How API keys stay in a local `.env` file and out of Git. `.env` is already listed in `.gitignore`.

## What you will practise

- Writing prompts for a single, well-defined task, such as summarizing a paragraph or extracting a list.
- Comparing a vague prompt with a precise one and noting what changed in the answer.
- Saving example prompts and the responses you got, so you can see your progress.

## How to use this folder

Add exercises only after you have a model API key and have added the package that lesson requires to `requirements.txt`. Until then, you can keep prompt notes in Markdown files in this folder. Never commit API keys.
