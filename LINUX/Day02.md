# Day 01 - Basic Linux Commands

## Commands Learned

### pwd
Print Working Directory

Shows the current directory you are in.

Example:
```bash
pwd
```

Output:
```text
/home/nitya
```

---

### ls
List files and directories.

Example:
```bash
ls
```

Output:
```text
Documents Downloads Music Pictures
```

---

### ls -l
Lists files and directories in long format.

Example:
```bash
ls -l
```

Output:
```text
drwxr-xr-x 2 nitya nitya 4096 Jun 20 Documents
-rw-r--r-- 1 nitya nitya   25 Jun 20 notes.txt
```

---

### cd
Change directory.

Example:
```bash
cd Documents
```

---

### cd ..
Move one directory up.

Example:
```bash
cd ..
```

If current directory is:

```text
/home/nitya/Documents
```

After:

```bash
cd ..
```

You will be in:

```text
/home/nitya
```

---

### cd ~
Move to the home directory.

Example:
```bash
cd ~
```

Output:

```text
/home/nitya
```

## Practice

Today I learned:
- pwd
- ls
- ls -l
- cd
- cd ..
- cd ~

I practiced navigating between directories and viewing files.
