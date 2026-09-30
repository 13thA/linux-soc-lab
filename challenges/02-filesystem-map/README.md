# Challenge 02 — Filesystem Map

## Objective

Explore the Linux filesystem, understand the purpose of common directories, navigate using absolute and relative paths, create nested directories, and inspect hidden files.

## Commands Used

- `pwd` → Displays the current working directory.
- `cd` → Changes the current directory.
- `ls` → Lists files and directories.
- `ls -a` → Lists all files, including hidden files.
- `ls -l` → Displays files in long format with detailed information.
- `ls -la` → Displays detailed information, including hidden files.
- `mkdir -p` → Creates nested directories and any missing parent directories.

## Linux Path Concepts

- `/` → Root directory.
- `~` → Current user's home directory.
- `.` → Current directory.
- `..` → Parent directory.

## Absolute Paths

An absolute path starts from the root directory and specifies the complete location of a file or directory.

Example:

`/home/kali/linux-soc-lab/lab`

An absolute path points to the same location regardless of the current working directory.

## Relative Paths

A relative path starts from the current working directory.

Example:

`lab`

The meaning of a relative path depends on the current location.

## Nested Directory Structure

A multi-level directory structure was created using:

`mkdir -p lab/evidence/cases/case001`

If `lab` and `evidence` already exist, they are not recreated. The `-p` option creates only the missing directories in the path.

## Hidden Files

In Linux, files and directories beginning with `.` are considered hidden.

`ls` displays regular files and directories.

`ls -a` displays regular and hidden files.

`ls -la` displays regular and hidden files with detailed information.

To filter hidden files and directories while excluding `.` and `..`:

`ls -d .[^.]*`

## Key Takeaways

- Use `pwd` to verify the current location.
- Use `~` to navigate to the home directory.
- Use `..` to move to the parent directory.
- Understand the difference between absolute and relative paths.
- Use `cd` when navigating to a directory.
- A directory path entered without `cd` is interpreted by Bash as a command or executable path.
- Use `mkdir -p` to create nested directory structures.
- Use `ls -a` or `ls -la` to inspect hidden files.

## Lab Structure Created

```text
lab/
└── evidence/
    └── cases/
        └── case001/
```

## Status

Challenge completed.
