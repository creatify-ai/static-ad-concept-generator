# static-ad-concept-generator

> Generate proven ad concepts for any product — 320+ templates organized by angle, audience, and platform.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Claude Skill](https://img.shields.io/badge/Claude-Agent_Skill-blueviolet)](https://docs.anthropic.com)

## What This Does

Give it any product or brand, and it generates 5-10 fully specified ad concepts using battle-tested templates. Each concept includes headline, visual direction, CTA, and audience targeting — ready for design or production. Covers DTC, B2B, SaaS, health, beauty, food, finance, education, and more.

## Quick Install

```bash
# Clone into your Claude skills directory
git clone https://github.com/Creatify-AI/static-ad-concept-generator.git ~/.claude/skills/static-ad-concept-generator
```

## What's Inside

| Feature | Description |
|---------|-------------|
| 16 Universal Ad Angles | Problem, transformation, social proof, comparison, urgency, and 11 more |
| Category-Specific Templates | DTC, B2B/SaaS, health, beauty, food — 50+ templates with headline formulas |
| Headline Formula Library | 15+ proven structures: benefit, curiosity, social proof, comparison, urgency |
| Visual Direction Guide | 10 static image styles with descriptions and best-use recommendations |
| 6-Step Generation Process | Research → angles → headlines → visuals → audience → output |
| Production Integration | Turn concepts into static images, video ads, or avatar videos via API |

## Standalone Features

### 16 Universal Ad Angles
Every product can be sold from multiple angles. This framework covers 16 proven perspectives — from pain point and transformation to FOMO, risk reversal, and ingredient spotlight — each with 3+ headline templates ready to customize.

### Category-Specific Concept Templates
Pre-built concept tables for DTC e-commerce, B2B/SaaS, health & wellness, beauty & skincare, and food & beverage. Each includes the concept name, headline template, and visual direction.

### Headline Formula Library
15+ fill-in-the-blank headline structures organized by driver: benefit, curiosity, social proof, comparison, and urgency. Tested across thousands of ad campaigns.

### Visual Direction Guide
10 static image styles (hero product, lifestyle, flat lay, before/after, infographic, testimonial card, comparison, text-heavy, UGC screenshot, ingredient/feature) with descriptions and best-use recommendations.

### 6-Step Concept Generation Process
Systematic process from research to output: understand the product, select angles, generate headlines, specify visuals, assign audience + CTA, and output 5-10 production-ready concepts.

## API Automation (Creatify)

Turn your concepts into production-ready assets with the [Creatify API](https://creatify.ai):

- **IAB Images** — Generate display banners in all standard sizes from a product image
- **URL to Video** — Feed a product URL and get a complete video ad
- **AI Avatar** — Turn concept scripts into talking-head video ads
- **Asset Generator** — Generate product photography with Nano Banana or Flux Pro

Get your API credentials at [creatify.ai](https://creatify.ai) → Settings → API.

## File Structure

```
static-ad-concept-generator/
├── SKILL.md                      # Main skill (install this)
├── references/
│   └── format-patterns.md        # Platform-specific format patterns
├── README.md
└── LICENSE
```

## See Also

Other ad creation skills by [Creatify](https://creatify.ai):

- [video-ad-generator](https://github.com/Creatify-AI/video-ad-generator) — Product URL → video ad pipeline
- [ai-avatar-video](https://github.com/Creatify-AI/ai-avatar-video) — AI talking-head videos with 1,500+ personas
- [ai-ad-prompt-guide](https://github.com/Creatify-AI/ai-ad-prompt-guide) — Battle-tested prompting for AI ad creative
- [ad-creative-evaluator](https://github.com/Creatify-AI/ad-creative-evaluator) — Score any video ad with AI expert panel
- [video-ad-reverse-engineer](https://github.com/Creatify-AI/video-ad-reverse-engineer) — Reverse-engineer competitor ads

## Contributing

PRs welcome! Please open an issue first to discuss changes.

## License

MIT © [Creatify](https://creatify.ai)
