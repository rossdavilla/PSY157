# Art for the Love Languages Survey: Instructions for ChatGPT

The survey already runs without any art. Each image you make simply replaces a built-in placeholder, so you can add art a few pieces at a time and nothing breaks if a file is missing. Save every finished image into the `art` folder that sits next to `index.html`, using the exact file name listed for it.

## How to work in ChatGPT

Do all of the images in a single ChatGPT conversation so the style stays consistent. Paste the Style Guide below as your first message, then make the intro hero illustration first. Once you like it, upload that image back into the chat with each later request and say "match the style of this image exactly." That reference image does more for consistency than any amount of description.

Ask for one image per message. Image generators drift when asked for several at once.

## Style Guide (paste this first)

> I'm creating a set of illustrations for an interactive college psychology survey about love languages. Every image in this set must share one consistent style. Please follow these rules for every image I ask for in this conversation:
>
> **Style:** soft, modern flat illustration with gentle hand-drawn texture and a light paper grain. Rounded, friendly shapes. Minimal shading, no harsh outlines, no photorealism, no 3D rendering, no glossy effects. The feel is warm, calm, and inclusive, closer to an editorial magazine spot illustration than a greeting card.
>
> **Palette:** use only these colors plus white: #F2DCD8 (blush), #F5B3BA (soft pink), #E67A8C (rose), #7996C9 (periwinkle blue), #F5E6D7 (cream). For the darkest details (hair, small accents), use a deep plum, #3B2F3F, sparingly.
>
> **People:** when people appear, show a range of skin tones, body types, and genders, including same-gender couples. Keep faces simple and stylized (dot eyes or closed eyes, small smiles) so no one looks like a specific real person. Hands are often better than full figures.
>
> **Never include:** any text, letters, numbers, logos, or watermarks. No hearts with faces, no cupids, no clip-art cliches, nothing sexual or suggestive.
>
> Please confirm you understand, and wait for my first request.

## Asset list

| File name | Shape and size | Background | Where it appears |
|---|---|---|---|
| `bg-intro.png` | Landscape, 1536 x 1024 | Full scene | Behind the opening screen |
| `bg-question.png` | Landscape, 1536 x 1024 | Full scene, very quiet | Behind all 20 question screens |
| `bg-results.png` | Landscape, 1536 x 1024 | Full scene | Behind the results screen |
| `hero-intro.png` | Square, 1024 x 1024 | Transparent | Right side of the opening screen |
| `hero-results.png` | Square, 1024 x 1024 | Transparent | Results screen, used for ties or if a language image is missing |
| `results-WA.png` | Square, 1024 x 1024 | Transparent | Results screen when Words of Affirmation is the top score |
| `results-QT.png` | Square, 1024 x 1024 | Transparent | Results screen for Quality Time |
| `results-AS.png` | Square, 1024 x 1024 | Transparent | Results screen for Acts of Service |
| `results-PT.png` | Square, 1024 x 1024 | Transparent | Results screen for Physical Touch |
| `results-RG.png` | Square, 1024 x 1024 | Transparent | Results screen for Receiving Gifts |
| `icon-WA.png` through `icon-RG.png` | Square, 1024 x 1024 | Transparent | Tiny icons beside each bar in the results chart |

The survey frame is 720 x 450, a wider shape than ChatGPT's 1536 x 1024 landscape. Backgrounds are cropped slightly at the top and bottom to fill the frame, so keep anything important away from those edges.

## Prompts, in the recommended order

### 1. Opening hero, `hero-intro.png` (make this first; it becomes your style reference)

> Create a square 1024 x 1024 illustration with a fully transparent background. Show two figures of different skin tones sitting close together and leaning toward each other, one gently resting their head on the other's shoulder, surrounded by a loose ring of small floating symbols that hint at the five love languages: a speech bubble, a small wrapped gift, a coffee mug, a pair of linked hands, and a folded laundry basket. Keep the whole composition centered with generous empty space around the edges, and make it read clearly when shown at about 270 pixels wide. No text.

This image is displayed beside a text card, about the size of a large playing card, so a centered composition with breathing room works best.

### 2. Opening background, `bg-intro.png`

> Create a landscape 1536 x 1024 background illustration in the same style. Mostly soft blush (#F2DCD8) with large, gentle organic shapes in soft pink and cream drifting in from the corners, a few small scattered sparkles and tiny hearts in rose and periwinkle, and a subtle paper grain. The left 60 percent of the image should stay especially calm and low in detail, because a text card will sit on top of it. No people, no text.

### 3. Question background, `bg-question.png`

> Create a landscape 1536 x 1024 background in the same style and palette as the previous background, but much quieter. The center 85 percent will be completely covered by a card, so put any decoration only along the outer edges and corners: a few soft blobs, a thin dotted line, two or three tiny sparkles. The overall impression should be calm and almost plain. No people, no text.

### 4. Results background, `bg-results.png`

> Create a landscape 1536 x 1024 background in the same style. Slightly more celebratory than the others: soft confetti-like dots and small sparkles in rose, soft pink, and periwinkle, concentrated on the right third of the image and along the edges. The left 60 percent should stay calm because a chart card covers it. No people, no text.

### 5. Results hero, `hero-results.png`

> Create a square 1024 x 1024 illustration with a fully transparent background, in the same style. A single large rose-colored heart, softly textured, with a few small periwinkle and pink sparkles around it, centered with plenty of empty margin. It should read clearly at about 176 pixels wide. No text.

### 6. One results illustration per love language

Use this template for each one, swapping in the scene below it. Upload your intro hero as the style reference each time.

> Create a square 1024 x 1024 illustration with a fully transparent background, matching the attached image's style exactly. [SCENE]. Center the subject with generous empty space around it so it reads clearly at about 176 pixels wide. No text, letters, or symbols that look like writing.

- `results-WA.png`: Two overlapping speech bubbles, one rose and one periwinkle, with a small heart where they overlap, and a few tiny sparkles.
- `results-QT.png`: Two coffee mugs side by side on a small round table, steam curling together into a soft heart shape, two chairs pulled close.
- `results-AS.png`: Two pairs of hands with different skin tones, one handing the other a full grocery bag with a baguette and leafy greens peeking out.
- `results-PT.png`: Two hands with different skin tones, fingers interlaced, with a soft glow around them.
- `results-RG.png`: A small wrapped gift box in rose with a periwinkle ribbon, and a blank handwritten-style tag hanging from it (the tag must stay blank).

### 7. Chart icons, `icon-WA.png`, `icon-QT.png`, `icon-AS.png`, `icon-PT.png`, `icon-RG.png`

These show at only 24 pixels, so they need to be bold, simple silhouettes. Ask for all five in a single conversation thread, one per message:

> Create a square 1024 x 1024 icon with a fully transparent background: a single bold, simple [OBJECT] shape in solid #E67A8C, flat, no texture, no outline, no shading, filling about 80 percent of the canvas. It must still be recognizable when shrunk to 24 pixels. No text.

Objects: speech bubble (WA), hourglass (QT), helping hand holding a small box (AS), two linked hands (PT), wrapped gift (RG).

The chart already draws a small colored dot behind each icon, so these are a finishing touch and can be skipped.

## Checking and saving each image

ChatGPT sometimes draws a gray-and-white checkerboard into the picture instead of producing real transparency. Open the downloaded PNG on your computer: if you see a checkerboard pattern where the background should be empty, reply "the background is not actually transparent; please regenerate with a true transparent background." If it keeps happening, a free remover such as remove.bg or the "Remove Background" option in macOS Preview (Tools menu) will fix it in seconds.

Watch for stray letters or squiggles that look like writing, which image models like to add to tags, mugs, and speech bubbles. Ask for a regeneration if any appear.

Rename each file to the exact name in the table (lowercase `.png`, capital letters in the two-letter codes) and drop it into the `art` folder. Refresh the survey in your browser to see it. If a file name is off by even one character, the survey quietly keeps using its built-in placeholder, which is the first thing to check if an image does not show up.
