# Install a coding agent yourself lab: set up opencode and point it at a model, on a small project with tests

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [日本語](README.ja.md) | [Deutsch](README.de.md)

[![check](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml/badge.svg)](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml)

A ready-made lab for classrooms, from the [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning), where schools, colleges and universities give every student their own databases, containers and terminal in the browser. It is a lab where nothing is installed: you install opencode, an open-source AI agent, tell it where its model is, and then use it on a small project with tests.

## Using it on the platform

**This lab runs on the platform only.** Its agent reaches a model and a package proxy that the platform provides next to each student's copy, so `compose.yaml` does not start on its own machine. Every student gets a private copy with no way out to the internet.

**To try it:** open the [container page](https://mitsurutech.co.uk/container), find this lab in **Sample labs** and press Start. It needs a free account.

**To set it as work for a class:**

1. In your module, make a task of type **Lab** and choose **In a GitHub repository**.
2. Give `https://github.com/mitsurutech/lab-ai-agent-install` with the branch `main`. The compose file is the default, `compose.yaml`. Fork the repository first if you want to change it.
3. Publish. Every student's copy starts from the commit you published, so a later change here does not alter a lab already set.

The help manual's [page for this lab](https://mitsurutech.co.uk/help/lab-ai-agent-install) and its [guide to container labs](https://mitsurutech.co.uk/help/labs) cover the rest. The matching basic lesson is **AI Coding Agent Basics**. No college account yet? [Your first year is free](https://mitsurutech.co.uk/pricing) for up to 50 students, and [signing up](https://mitsurutech.co.uk/signup) takes an email address.

## What to know

The comment at the top of `compose.yaml` says how to start and what the agent may do. The agent asks before it changes a file or runs a command: read what it wants to do and say yes only when you understand it. **Nothing is saved**: stopping the lab forgets every file, so a student downloads their work before they stop it. What an assistant answers differs from one run to the next, so no result here is promised.

## Licence

This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). You may share it and adapt it for learning and teaching, if you credit Mitsuru Technologies Ltd, do not use it commercially, and share anything you make from it under the same licence. The full text is in the `LICENSE` file.

## About

Made by [Mitsuru Technologies](https://mitsurutech.co.uk) for the [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning): Python, Java, Go, Node, SQL and Linux in the browser for schools and colleges, with container labs, web apps deployed from GitHub, and quizzes that mark themselves. Try code with no account in the [playground](https://mitsurutech.co.uk/playground).

More labs from the same place: [lab-ai-agent](https://github.com/mitsurutech/lab-ai-agent), [lab-quantum-sim](https://github.com/mitsurutech/lab-quantum-sim), [lab-jupyter-data](https://github.com/mitsurutech/lab-jupyter-data) and [lab-git-gitea](https://github.com/mitsurutech/lab-git-gitea).
