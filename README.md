# Git hooks templates

This repo is meant to hold my collection of git hooks. Bellow, I'll write a small summary for each of the available hooks. You can find the `hooks` inside the respective folder.

Looking for the article I wrote about git hooks? You can find it [here](https://dev.to/rafaelcpalmeida/enhancing-your-git-commit-messages-3mk7) or [here](https://hackernoon.com/enhancing-your-git-commit-messages-2a299295o).

# Prepare commit message
This hook retrieves your ticket ID from your branch name. Given, for instance, the following branch name `feature/ABC-1234-Feature-testing` every time you write a new commit message it will prepend `ABC-1234 - ` to your commit message.
