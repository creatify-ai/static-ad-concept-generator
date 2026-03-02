# Platform-Specific Format Patterns

Ad format specs and creative patterns by platform. Use these to tailor concepts for each channel.

---

## Platform Specifications

### Meta (Facebook + Instagram)

| Format | Dimensions | Aspect Ratio | Max Text | Notes |
|--------|-----------|--------------|----------|-------|
| Feed (square) | 1080×1080 | 1:1 | 125 chars primary | Most versatile, works in both feeds |
| Feed (portrait) | 1080×1350 | 4:5 | 125 chars primary | More real estate, better engagement |
| Stories/Reels | 1080×1920 | 9:16 | Keep text in safe zone | Full-screen, highest engagement |
| Carousel | 1080×1080 each | 1:1 | Up to 10 cards | Great for storytelling, features, steps |
| Right column | 1200×628 | ~1.91:1 | Short headlines | Desktop only, lower cost |

**Creative Patterns That Work on Meta:**
- Single product hero with bold headline overlay
- Before/after split frame (especially 4:5)
- Carousel: problem → solution → proof → CTA
- UGC-style screenshot with review text
- "Us vs Them" comparison graphic
- Ingredient/feature callout with clean background

### Google Display Network

| Format | Dimensions | Type | Notes |
|--------|-----------|------|-------|
| Leaderboard | 728×90 | Banner | Top of page, high visibility |
| Medium Rectangle | 300×250 | Banner | Most available inventory |
| Wide Skyscraper | 160×600 | Sidebar | Good for vertical messaging |
| Large Rectangle | 336×280 | Banner | Higher CTR than 300×250 |
| Billboard | 970×250 | Banner | Premium placements |
| Mobile Banner | 320×50 | Mobile | Small but high volume |
| Large Mobile | 320×100 | Mobile | 2x mobile banner |

**Creative Patterns for Display:**
- Simple: product + headline + CTA button
- Keep to 3 elements max (image, text, CTA)
- High contrast for readability at small sizes
- Brand colors for recognition across placements
- Animate if possible (GIF) for attention

### TikTok

| Format | Dimensions | Aspect Ratio | Duration | Notes |
|--------|-----------|--------------|----------|-------|
| In-Feed | 1080×1920 | 9:16 | 5-60s | Native content feel required |
| TopView | 1080×1920 | 9:16 | 5-60s | First ad users see |
| Spark Ads | 1080×1920 | 9:16 | Any | Boost organic posts |

**Creative Patterns for TikTok:**
- Hook in first 1 second (visual or text)
- UGC aesthetic over polished
- Text overlays for sound-off viewing
- Trending format adaptation
- Problem → product → result arc
- "Things I wish I knew" / listicle format

### LinkedIn

| Format | Dimensions | Aspect Ratio | Notes |
|--------|-----------|--------------|-------|
| Single Image | 1200×628 | 1.91:1 | Standard feed image |
| Single Image (square) | 1080×1080 | 1:1 | Higher engagement |
| Carousel | 1080×1080 | 1:1 | Up to 10 cards, PDF upload |
| Stories | 1080×1920 | 9:16 | Mobile only |

**Creative Patterns for LinkedIn:**
- Data/stat-driven visuals with clean design
- "Hot take" text posts with supporting image
- Case study snapshots with metric callouts
- Carousel: insight per slide, educational
- Professional but not boring — bold typography works

### Pinterest

| Format | Dimensions | Aspect Ratio | Notes |
|--------|-----------|--------------|-------|
| Standard Pin | 1000×1500 | 2:3 | Recommended default |
| Long Pin | 1000×2100 | 1:2.1 | More content space |
| Square Pin | 1000×1000 | 1:1 | For simpler concepts |

**Creative Patterns for Pinterest:**
- Text overlay on aspirational lifestyle imagery
- Step-by-step infographic format
- Product in beautiful context (not isolated)
- Warm, bright color palettes perform best
- "How to" and tutorial formats

### YouTube

| Format | Dimensions | Aspect Ratio | Notes |
|--------|-----------|--------------|-------|
| Display Ad | 300×250 | — | Beside video player |
| Overlay | 480×70 | — | Bottom of video |
| Companion Banner | 300×60 | — | With video ads |
| Thumbnail | 1280×720 | 16:9 | For video content |

---

## Cross-Platform Adaptation Strategy

### From One Concept to Multiple Platforms

Start with a single strong concept, then adapt:

```
1. HERO CONCEPT (platform-agnostic)
   └── Angle + Headline + Visual Direction + CTA

2. ADAPT TO FORMATS
   ├── Meta Feed (1080×1080): Full concept with image
   ├── Meta Stories (1080×1920): Vertical with animated text
   ├── Google Display (300×250): Simplified to product + headline + CTA
   ├── TikTok (1080×1920): UGC-style video version
   ├── LinkedIn (1200×628): Data-driven version of same angle
   └── Pinterest (1000×1500): Lifestyle-context version
```

### Adaptation Rules

1. **Simplify for smaller formats**: Display banners need 50% fewer words than feed posts
2. **Verticalize for mobile-first**: Stories/Reels/TikTok need vertical composition
3. **Match platform tone**: LinkedIn = professional, TikTok = casual, Pinterest = aspirational
4. **Adjust CTA language**: "Shop Now" (Meta), "Learn More" (LinkedIn), "Try It" (TikTok)
5. **Respect safe zones**: Stories/Reels have top and bottom UI overlap areas

---

## IAB Standard Banner Sizes

For programmatic display advertising, these are the standard IAB sizes:

| Size | Name | Use |
|------|------|-----|
| 728×90 | Leaderboard | Desktop header |
| 300×250 | Medium Rectangle | Universal, highest fill |
| 160×600 | Wide Skyscraper | Desktop sidebar |
| 300×600 | Half Page | Premium desktop |
| 320×50 | Mobile Leaderboard | Mobile standard |
| 320×100 | Large Mobile Banner | Mobile premium |
| 970×250 | Billboard | Desktop premium |
| 970×90 | Large Leaderboard | Desktop header |
| 336×280 | Large Rectangle | Desktop in-content |

Use Creatify's IAB Images endpoint to generate all standard sizes from a single product image automatically.
