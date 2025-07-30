# Lab #1

This lab focuses on outcomes related to passing in 3 different params (File Argument, Directory Argument, Empty Argument) for each of the following terminal commands: `cd`, `ls`, and `cat`.

## Overview

In this lab, we explored how basic Unix commands respond when given:
- A **file argument** (e.g., `cd file.txt`)
- A **directory argument** (e.g., `ls folder/`)
- An **empty argument** (just the command alone, e.g., `cat`)

We captured screenshots of each case and documented the behavior.

---

## `cd` Command

| Argument Type       | Screenshot            | Description |
|---------------------|-----------------------|-------------|
| Empty Argument      | `cd_blankargs`        | Shows current behavior when no directory is specified. Typically navigates to the user's home directory. |
| File Argument       | `cd_fileArgs`         | Demonstrates error when trying to `cd` into a file. |
| Directory Argument  | `cd_DirectoryArgs`    | Navigates into the specified directory without issues. |

---

## `ls` Command

| Argument Type       | Screenshot            | Description |
|---------------------|-----------------------|-------------|
| Empty Argument      | `ls_blankargs`        | Lists contents of the current directory. |
| File Argument       | `ls_fileArgs`         | Displays the filename if it exists, or an error if it doesn't. |
| Directory Argument  | `ls_DirectoryArgs`    | Lists contents inside the specified directory. |

---

## `cat` Command

| Argument Type       | Screenshot            | Description |
|---------------------|-----------------------|-------------|
| Empty Argument      | `cat_blankargs`       | Waits for user input from stdin (keyboard); shows no output until terminated. |
| File Argument       | `cat_fileArgs`        | Displays the contents of the specified file. |
| Directory Argument  | `cat_DirectoryArgs`   | Throws an error — cannot `cat` a directory. |

---

## Summary

This lab helped reinforce the way Unix-based systems interpret arguments passed to basic shell commands. The error handling and default behaviors of `cd`, `ls`, and `cat` depend strongly on the type of argument passed in.

