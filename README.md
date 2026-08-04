# Daniel Park — Personal Site

Five design directions for the same personal site. Same bio, same activities, same
honors in every one; only the design language changes.

**Live:** https://wooyoungcode.github.io/danielpark/

| | Direction | Character |
|---|---|---|
| A | [Editorial Record](Site-A-Editorial-Record.dc.html) | Serif on warm paper, numbered sections, print dossier feel |
| B | [Instrument Panel](Site-B-Instrument-Panel.dc.html) | Dark charcoal, bordered modules, monospace, amber awards |
| C | [Swiss Grid](Site-C-Swiss-Grid.dc.html) | Helvetica at scale, deep whitespace, one vermillion accent |
| D | [Academic Homepage](Site-D-Academic-Homepage.dc.html) | Light cards, sidebar portrait, dated news feed |
| E | [Research Lab](Site-E-Research-Lab.dc.html) | Full-bleed hero photo, lowercase voice, selected-record feed |

- [Directions.dc.html](Directions.dc.html) — the overview that compares all five (this is what `/` redirects to)
- [Daniel Park Portfolio.dc.html](Daniel%20Park%20Portfolio.dc.html) — all five side by side on one canvas

## Resume

[`Daniel-Park-Resume.pdf`](Daniel-Park-Resume.pdf) is what the Resume button on every
direction links to. It is built from [Jake Gutierrez's LaTeX resume template](https://github.com/jakegut/resume)
(MIT), with the source in [`resume/`](resume/):

- `daniel-park-resume.tex` — the resume itself
- `jake-resume-template.tex` — the unmodified template it came from

Rebuild it with:

```
tectonic resume/daniel-park-resume.tex
cp resume/daniel-park-resume.pdf Daniel-Park-Resume.pdf
```

## Still placeholder

The email address and every photograph. Photo boxes are drag-and-drop and shared across
all five sites, so an image dropped into one appears in the others.
