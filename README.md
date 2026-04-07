# Project 1 — Loom to Bloom

Loom to Bloom is a one-page interactive website about Indian textiles and the designers who are reimagining them in contemporary fashion. The experience is designed as an editorial and immersive web piece rather than a commercial or product-based site. It begins with a cinematic collage and transitions into a five-panel interactive layout where each collection opens into its own visual world through hover-based interaction.

---

## Design Intent

### 1. Core Idea
This project is a one-page interactive website about Indian textiles and the designers who are reimagining them in contemporary fashion. It begins with a cinematic introduction and then moves into a five-panel interactive layout. Each panel highlights a different designer and collection through imagery, typography, color, and hover interaction.

---

### 2. Mood
The mood should feel warm, rich, and editorial, with a sense of quiet luxury. It should combine the beauty of Indian textiles with a cinematic and fashion-forward atmosphere, so the website feels immersive, elegant, and emotionally layered rather than simple or commercial.

---

### 3. Visual Keywords
- Warm
- Editorial
- Cinematic
- Luxurious
- Textile
- Romantic
- Heritage
- Immersive

---

### 4. Typography

| Role | Font | Weight | Size | Notes |
|---|---|---|---|---|
| Heading | Cormorant Garamond | Bold | ~84px | Stage 1 title. Line height 95%, slightly reduced tracking. |
| Subheading | Neue Haas Grotesk | Medium | ~20px | Stage 1 subtitle and short supporting lines. Line height 140%. |
| Body | Neue Haas Grotesk | Regular | ~16px | Hover-state supporting text. Line height 145–150%. |
| Panel Labels | Neue Haas Grotesk | Bold | ~22px | Vertically oriented, high contrast, minimal tracking. |

---

### 5. Color System

| Token | Value | Usage |
|---|---|---|
| Primary Background | `#532128` | Main background — deep muted maroon, warm and heritage-inspired |
| Text | `#FFF39E` | Headings and key text — soft warm gold |
| Intro Tint 1 | `#532122` at 25% opacity | Adds warmth and depth to the opening screen |
| Intro Tint 2 | `#220001` at 40% opacity | Darker overlay for cinematic, moody intro tone |
| Stage 2 Overlay | `#532128` at 25% opacity | Unifies panel images and maintains visual consistency |
| Panel Overlay | `#330304` at 10% opacity | Subtle panel deepening without losing image detail |

---

### 6. Layout Rules

The layout moves through three clear visual states: an atmospheric introduction, a structured selection screen, and an expanded hover state. Each stage should feel connected to the same visual world, shifting from mood to interaction in a smooth and intentional way.

#### Stage 1 — Intro Screen
The website opens on a full-screen cinematic collage that fills the entire viewport. The composition should feel layered, immersive, and editorial, using overlapping imagery rather than a rigid grid. Images should vary in scale and cropping within one unified warm, moody palette. The title is placed prominently at center as the main focal point, with the subtitle directly below. This stage is not interactive — its role is to establish context, mood, and visual richness before the selection screen appears.

#### Stage 2 — Default Selection Screen
After the intro fades, the layout shifts into a five-panel full-screen composition. The screen is divided into five equal vertical panels, each taking up 20% of the width. Panels should sit flush with little to no spacing so the screen feels continuous and immersive. Each panel contains a full-length or near full-length fashion image. Collection names are placed consistently near the bottom of each panel.

#### Stage 3 — Hover / Expanded State
When the user hovers over a panel, that panel expands to become the dominant visual focus — growing to approximately 60% of the screen width. The remaining four panels compress proportionally and visually recede. Additional content appears inside the selected panel (designer name, brand name, collection name, and brief supporting information) with generous breathing room.

#### Spatial Hierarchy
Imagery should remain the primary visual driver at all times, with typography as a supporting layer. The layout should always feel full-screen, immersive, and visually controlled — never cluttered or overly interface-heavy.

#### Composition Rules
All imagery should be cropped to protect garment silhouette and textile detail. Text placement should stay consistent across the five panels so the system feels intentional. The layout should balance editorial drama with interface clarity.

---

### 7. Motion Rules

Motion should feel smooth, restrained, and cinematic — never flashy or overly energetic.

| State | Timing | Behavior |
|---|---|---|
| Intro fade out | 0.6s ease | Soft veil lifting — not a hard cut |
| Intro duration | ~1.2s visible | Calm atmospheric opening |
| Hover expansion | ~0.45s ease-in-out | Panel widens while others compress simultaneously |
| Overlay / emphasis change | 0.3–0.35s | Image filter and tint transitions |
| Text reveal delay | 0.1–0.12s after expansion begins | Fade in over ~0.25s |

All motion should remain subtle and purposeful — no bouncing, snapping, or exaggerated movement.

---

### 8. Hover Behavior

#### Default State
All five panels appear equal in width and importance. Collection name is the only text visible.

#### Expanded Hover State
The hovered panel becomes dominant. It expands, revealing more of the garment and additional collection information. Non-hovered panels compress and dim.

#### Information Reveal Order
1. Brand name
2. Collection name
3. Designer name
4. Short descriptive body text

Text should feel integrated into the image — not placed on top as a separate interface block.

#### Hover State Content

| Panel | Brand | Collection | Designer |
|---|---|---|---|
| 1 | Tilla | The Vintage Project | Aratrik Dev Varman |
| 2 | Injiri | Rasa | Chinar Farooqui |
| 3 | Payal Khandwala | Release 13 | Payal Khandwala |
| 4 | Torani | Juloos | Karan Torani |
| 5 | Anita Dongre | Crafts of India 2025 | Anita Dongre |

#### Hover Body Copy

**Panel 1 — Tilla / The Vintage Project**
The Vintage Project pays homage to traditional textiles and folk embroideries from the Indian subcontinent by repurposing old pieces collected for their workmanship and heirloom value.

**Panel 2 — Injiri / Rasa**
Rasa is a kind of sentiment and the audience gets the sentiment from a piece of creative object. It is an inborn desire of humankind to express the emotions and feelings we get from our daily acts and observation.

**Panel 3 — Payal Khandwala / Release 13**
Our newest release places handwoven silk, our signature textile, at the heart of your wardrobe. In this collection, Payal reimagines the fabric with versatility in mind, designing pieces that transcend effortlessly across seasons and occasions.

**Panel 4 — Torani / Juloos**
Juloos is a celebration of India's multicultural spirit, drawing from festivity, community, and shared joy. The collection feels cinematic and nostalgic, turning moments of togetherness into a rich, expressive fashion story.

**Panel 5 — Anita Dongre / Crafts of India 2025**
Crafts of India 2025 brings together a rich range of Indian textile traditions through handwoven Benarasi silk, Ajrakh hand-block printing, Bandhani, and SEWA hand embroidery. The collection feels celebratory and craft-forward, presenting heritage techniques through refined, contemporary silhouettes.

---

### 9. Content Hierarchy

At every stage, the website should prioritize mood, fashion imagery, and textile presence first — with text supporting the experience rather than dominating it.

- **Stage 1** — Title dominant. Subtitle below. Collage as atmosphere.
- **Stage 2** — Imagery dominant. Collection name the only visible text.
- **Stage 3** — Image still primary. Text reveals in hierarchy: brand → collection → designer → description.

Content moves from broad context → selection → deeper detail across the three stages.

---

### 10. Image Selection Rules

- All images should feel editorial, cinematic, textile-rich, and visually curated
- Emphasize silhouette, material, texture, and mood — not e-commerce catalog style
- Show full body or near full body of the garment where possible
- Lighting, tone, and background should remain reasonably consistent across all five panels
- Textile detail (embroidery, weave, drape, surface) must be visible and legible
- Each panel should have a distinct mood while still belonging to one cohesive visual world
- Avoid: overly commercial, flat, or portraiture-focused images

---

### 11. Non-Negotiables

- The website must feel editorial, cinematic, and textile-rich — not commercial or product-based
- Imagery must foreground garment, textile, and mood rather than portraiture alone
- Hover interaction must create a clear and dramatic change in hierarchy
- The five collections must feel distinct but still belong to one cohesive atmosphere
- Typography must remain elegant and fashion-forward
- The final experience should prioritize art direction, mood, and visual storytelling over unnecessary complexity

---

### 12. Constraints

- Single-page only — no routing
- No backend functionality
- Core interaction: five-panel full-screen layout with hover-based expansion
- No complex navigation or multiple pages
- Main differentiator is visual concept, typography, imagery, and interaction design — not technical complexity

---

### 13. Sketch / Layout Notes

**Stage 1 — Intro Overlay**
- Heading: *Loom to Bloom*
- Subheading: *Explore Indian Textiles & Designers*

**Stage 2 — Five-Panel Default State**
- Panel 1: The Vintage Project
- Panel 2: Rasa
- Panel 3: Release 13
- Panel 4: Juloos
- Panel 5: Crafts of India 2025

---
