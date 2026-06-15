---
name: cross-cultural-ad-risk-auditor
description: Use this skill to review advertising copy, visual concepts, slogans, campaign ideas, influencer scripts, landing-page text, or short video concepts for cross-cultural communication risks before international launch. It identifies possible cultural, religious, linguistic, visual, regulatory, and platform-context risks, explains why they may matter, and suggests lower-risk alternatives while preserving the campaign's intent.
---

# Cross-Cultural Ad Risk Auditor / 跨文化广告风险审阅器

## Purpose

This skill helps users run a structured “cultural risk pre-check” for ads intended for overseas or multi-cultural audiences.

It is designed for:

- brand teams preparing international campaigns
- students learning advertising, branding, or cross-cultural communication
- agencies reviewing creative ideas before client presentation
- cross-border e-commerce teams localizing product pages, videos, and social ads
- founders or creators who need a first-pass cultural sensitivity review

The skill does **not** replace legal review, local market research, religious/cultural consultation, platform policy review, or native-speaker copy review. Treat it as an early warning and improvement tool.

## When to Use This Skill

Use this skill when the user asks about any of the following:

- cross-cultural advertising
- overseas advertising
- brand localization
- cultural taboo checking
- ad “翻车” risk
- international campaign review
- cultural sensitivity review
- slogan localization
- social media campaign risk
- visual concept risk
- influencer script risk
- cross-border e-commerce ad copy

## Inputs to Request

If the user has not provided enough information, request only the missing items that materially affect risk judgment.

Recommended input template:

```markdown
## Campaign Information

- Brand / product:
- Industry category:
- Target market or region:
- Target audience:
- Campaign objective:
- Media platform:

## Creative Materials

- Ad copy / slogan:
- Visual description:
- Video / storyboard description:
- Key symbols, colors, gestures, characters, animals, food, music, clothing:
- Claims or promises made in the ad:

## Constraints

- What must be preserved:
- What can be changed:
- Deadline / usage scenario:
```

If the user only provides partial information, proceed with clearly marked assumptions.

## Core Review Framework

Review the ad from eight dimensions.

### 1. Language and Translation Risk

Check for:

- literal translation problems
- unintended double meanings
- homophones, slang, or vulgar associations
- unnatural wording in the target language
- overpromising claims
- culturally inappropriate humor
- slogan ambiguity

### 2. Religious and Customary Risk

Check for:

- religious symbols used casually or commercially
- food, alcohol, pork, beef, fasting, or ritual-related issues
- clothing, body exposure, gender interaction, or sacred spaces
- festival misuse
- disrespectful treatment of religious figures, texts, or rituals

### 3. Visual Symbol Risk

Check for:

- colors with negative meanings in the target context
- gestures with offensive meanings
- animals with taboo or insulting connotations
- numbers, icons, flags, maps, borders, national symbols
- funerary, military, political, or sacred imagery

### 4. Identity, Gender, and Representation Risk

Check for:

- racial or ethnic stereotyping
- gender objectification
- age, disability, body-shape, class, occupation, or regional stereotypes
- tokenistic diversity
- “exoticizing” local culture
- unequal power relationships in the scene

### 5. Value Conflict Risk

Check whether the creative idea conflicts with local mainstream expectations around:

- individualism vs. collectivism
- family and authority
- modesty and self-display
- humor and sarcasm
- competition and comparison
- hierarchy and respect
- privacy and social boundaries

Use cultural frameworks such as Hofstede’s cultural dimensions only as broad references, never as deterministic stereotypes.

### 6. Political and Geopolitical Risk

Check for:

- maps, borders, flags, disputed territories
- national dignity or historical trauma
- colonial, war, or ethnic conflict references
- protest symbols or politically sensitive language
- jokes about national identity

### 7. Platform and Context Risk

Check for:

- platform policy sensitivity
- influencer authenticity issues
- comment-section misinterpretation risk
- short-video visual compression causing misunderstanding
- meme culture differences
- whether the same creative means different things on TV, outdoor ads, TikTok, Instagram, YouTube, Xiaohongshu, Amazon, or e-commerce pages

### 8. Legal, Regulatory, and Category Risk

Flag potential issues around:

- health, medical, cosmetic, finance, children, education, food, alcohol, supplements, gambling, political ads
- before/after claims
- environmental or ESG claims
- price, discount, and performance claims
- endorsements and influencer disclosure

Do not provide legal advice. Recommend local legal or compliance review when necessary.

## Risk Rating Method

Use a 0–100 risk score, where higher means higher risk.

| Score | Level | Meaning |
|---:|---|---|
| 0–20 | Low | Minor localization issues or no obvious risk |
| 21–45 | Watch | Some wording or visual elements may need adjustment |
| 46–70 | High | Clear possibility of audience backlash or platform/compliance concern |
| 71–100 | Critical | Strong risk of public controversy, regulatory issue, religious/cultural offense, or brand damage |

For every finding, include a confidence label:

- **High confidence**: based on widely known, well-documented, or user-provided market facts
- **Medium confidence**: plausible but requires local verification
- **Low confidence**: speculative; include as a watch item only

Do not invent certainty. When uncertain, say “needs local validation.”

## Output Format

Always produce a structured report.

```markdown
# Cross-Cultural Ad Risk Report / 跨文化广告风险报告

## 1. Executive Summary / 核心结论

- Overall risk score:
- Risk level:
- Main concern:
- Go / revise / stop recommendation:

## 2. Input Recap / 输入信息复述

- Target market:
- Platform:
- Product category:
- Creative idea:
- Assumptions:

## 3. Risk Map / 风险地图

| Dimension | Risk Level | Evidence / Reason | Confidence | Suggested Action |
|---|---|---|---|---|

## 4. Key Risk Findings / 重点风险点

### Risk 1: [Name]

- Trigger element:
- Why it may be risky:
- Possible audience reaction:
- Severity:
- Confidence:
- How to verify:

## 5. Safer Alternatives / 低风险改编方案

Provide 3–5 alternatives that preserve the core campaign intent.

For each alternative:

- Replacement wording / visual:
- Why it is safer:
- What creative value is preserved:
- Remaining risk:

## 6. Local Validation Checklist / 本地验证清单

- Native-language copy review
- Local legal/compliance review
- Platform policy check
- Local focus group or small-scale A/B test
- Religious/cultural consultant review if relevant

## 7. Final Recommendation / 最终建议

Give a clear recommendation:

- Safe to proceed
- Proceed after minor localization
- Major revision required
- Do not launch before local expert review
```

## Response Style

- Be practical and specific.
- Avoid stereotypes and exaggerated claims.
- Do not shame any culture, country, religion, or group.
- Prefer “may be perceived as…” rather than “people in X country always think…”
- Separate confirmed risks from possible risks.
- Explain the reasoning behind each warning.
- Give usable alternatives, not only criticism.
- Preserve the advertiser’s core intent where possible.

## Source and Verification Rules

When the environment allows web browsing or file lookup:

1. Prioritize official sources, platform policies, academic sources, reputable media, and local regulatory pages.
2. If using case examples, verify the case and do not repeat rumors as facts.
3. Mark unsupported claims as “needs verification.”
4. Do not rely only on viral social media posts.

When browsing is unavailable:

1. Clearly state that the report is a first-pass review.
2. Avoid exact factual claims that require up-to-date verification.
3. Recommend local/native review for high-risk markets or regulated categories.

## Common Use Cases

### Use Case 1: Slogan Review

User provides a slogan and target market. Review translation risk, emotional tone, cultural associations, and safer wording.

### Use Case 2: Visual Concept Review

User describes images, actors, colors, gestures, food, clothing, music, and symbols. Review visual risks and suggest safer design changes.

### Use Case 3: Cross-Border E-Commerce Listing

User provides product page copy for Amazon, TikTok Shop, Shopee, Lazada, Shopify, or independent sites. Review claims, localization, images, and audience expectations.

### Use Case 4: Classroom Demonstration

User asks for a teaching example. Produce a before/after comparison showing how cultural risks are identified and improved.

## Limitations

- This skill cannot guarantee an ad will be accepted by all audiences.
- Cultural meaning changes over time and varies across regions, age groups, religions, subcultures, and platforms.
- Local review is necessary for important launches.
- Regulated categories require professional compliance review.
