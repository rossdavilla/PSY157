# Love Mixer — Art Prompts

Eight images for the Love Mixer embed, one per love type. Written for ChatGPT image
generation.

Live copy: https://claude.ai/artifact/D9EJh6Q9qTem4pyF5JyLMZ

## Read me first — this replaces the earlier set

The first version of these prompts asked for dense, ornate, Mary Blair style paintings with
decorative borders. They came out beautifully, but **the page shows them at about 200 pixels
wide**, and at that size the detail turns to mush. These prompts are a rewrite for
legibility.

Two things changed:

1. **The art style is now the same simple cartoon style as Dr. Love's Office** — thick black
   ink contours, flat colour, big round eyes, deadpan faces, lots of empty space. It reads
   at a glance, which is the whole point.
2. **Every composition is pared back to two figures and at most three symbols.** No
   decorative borders, no background scenery, no crowds, no patterned frames. The border was
   the single biggest source of visual noise and it is gone.

**The palette stays as it was**, so the new art still belongs to the Mixer rather than the
Doctor: deep near-black, dark ochre gold, hot vermilion red, muted teal-cyan, warm bone
white, olive green.

One consequence worth flagging. The Correll-ish cartoon style puts black ink on a pale
ground, so these will come back as **bone-white pictures** rather than the dark ones you
have now. On the Mixer's dark page they read as bright plates in a coloured frame, which
looks deliberate — but it is a real change, so say the word if you'd rather keep a dark
ground and have the linework in bone white instead.

**You will need to regenerate all eight.** The current files still work until you replace
them.

## The style brief

Send this once, first, in the chat you will generate all eight images in.

> I need a set of eight cartoon illustrations that all look like they came from the same
> sketchbook. Here is the style, and it applies to every image I ask for in this
> conversation.
>
> Spare, graphic cartoon drawing. Everything built from thick, confident black ink contours
> of even weight, like a felt-tip pen. Flat areas of colour inside the lines, no shading, no
> gradients, no texture, no crosshatching. Figures are angular and simplified, slightly
> awkward, with oversized round eyes, tiny dot pupils and deadpan, under-reacting
> expressions. Dry and funny rather than cute.
>
> **Keep every picture extremely simple.** These are displayed very small, about the size of
> a postage stamp, so they must read instantly. Two figures and at most three simple symbols
> per image. Large shapes, generous empty space around everything. No decorative borders, no
> patterned frames, no background scenery, no crowds, no small fiddly detail anywhere.
>
> Use exactly these six colours and nothing else:
> — warm bone white #F2E5CD for the background and most interior shapes
> — deep near-black #17121F for every outline and all linework
> — hot vermilion red #E0462F
> — muted teal-cyan #4A9FB0
> — dark ochre gold #D4972E
> — olive green #7F8C3C
>
> Every image: square, flat 2D cartoon, plain bone-white background, no text, no words, no
> lettering, no signature, no watermark, no border or frame drawn around the picture.
>
> Please confirm you have this, then I will send the images one at a time.

## The eight images

One per message, after the style brief. Each one names its figures and its symbols, and
nothing else should appear.

**1. `non-love.jpg`**

> Two figures sitting on a plain bench, far apart, both facing forward, blank neutral
> expressions, not looking at each other. One in olive, one in teal. No symbols at all. Lots
> of empty space between and around them.

**2. `infatuation.jpg`**

> Two figures. The left one leans eagerly toward the right one with enormous shining eyes
> and a huge red heart floating above their head. The right figure faces away, arms folded,
> completely unaware. One heart only.

**3. `liking.jpg`**

> Two figures sitting side by side, both laughing, turned slightly toward each other. Two
> teal speech bubbles above them, empty, no writing inside. Warm and easy. No hearts.

**4. `empty-love.jpg`**

> Two figures standing far apart, both upright and facing forward with flat expressions. One
> large ochre wedding ring floats in the gap between them. Muted and still. No hearts, no
> speech bubbles.

**5. `romantic-love.jpg`**

> Two figures embracing, turned fully toward each other, eyes closed, clearly delighted.
> Three red hearts floating around them. Nothing else — no house, no ring.

**6. `companionate-love.jpg`**

> Two older figures standing side by side holding hands, calm and content, grey hair. One
> small olive house behind them. No hearts.

**7. `fatuous-love.jpg`**

> Two figures running fast to the right, leaning forward, grinning but not looking at each
> other. One ochre ring and one red heart tumbling in the air behind them, plus a few simple
> black speed lines. Tilted, off balance.

**8. `consummate-love.jpg`**

> Two figures embracing in the centre, both smiling warmly. Three symbols arranged simply
> and evenly around them: one red heart, one ochre ring, one olive house. Balanced and
> settled. The most colourful of the set, but still simple.

## The kitchen backdrop

`kitchen.jpg` already exists and is wired in behind the jars and pot. It sits under a heavy
dark gradient so it reads as texture rather than a picture, which means the style change
above does not really touch it. Leave it unless you want to redo it, in which case:

> A plain kitchen wall and countertop seen straight on, empty, no objects on the counter.
> Mostly dark near-black wall with a band of dark ochre counter across the lower third.
> A few simple flat shapes only. Very low contrast and quiet, because text and glass jars
> sit on top of it. Wide 16:9 landscape.

## What not to replace

**The jars, ingredients, pot, spoon and hand stay as SVG.** They are drawn inside the page,
not as image files, because they animate — lids tilt open, the hand reaches in and carries
two ingredients across, the spoon stirs, the pot tips and pours. A flat picture cannot do
any of that.

## Where the files go

This folder, `PSY157/Triangular Love Theory/art/`.

| File | What it is |
| --- | --- |
| `non-love.jpg` | Result art, square |
| `infatuation.jpg` | Result art, square |
| `liking.jpg` | Result art, square |
| `empty-love.jpg` | Result art, square |
| `romantic-love.jpg` | Result art, square |
| `companionate-love.jpg` | Result art, square |
| `fatuous-love.jpg` | Result art, square |
| `consummate-love.jpg` | Result art, square |
| `kitchen.jpg` | Backdrop, 16:9, already done |

**Format and size.** Square, around 800×800, saved as JPEG. ChatGPT returns PNGs of roughly
1.4 MB each; re-saved as JPEG at quality 88 the same picture is around 200 KB with no
visible difference at display size. The page looks for `.jpg` first and `.png` second, so
either works — drop the PNGs straight in if that's easier and I'll convert them.

**The names are exact** — the page builds the path from the love type, so a typo means that
one type silently falls back to its drawn placeholder. You can replace them one at a time;
nothing breaks while the set is half old and half new.
