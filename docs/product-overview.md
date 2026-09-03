# OX-ELL Product Overview

## What OX-ELL is

OX-ELL is an AI-native operating layer for conversations and execution. It connects Telegram, Zalo, and terminal-style workflows so that a user can move from an instruction to an action without losing context between channels.

The product is designed around a simple idea: an agent should become more useful over time by retaining the context needed to plan, use tools, and continue work naturally.

## The problem

Most chat experiences end at an answer. Real work usually needs more: keeping track of the goal, breaking work into steps, invoking the right tools, and returning to the task later from another channel.

OX-ELL aims to provide that continuity in a messaging-first experience.

## Core capabilities

- **Conversation with context** — carry relevant history and intent through a task instead of treating each message as isolated.
- **Terminal-style interaction** — support deliberate, multi-line input and command-oriented workflows alongside ordinary chat.
- **Slash commands and task planning** — give users direct ways to initiate repeatable workflows and turn intent into an actionable plan.
- **Tool execution and automation** — connect an agent's reasoning to tools so it can help perform work, not only describe it.
- **Cross-channel continuity** — make Telegram, Zalo, and CLI touchpoints feel like one ongoing workspace.
- **Memory and learning loops** — retain useful context so the agent can adapt to the user over time.

## Product principles

### Messaging first

The conversation is the interface. OX-ELL should feel natural in the chat apps people already use, while remaining capable enough for technical and structured work.

### Action over answers

An answer is valuable when it helps move work forward. OX-ELL is built to bridge chat, planning, and execution in one flow.

### Context should travel

Users should be able to begin in one channel and continue in another without repeatedly reconstructing the task.

### Memory should earn trust

Remembered context must be useful, relevant, and handled with care. Memory is a product capability, not an excuse to retain everything.

## Conceptual flow

1. A user sends a message in Telegram, Zalo, or the CLI.
2. OX-ELL interprets the request with the available conversation context.
3. The agent responds, plans next steps, or selects an appropriate tool or automation.
4. The result becomes part of the continuing task context, available when the user returns through another supported channel.

## Current scope

OX-ELL is under active development. The repository currently communicates the product direction and contribution process; implementation details, public APIs, supported integrations, and deployment instructions will be documented as they become stable.

## Contributing

See [CONTRIBUTING.md](../CONTRIBUTING.md) for the contribution workflow and [SECURITY.md](../SECURITY.md) for responsible vulnerability reporting.
