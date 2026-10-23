# art/

Generated artwork for the two Top Hat embeds. The Dr. Love set is complete; the Love Mixer set needs regenerating in the simpler style. **Every slot below is optional** — both pages
draw their own placeholder when a file is missing, and each real file takes over the moment
it lands. No code change is needed when you add one; just commit it.

## The prompt sheets

| Sheet | For | Style |
| --- | --- | --- |
| [love-mixer-image-prompts.md](love-mixer-image-prompts.md) | `love-mixer-embed.html` | Flat cartoon — 6 colours, bone ground |
| [dr-love-office-image-prompts.md](dr-love-office-image-prompts.md) | `love-doctor-embed.html` | Flat cartoon — 5 colours, white ground |

Both activities now use the same flat cartoon style, told apart by their palettes: the
Mixer keeps its dark ochre/red/cyan/olive set, the Doctor its red/teal/mustard.

## What goes here

**Love Mixer** — square, ~800×800, JPEG:

- `non-love.jpg`
- `infatuation.jpg`
- `liking.jpg`
- `empty-love.jpg`
- `romantic-love.jpg`
- `companionate-love.jpg`
- `fatuous-love.jpg`
- `consummate-love.jpg`
- `kitchen.jpg` — the kitchen backdrop, 16:9 (already wired in)

**Dr. Love's Office** — ~1200px long edge, JPEG:

- `dr-love-title.jpg` — 3:2
- `couple-001.jpg` … `couple-008.jpg` — 4:3

Save everything as JPEG — the pages try `.jpg` first, then `.png`. Filenames are exact. Both pages build the path in JavaScript, so a typo means that one slot
silently keeps its placeholder rather than erroring.
