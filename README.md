# Pepper — AI-Powered Human–Robot Brainstorming

**Bachelor's thesis project · Computer Science & Engineering · TU Delft · 2026**

How does collaborating with an AI-powered robot affect the way people brainstorm—and how capable they feel while doing it?

For my bachelor's thesis, I independently developed a research implementation using **Pepper**, a humanoid social robot, to investigate how different forms of robot participation influence human creativity, collaboration, and self-perception.

## Project overview

I implemented and evaluated two approaches to robot-assisted brainstorming:

* **Dynamic collaborator:** Pepper listens to the discussion, responds in real time, asks clarifying questions, builds on ideas, and helps the group move from generating possibilities to refining a final proposal.
* **Prepared intervention partner:** Pepper contributes pre-generated ideas and structured interventions at set moments, supported by visual material shown on a laptop.

The goal was not to find the “best” language model, but to explore how a robot's **interaction style** changes people's experience of working with it.

## What I built

* An end-to-end spoken-interaction pipeline connecting participant speech to AI-generated or prepared robot responses.
* **Speech recognition** using Deepgram Nova, with two microphones to capture the participants' contributions.
* **Real-time dialogue** using Qwen3-8B, including behaviour triggered by direct questions, pauses, uncertainty, or repetitive discussion.
* A structured brainstorming flow that supports **divergent thinking** (generating ideas) and **convergent thinking** (developing a solution).
* A second interaction mode featuring prepared interventions and visual summaries, using material generated with GPT-5.5 and GPT-image-2.0.
* Study procedures and questionnaires to evaluate the participant experience.

The live robot interactions were **system-driven**, not controlled by a hidden human operator.

## Technology

`Python` · `Pepper robot` · `Deepgram Nova` · `Qwen3-8B` · `GPT-5.5` · `GPT-image-2.0` · `Speech interfaces` · `Human–Robot Interaction`

## Research and findings

I conducted a between-subjects study with **20 participants in 10 pairs**, comparing the two Pepper configurations during creative brainstorming sessions.

The study explored perceived collaboration, social comparison, self-efficacy, perceived competence, engagement, and the robot's contribution to the group.

**Descriptively**, real-time collaboration was associated with higher self-efficacy and perceived competence; prepared interventions were rated slightly more engaging and useful but also led participants to perceive Pepper as more influential. Given the small sample, these are exploratory observations rather than definitive causal conclusions.

## My contribution

I independently designed and implemented the **thesis-specific Pepper interaction system** and carried out the study as part of my TU Delft bachelor research, with academic supervision. This repository is forked from a shared university project; the original contributors and repository history remain credited.

## Repository notes

This is a **research prototype**, not a ready-to-install consumer application. Running it may require access to a Pepper robot, compatible software, and configured external AI and speech services. Environment-specific installation instructions are not documented here.

For the full research context, see my bachelor's thesis:

*When Pepper Brainstorms With Us: Robot Facilitation and Social Comparison in Creative Group Ideation* (TU Delft, June 2026).
