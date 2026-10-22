# Challenge 04: Evidence Backup and Integrity Verification

## Objective

The objective of this challenge was to practice backing up evidence files and verifying their integrity using Linux command-line tools.

## Tasks Completed

- Created backup copies of the original evidence files.
- Stored the backup copies in a separate directory.
- Compared the original files with their backups using `diff` and `cmp`.
- Checked the line counts of the files using `wc -l`.
- Checked the file sizes in bytes using `wc -c`.
- Calculated and compared SHA-256 hashes using `sha256sum`.

## Evidence Files

The original files are stored in `lab/evidence/raw/`:

- `auth.log`
- `incident.txt`
- `network.txt`

The backup copies are stored in `lab/backup/raw_backup/`.

## Tools and Commands

| Command | Purpose |
|---|---|
| `cp` | Copies files to a backup directory. |
| `diff` | Identifies differences between file contents. |
| `cmp` | Compares two files byte by byte. |
| `wc -l` | Counts the lines in a file. |
| `wc -c` | Counts the bytes in a file. |
| `sha256sum` | Calculates SHA-256 hashes to help verify file integrity. |

## Key Learnings

This challenge demonstrated that creating a backup is not enough on its own. The backup must also be checked against the original file.

I learned how to compare file contents, check line counts and file sizes, and use SHA-256 hashes to verify that the original evidence files and their backups match.

These techniques are useful when preserving and handling digital evidence in security investigations.
