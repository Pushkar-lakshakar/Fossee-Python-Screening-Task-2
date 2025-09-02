# Python Debugging Assistant

This repository contains a short, reusable prompt (in `PROMPT.md`) and supporting notes to run an AI assistant that helps students debug Python code without providing the final corrected solution. The assistant is designed to guide with hints, diagnostics, and questions that build debugging skills.

## Setup instructions

Clone or download the repository to your machine (`git clone <repo-url>` or use the GitHub UI). Open the file `PROMPT.md` and copy its contents into your AI assistant of choice as the system instruction or initial prompt. When using the assistant, paste the student's code, the exact error messages or failing outputs, and a short statement of the intended behavior and constraints; then ask the assistant to debug in no-solution mode. Keep the assistant pinned to the prompt so it continues to refuse direct solutions and instead offers tiered hints, diagnostics (print/`assert`/`breakpoint()` examples only), and a reflective question at the end of each reply.

## Files included

The repository includes two files: `PROMPT.md`, which holds the full prompt to give the AI, and this `README.md`, which contains setup steps and concise reasoning.

## Reasoning

The prompt is intentionally brief and prescriptive so the assistant understands its role and boundaries: diagnose with evidence, suggest checks and minimal debugging snippets, and avoid pasting corrected functions or final algorithms. This structure encourages students to fix bugs themselves while learning debugging habits. The prompt also adapts automatically to learner level by asking the assistant to simplify language for beginners and to focus on invariants and test design for advanced learners.

If you want, I can also add a one-line example of the initial user message to paste alongside the prompt (keeps the repo minimal but more usable).

