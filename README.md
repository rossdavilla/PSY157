# PSY157 — Personal Relationships

Class activities for PSY157 at UC Merced. Each one is a single self-contained HTML page: no build
step, no dependencies, and nothing collected — no accounts, no backend, no analytics.

**Live site:** https://rossdavilla.github.io/PSY157/

## Activities

| Activity | What it does | Top Hat embed |
| --- | --- | --- |
| [Attribution Theory](https://rossdavilla.github.io/PSY157/Attributions/attribution.html) | Classify the causes of everyday behavior: internal or external, stable or unstable. | [720×450](https://rossdavilla.github.io/PSY157/Attributions/attribution-iframe.html) |
| [Social Exchange Theory](https://rossdavilla.github.io/PSY157/SocialExchangeTheory/) | Set Outcomes, CL and CL-alt to see the resulting satisfaction, dependence, and a matching relationship scenario. | [720×450](https://rossdavilla.github.io/PSY157/SocialExchangeTheory/social-exchange-iframe.html) |
| [Social Personality Scale](https://rossdavilla.github.io/PSY157/Shyness%20and%20Introversion%20Scale/) | Twelve statements that score shyness and introversion separately, 0–100, with an interpretation. | [720×450](https://rossdavilla.github.io/PSY157/Shyness%20and%20Introversion%20Scale/embed.html) |
| [Triangular Theory of Love](https://rossdavilla.github.io/PSY157/Triangular%20Love%20Theory/) | Mix passion, intimacy and commitment to arrive at Sternberg’s eight types of love. | — |
| [Love Mixer](https://rossdavilla.github.io/PSY157/Triangular%20Love%20Theory/love-mixer.html) | Set each of the three components high or low, then mix to see which type of love you made. | [720×450](https://rossdavilla.github.io/PSY157/Triangular%20Love%20Theory/love-mixer-embed.html) |
| [The Love Doctor](https://rossdavilla.github.io/PSY157/Triangular%20Love%20Theory/love-doctor.html) | Diagnose each couple’s type of love from what they tell you about passion, intimacy and commitment. | [720×450](https://rossdavilla.github.io/PSY157/Triangular%20Love%20Theory/love-doctor-embed.html) · [v2](https://rossdavilla.github.io/PSY157/Triangular%20Love%20Theory/love-doctor-embed2.html) |
| [Love Languages Survey](https://rossdavilla.github.io/PSY157/Love%20Languages%20Survey/) | Rate 20 things a partner might do by how much each would mean to you. | — |

The attachment-style activities for this course live in their own repository,
[Attachment_Games](https://github.com/rossdavilla/Attachment_Games); `attachment-apps/` here
holds a 720×450 embed of the quiz.

```html
<iframe src="https://rossdavilla.github.io/PSY157/SocialExchangeTheory/social-exchange-iframe.html"
        width="720" height="450" style="border:0;max-width:100%"
        title="Social Exchange Theory"></iframe>
```

## Running it

Serve the repository root, since several activities load local images:

```bash
python3 -m http.server 8000
```

Folder names contain spaces, so URLs need `%20`. Art direction for the illustrations lives beside
each activity — `Love Languages Survey/ChatGPT Art Instructions.md` and
`Triangular Love Theory/art/`.
