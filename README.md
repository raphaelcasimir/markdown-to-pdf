# Type in *Markdown*, use the power of *LaTeX*, render in *PDF*, All-in-one.
_Using sublime-text build system._

**Very useful to write small reports, usually less than 10 pages.
It behaves just as you expect.**

You must have [sublime text](https://www.sublimetext.com/docs/3/linux_repositories.html) already installed.
Then:

```bash
sudo apt install texlive pandoc
```
Clone the repo:

```bash
git clone https://github.com/raphaelcasimir/markdown-to-pdf.git
```

Then modify the `Markdown to PDF.sublime-build` file so the path to the `default.latex` matches the actual path of the file (included in this repo, so you cloned it).

Then copy `Markdown to PDF.sublime-build` to your sublime packages folder:

```bash
cp Markdown\ to\ PDF.sublime-build ~/.config/sublime-text-3/Packages
```

Set your document's syntax to markdown: <kbd>CTRL</kbd>+<kbd>SHIFT</kbd>+<kbd>P</kbd> and `ssm` (set syntax markdown).

Use <kbd>CTRL</kbd>+<kbd>B</kbd> to build your markdown document. A PDF file will be generated at your document's location and evince (you can change that in the .sublime-build file) will show it.

**Enjoy!**
