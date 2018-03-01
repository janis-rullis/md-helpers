# Markdown viewers

Mostly I write md files in terminal, so it's a pain to switch to gui just to check the result of the md file.
That's why I need a md viewer that should be launched from terminal and displays the content without any 
additional switches.

## Sources
* [View Markdown Files in your terminal](https://tosbourn.com/view-markdown-files-terminal/).
* [10 Best Markdown editors for linux](https://www.tecmint.com/best-markdown-editors-for-linux/).
* [Simple Markdown viewer for Linux](https://softwarerecs.stackexchange.com/questions/17714/simple-markdown-viewer-for-ubuntu).

## My choice - ReText

### Install

```bash
apt install retext
```

### Launch from CLI

```bash
retext --preview README.md
```

### [Create a shorter command - `mdpr`](https://github.com/janis-rullis/shell-scripts/blob/master/mdpr.sh).
