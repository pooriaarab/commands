# commands design

## Overview

This repository is reserved for slash commands and shortcuts for agent CLIs.

No command is implemented. This document records current evidence and prevents invented interface rules.

## Colors

No palette or terminal color behavior exists. Do not assign semantic colors before an implemented command needs them.

## Typography

No font, text scale, or terminal emphasis rule exists.

Use plain Markdown for repository documentation. Rendered command text remains undefined until a command implementation sets its contract.

## Layout

The only command path is the empty `commands/` directory. It contains `.gitkeep` and no command hierarchy.

The root README explains this repository's place among `agents`, `skills`, `clis`, `scripts`, and `prompts`.

## Elevation & Depth

No graphical elevation or command depth exists.

Do not document nesting, menus, or interaction layers until repository files implement them.

## Shapes

No icon, logo, border, container, or other visual shape exists.

Do not borrow visual assets from the sibling repositories listed in the README.

## Components

There are no command files, templates, parsers, runtime components, or packages.

`README.md`, `.gitignore`, and `commands/.gitkeep` are the only tracked files before this design context.

## Do's and Don'ts

Do keep statements tied to tracked files.

Do update this document when an implemented command establishes a real interface pattern.

Do state incomplete work as incomplete.

Don't invent command names, syntax, flags, output, shortcuts, or execution behavior.

Don't invent a visual identity, website, custom domain, deployment target, or release process.

Don't treat the sibling repository list as a shared runtime contract.
