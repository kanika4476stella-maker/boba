# The Last Signal --- Interactive Story Website

**The Last Signal** is a small interactive story website I built using
HTML, CSS, and JavaScript. It follows Nova, who receives a strange
signal from deep under the ocean and sets out to discover where it came
from.

As you scroll through the story, you can solve a few simple challenges,
uncover hidden messages, launch a space elevator, and choose how the
story ends. The idea is to make the page feel more like an adventure
than a regular website.

[Jump to Installation](#installation) · [Jump to Usage](#usage) · [Jump
to the Markdown Cheat Sheet](#markdown-cheat-sheet)

------------------------------------------------------------------------

## Table of Contents

-   [About the Project](#about-the-project)
-   [Features](#features)
-   [Technologies Used](#technologies-used)
-   [Project Structure](#project-structure)
-   [Installation](#installation)
-   [How to Use It](#how-to-use-it)
-   [How the Story Works](#how-the-story-works)
-   [Making Changes](#making-changes)
-   [Contributing](#contributing)
-   [License](#license)
-   [Contact](#contact)
-   [Markdown Cheat Sheet](#markdown-cheat-sheet)
    -   [1. Headings](#1-headings)
    -   [2. Text Formatting](#2-text-formatting)
    -   [3. Paragraphs and Line Breaks](#3-paragraphs-and-line-breaks)
    -   [4. Lists](#4-lists)
    -   [5. Code](#5-code)
    -   [6. Blockquotes](#6-blockquotes)
    -   [7. Links](#7-links)
    -   [8. Images](#8-images)
    -   [9. Tables](#9-tables)
    -   [10. Escaping Characters](#10-escaping-characters)
    -   [11. HTML in Markdown](#11-html-in-markdown)
    -   [12. GitHub Flavored Markdown](#12-github-flavored-markdown)
    -   [13. Common README Sections](#13-common-readme-sections)
    -   [14. Quick Reference](#14-quick-reference)

------------------------------------------------------------------------

## About the Project

I wanted to try a different way of presenting a story online. Instead of
putting everything on one screen, the story unfolds chapter by chapter
as the visitor scrolls.

The visitor helps Nova decode a signal, restore an old computer, and
reach a space station. At the end, they uncover three messages and
decide whether Nova should keep the discovery secret or share it with
everyone.

## Features

-   **A story that unfolds while scrolling:** follow Nova from the ocean
    to space.
-   **Small interactive challenges:** solve a code puzzle and choose the
    right computer repair.
-   **Simple CSS animations:** moving fish, a floating visual, and a
    space elevator.
-   **Hidden story messages:** reveal the final fragments one at a time.
-   **Two possible endings:** the final choice changes the message you
    see.
-   **Progress bar and fragment counter:** keep track of the journey.
-   **Replay option:** start the story again without refreshing the
    page.
-   **Responsive design:** the layout adjusts for smaller screens.

## Technologies Used

  -----------------------------------------------------------------------
  Technology                          What it does
  ----------------------------------- -----------------------------------
  HTML5                               Holds the page structure and story
                                      text

  CSS3                                Controls the layout, colours,
                                      animations, and mobile styling

  JavaScript                          Handles the quizzes, story
                                      fragments, progress bar, and
                                      endings

  Intersection Observer               Adds a reveal effect when a chapter
                                      enters the screen
  -----------------------------------------------------------------------

The project does not need a framework or any external libraries. The
HTML, CSS, and JavaScript are all in one file.

## Project Structure

``` text
the-last-signal/
└── index.html
```

`index.html` contains the whole website, including its styles and
JavaScript.

## Installation

### Run it in a browser

1.  Download the project files.
2.  Find `index.html` in the project folder.
3.  Open the file in your browser.

### Run it in VS Code

1.  Open the project folder in VS Code.
2.  Open `index.html`.
3.  If you have the **Live Server** extension, right-click the file.
4.  Select **Open with Live Server**.

You can also publish the project on GitHub Pages once the repository is
ready.

### Clone from GitHub

If you have uploaded the project to GitHub, clone it with:

``` bash
git clone https://github.com/your-username/the-last-signal.git
cd the-last-signal
```

Replace the example URL with your actual repository link.

## How to Use It

1.  Click **Start your adventure**.
2.  In the first chapter, decode `3 - 1 - 20`. With `A = 1`, `B = 2`,
    and so on, the answer is `CAT`.
3.  In the next chapter, choose **Power supply** to bring the computer
    back online.
4.  In the space chapter, click **Launch the elevator**.
5.  At the end, reveal the three story fragments in order.
6.  Choose whether Nova should keep the discovery secret or share it.
7.  Click **Begin the adventure again** if you want to replay.

If something does not respond, check that JavaScript is enabled and look
at the browser's developer console for errors.

## How the Story Works

1.  **The Signal:** Nova picks up a mysterious message from the deep
    sea.
2.  **The Station:** an old computer reveals where the space elevator is
    located.
3.  **The Elevator:** Nova gets the elevator working and heads towards
    the stars.
4.  **The Final Transmission:** three hidden messages reveal what the
    explorers left behind.
5.  **The Choice:** the visitor decides what Nova should do with the
    discovery.

## Making Changes

You can edit everything in `index.html`.

-   Change the story by editing the text inside the HTML sections.
-   Change the colours by updating CSS values such as `#175b79` and
    `#ed8269`.
-   Update quiz answers and feedback in the JavaScript functions.
-   Change the event name in the header or footer if you want to reuse
    the design.
-   Adjust the mobile layout in the `@media` section of the CSS.

One small thing to watch out for: some JavaScript functions look for
specific HTML `id` values. If you rename an ID, update its matching
reference in the JavaScript too.

## Contributing

If you want to improve the project, you can:

1.  Fork the repository.
2.  Create a branch for your changes.
3.  Make your changes and test them in a browser.
4.  Commit your work with a short, clear message.
5.  Open a pull request and explain what you changed.

Please check that the website still works on desktop and mobile before
submitting changes.

## License

A license has not been chosen for this project yet. If you plan to let
other people reuse or modify the code, add a `LICENSE` file and update
this section with the license you choose.

## Contact

For now, the easiest way to share feedback is through the project's
GitHub repository. Once you publish it, add the real repository link
here and replace any example contact details with your own.

------------------------------------------------------------------------

# Markdown Cheat Sheet

Markdown is a simple way to format text without writing lots of HTML. It
is often used for `README.md` files, notes, and project documentation.

The examples below show the Markdown you type and what it normally looks
like when rendered. A few features can look different depending on the
platform.

## 1. Headings

Add `#` at the start of a line. More hash symbols mean a smaller
heading.

**Syntax:**

``` markdown
# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6
```

**Expected output:** six heading sizes, from a main page title to a
small subsection heading.

Tip: use one main `#` heading for the page title, then use the other
levels to organise sections.

## 2. Text Formatting

**Syntax:**

``` markdown
**Bold text**
*Italic text*
***Bold and italic text***
~~Strikethrough text~~
`inline code`
---
```

**Expected output:**

-   **Bold text** stands out.
-   *Italic text* adds emphasis.
-   ***Bold and italic text*** uses both styles.
-   ~~Strikethrough text~~ appears crossed out.
-   `inline code` highlights short code, filenames, or commands.
-   `---` creates a horizontal line.

## 3. Paragraphs and Line Breaks

Leave a blank line between paragraphs.

**Syntax:**

``` markdown
This is the first paragraph.

This is the second paragraph.

This line ends with two spaces.  
This starts on a new line.
```

**Expected output:** two separate paragraphs, followed by a line break
inside the final paragraph. Two trailing spaces work in many Markdown
renderers; a blank line is usually easier to maintain.

## 4. Lists

### Unordered list

**Syntax:**

``` markdown
- HTML
- CSS
- JavaScript
```

**Expected output:** a bulleted list.

### Ordered list

**Syntax:**

``` markdown
1. Open the project.
2. Edit `index.html`.
3. Refresh the browser.
```

**Expected output:** a numbered list of steps.

### Nested list

**Syntax:**

``` markdown
- Frontend
  - HTML
  - CSS
  - JavaScript
- Testing
  - Desktop
  - Mobile
```

**Expected output:** sub-items appear underneath their parent items.
Indent child items with spaces.

### Task list

Task lists are supported by GitHub Flavored Markdown.

**Syntax:**

``` markdown
- [x] Create the HTML page
- [x] Add the CSS
- [ ] Test the mobile layout
```

**Expected output:** two checked tasks and one unchecked task on GitHub.

## 5. Code

### Inline code

Use one backtick on either side of a short piece of code.

**Syntax:**

``` markdown
Open `index.html` in your browser.
```

**Expected output:** `index.html` appears in a code-style font inside
the sentence.

### Fenced code block

Put three backticks before and after the code.

**Syntax:**

```` markdown
```html
<h1>Hello, world!</h1>
```
````

**Expected output:** a separate code block. The `html` label asks
supported renderers to apply HTML syntax highlighting.

### Language-specific highlighting

Add the language name after the opening backticks.

**Syntax:**

```` markdown
```javascript
function greet() {
    console.log("Hello!");
}
```

```css
body {
    background: #eaf7fb;
}
```

```bash
git status
```
````

**Expected output:** JavaScript, CSS, and Bash code blocks, with syntax
highlighting where available.

Common language labels include `html`, `css`, `javascript`, `python`,
`bash`, `json`, and `text`.

## 6. Blockquotes

Put `>` at the start of the line.

### Single-level quote

**Syntax:**

``` markdown
> Every discovery starts with curiosity.
```

**Expected output:** an indented quotation.

### Nested quote

**Syntax:**

``` markdown
> Nova found a message.
>
> > The message contained a warning.
```

**Expected output:** a quote inside another quote.

Blockquotes are handy for quotes, notes, and short reminders.

## 7. Links

### Clickable text

**Syntax:**

``` markdown
[Open GitHub](https://github.com)
```

**Expected output:** "Open GitHub" becomes a clickable link.

### URL and email link

**Syntax:**

``` markdown
https://github.com

[Email the project maintainer](mailto:hello@example.com)
```

**Expected output:** GitHub usually turns the plain URL into a link
automatically. The email link opens the user's email app. Replace the
example address before publishing.

### Link to a section

**Syntax:**

``` markdown
[Jump to Installation](#installation)

## Installation
```

**Expected output:** clicking the first line jumps to the Installation
heading on platforms that support heading anchors.

On GitHub, heading links are generally made from the heading text in
lowercase, with spaces replaced by hyphens.

## 8. Images

### Basic image and alt text

**Syntax:**

``` markdown
![A submarine exploring the ocean](images/submarine.png)
```

**Expected output:** an image appears if the file exists at that path.
The text in square brackets is alternative text for screen readers and
when the image cannot load.

### Image with a title

**Syntax:**

``` markdown
![A submarine exploring the ocean](images/submarine.png "Ocean exploration")
```

**Expected output:** the image may show "Ocean exploration" as a tooltip
on supported platforms.

### Clickable image

**Syntax:**

``` markdown
[![Project preview](images/preview.png)](https://github.com)
```

**Expected output:** clicking the preview image opens GitHub.

Make sure image paths point to real files in your repository.

## 9. Tables

Use pipes (`|`) between columns and a row of hyphens below the headings.

### Basic table

**Syntax:**

``` markdown
| Technology | Purpose |
| --- | --- |
| HTML | Page structure |
| CSS | Styling |
| JavaScript | Interactivity |
```

**Expected output:** a two-column table with a heading row and three
data rows.

### Alignment

Use colons in the separator row to control alignment.

**Syntax:**

``` markdown
| Left aligned | Center aligned | Right aligned |
| :--- | :---: | ---: |
| Text | Text | 123 |
```

**Expected output:** the first column is left-aligned, the second
centered, and the third right-aligned.

### Code inside a table

**Syntax:**

``` markdown
| Item | Example |
| --- | --- |
| Filename | `index.html` |
| Command | `git status` |
```

**Expected output:** inline code formatting appears inside the table
cells.

## 10. Escaping Characters

Add a backslash (`\`) before a Markdown character when you want to
display it literally.

**Syntax:**

``` markdown
\*This is not italic\*

\# This is not a heading

Use \`backticks\` to show the symbols.
```

**Expected output:** the asterisks, hash symbol, and backticks appear as
characters instead of applying formatting.

Common characters that can be escaped include:

``` text
\* \_ \# \` \[ \] \( \) \! \| \\
```

## 11. HTML in Markdown

Some Markdown renderers allow HTML tags inside Markdown files. GitHub
supports a number of common tags, but it removes or restricts unsafe
HTML.

**Syntax:**

``` html
<p>This is a paragraph written with HTML.</p>

<strong>Important text</strong>

<em>Emphasised text</em>

<br>

<details>
  <summary>Show more</summary>
  This content can be expanded or collapsed on supported platforms.
</details>
```

**Expected output:** a paragraph, bold text, italic text, a line break,
and an expandable section where supported.

A couple of things to remember:

-   Not every Markdown renderer supports every HTML tag.
-   Markdown inside some HTML blocks may not be processed.
-   JavaScript and unsafe HTML attributes may be removed for security
    reasons.

## 12. GitHub Flavored Markdown

GitHub Flavored Markdown (GFM) adds a few useful features to standard
Markdown.

### Task lists

**Syntax:**

``` markdown
- [x] Add story chapters
- [ ] Improve keyboard navigation
```

**Expected output:** checkboxes on GitHub.

### Tables

**Syntax:**

``` markdown
| Feature | Status |
| --- | --- |
| Story | Complete |
| Mobile layout | Complete |
```

**Expected output:** a formatted table.

### Autolinks

**Syntax:**

``` markdown
Visit https://github.com
Contact support@example.com
```

**Expected output:** GitHub generally makes the URL and email address
clickable.

### Strikethrough

**Syntax:**

``` markdown
~~This feature was removed~~
```

**Expected output:** the text appears crossed out.

### Footnotes

**Syntax:**

``` markdown
This project uses plain JavaScript.[^note]

[^note]: No JavaScript framework is required.
```

**Expected output:** a footnote reference linked to a note near the
bottom of the rendered document.

### Alerts

GitHub supports special note and warning blocks.

**Syntax:**

``` markdown
> [!NOTE]
> This is useful information.

> [!WARNING]
> Check your changes before publishing.
```

**Expected output:** styled callouts on supported GitHub pages. Other
Markdown renderers may show them as regular blockquotes.

## 13. Common README Sections

A README usually tells people what the project is, how to run it, and
how to get involved.

### Project title and description

**Syntax:**

``` markdown
# Project Name

A short explanation of what the project does.
```

**Expected output:** a main title and a short description underneath.

### Features

**Syntax:**

``` markdown
## Features

- Interactive story
- Responsive layout
- Animated elements
```

**Expected output:** a list of the project's main features.

### Installation

**Syntax:**

```` markdown
## Installation

```bash
git clone https://github.com/your-username/your-project.git
cd your-project
```
````

**Expected output:** installation commands in a shell code block.
Replace the sample URL with your actual repository link.

### Usage

**Syntax:**

``` markdown
## Usage

1. Open `index.html`.
2. Start the story.
3. Complete each challenge.
```

**Expected output:** a numbered list explaining how to use the project.

### Technologies

**Syntax:**

``` markdown
## Technologies

- HTML5
- CSS3
- JavaScript
```

**Expected output:** a list of the tools used.

### Contribution guidelines

**Syntax:**

``` markdown
## Contributing

1. Fork the repository.
2. Create a branch.
3. Test your changes.
4. Open a pull request.
```

**Expected output:** a short set of steps for contributing.

### License

**Syntax:**

``` markdown
## License

This project is licensed under the MIT License.
```

**Expected output:** a license statement. Only use it if you have
actually chosen the MIT License and included it in the repository.

### Contact information

**Syntax:**

``` markdown
## Contact

- GitHub: [your-username](https://github.com/your-username)
- Email: [hello@example.com](mailto:hello@example.com)
```

**Expected output:** clickable contact links. Replace the sample details
with your own before publishing.

## 14. Quick Reference

  Element              Markdown syntax
  -------------------- -------------------------------------
  Heading 1            `# Heading`
  Heading 2            `## Heading`
  Bold                 `**text**`
  Italic               `*text*`
  Bold and italic      `***text***`
  Strikethrough        `~~text~~`
  Inline code          `` `code` ``
  Horizontal rule      `---`
  New paragraph        Leave a blank line
  Unordered list       `- Item`
  Ordered list         `1. Item`
  Nested list          Indent child items
  Task list            `- [ ] Task`
  Link                 `[text](https://example.com)`
  Image                `![alt text](image.png)`
  Blockquote           `> Quote`
  Nested quote         `> > Nested quote`
  Fenced code          Three backticks before and after
  Table                Pipes and a separator row
  Left alignment       `:---`
  Center alignment     `:---:`
  Right alignment      `---:`
  Escape a symbol      `\*`
  Email link           `[Email](mailto:hello@example.com)`
  Anchor link          `[Section](#section)`
  Footnote             `[^note]`
  HTML line break      `<br>`
  Expandable section   `<details>` and `<summary>`

------------------------------------------------------------------------

## A Few Final Tips

-   Preview the file on GitHub or in a Markdown preview before
    publishing it.
-   Keep the table of contents in sync with the headings.
-   Use clear link text and helpful image alt text.
-   Replace example usernames, URLs, and email addresses with real
    details.
-   Keep the README useful and honest about what the project currently
    does.

**Thanks for checking out The Last Signal!**
