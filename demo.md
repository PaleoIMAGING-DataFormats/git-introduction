# GitHub Markdown Demonstration

This document demonstrates commonly used **Markdown syntax** on GitHub.

## 1. Text Formatting

You can format text using:

* **Bold text**
* *Italic text*
* ***Bold and italic text***
* ~~Strikethrough text~~

You can also create a [link](https://www.unibe.ch).

## 2. Lists

### Unordered List

* Hyperspectral imaging
* X-ray fluorescence
* Mass spectrometry imaging

### Ordered List

1. Create a repository
2. Clone the repository
3. Edit files
4. Commit changes
5. Push to GitHub

### Task List

* [x] Create repository
* [x] Add README
* [ ] Make changes
* [ ] Push changes

## 3. Code

Inline commands can be written as `git status`.

A code block can be written as:

```bash
git clone <repository-url>
cd <repository-name>
git status
git add .
git commit -m "Update documentation"
git push
```

## 4. Blockquote

> Git allows changes to files to be tracked over time.

## 5. Table

| Command      | Purpose                               |
|--------------|---------------------------------------|
| `git status` | Show the current repository status    |
| `git add`    | Stage changes                         |
| `git commit` | Save staged changes                   |
| `git push`   | Upload commits to a remote repository |
| `git pull`   | Retrieve and integrate remote changes |

## 6. Image

Images can be included using:

![Warsaw](image/warsaw.jpg)
*Figure 1. Old Town Market Square, Warsaw, Poland.*

## 7. Mathematical Expression

GitHub Markdown supports mathematical expressions using LaTeX syntax:

$$
E = mc^2
$$

Inline mathematics can also be written as $x^2 + y^2 = z^2$.

---

## Markdown → Other Formats

Markdown files can also be converted into other document formats using **Pandoc**.

For example:

```bash
pandoc demo.md -o demo.pdf
pandoc demo.md -o demo.docx
pandoc demo.md -o demo.html
```

This allows the same Markdown source file to be maintained with Git while producing different output formats.
