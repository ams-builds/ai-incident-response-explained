# Jargon Buster

Simple meanings of the technical words in this project. The README avoids these words where it can. This file gives the exact words for readers who want them.

**Agent**
An AI system that plans steps and uses tools, such as a search, a database, or an API, to do a task.

**Agent skill**
A `SKILL.md` file that gives an AI agent instructions for one task. The open [Agent Skills](https://agentskills.io) format works with many AI agents.

**Blast radius**
How much an incident can damage: how many users, how much data, and which systems.

**Blameless review**
A meeting after an incident that looks for the cause and the fix. It does not look for a person to blame. The source calls it a blameless post-mortem.

**Containment**
The first actions that stop the damage of an incident. Examples are to disable a tool, to roll back to an earlier version, or to block an input.

**Data poisoning**
An attack that puts bad data into the data that a model learns from or reads. The bad data changes what the model says or does.

**Eradication**
The removal of the cause of an incident, for example a bad data source or a weak prompt.

**Forensics**
The investigation of an incident from the records. For an AI system, the records include the prompts, the raw output, and the tool calls.

**Guardrail**
A check that stops a model or an agent from an unsafe input or output.

**Incident**
An event that damages an AI system, its data, or its users, or that can damage them.

**Least privilege**
A rule that gives an agent only the access that its task needs, and no more.

**Playbook**
A short written plan for one type of incident. It tells you how to detect it, how to contain it, how to fix it, and who to tell.

**Prompt injection**
An attack that hides instructions in text that the agent reads, such as a web page or an email. The agent then follows the instructions of the attacker.

**RACI**
A table that shows who is Responsible, Accountable, Consulted, and Informed for each task in an incident.

**Raw output**
The exact text or action that the model gave, before any filter or change. An AI model can give a different answer to the same input, so the raw output is important evidence.

**Retrieval (RAG)**
Retrieval-augmented generation. The model reads documents from a data source before it answers.

**Rollback**
A return to an earlier version that worked correctly.

**Telemetry**
The signals that a system records about its operation, such as logs, errors, and usage.

**Triage**
The first decision about how serious an incident is, and who must know about it.
