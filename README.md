# ALX Pre-Course — Git & Development Environment Foundations

> First steps in the ALX Software Engineering curriculum: version control with Git, shell scripting, and introductory C compilation.

## Overview

This module covers the **pre-course onboarding phase** of the ALX Software Engineering program. It introduces the fundamental toolchain every engineer needs before writing production code: a Linux development environment, Git for version control, Bash for automation, and a first encounter with the C compiler.

Each task produces runnable scripts or compiled output.

## Skills covered


- Git repository initialization with proper `.gitignore` conventions
- Bash script authoring with correct shebangs, executable permissions, and POSIX-compliant syntax
- Git workflow practice: staging, committing, branching, and staying up to date with remote repositories
- First C program compilation and execution using `gcc`, including the edit-compile-run cycle
- Linux filesystem navigation and shell commands for daily development tasks

## Tech Stack

| Tool | Purpose |
|---|---|
| Git | Version control and collaboration |
| Bash | Shell scripting and automation |
| GCC | C compilation |
| Linux (Ubuntu) | Development environment |

## Project Structure

| Module | Topic | What Was Practiced |
|---|---|---|
| `0x01-git` | Git basics | Repository setup, `.gitignore`, Bash scripts (`alx`, `school`, `98`), first C file (`c_is_fun.c`), keeping branches up to date |

### Key files in `0x01-git`

| File | Description |
|---|---|
| `bash/alx` | Shell script printing a formatted greeting — first executable Bash program |
| `bash/school` | Shell script demonstrating basic output and script structure |
| `bash/98` | Script practicing multi-line output and shebang conventions |
| `c/c_is_fun.c` | First C source file — compiled with `gcc` to produce a runnable binary |
| `up_to_date` | Script demonstrating how to sync a local branch with its remote tracking branch |
| `.gitignore` | Configured to exclude editor artifacts and compiled binaries from version control |

## Getting Started

```bash
git clone https://github.com/mgn-dev/alx-pre_course.git
cd alx-pre_course

# Run a Bash script
chmod +x 0x01-git/bash/alx
./0x01-git/bash/alx

# Compile and run the C file
gcc 0x01-git/c/c_is_fun.c -o c_is_fun
./c_is_fun
```

**Requirements:** Ubuntu (or Vagrant VM), Git, GCC, Bash.

## Curriculum Context

This is the **entry point** of the ALX Software Engineering journey.

| Previous | Next |
|---|---|
| — | [alx-zero_day](https://github.com/mgn-dev/alx-zero_day) — deeper Git workflow practice |
| — | [zero_day](https://github.com/mgn-dev/zero_day) — Vagrant/Ubuntu environment setup |
