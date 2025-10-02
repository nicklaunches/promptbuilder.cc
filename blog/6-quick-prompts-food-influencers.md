# 6 Quick Prompts Every Food Influencer Should Try

These are copy-pasteable prompt templates. Each item shows the **original prompt (idea)** you’d type into PromptBuilder’s Generate flow and the **optimized prompt** to run in ChatGPT/Claude/Gemini.

---

## ["Sponsored Recipe Reel in 30 Seconds"](https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates#sponsored-recipe-reel-in-30-seconds)

**original prompt (idea)**
```text
30-sec IG Reel for sponsored [Brand] pasta sauce. Recipe: 1-pan creamy tomato gnocchi.
```

**optimized prompt**
```text
You are a social media content creator tasked with producing a 30-second Instagram Reel for a sponsored brand's pasta sauce. The recipe is for a 1-pan creamy tomato gnocchi.

Task: Create a concise and engaging script for the Reel that highlights the recipe and showcases the pasta sauce.

Inputs:
- Brand: {{Brand}}
- Tone: {{tone}} (e.g., fun, informative)
- Length: 30 seconds
- Style: {{style}} (e.g., casual, professional)

Output Format:
- Opening (5 sec): Introduce the dish and brand.
- Cooking Steps (20 sec): Briefly outline the recipe steps.
- Closing (5 sec): Call to action (e.g., "Try it today!").

Constraints:
- Use engaging language.
- Include a clear call to action.
- Avoid complex jargon; keep it accessible.

Quality Checklist:
- Is the script engaging and concise?
- Does it clearly highlight the brand and sauce?
- Is the call to action compelling?

Fallback Behavior: If any inputs are missing, ask:
1) What is the brand name?
2) What tone do you prefer?
3) What style should the video reflect?
```

---

## ["Plan a Trend-Focused Video Series"](https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates#plan-a-trend-focused-video-series)

**original prompt (idea)**
```text
Weekly Reels idea: trending summer salads for Gen Z.
```

**optimized prompt**
```text
You are a content strategist planning a short video series that rides a current food trend.

Task: Produce a 4-episode Instagram/TikTok series plan around a single trend.

Inputs:
- Trend Topic: {{trend_topic}} (e.g., "summer salads")
- Audience Persona: {{audience_persona}} (e.g., Gen Z, busy parents)
- Primary Platform: {{platform}} (Instagram Reels | TikTok | YouTube Shorts)
- Cadence: Weekly
- Tone/Style: {{tone_style}} (e.g., playful, educational)

Output Format:
- Series Overview: One-paragraph concept & why it fits the trend.
- Episodes (1–4): For each episode include:
  - Title/Hook
  - Ingredients or talking points
  - Beat-by-beat outline (30–45s)
  - On-screen text ideas
  - Caption + 5–10 hashtags
  - CTA (e.g., save, follow, comment)
- Simple production notes: props, locations, B-roll list.

Constraints:
- Keep scripts shootable on a phone.
- Hooks must be under 8 words and punchy.

Quality Checklist:
- Does each episode stand alone yet ladder into the series?
- Is the trend obvious in the first 3 seconds?
- Are CTAs varied to encourage saves/comments/follows?

Fallback Behavior: If missing inputs, ask for {{trend_topic}} and {{audience_persona}}.
```

---

## ["Pitch Email for Brand Collaborations"](https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates#pitch-email-for-brand-collaborations)

**original prompt (idea)**
```text
Pitch email to [Brand] for sponsored reels featuring air fryer recipes. Audience: health-focused parents.
```

**optimized prompt**
```text
You are a food creator emailing a brand to propose a sponsored collaboration.

Task: Draft a professional pitch email that demonstrates audience fit, concept ideas, and expected deliverables.

Inputs:
- Recipient Brand: {{brand_name}}
- Niche/Angle: {{niche_angle}} (e.g., air fryer healthy recipes)
- Audience: {{audience_desc}} (e.g., health-focused parents)
- Proposed Deliverables: {{deliverables}} (e.g., 3 Reels + 3 Stories + usage rights)
- Creator Stats: {{metrics}} (avg views, ER%, followers, demographics)
- Packages/Rates (optional): {{rates}}

Output Format:
- Subject line (3 options, <60 chars)
- Greeting
- Opening credibility + audience fit
- 3 creative concept bullets with why they work
- Deliverables + timeline
- Light CTA to discuss next steps
- Signature with links

Constraints:
- Keep to 150–200 words.
- Avoid spammy phrasing and hard selling.

Quality Checklist:
- Clear value prop for the brand?
- Measurable deliverables and timeline?
- Polite, confident tone?

Fallback Behavior: Ask for {{brand_name}}, {{metrics}}, and {{deliverables}} if missing.
```

---

## ["Food Photography Shot Checklist"](https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates#food-photography-shot-checklist)

**original prompt (idea)**
```text
Shot list for Instagram carousel featuring vegan brownies. Mood: rustic & cozy.
```

**optimized prompt**
```text
You are a food photographer planning a 6-image carousel.

Task: Generate a practical shot list with composition notes, props, and lighting tips.

Inputs:
- Dish: {{dish}} (e.g., vegan brownies)
- Mood/Style: {{mood_style}} (e.g., rustic & cozy)
- Props: {{props}} (e.g., parchment, cooling rack, linen)
- Lighting: {{lighting}} (e.g., window light, late afternoon)

Output Format:
- Shot 1: Hero (angle, framing, lens equiv., styling notes)
- Shot 2: Overhead process (key step)
- Shot 3: Texture close-up (crumb/frosting)
- Shot 4: Slice/serve moment (hands in frame)
- Shot 5: Ingredient flat-lay (ordered chaos)
- Shot 6: Lifestyle context (coffee/plates)
- Color & background tips
- Safety/cleanliness reminders

Constraints:
- Each shot note max 2 sentences.
- Home-studio friendly gear only.

Quality Checklist:
- Varied angles & focal lengths?
- Consistent mood/props?
- Clear story from prep → serve?

Fallback Behavior: Ask for {{dish}} and {{mood_style}}.
```

---

## ["Weekly Instagram Content Calendar"](https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates#weekly-instagram-content-calendar)

**original prompt (idea)**
```text
7-day Instagram content plan, theme: global breakfast recipes.
```

**optimized prompt**
```text
You are a social content planner building a one-week calendar around a unifying theme.

Task: Produce a 7-day plan with hooks, captions, and hashtags that interlock into a coherent mini-campaign.

Inputs:
- Theme: {{theme}} (e.g., global breakfast recipes)
- Goal: {{goal}} (saves, followers, link clicks, comments)
- Posting Days: {{days}} (e.g., Mon–Sun)
- Brand Voice: {{voice}} (e.g., warm, witty)
- Hashtag Strategy: {{hashtag_style}} (e.g., niche + geo + trend)

Output Format (table):
| Day | Format | Post Concept | Hook (≤8 words) | Caption (2–3 lines) | CTA | Hashtags (8–12) |
|-----|--------|--------------|------------------|----------------------|-----|------------------|

Constraints:
- Mix at least 3 formats (Reel, Carousel, Single, Story).
- Rotate CTAs (save, comment, follow, share).

Quality Checklist:
- Clear daily variety?
- Hooks match the theme and goal?
- Logical progression across the week?

Fallback Behavior: Ask for {{theme}} and {{goal}}.
```

---

## ["Quick FAQ & Objection Responses"](https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates#quick-faq--objection-responses)

**original prompt (idea)**
```text
FAQ: "I'm a beginner—can I make your 1-pan pasta?"
```

**optimized prompt**
```text
You are a helpful creator replying to DMs/comments with short, confidence-building answers.

Task: Provide three concise response options tailored for comments, Stories, and pinned replies.

Inputs:
- Question/Objection: {{question_text}}
- Tone: {{tone}} (friendly, reassuring, expert)
- Next Step/CTA: {{cta}} (e.g., "save this," "watch tutorial," link)

Output Format:
- Response A (comment-length, ≤200 chars)
- Response B (Story script, 10–12s)
- Response C (pinned reply, 1–2 sentences)

Constraints:
- No jargon. Encourage, don’t gatekeep.

Quality Checklist:
- Warm, inclusive language?
- Specific next step the follower can take?
- Works as a copy-paste reply?

Fallback Behavior: Ask for {{question_text}} and {{cta}}.
```

---

**Original post:** https://promptbuilder.cc/blog/6-quick-prompts-food-influencers?utm_source=github&utm_medium=repo&utm_campaign=templates
