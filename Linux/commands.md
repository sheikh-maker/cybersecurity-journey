# Linux Commands Cheat Sheet

## Navigation & File Management

| Command | Description |
|---|---|
| pwd | Show current directory |
| ls | List files and directories |
| ls -la | List all files including hidden files with details |
| cd | Change directory |
| cd .. | Move to parent directory |
| mkdir | Create a new directory |
| touch | Create a new file |
| cp | Copy files or directories |
| mv | Move or rename files/directories |
| rm | Remove files |
| rm -r | Remove directories recursively |
| file | Identify file type |

---

## Reading Files

| Command | Description |
|---|---|
| cat | Display file contents |
| less | Read files page by page |
| more | Read files page by page |
| head | Show first lines of a file |
| tail | Show last lines of a file |
| tail -f | Monitor file changes in real time |
| nano | Edit files in terminal |
| vim | Advanced text editor |

---

## Searching & Filtering

| Command | Description |
|---|---|
| find | Search for files and directories |
| locate | Quickly search files |
| grep | Search text patterns |
| grep -r | Search recursively inside directories |
| sort | Sort output |
| uniq | Remove duplicate lines |
| wc | Count lines, words, characters |
| cut | Extract sections from text |
| awk | Process and analyze text |
| sed | Search and modify text |

---

## File Permissions

| Command | Description |
|---|---|
| chmod | Change file permissions |
| chown | Change file ownership |
| chgrp | Change group ownership |
| ls -l | View permissions |

Permission examples:

```bash
chmod +x file.sh
chmod 755 file
