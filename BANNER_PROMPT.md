# Banner generation prompts — Aman Pandey GitHub profile

**Concept (v2):** A stylized human figure engaging with an AI / RAG visualization — the "engineer trying to understand the system." Inspired by Brijesh's banner concept (person + AI imagery) but original in composition, color, and treatment. Premium dark aesthetic preserved from v1.

Target: **1500 × 500 px** PNG. Export to `./assets/banner.png`.

Recommended tools (in rough order of best results for this brief):
1. **Midjourney v6+** — best for the cinematic, atmospheric quality this banner needs. Append `--ar 3:1 --style raw --quality 2 --stylize 300`.
2. **Flux.1 [pro]** — strong on stylized human figures + abstract overlays.
3. **DALL-E 3 (via ChatGPT or API)** — handles the brief well; combine with the no-text instruction.
4. **Stable Diffusion XL** — works if you provide the negative prompt below.

---

## 1. Concise prompt (paste-and-go)

> Wide cinematic banner illustration for a GitHub profile header. A stylized silhouette of a young male engineer, shown from the side or three-quarter back view, contemplating a luminous AI / neural-network visualization that flows out from his perspective — embedding dots, vector lines, and a glowing retrieval node forming in the air around him. The figure is rendered in deep navy silhouette with subtle cyan rim-light, set against a dark gradient background (navy → indigo → violet). The neural visualization spreads from the figure's eye-line outward to the right of the frame. Minimal, premium, futuristic — like a research-lab keynote slide. No text, no logos, no facial detail. 16:5 aspect ratio.

Midjourney form: append `--ar 3:1 --style raw --quality 2 --stylize 300`.

---

## 2. Detailed prompt (for fine control)

> A 1500 × 500 pixel cinematic banner for a senior AI / ML engineer's GitHub profile. The concept: **"the engineer trying to understand AI."**
>
> **Composition.** Left third of the frame contains a stylized silhouette of a young South Asian male engineer (short hair, slim build, casual hoodie or simple sweater), shown from the side or three-quarter back view, head slightly tilted upward in contemplation. He is rendered almost entirely as a deep-navy silhouette with a thin cyan rim-light tracing his profile. **No facial features visible** — he is a silhouette, not a portrait. He fills roughly the left 25–30% of the canvas.
>
> Middle and right two-thirds: a luminous AI / neural-network visualization emerging outward from the figure's eye-line. The visualization consists of small luminous embedding-dots clustering at his temple, thin vector lines flowing rightward and slightly upward, passing through a softly glowing hexagonal retrieval node about two-thirds across the frame, then dissolving into a translucent neural-network silhouette in the far right (nodes + edges, very low opacity, atmospheric).
>
> The visualization should feel like it's **emanating from his perspective** — as though we're seeing what he's reasoning through, not a poster on a wall behind him.
>
> **Palette.** Deep navy `#0B1020` as the dominant background, transitioning to indigo `#1B1740` and a subtle violet `#332253` toward the bottom right. The figure: navy silhouette `#0B1020` with thin cyan rim-light `#5BC8FF`. The visualization: pale electric blue `#7AA7FF` embedding dots, cyan `#5BC8FF` vector lines, and a single warm-gold `#F2C36B` glow at the retrieval node to break the cool palette and serve as the eye's focal point.
>
> **Style.** Minimalist, premium, slightly cinematic. Soft volumetric glow around the retrieval node. Subtle film grain. 2D vector + soft glow aesthetic — the kind of artwork that fits a research-lab landing page or an Anthropic / OpenAI keynote slide. Clean, futuristic, restrained. **Not** a stock photo of a person at a laptop. **Not** a photorealistic portrait. **Not** the cliché "man-touching-glowing-hologram." The figure should feel thoughtful and grounded, not in awe.
>
> **Restrictions.** No text in the image — text will be added by the README markdown. No logos, no brand marks. No visible facial features (silhouette only). No glasses, no beard detail, no eyes. No laptops, no monitors, no keyboards, no server racks, no chairs, no offices. No robots, no humanoid AI figures. No reaching hands, no "holding a brain" pose, no AR/VR headsets. No matrix code rain. No glitch artifacts. No rainbow gradients. No floating "AI" letters.
>
> **Output.** Wide horizontal format suitable for a GitHub profile banner, 16:5 aspect ratio (1500 × ~470, padded to 1500 × 500). High detail on the figure's silhouette edge and the retrieval-node focal point; soft and atmospheric in the corners.

---

## 3. Alternate composition (if the side-view feels off)

If the side-view render doesn't land, try this variant — same palette, same restrictions:

> Stylized silhouette of a young male engineer shown **from behind**, standing slightly left of center, looking out into a vast dark space. From his shoulders and head, faint luminous lines and embedding dots radiate forward and outward into the right two-thirds of the frame, forming a soft constellation that converges on a single glowing gold retrieval node in the upper right. The figure occupies the lower-left quadrant; the AI visualization fills the rest. Same navy → indigo → violet gradient. No text, no facial features, no laptop, no chair, no environmental props. The figure should feel small relative to the vastness of the visualization in front of him — emphasizing scale and depth of thought.

This back-view version often reads cleaner in image models because there are no facial-feature artifacts to fight.

---

## 4. Negative prompt (for SDXL / Flux UIs that accept one)

```
text, words, letters, watermark, logo, signature, facial features, eyes, face, beard, glasses, mustache, mouth, nose, ears, hands, fingers, laptop, computer screen, monitor, keyboard, mouse, desk, chair, office, server rack, robot, humanoid robot, AI headset, VR headset, AR glasses, matrix code, falling green characters, glitch, neon pink, neon green, rainbow gradient, holding brain, touching hologram, reaching hand, stock photo pose, low quality, jpeg artifacts, blurry, oversaturated, cartoon, anime, comic, 3d render plastic, two figures, crowd
```

---

## 5. Dimensions

- **Target export**: `1500 × 500 px`, PNG. Solid dark background, no transparency.
- **Aspect**: 3:1 (correct for README hero placement at `width="100%"`).
- **Safe area for typography overlay** (if you ever bake text into the banner): right 40% of the canvas — keep the figure on the left, leave the right open. Default recommendation: keep typography in markdown so the banner stays reusable.

## 6. Color palette (hex)

| Hex       | Role                                             |
| --------- | ------------------------------------------------ |
| `#0B1020` | Deep navy — primary background + figure silhouette |
| `#1B1740` | Indigo — mid-gradient                            |
| `#332253` | Violet — lower-right gradient                    |
| `#5BC8FF` | Cyan — rim-light on figure, vector-line accents  |
| `#7AA7FF` | Pale electric blue — embedding dots              |
| `#F2C36B` | Warm gold — single focal accent at retrieval node |
| `#E7ECF5` | Off-white — for typography (markdown, not image) |

## 7. Text placement

**Do NOT bake text into the banner image.** Name and tagline live in the markdown `<h1>` and `<p>` under the banner. This keeps the banner reusable when the tagline evolves, keeps text sharp at all zoom levels, and avoids generative-model text artifacts.

## 8. After generation — QA checklist

Before saving as final:
- [ ] Is the figure clearly a silhouette, not a portrait with mangled features? (Image models often try to add a face — if you see one, regenerate.)
- [ ] Does the AI visualization look like it's coming *from* the figure (his perspective / reasoning) rather than a poster behind him?
- [ ] Is the retrieval node the brightest single point? Eye should land there second, after the figure.
- [ ] Are the dark areas truly dark (`#0B1020`-ish), not muddy gray?
- [ ] Zero visible letters anywhere? (Regenerate or inpaint if any sneaked in.)
- [ ] Does it look crisp at full README width on a 1440px monitor?
- [ ] Squint test: cover the figure with your hand — does the right side of the banner still read as "AI / RAG visualization"? Cover the visualization — does the figure read as "engineer in thought"?

## 9. About v1 (the abstract-only render)

The earlier render at `assets/banner_option_1.png` (abstract embeddings + retrieval node, no figure) is good craft but reads as a data-viz screensaver. The v2 concept above keeps the same palette and AI imagery but anchors it with a human silhouette — adds intentionality and "someone is thinking through this" warmth, in the spirit of Brijesh's banner without copying his composition, treatment, or specific imagery.

If you render v2 and prefer v1's pure-abstract look anyway, that's a valid call — just rename the chosen file to `banner.png` before pushing.

## 10. Fallback if no render works today

Skip the banner for v1 of the README. The page still works with just the `<h1>` + role tagline + badges row. Add the banner in v1.1 once you have an image you actually like. Great profile without a banner > mediocre profile with a stock-feeling one.
