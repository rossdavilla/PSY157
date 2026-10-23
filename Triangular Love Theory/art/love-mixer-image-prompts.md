# Love Mixer — Mary Blair Art Prompts

Prompts for generating the artwork the Love Mixer embed expects. Written for ChatGPT
image generation; the Midjourney style reference that inspired them is noted inside.

Live copy: https://claude.ai/artifact/D9EJh6Q9qTem4pyF5JyLMZ

## How to use these in ChatGPT

`Mary Blair --v 8.2` will not work here. `--v 8.2` is a Midjourney version flag; ChatGPT
has no flags and will read it as literal text. The style has to be described in words
instead, which is what the next section does.

The method:

1. Open one ChatGPT conversation and keep every image in it. The model carries style
   across turns, so all eight pictures come out looking like a set. Starting a fresh chat
   per image is the main cause of mismatched results.
2. Paste the **house style block** once, as your first message, and let it answer.
3. Then send the per-image line on its own. One image per message.
4. Save the result under the exact filename listed with that prompt.

If a picture drifts off-style, reply "same style as before, but ..." rather than
re-pasting the whole block.

Two notes on naming the artist. Mary Blair died in 1978 and is normally fine to name, but
ChatGPT sometimes declines artist names anyway. If that happens, drop her name and send
the rest of the block — it is written to stand on its own, because it describes the look
rather than relying on the name. "Mid-century Disney concept art" is a good substitute
phrase.

Ask for a **square frame** on all eight so they drop into the page at one size.

## The house style block

Send this once, first, in the chat you will generate all eight images in.

> For this whole conversation I want every image in one consistent art style, inspired by
> the mid-century concept art of Mary Blair.
>
> The style: flat, graphic, painterly shapes with bold dark outlines. Strong geometric
> construction — figures and objects simplified into triangles, arcs and wedges. Richly
> textured brushwork over flat colour. Dense decorative motifs, especially stylised
> flowers, leaves and small animals. Theatrical, storybook staging on a dark ground, with
> ornate decorative framing around the edges. High contrast, vivid saturated colour,
> dreamy and warm. Deliberately naive and childlike, never photorealistic, no 3D
> rendering, no gradients or lens effects.
>
> Palette, in roughly this proportion: deep near-black (about a third of the image), dark
> ochre gold, hot vermilion red, muted teal-cyan, warm bone white, and olive green. Keep
> to these six.
>
> Every image: square, flat 2D illustration, no text, no words, no lettering anywhere in
> the picture, no watermark, no border outside the artwork itself.
>
> Reply "ready" and then I will send each image one at a time.

The palette comes from the Midjourney style reference: black 34%, dark ochre 18%, red 15%,
muted cyan 14%, bone white 11%, olive 8%. Those same six colours are what the embed page is
built in, so the generated images will sit inside it without clashing.

The "no text, no lettering" line matters — image models like to write words into
illustrations, and the page puts its own captions over the art.

## The eight love-type images

Send these one at a time, after the house style block. Each one ends by naming the motifs
that should appear in the decorative border — those are the same ingredients that go into
the pot in the activity, so the picture ties back to what the student just mixed.

**1. `non-love.jpg`**

> Two people sitting on the same bench in a waiting room, turned away from each other, a
> wide cold gap between them. Both stare straight ahead. Neither has noticed the other.
> Flat grey-olive and bone tones, almost no warm colour, bare geometric plants in the
> background. Decorative border of empty bowls and closed doors.

**2. `infatuation.jpg`**

> One figure in a crowded room gazing across at another, utterly transfixed, hot red hearts
> and stars spiralling out of their chest and filling the air around them. The other person
> is turned away and has not noticed. Blazing vermilion and dark ochre, the dreamer lit,
> everyone else in silhouette. Decorative border of peaches and eggplants.

**3. `liking.jpg`**

> Two friends sitting cross-legged facing each other, mid-conversation, both laughing,
> teacups and open books between them. Easy and warm but with no romance — no hearts.
> Muted teal-cyan and bone, soft ochre light. Decorative border of speech bubbles and
> teapots.

**4. `empty-love.jpg`**

> An older couple at opposite ends of a long formal dinner table, both upright and silent,
> a single candle between them. The room is grand and ornate and cold. Muted cyan and grey
> dominate, the gold of their wedding rings the only warm note. Decorative border of
> wedding rings and empty chairs.

**5. `romantic-love.jpg`**

> Two lovers entwined under a canopy of huge stylised flowers and stars, deep in each
> other, surrounded by hearts. Behind them an open road runs off to a horizon with no house
> on it. Hot pink, vermilion and deep night blue. Decorative border of peaches, hearts and
> blossoms.

**6. `companionate-love.jpg`**

> An elderly couple holding hands on a garden bench, calm and settled, a small cottage
> behind them with smoke curling from the chimney. Deep affection, no fire — no hearts or
> flames. Olive green, bone white and soft ochre. Decorative border of houses, speech
> bubbles and garden flowers.

**7. `fatuous-love.jpg`**

> A couple rushing headlong toward a wedding arch in a whirlwind, confetti, rings and
> blossoms flying past in streaks of motion, everything tilted and off balance. They are
> grinning but not looking at each other. Vermilion and bright ochre against black.
> Decorative border of wedding rings and peaches, tumbling and scattered.

**8. `consummate-love.jpg`**

> A couple embracing at the centre of a warm radiant composition: a hearth fire behind
> them, a small house, blossoming trees, hearts and wedding rings woven into a symmetrical
> decorative frame all around. Every element in balance. Rich gold, vermilion, teal and
> bone, the most saturated of the set. Decorative border combining peaches, hearts, speech
> bubbles, rings and houses.

## One optional extra, and what not to replace

**Do not replace the jars, ingredients, pot, spoon or hand.** Those are drawn as SVG inside
the page, not as image files, because they have to animate — the lids tilt open, the hand
reaches in and carries two ingredients across, the spoon stirs, the pot tips and pours. A
flat picture cannot do any of that, so dropping images in would break the animation rather
than improve it. They are already drawn in the same six colours as the prompts above, so
they match the generated art.

**The one thing worth generating is a kitchen backdrop.** It sits behind the jars and pot
as a CSS background and needs no code changes beyond one line.

> A plain kitchen wall and countertop seen straight on, empty, no objects on the counter.
> Mostly dark near-black wall with a band of dark ochre counter across the lower third.
> Sparse decorative motifs — a few stylised leaves and small geometric tiles. Very low
> contrast and quiet, because text and glass jars will sit on top of it. Wide 16:9
> landscape.

Save it as `kitchen.jpg`. Tell me when it exists and I will wire it in — it needs a
one-line CSS change, and the dark overlay on top may need adjusting so the jars stay
readable.

## Where the files go

Put every image in `PSY157/Triangular Love Theory/art/` — this folder.

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
| `kitchen.jpg` | Optional backdrop, 16:9 |

The filenames are exact — the page builds the path from the love type, so a typo means that
one type silently falls back.

**Format and size.** Square, around 800×800. **Save as JPEG, not PNG.** The page displays them between 132 and
200 pixels wide, so anything larger is wasted download; anything under 400×400 will look
soft on a high-density screen. ChatGPT hands these back as PNG, which runs about 1.4 MB each for painterly art like this — roughly ten times what the same picture needs. Re-save each one as JPEG at quality 82 before committing. The page looks for `.jpg` first and `.png` second, so either works, but the JPEGs load about ten times faster on a phone.

**You can add them one at a time.** The page already draws its own placeholder for every
type: a decorative medallion in that type's colour with the relevant ingredients arranged
inside. When a real file is present it is used; when it is missing the placeholder stays. So
nothing breaks while the set is half finished, and there is no code change needed when a
file lands — just commit it.
