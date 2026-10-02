## AI interaction 1

Date: 10/1/2026

Assistant: Claude Opus 5.5 Medium

Purpose: Provide explanation

Prompt: Explain the difference between a repository, branch, commit, pull request, and issue. Give a three sentence summary.

Response: A repository is the whole project and its full history, made up of commits, which are individual snapshots of changes with a message and unique ID. A branch is a separate line of commits that lets you work on a feature or fix without affecting the main code. A pull request asks to merge one branch into another so teammates can review the changes, while an issue is a tracked bug, task, or request that describes work to be done and is often closed by a pull request.



## AI interaction 2

Date: 10/1/2026

Assistant: Claude Opus 5.5 Medium

Purpose: Ask for checklist

Prompt summary: \[Issue text from repo] Suggest a checklist for a complete pull-request description.

Response: ## Summary

- [ ] One or two sentences describing what this PR changes and why

- [ ] List of the main changes (files added or modified)



## Linked issue

- [ ] Closing keyword referencing the issue (e.g., `Closes #1`)



## Changes

- [ ] README.md updates, if any

- [ ] ai-log.md added with three logged AI interactions

- [ ] Any other files added or modified



## Evidence

- [ ] Link to or list of the commits on the feature branch (at least three)

- [ ] Screenshots or rendered previews of key files (README, ai-log.md)

- [ ] Confirmation that the branch is up to date with `main` and has no merge conflicts



## AI use

- [ ] Brief note on how AI was used for this change

- [ ] Pointer to ai-log.md entries showing accepted, revised, and rejected suggestions



## Review checklist

- [ ] Branch name follows a clear convention (e.g., `feature/ai-workflow-docs`)

- [ ] Commit messages are descriptive and explain \*why\*, not just \*what\*

- [ ] Self-review completed before requesting review

- [ ] Acceptance criteria from the issue are addressed

Decision: Revised

Reason: Remove references to pointers and screenshots.

GitHub link: https://github.com/beburger/swe325_525-github-ai-practice/pull/2



## AI interaction 3

Date: 10/1/2026

Assistant: Claude Opus 5.5 Medium

Purpose: Propose improvement 

Prompt summary: Review my README.md for clarity and suggest simple revisions: \[README.md content]

Useful suggestion:

# SWE 325/525 GitHub AI Practice



This repository documents my GitHub workflow using AI assistance for Lab 8 of SWE 525 Software Construction.

**Author:** Braeden Burger

## Purpose

Practice a standard GitHub workflow (issues, feature branches, commits, and pull requests) while recording how AI tools were used along the way.

## Repository contents

| File | Description |
| --- | --- |
| `README.md` | Overview of the repository |
| `ai-log.md` | Record of AI interactions, including accepted, revised, and rejected suggestions, plus reflection answers |
| `workflow-notes.md` | Notes on the GitHub workflow followed for this lab |

## Workflow

1. Create an issue describing the work
2. Develop changes on a feature branch
3. Make small, meaningful commits
4. Open a pull request linked to the issue
5. Review, revise, and merge

## Scope

This lab is limited to GitHub workflow and AI-use documentation.

Decision: Accepted

Reason: The revised README.md contains a more in depth summary of the repository with info about each of the newly added files.

Related GitHub URLs: 
https://github.com/beburger/swe325\_525-github-ai-practice/commit/2ef49020ee0995385788211c76df03e513a3aebf
https://github.com/beburger/swe325\_525-github-ai-practice/commit/d5c589b13fa34b8925594ecedce09dec69a4197a
