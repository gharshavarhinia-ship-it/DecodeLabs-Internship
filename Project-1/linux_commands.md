# Linux Commands

This document contains commonly used Linux commands required for basic system navigation and file management.

---

## Navigation Commands

### Display Current Directory

```bash
pwd
```

Displays the current working directory.

---

### List Files and Directories

```bash
ls
```

Lists all files and folders in the current directory.

---

### Change Directory

```bash
cd folder_name
```

Moves into the specified directory.

Example:

```bash
cd Documents
```

---

### Move Back One Directory

```bash
cd ..
```

Moves to the parent directory.

---

## File and Directory Commands

### Create a Directory

```bash
mkdir folder_name
```

Example:

```bash
mkdir Project
```

---

### Create an Empty File

```bash
touch filename.txt
```

Example:

```bash
touch notes.txt
```

---

### Display File Contents

```bash
cat filename.txt
```

Example:

```bash
cat notes.txt
```

---

### Copy Files

```bash
cp source_file destination_file
```

Example:

```bash
cp notes.txt backup.txt
```

---

### Move or Rename Files

```bash
mv old_name new_name
```

Example:

```bash
mv backup.txt final.txt
```

---

### Delete a File

```bash
rm filename
```

Example:

```bash
rm final.txt
```

---

### Delete a Directory

```bash
rm -r folder_name
```

Example:

```bash
rm -r Project
```

---

## Viewing File Contents

### Display First 10 Lines

```bash
head filename.txt
```

---

### Display Last 10 Lines

```bash
tail filename.txt
```

---

## File Permissions

### Change File Permissions

```bash
chmod 755 filename
```

Example:

```bash
chmod 755 script.sh
```

---

## Useful Commands

### Clear Terminal

```bash
clear
```

---

### View Command History

```bash
history
```

---

### Display Current User

```bash
whoami
```

---

### Display Current Date and Time

```bash
date
```

---

### Display Calendar

```bash
cal
```

---

## Summary

| Command | Description |
|----------|-------------|
| pwd | Show current directory |
| ls | List files and folders |
| cd | Change directory |
| cd .. | Move to parent directory |
| mkdir | Create directory |
| touch | Create file |
| cat | Display file contents |
| cp | Copy files |
| mv | Move or rename files |
| rm | Delete files |
| rm -r | Delete directories |
| head | Display first 10 lines |
| tail | Display last 10 lines |
| chmod | Change file permissions |
| clear | Clear terminal |
| history | Show command history |
| whoami | Display current user |
| date | Display date and time |
| cal | Display calendar |