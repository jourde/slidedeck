# Welcome to Markdown Slidedeck

A minimal, distraction-free presentation tool.
Write slides in plain Markdown — no plugins, no accounts, no internet required.

-- duration: 30s
Everything stays local in your browser. Nothing is uploaded anywhere.

---

## Getting Started

1. Click **Choose delimiters** to confirm how your slides are separated
2. Click **Import MD file** to load your Markdown file
3. Navigate with the **arrow keys** or the on-screen controls

That's it. Your presentation is ready.

-- duration: 45s
The app parses your Markdown file entirely in the browser using the marked.js library.

---

## Slide Delimiters

Slides are separated by a delimiter on its own line.

The default delimiter is `---`:

```
Slide one content

---

Slide two content
```

Other options: `===`, or **# H1** mode where each top-level heading starts a new slide.
Change the delimiter anytime via the **Choose delimiters** panel.

-- duration: 1m
The delimiter must be on its own line with no surrounding text.
In H1 mode, the heading text becomes the slide title and the delimiter is implicit.

---

## Speaker Notes

Add speaker notes after the notes delimiter `--`:

```
Slide content visible to the audience

--
These notes are only shown in the notes panel.
They can span multiple lines.
```

Notes are hidden from the main slide view and only visible in the speaker notes area.

-- duration: 45s
Speaker notes support full Markdown formatting — bullet points, bold, code, etc.

---

## Slide Timing

Add a duration hint directly on the notes delimiter line:

- `-- duration: 2m` — minutes
- `-- duration: 90s` — seconds
- `-- duration: 1m30s` — minutes and seconds combined

Once durations are set, a **progress bar** appears at the bottom of the slide.
A **global timer** tracks your total session progress across all slides.

-- duration: 1m
Durations are optional — you can add them to some slides and leave others without.
The global bar only appears when at least one slide has a duration set.

---

## Navigation

| Action | Key or control |
|---|---|
| Next slide | `→` `Space` `Page Down` |
| Previous slide | `←` `Page Up` |
| Toggle nav arrows | Arrow button (bottom right) |

The on-screen arrows can be shown or hidden with the **⇄** button.
They are hidden by default for a cleaner presentation view.

-- duration: 30s
Keyboard navigation is the fastest way to move through slides during a presentation.

---

## Search

Press `Ctrl F` (or `Cmd F` on Mac) to open the search bar.

- Type to highlight matching text across all slides
- Use `↑` `↓` to jump between matches
- The slide view navigates automatically to each match

-- duration: 30s
Search is case-insensitive and works across slide content only — not speaker notes.

---

## Slide Map

Press `Alt M` to toggle the **train map** — a compact overview of all slides.

- Each dot represents one slide
- The current slide is highlighted
- Click any dot to jump directly to that slide
- Slides with a duration show a small timer badge

-- duration: 30s
The train map is especially useful in long presentations to keep track of where you are.

---

## Interface Settings

Click the **⊟ tune** button (bottom right) to open the settings panel.

**Background** — choose from 6 soft colour palettes:
Cloud · Warm · Sage · Slate · Lavender · Dusk

**Font** — choose from 4 system typefaces:
Sans-serif · Serif · Rounded · Monospace

Settings are saved automatically and restored on your next visit.

-- duration: 45s
All settings are stored in your browser's localStorage — they persist across reloads but are local to your machine.

---

## Markdown Support

Full **CommonMark** Markdown is supported:

- Headings (`#` `##` `###`)
- **Bold**, *italic*, ~~strikethrough~~, `inline code`
- Ordered and unordered lists
- Blockquotes, tables, horizontal rules
- Fenced code blocks with syntax hints
- Images — automatically constrained to fit the slide

-- duration: 45s
Images are scaled to a maximum of 100% width and 65% viewport height, preserving aspect ratio. No manual sizing needed.

---

## Code Blocks

Fenced code blocks render with a clean monospace style:

```javascript
function greet(name) {
  return `Hello, ${name}!`;
}
```

```python
def greet(name):
    return f"Hello, {name}!"
```

Language hints after the opening ` ``` ` are supported.

-- duration: 30s
Code blocks scroll horizontally if the content is wider than the slide.

---

## A Complete Slide Example

Here is a full slide with all elements combined:

```markdown
## My Slide Title

Some **bold** and *italic* text.

- Point one
- Point two

---  ← slide delimiter

-- duration: 1m30s  ← notes delimiter + duration
Speaker notes go here.
```

-- duration: 1m
The delimiter line must contain only the delimiter characters — no spaces before or after on the same line.

---

## Tips

- Keep slides **focused** — one idea per slide works best
- Use `---` on its own line; extra spaces will break detection
- Speaker notes are a great place for **talking points** and **statistics**
- The `# H1` delimiter mode works well for existing Markdown documents
- All processing happens **in your browser** — your files never leave your device

-- duration: 1m
You can re-import a file at any time — the app will reload from the beginning.

---

## Ready to Present

Load your own Markdown file and start presenting.

*Write in Markdown. Present anywhere.*

-- duration: 15s
This slide deck was itself written in Markdown and presented using this app.
