# OX-ELL

<p align="center">
  <img src="https://raw.githubusercontent.com/venus-ox/ox-alpha/main/assets/hermes-banner.png" alt="OX-ELL" width="100%" />
</p>

OX-ELL is a real terminal-style AI agent platform built for messaging-first workflows, designed to live directly inside Telegram and Zalo. It gives users a powerful conversational interface with multi-line editing, slash-command autocomplete, conversation history, interruption and redirection, and streaming tool output in a fast, natural experience.

This project is not just a chatbot. It is a unified gateway for intelligent communication and action across the channels people already use every day. OX-ELL is meant to be the AI layer that handles work, queries, automation, and collaboration directly inside the same apps users already trust.

## Overview

OX-ELL brings together a full terminal interface and a modern AI assistant experience in one system. It supports:

-    Full TUI with multi-line editing
-    Slash-command autocomplete
-    Conversation history and context continuity
-    Interrupt-and-redirect workflow
-    Streaming tool output in real time
-    Cross-platform continuity across Telegram, Zalo, and CLI
-    Voice memo transcription and follow-up processing
-    A single gateway process for multiple messaging surfaces

This makes OX-ELL ideal for users who want an AI assistant that feels native to chat apps while still being powerful enough for real execution and automation.

## Where OX-ELL lives

OX-ELL is designed to operate where users already communicate:

-    Telegram
-    Zalo
-    WhatsApp
-    Signal
-    Discord
-    Slack
-    CLI environment

The system is built around a single gateway process that can route messages and actions across channels without breaking continuity. This creates a seamless experience for personal use, team operations, and automation workflows.

## Closed learning loop

OX-ELL includes a memory system that improves over time through usage. Its learning loop is designed to:

-    Curate memory from conversations and tasks
-    Send periodic nudges and reminders
-    Create autonomous skills after complex tasks
-    Improve skills through repeated use
-    Search session history with FTS5 indexing
-    Summarize cross-session knowledge with LLM-based recall
-    Model user behavior with dialectic user modeling
-    Remain compatible with the open agentskills.io standard

This creates a system that learns, adapts, and becomes more capable with each interaction.

## Scheduled automations

OX-ELL supports scheduled automations for unattended execution, including:

-    Daily reports
-    Nightly backups
-    Weekly audits
-    Triggered reminders
-    Automated task summaries
-    Group or channel notifications

These tasks can be delivered to any platform and run naturally in language rather than raw scripts.

## Delegation and parallelism

OX-ELL is built to scale with work.

It can:

-    Spawn isolated subagents for parallel workstreams
-    Delegate complex tasks to specialized agents
-    Run Python scripts over RPC-based tool access
-    Collapse multi-step pipelines into low-context turns
-    Improve throughput without losing clarity

This gives the system a strong foundation for both individual productivity and team-level automation.

## Runs anywhere

OX-ELL is designed to work across different environments, not just on a local laptop. It supports multiple terminal backends, including:

-    Local terminal
-    Docker
-    SSH
-    Singularity
-    Modal
-    Daytona
-    Vercel Sandbox

This flexibility allows the system to run on low-cost infrastructure as well as GPU-powered clusters. Daytona and Modal can preserve environment state when idle, which reduces cost while keeping the agent ready when needed.

## Research-ready capabilities

OX-ELL is also suitable for research and model-training workflows:

-    Batch trajectory generation
-    Trajectory compression
-    Tool-calling model data collection
-    Evaluation pipelines for agent behavior
-    Iterative improvement of reasoning and action quality

This makes it useful both as a real-world assistant and as a research platform for the next generation of agentic systems.

## Core values

OX-ELL is built around a few core ideas:

-    Human-centered interaction
-    Practical automation
-    Persistent memory
-    Reliable execution
-    Cross-platform continuity
-    Fast and clear communication

## Project vision

The long-term goal of OX-ELL is to become a universal AI gateway for real-world communication and automation. Instead of forcing users into a single interface, OX-ELL sits at the center and connects intelligence across Telegram, Zalo, CLI, and other workflows.

It is built to help users move from conversation to action, from intent to execution, and from scattered tools to one continuous AI operating layer.

## Getting started

```bash
git clone https://github.com/venus-ox/ox-alpha.git
cd ox-alpha
# install dependencies
# run the project
```

## Project structure

## License

This project is currently under active development. Please check the repository for license details and usage terms.

---

Built for a smarter, more connected AI experience across chat and command-line workflows.
