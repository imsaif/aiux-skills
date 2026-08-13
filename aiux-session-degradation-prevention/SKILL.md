---
name: aiux-session-degradation-prevention
description: "Use when long conversations erode safety or quality: multi-hour chats, 'the AI gets too agreeable over time', boundary drift, session limits and refreshed checks. Session Degradation Prevention keeps late-session behavior as safe as the first message."
---

# Session Degradation Prevention

Why it matters: AI safety weakens during extended conversations - the system becomes more agreeable and less cautious. ChatGPT maintained harmful conversations for 4+ hours with degrading boundaries.

## The moves

1. Strengthen safety checks as session length increases (don't weaken)
2. Show visible timer: elapsed + remaining time in header
3. Progressive warnings: green → yellow → red visual progression
4. Force breaks non-negotiable for sensitive topics (not suggestions)
5. Save conversation context so users can resume safely

Reference: https://aiuxdesign.guide/patterns/session-degradation-prevention

When this applies, make the smallest change that genuinely realises the pattern. Do not add UI the product does not need, and say what you changed and why.

---

Generated from [aiuxdesign.guide](https://aiuxdesign.guide/?utm_source=github&utm_medium=skills-repo&utm_campaign=aiux-skills), a library of 38 AI UX patterns from shipped products. Full pattern with examples and demos: [https://aiuxdesign.guide/patterns/session-degradation-prevention](https://aiuxdesign.guide/patterns/session-degradation-prevention?utm_source=github&utm_medium=skills-repo&utm_campaign=aiux-skills). Not sure which patterns your product needs? [Run the free audit](https://aiuxdesign.guide/audit?utm_source=github&utm_medium=skills-repo&utm_campaign=aiux-skills).
