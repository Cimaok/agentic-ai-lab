# 05 — MCP

This folder is for the Model Context Protocol (MCP). MCP is a standard way for an AI application to connect to tools and data sources. Instead of wiring every tool by hand inside one script, an MCP server exposes tools that a client (such as an agent or Cursor) can discover and call.

This is a practice space alongside Ed Donner's course. It does not replace the course materials.

## What you will learn

- What an MCP server and an MCP client are, and how they talk to each other.
- How a server lists its tools so a client can discover them.
- How this differs from tool calling written directly inside one Python file.
- Why a shared protocol makes it easier to reuse the same tools across different apps.
- The basic shape of a small local MCP server before you connect to anything remote.

## What you will practise

- Reading an MCP tool list and explaining, in your own words, what each tool does.
- A minimal local server that exposes one simple tool.
- Connecting a client to that server and calling the tool end to end.

## How to use this folder

Add notes and small examples as the course introduces MCP. Keep servers local while you are learning. Write down which process is the server and which is the client so the roles stay clear.
