# 🐚 shell-scripts

Helpful shell scripts written by @droxey.

## How to Use

* Run `chmod +x name-of-script.sh` in order to run each script.
* Run `name-of-script.sh -h` for usage information and options.

## Included Scripts

### 👤➡️👤 Change Repository Git Author 

Clones a GitHub repository in bare mode, amends the username and email address of each commit, and pushes the amended commits to the original GitHub repository. Does not change commit date or message information!

```bash
./change-author-git.sh -n "Dani Roxberry" -r git@github.com:droxey/droxey.github.io.git -o "dani@bitoriented.com" -n "droxey@gmail.com"
```

### 🖥  Static Website Slide Generator

Creates a static website from a markdown file via `reveal-md`. Removes common static assets. Names the resulting `.html` file the same name as the parent directory. Store the `.html` file in the root of your git repository, in a directory called `Slides`. 

```bash
./slidegen.sh README.md
```
