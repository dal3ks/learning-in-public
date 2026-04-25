# dal3ks — learning in public

> turning friction into flow

## contents
- [cli commands](#cli-commands)
- [git commands](#git-commands)
- [python terminal commands](#python-terminal-commands)
- [python code patterns](#python-code-patterns)
- [makers progress](#makers-progress)

---
## cli commands

| command | what it does |
|---------|-------------|
| `cat filename` | print file contents to terminal |
| `clear` | clears the terminal screen |
| `history` | shows your recent commands |
| `man commandname` | shows the manual for any command |
| `pwd` | shows your current directory |
| `mkdir foldername` | creates a new folder |
| `touch filename` | creates a new file |
| `ls` | lists files in current directory |
| `ls -lh` | lists files with details and readable file sizes |
| `ls -a` | lists all files including hidden ones |
| `cd foldername` | move into a folder |
| `cd ..` | move up one level |
| `code .` | opens current folder in VSCode |
| `nano filename` | edit a file in the terminal |
| `echo "text"` | print text to terminal |
| `echo "text" > file` | write text to file (overwrites) |
| `echo "text" >> file` | append text to file |
| `cp file destination` | copy a file |
| `mv file destination` | move or rename a file |
| `rm filename` | delete a file |
| `rm -rf foldername` | delete a folder and everything in it |

---
## git commands

| command | what it does |
|---------|-------------|
| `git init` | initialises a new git repository |
| `git add filename` | stages a specific file |
| `git add .` | stages all changed files |
| `git commit -m "message"` | commits staged files with a message |
| `git status` | shows staged files and any untracked changes |
| `git push` | pushes commits to remote repository |
| `git pull` | pulls latest changes from remote repository |
| `git log` | shows history of commits |
| `git clone url` | copies a remote repository to your machine |
| `git branch` | shows all branches |
| `git checkout -b branchname` | creates and switches to a new branch |
| `git merge branchname` | merges a branch into current branch |
| `git diff` | shows changes since last commit |
| `git branch -d branchname` | deletes a branch |

---
## python terminal commands

| command | what it does |
|---------|-------------|
| `python3 filename.py` | runs a Python file |
| `python3 -m venv venvname` | creates a virtual environment |
| `source venv/bin/activate` | activates virtual environment (Mac/Linux) |
| `deactivate` | deactivates virtual environment |
| `pip install packagename` | installs a package |
| `pip install pytest` | installs pytest |
| `pytest` | runs all tests |
| `pytest -x` | stops after first failure |
| `pytest -v` | verbose output — shows each test name |
| `pytest --cov` | shows test coverage |

---
## python code patterns

### for loop
```python
for item in list:
    print(item)
```

### while loop
```python
while condition:
    # do something
```

### list comprehension
```python
result = [item for item in list if condition]
```

### slicing
```python
string[0:3]   # first 3 characters
string[-3:]   # last 3 characters
```

### class
```python
class MyClass:
    def __init__(self):
        self.property = value
    
    def my_method(self):
        pass
```

### type conversion
| convert to | command |
|------------|---------|
| integer | `int(data)` |
| float | `float(data)` |
| string | `str(data)` |
| list | `list(data)` |
| dictionary | `dict(data)` |