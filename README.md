# Version Control with Git
---

This repo is intended as a guide to set up the Git version control system on your computer.

## Installing Git
---

[Git Download](https://git-scm.com/downloads)

## Configuring Git
---

1. Clone this repo.
2. Follow the instructions in either one of the videos below - depending on your computer's operating system:
   * On Mac:
     [![IMAGE MAC](https://img.youtube.com/vi/h00n9QLfbqU/0.jpg)](https://www.youtube.com/watch?v=h00n9QLfbqU)
   * On Windows:
     [![IMAGE WINDOWS](https://img.youtube.com/vi/CCYjHfBk9hw/0.jpg)](https://www.youtube.com/watch?v=CCYjHfBk9hw&feature=emb_logo)

## First-time Git Configuration
---

1. Sets up Git with your name:

```
git config --global user.name “your-name”
```

2. Sets up Git with your email:

```
git config --global user.email “your-email”
```

3. Makes sure that Git output is colored:

```
git config --global color.ui auto
```

4. Displays the original state in a conflict:

```
git config --global merge.conflictstyle diff3

git config --list
```

## Git & Code Editor
---

* Associates Vim with Git:

```
git config --global core.editor “vim”
```

* Associates Visual Studio Code with Git:

```
git config --global core.editor “code --wait”
```