# Dr. Love's Office — Art Bot Instructions

Nine images for the Love Doctor activities: one title card and eight couples. Written to be
handed to a Claude bot driving ChatGPT in Chrome — it can follow this top to bottom.

Live copy: https://claude.ai/artifact/RW48qGzGpdKannWVZNKHsr

**Two pages share this artwork, so generate all nine whichever one you are working on.**
`love-doctor-embed.html` uses every image. `love-doctor-embed2.html` — the shorter version,
with the live diagnosis under the button and a review sheet at the end — dropped Non-Love as
a case, so it never shows `couple-001.jpg`, and it draws four of the remaining seven couples
at random each round. Neither page needs anything beyond these nine. See **Where each image
is used** below.

## Read me first

The job: generate nine images in ChatGPT, in one conversation, and save each under an exact
filename.

**The thing most likely to go wrong: every couple comes out looking like the same two
people.** This is the default failure, not a fluke. A flat cartoon style with big round eyes
and dot pupils gives the model very little to vary, so unless you describe each person
specifically it will reuse one house face sixteen times. The fix is the **character sheet**
below — every one of the sixteen people has their own hair, build and silhouette, and the
prompts name them explicitly. Do not shorten those descriptions.

**The second thing: do not ask for "the style of Gemma Correll."** She is a living, working
illustrator, born 1984. ChatGPT routinely refuses requests that name a living artist's
style, and a refusal early in the run can make the rest of the conversation cautious. The
style brief below describes her look in plain visual terms and never names her. Use it as
written.

That description comes from a Midjourney style reference: spare graphic cartoon drawings
built from thick black ink contours, flat white and intensely red areas, a deliberately
limited palette, exaggerated eyes, angular simplified bodies and deadpan expressions. Its
measured palette was white 48%, vivid red 33%, black 10%, grey 4%. We widen that to five
colours by adding teal and mustard.

Three rules that matter more than they look:

1. **One conversation for all nine images.** ChatGPT carries style across turns. Nine
   separate chats will give nine mismatched drawings, and these sit next to each other in
   the same activity.
2. **Sixteen different people, not one couple restyled.** See the character sheet.
3. **Never let the drawing contain text.** Every prompt ends with a no-lettering
   instruction. Image models like to write words into cartoons, and the page lays its own
   captions over the art.

## The style brief

This is message one. Paste it exactly, wait for the reply, then start on the images.

> I need a set of nine cartoon illustrations that all look like they came from the same
> sketchbook. Here is the style, and it applies to every image I ask for in this
> conversation.
>
> Spare, graphic cartoon drawing. Everything built from thick, confident black ink contours
> of even weight, like a felt-tip pen. Flat areas of colour inside the lines, no shading, no
> gradients, no texture, no crosshatching. Figures are angular and simplified, slightly
> awkward, with oversized round eyes, tiny dot pupils and deadpan, under-reacting
> expressions. Dry and funny rather than cute. Plenty of empty white space around the
> subject.
>
> Use exactly these five colours and nothing else:
> — off-white #FAF7F2 for the background and most interior shapes
> — near-black #1A1A1A for every outline and all linework
> — vivid red #EE3B2E
> — teal #2F9C95
> — mustard yellow #F2B134
>
> White dominates. Red is the loudest accent. Teal and mustard appear in smaller amounts.
> Objects keep the same colours from image to image — once the couch is a colour, it stays
> that colour in every drawing.
>
> **Important: across this set I will ask you to draw sixteen different people. They must
> look like sixteen genuinely different individuals, not the same face in different
> clothes.** I will give you each person's hair, build and features, and I want those
> followed exactly. Vary head shape, body shape, height and hairstyle between every
> character. No two people in the whole set should share a hairstyle. Within each couple the
> two people should be obviously different heights or builds.
> Keep the room bare. **Nothing on the floor in any image** — no bags, backpacks,
> suitcases, boxes, plants or objects beside or in front of the couch, and nothing held in
> anyone's hands or lap. The only things in the room are the couch, the two people, and the
> few wall details I name. A prop invented for one drawing has a habit of reappearing in
> every drawing after it, and I do not want that.
>
> Every image: flat 2D cartoon, plain off-white background, no text, no words, no lettering,
> no speech bubbles with writing in them, no signature, no watermark, no frame or border
> drawn around the picture.
>
> Please confirm you have this, then I will send the images one at a time.

**Pin the couch colour on the first drawing.** The couch appears in all nine images, so
whatever colour it comes out in image 1 is the colour to insist on afterwards. The prompts
below ask for a red couch; if ChatGPT makes it teal instead, keep teal and say "same teal
couch as before" from then on. Consistency beats the original choice.

## The character sheet

Sixteen people. The things that actually distinguish a character in a flat, limited-palette
cartoon are **hair, head shape, body shape, height, eyewear and facial hair** — colour and
clothing do far less work than you'd expect, because the palette is so narrow. So every
person below is pinned on those first.

Two notes. Case 001's Marcus and case 005's Marcus are **different men who happen to share a
name** — draw them nothing alike. And no one in this set wears a visible wedding ring; see
the warning under the couple prompts.

| # | Person | Hair & face | Build | Wearing |
| --- | --- | --- | --- | --- |
| 001 | Marcus | Close-cropped hair, thin moustache, square black glasses | Tall, lanky, long neck | Teal blazer, collared shirt |
| 001 | Jennifer | Sharp blonde bob, blunt fringe, no glasses | Short, compact, square shoulders | Mustard turtleneck |
| 002 | Sam | Enormous round curly afro, gap-toothed grin, round face | Medium, stocky | Red-and-white striped hoodie |
| 002 | Alex | Long straight hair in a high ponytail, round wire glasses | Very tall, very skinny | Denim overalls |
| 003 | Diego | Messy black curls flopping over his forehead, light stubble | Short, broad, barrel-chested | Plain red t-shirt, sneakers |
| 003 | Zoe | Sleek shoulder-length hair tucked behind one ear, big hoop earrings | Tall, angular | Teal jumpsuit |
| 004 | Harold | Bald on top, white tufts over the ears, bushy white moustache, half-moon glasses | Short, round, stooped | Mustard cardigan, slippers |
| 004 | Evelyn | Tight white permed curls, pearl necklace, long thin face | Small, upright, birdlike | High-collared teal blouse |
| 005 | Chloe | Shoulder-length curls with a red headscarf tied in them, freckles | Medium, rounded | Denim jacket |
| 005 | Marcus | Shaved head, full dark beard, heavy brows | Broad, muscular, thick-necked | Mustard t-shirt |
| 006 | Ruth | Silver-grey hair in a loose bun, large round red glasses | Tall, soft, long-limbed | Long teal cardigan |
| 006 | David | Short grey hair, neat grey beard, reading glasses pushed up on his head | Medium, slight paunch | Mustard button-down |
| 007 | Brittany | Long wavy blonde hair, heart-shaped sunglasses pushed up, sunburnt nose | Petite, bouncy | Mustard sundress |
| 007 | Ryan | Spiky bleached hair, backwards red cap, square jaw | Tall, gym-built, broad | Red shirt, flip-flops |
| 008 | Elena | Dark hair in a long braid over one shoulder, small square glasses | Medium, poised | Teal sweater |
| 008 | Thomas | Receding hairline, salt-and-pepper at the sides, clean-shaven, round friendly face | Medium, comfortable | Red henley |

### Optional: skin tones

Everyone above will come out as white paper with black outlines, which is how this style
normally works — but it does mean all sixteen people read as the same ethnicity. If you want
that variety, add this line to the style brief:

> You may also use two skin tones outside the five colours: a light tan #E8C9A0 and a deep
> brown #8A5A3B. Use them for skin only, nothing else.

That widens the palette to seven and means regenerating anything already drawn, so it is
your call. If you take it, assign the deeper tone to roughly half the cast and mix it
**within** couples as well as between them.

## Image 1 — the title card

Save as **`dr-love-title.jpg`**. Landscape, 3:2.

The couple here is a generic ninth pair, not one of the eight cases — give them a look that
doesn't match anyone on the character sheet.

> Wide landscape cartoon, 3:2. A therapist's office seen from behind the therapist's
> shoulder.
>
> In the near foreground, filling the lower third and seen from directly behind, the back of
> the therapist's head and shoulders — a large soft silhouette shape in flat teal,
> deliberately out of focus and blurry, with soft fuzzy edges and no outline, no facial
> features, no hair detail, nothing that would say man or woman. It is just a vague,
> friendly, anonymous shape. It should read as the viewer's own head and shoulders, as if
> they are sitting in the therapist's chair.
>
> Beyond it, in sharp focus with crisp black ink outlines, a couple sitting side by side on
> a red two-seater couch, facing the viewer: one with a short dark bob and a mustard scarf,
> the other bald with round glasses and a teal jumper, noticeably taller. Both have the
> oversized round eyes and flat deadpan expressions. They are mid-session: one is talking,
> the other is listening. Behind them a plain off-white wall with a framed certificate, a
> wall clock and a potted plant in mustard and teal.
>
> The contrast between the blurred foreground shape and the crisp couple is the whole point
> of the picture.
>
> Flat 2D cartoon, the five colours only, no text, no lettering, no signature, no border.

If the blur comes back as a hard-edged silhouette, ask for it again as "a soft out-of-focus
blob with fuzzy edges, like a camera focused on the couple behind." Image models tend to
draw clean shapes by default; asking twice usually gets it.

## Images 2–9 — the eight couples

All eight are **landscape 4:3**, the same couch in the same room, viewed straight on from
where the therapist sits.

Every prompt below already opens with the line that keeps the set consistent *and* keeps the
people different. Send them exactly as written — the physical descriptions are what stop all
eight couples looking alike.

These drawings carry appearance and posture only. **No floating hearts, no visible wedding
rings, no symbols of any kind** — the student is meant to diagnose from the written case, and
a picture that gives away the answer turns the activity into a spotting game. Posture is
fair; props that hint at the diagnosis are not. This holds for both pages: the first lays a
written case note over the drawing, the second the couple's own spoken dialogue, and either
way the picture is what the student looks at while deciding.

**And no objects on the floor.** Whatever you let into one drawing tends to reappear in
the next — a bag drawn beside the couch once will follow you through the whole set. The
floor stays empty in all eight.

**1. `couple-001.jpg`** — two colleagues *(first page only; `love-doctor-embed2.html` has no
Non-Love case, so this one never appears there — but draw it, because the first page still
shows it)*

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far.
>
> On the left, Marcus: tall and lanky with a long neck, close-cropped hair, a thin
> moustache and square black glasses, in a teal blazer over a collared shirt. On the right,
> Jennifer: short and compact with square shoulders, a sharp blonde bob with a blunt fringe,
> no glasses, in a mustard turtleneck.
>
> They sit at opposite ends of the couch with a clear gap between them, both facing the
> viewer politely, neutral and slightly bored. The floor is completely empty. They look like two
> people who were put in the same room.

**2. `couple-002.jpg`** — two old friends

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far.
>
> On the left, Sam: medium height and stocky with a round face, an enormous round curly
> afro and a gap-toothed grin, in a red-and-white striped hoodie. On the right, Alex: very
> tall and very skinny, long straight hair in a high ponytail, round wire glasses, in denim
> overalls.
>
> They sit close together, both mid-laugh, completely relaxed and sprawling. Sam is
> gesturing wildly mid-story, Alex is cracking up. Easy and warm, nothing romantic about it.

**3. `couple-003.jpg`** — the eager one

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far.
>
> On the left, Diego: short, broad and barrel-chested, messy black curls flopping over his
> forehead, light stubble, in a plain red t-shirt and sneakers. On the right, Zoe: tall and
> angular with sleek shoulder-length hair tucked behind one ear and big hoop earrings, in a
> teal jumpsuit.
>
> Diego leans far forward toward the viewer, elbows on knees, eyes enormous and shining,
> grinning hopefully. Zoe sits back against the cushions with her arms folded, polite but
> faintly puzzled, eyebrows slightly raised. The gap between their body language is the joke.

**4. `couple-004.jpg`** — the long-married pair

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far. Both are in their seventies.
>
> On the left, Harold: short, round and slightly stooped, bald on top with white tufts over
> the ears, a bushy white moustache and half-moon reading glasses, in a mustard cardigan and
> slippers. On the right, Evelyn: small, upright and birdlike with a long thin face, tight
> white permed curls and a pearl necklace, in a high-collared teal blouse.
>
> Both sit bolt upright with hands folded, a wide gap between them, staring straight ahead at
> the viewer with flat, patient, unreadable expressions. Very still, very composed.

**5. `couple-005.jpg`** — the new couple

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far. This Marcus is a different man from the Marcus in an
> earlier drawing; draw him nothing alike.
>
> On the left, Chloe: medium build and rounded, shoulder-length curls with a red headscarf
> tied in them, freckles, in a denim jacket. On the right, Marcus: broad, muscular and
> thick-necked with a shaved head, a full dark beard and heavy brows, in a mustard t-shirt.
>
> They are pressed close together, knees touching, turned toward each other mid-conversation,
> both animated and delighted. Chloe has a hand on Marcus's arm. Loose, happy, slightly messy
> posture.

**6. `couple-006.jpg`** — the settled pair

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far. Both are in their fifties.
>
> On the left, Ruth: tall, soft and long-limbed, silver-grey hair in a loose bun, large round
> red glasses, in a long teal cardigan. On the right, David: medium build with a slight
> paunch, short grey hair, a neat grey beard, reading glasses pushed up on his head, in a
> mustard button-down.
>
> They sit comfortably close, shoulders touching, both completely at ease, calm contented
> half-smiles, facing the viewer. One rests a hand near the other's. They look like they have
> sat like this ten thousand times.

**7. `couple-007.jpg`** — the whirlwind

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far.
>
> On the left, Brittany: petite and bouncy, long wavy blonde hair, heart-shaped sunglasses
> pushed up on her head, a sunburnt nose, in a mustard sundress. On the right, Ryan: tall,
> gym-built and broad with a square jaw, spiky bleached hair and a backwards red cap, in a
> red shirt and flip-flops.
>
> Squeezed right up against each other, both beaming enormous grins directly at the viewer
> with wide eyes, slightly manic. Energetic and a little too much.

**8. `couple-008.jpg`** — the established couple

> Same style, same red couch, same office. A completely new couple — different hair, builds
> and faces from anyone drawn so far. Both are in their forties.
>
> On the left, Elena: medium build and poised, dark hair in a long braid over one shoulder,
> small square glasses, in a teal sweater. On the right, Thomas: medium and comfortable, a
> receding hairline with salt-and-pepper at the sides, clean-shaven, a round friendly face,
> in a red henley.
>
> They sit close and turned slightly toward each other, relaxed and warm, both smiling
> genuinely. Comfortable in their own skin and in the room.

## Where each image is used

Two pages draw on this folder. Nothing about the artwork itself differs between them — the
second page simply uses less of it.

| File | `love-doctor-embed.html` | `love-doctor-embed2.html` |
| --- | --- | --- |
| `dr-love-title.jpg` | Title screen | Title screen |
| `couple-001.jpg` — Marcus & Jennifer, Non-Love | One of the eight cases | **Not used** |
| `couple-002.jpg` … `couple-008.jpg` | The other seven cases | Four of these seven, picked at random each round |

Two things follow from that right-hand column. **Every one of the seven has to be finished**,
because a random four of them come up each round — there is no rarely-seen slot to leave for
later. And the second page's closing review sheet needs no artwork at all: it is drawn in the
page as small love triangles, one per type, not as pictures.

## The run sheet

For the bot, in order:

1. Open ChatGPT and start **one new conversation**. Use it for all nine images.
2. Send the style brief. Wait for the confirmation reply.
3. Send the title-card prompt. When the image returns, run **the four checks** below. If it
   passes, download it and rename it `dr-love-title.jpg`.
4. Send each couple prompt in order, one message at a time, waiting for each image before
   sending the next. Run the four checks on each. Download and rename as you go:
   `couple-001.jpg` through `couple-008.jpg`.
5. Put all nine files in `PSY157/Triangular Love Theory/art/`.

**The four checks on every image.** Reject and regenerate if any fails:

- **The swap test.** Put the new drawing beside the previous one. Could you swap a face
  between the two couples and not notice? If yes, regenerate — this is the failure this
  whole sheet exists to prevent. Name the specific features that got lost: "Sam needs a big
  round afro and Alex needs a high ponytail — right now they look identical."
- **No text anywhere.** Any lettering, signature or watermark means regenerate.
- **Only the five colours** (seven if you took the skin-tone option). If another colour has
  crept in, say "same image but only the colours we agreed."
- **The couch matches the other drawings.** Same colour, same shape, same position.

**When something goes wrong:**

| What happens | What to do |
| --- | --- |
| The couples all look like the same two people | Regenerate naming the two people's hair and builds again, and add "these must look like different individuals from the previous couple" |
| A bag, backpack or suitcase appears beside the couch | It has carried over from an earlier drawing. "Remove the bag — the floor is completely empty" and regenerate |
| Both people in one couple look like siblings | "Make them clearly different heights and builds" — within-couple sameness is as bad as between-couple |
| It drops the glasses, beard or hairstyle you asked for | Re-send that person's line from the character sheet verbatim |
| It names Gemma Correll back at you, or refuses on artist-style grounds | You named her — you should not have. Re-send the style brief as written, which never does |
| The drawing drifts away from the style | Reply "same style as the earlier images" rather than re-pasting the whole brief |
| The couch changes colour | "Use the same couch as the previous image" and regenerate |
| It adds hearts, rings or symbols | Regenerate: "no symbols, no hearts, no props — just the two people on the couch" |
| Text appears in the picture | Regenerate: "no text or lettering of any kind anywhere in the image" |

**Format. Save as JPEG, not PNG.** Title card 3:2, couples 4:3, around 1200px on the long edge. ChatGPT returns PNGs of roughly 1.4 MB each for this kind of art; re-saved as JPEG at quality 82 the same picture is about 200 KB with no visible difference at the size the page shows it. Both pages look for `.jpg` first and `.png` second, so either works — but on a phone the JPEGs load about ten times faster.

**Nothing breaks while the set is incomplete.** Every slot already has a placeholder drawn
into both pages in these same five colours, and each real file replaces its placeholder the
moment it exists. Files can land one at a time, in any order, with no code change — so you
can redo a single couple that came out wrong without touching the rest.
