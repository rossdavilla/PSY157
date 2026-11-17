# PSY157 — Personal Relationships

Class activities for **PSY157** at UC Merced. Live at <https://rossdavilla.github.io/PSY157/>.

## Layout

One folder per activity (plus a couple of loose pages). Everything is plain HTML/CSS/JS inline in
a single page — no build step, no framework, no package manager. `.nojekyll` is present so
GitHub Pages serves the folders as-is.

| Path | Activity |
|---|---|
| `Attributions/attribution.html` | Attribution Theory — classify causes as internal/external, stable/unstable |
| `SocialExchangeTheory/index.html` | Social Exchange Theory — set Outcomes, CL and CL-alt to see satisfaction and dependence |
| `Shyness and Introversion Scale/index.html` | Social Personality Scale — 12 items scoring shyness and introversion separately |
| `Triangular Love Theory/index.html` | Sternberg's triangle — mix passion, intimacy and commitment to get the eight types of love |
| `Triangular Love Theory/love-mixer.html` | Love Mixer — set each component high or low, then mix |
| `Triangular Love Theory/love-doctor.html` | The Love Doctor — diagnose each couple's type of love from what they say |
| `Love Languages Survey/index.html` | Love Languages — rate 20 things a partner might do |

## The `*-embed.html` / `*-iframe.html` copies

`Attributions/attribution-iframe.html`, `SocialExchangeTheory/social-exchange-iframe.html`,
`Shyness and Introversion Scale/embed.html`, `Triangular Love Theory/love-mixer-embed.html`,
`love-doctor-embed.html`, `love-doctor-embed2.html` and `attachment-apps/quiz-embed.html` are
**Top Hat copies**, laid out to fit a fixed **720 × 450** iframe with no scrolling.

They are separate files, not generated from the main pages, so a change to an activity has to be
made in its main page *and* its embed. Say so when you only change one. In the site directory
they belong in that app's `links`, not as cards of their own.

`attachment-apps/` holds an embed of the quiz that lives in the separate
[`Attachment_Games`](https://github.com/rossdavilla/Attachment_Games) repo — the activity itself
is maintained there.

## Conventions

- Nothing is collected: no backend, no analytics, no accounts. These run in class on students'
  own phones.
- Folder names contain spaces, so URLs need `%20`.
- Art direction for the illustrations lives beside the activity —
  `Love Languages Survey/ChatGPT Art Instructions.md`, `Triangular Love Theory/art/README.md`
  and the `*-image-prompts.md` files there. Edit those rather than generating images ad hoc.

## Publishing

GitHub Pages serves `main` from the repository root, so a push to `main` is the deploy.

After adding an activity, add it to `data/sites.json` in the
[`rossdavilla.github.io`](https://github.com/rossdavilla/rossdavilla.github.io) repo with the
`PSY157` tag (some of these are also tagged `PSY175`). Keep the README's activity list in sync
too — it is linked from the course materials.
