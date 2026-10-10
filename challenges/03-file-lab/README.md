# Challenge 03: File Lab

## Goal

In this challenge, I practiced creating files, writing text to them, and inspecting their contents using basic Linux commands.

## What I Practiced

- **`printf`**: Writing text and creating simple log records manually.
- **`>` and `>>`**: Learning the difference between overwriting a file and appending new content.
- **`cat` and `less`**: Reading file contents, either all at once or page by page.
- **`head` and `tail`**: Viewing the beginning and end of a file, including a specific number of lines.
- **`wc -c`, `wc -l`, and `wc -w`**: Counting bytes, lines, and words.
- **`file`**: Checking the type of a file.

## Basic Log Concepts

I learned how simple log records can be organized using fields such as:

- user: The account involved in an event.
- event: The type of activity, such as a login or authentication attempt.
- result: The outcome, such as failed, denied, or success.
- source: The IP address where the connection originated.
- destination: The target IP address.
- method: The authentication method, such as a password or SSH public key.
- timestamp: The date and time when the event occurred.

I created fictional authentication records containing failed and successful login attempts. I also practiced using a consistent timestamp format, such as 2026-10-10T08:12:07, and learned why keeping each record on a separate line makes logs easier to inspect.

These are simplified, manually created examples for learning. Real system logs may use different formats and field names.

## Files Created

| File | Purpose |
|---|---|
| `auth.log` | Contains manually written authentication records, including failed and successful login attempts. |
| `system.log` | Intended for sample system events and service messages. |
| `failed_logins.log` | Intended for records of failed login attempts. |
| `network.log` | Intended for simple network activity records. |
| `incident.txt` | Contains a short incident summary. |
| `analyst_notes.md` | Used for notes and observations during the investigation. |
| `empty_sample` | An empty file used to practice file creation and file-type checks. |

## Notes

All log records in this lab are fictional and were written manually for practice. They are not collected from real systems.

This challenge helped me understand basic file handling and how simple log records can be inspected during security analysis.
