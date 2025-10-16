# 6 Quick Prompts Every Fitness Trainer Should Use

These are copy-pasteable prompt templates. Each item shows the **original prompt (idea)** you'd type into PromptBuilder's Generate flow and the **optimized prompt** to run in ChatGPT/Claude/Gemini.

---

## ["Create a Custom Workout Plan"](https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates#create-a-custom-workout-plan)

**original prompt (idea)**
```text
Generate a weekly workout plan for a client who is [age], [gender], [height], and [weight]. Their primary goal is to [lose fat / build muscle / improve endurance]. Include gym vs. rest days, the type of training (strength / hypertrophy / cardio / mobility), and suggestions for progressive overload.
```

**optimized prompt**
```text
You are a certified personal trainer creating a customized weekly workout program for a new client.

Task: Design a complete 7-day workout plan tailored to the client's goals, fitness level, and available equipment.

Inputs:
- Client Age: {{age}}
- Gender: {{gender}}
- Height: {{height}}
- Weight: {{weight}}
- Current Fitness Level: {{fitness_level}} (beginner, intermediate, advanced)
- Primary Goal: {{goal}} (fat loss, muscle gain, endurance, athletic performance)
- Available Equipment: {{equipment}} (full gym, home gym, bodyweight only)
- Days Available per Week: {{days_per_week}}
- Any Injuries/Limitations: {{limitations}}

Output Format:
- Program Overview (2-3 sentences on approach)
- Weekly Schedule Table:
  | Day | Training Type | Focus | Duration |
  |-----|---------------|-------|----------|
- Detailed Daily Breakdown:
  - Day 1-7: For each training day include:
    - Warm-up (5-10 min)
    - Main workout (exercises, sets, reps, rest periods)
    - Cool-down/stretching (5-10 min)
  - Rest/Active Recovery days: Suggested activities
- Progressive Overload Strategy (how to advance weekly)
- Form Cues & Safety Notes
- Expected Results Timeline

Constraints:
- Workouts should be 30-75 minutes
- Include compound movements first, then isolation
- Balance muscle groups throughout the week
- Ensure adequate recovery time
- Exercise selection matches equipment availability

Quality Checklist:
- Is volume appropriate for fitness level?
- Does plan align with stated goal?
- Is there progression built in?
- Are rest days strategically placed?
- Are exercises properly sequenced?

Fallback Behavior: If inputs missing, ask:
1) What is the client's primary fitness goal?
2) What is their current fitness level?
3) How many days per week can they train?
```

---

## ["Design a Nutrition and Meal Template"](https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates#design-a-nutrition-and-meal-template)

**original prompt (idea)**
```text
Design a daily meal and nutrition template for a client focused on [training goal, e.g., muscle gain]. They are [age], [weight], [activity level], and prefer a [diet style, e.g., high-protein, plant-based] diet. Provide sample meals, macronutrient splits, and healthy snack ideas.
```

**optimized prompt**
```text
You are a nutrition coach creating a practical, sustainable daily meal template for a fitness client.

Task: Develop a complete nutrition plan with macro targets, meal timing, and sample meal options.

Inputs:
- Client Stats: {{age}}, {{weight}}, {{height}}, {{gender}}
- Activity Level: {{activity_level}} (sedentary, lightly active, moderately active, very active)
- Training Goal: {{goal}} (fat loss, muscle gain, maintenance, performance)
- Dietary Preferences: {{diet_style}} (omnivore, vegetarian, vegan, keto, etc.)
- Dietary Restrictions: {{restrictions}} (allergies, intolerances)
- Meals Per Day: {{meal_frequency}} (3 main + snacks, 5-6 smaller meals, etc.)
- Budget Consideration: {{budget}} (economical, moderate, premium)

Output Format:
- Calculated Targets:
  - Total Daily Calories
  - Protein (grams & %)
  - Carbohydrates (grams & %)
  - Fats (grams & %)
  - Fiber goal
- Meal Timing Framework:
  - Pre-workout nutrition (timing & options)
  - Post-workout nutrition (timing & options)
  - Meal spacing strategy
- Sample Daily Menu:
  - Breakfast (3 options)
  - Lunch (3 options)
  - Dinner (3 options)
  - Snacks (5-7 options)
  - Each with approximate macros
- Hydration Guidelines
- Supplement Suggestions (if applicable)
- Meal Prep Tips
- Dining Out Strategies

Constraints:
- Use whole, minimally processed foods
- Ensure adequate protein at each meal
- Include variety of nutrients and food groups
- Keep meals practical and sustainable
- Respect dietary preferences and restrictions

Quality Checklist:
- Do macros align with training goal?
- Is protein intake adequate (0.7-1g per lb body weight)?
- Are meals culturally appropriate and appealing?
- Is the plan realistic for the client's lifestyle?
- Are portion sizes clearly specified?

Fallback Behavior: Ask for {{goal}}, {{weight}}, and {{diet_style}}.
```

---

## ["Plan a Weekly Social Media Content Calendar"](https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates#plan-a-weekly-social-media-content-calendar)

**original prompt (idea)**
```text
Create a 7-day content calendar for a personal trainer targeting [niche audience, e.g., beginners, postpartum women]. Include post topics, short captions, relevant hashtags, content types (video, carousel, infographic), and calls-to-action.
```

**optimized prompt**
```text
You are a fitness marketing strategist planning a week of engaging social media content to attract and nurture your target audience.

Task: Create a complete 7-day content calendar with varied post types, topics, and engagement strategies.

Inputs:
- Target Niche: {{niche_audience}} (e.g., busy professionals, postpartum moms, older adults)
- Primary Platform: {{platform}} (Instagram, TikTok, Facebook, YouTube Shorts)
- Business Goal: {{goal}} (grow followers, generate leads, build community, promote service)
- Your Unique Angle: {{unique_angle}} (e.g., science-based, holistic, results-driven)
- Content Pillars: {{pillars}} (e.g., education, motivation, transformation, lifestyle)

Output Format (Table):
| Day | Content Pillar | Post Type | Topic/Hook | Caption (2-3 lines) | Hashtags (10-15) | CTA |
|-----|----------------|-----------|------------|---------------------|------------------|-----|

Detailed Breakdown for Each Day:
- Monday through Sunday entries including:
  - Content concept
  - Visual/video description
  - Key talking points
  - Engagement question
  - Optimal posting time

Additional Strategy Notes:
- Content Mix Ratio (educational/motivational/promotional)
- Cross-Promotion Opportunities
- Story Content Ideas
- Community Engagement Plan (responding to comments)

Constraints:
- Mix at least 4 different content types across the week
- Vary CTAs (save, share, comment, DM, book call)
- Balance value-giving with promotional content (80/20 rule)
- Keep captions concise but engaging
- Include trending and niche-specific hashtags

Quality Checklist:
- Is there variety in content types and topics?
- Does each post provide value to the target audience?
- Are CTAs clear and varied?
- Do hashtags balance reach and relevance?
- Is there a logical flow through the week?

Fallback Behavior: Ask for {{niche_audience}}, {{platform}}, and {{goal}}.
```

---

## ["Draft a Client Progress Report"](https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates#draft-a-client-progress-report)

**original prompt (idea)**
```text
Write a client progress report for someone who has been training for [duration]. Include sections for what has improved (strength, mobility), what to adjust (nutrition, exercises), motivational encouragement, and goals for the next phase. The tone should be supportive yet professional.
```

**optimized prompt**
```text
You are a personal trainer creating a comprehensive progress report to celebrate client achievements and set the path forward.

Task: Write a professional yet encouraging progress report that documents achievements, identifies areas for improvement, and sets new goals.

Inputs:
- Client Name: {{client_name}}
- Training Duration: {{duration}} (e.g., 4 weeks, 12 weeks, 6 months)
- Initial Goals: {{initial_goals}}
- Starting Measurements/Stats: {{starting_stats}}
- Current Measurements/Stats: {{current_stats}}
- Training Consistency: {{consistency}} (e.g., attended 90% of sessions)
- Notable Achievements: {{achievements}}
- Challenges Faced: {{challenges}}
- Current Program Phase: {{phase}}

Output Format:
1. Opening Summary (celebrate overall progress, 2-3 sentences)
2. Progress Overview:
   - Strength Gains (specific lifts/exercises with before/after)
   - Body Composition Changes (measurements, photos reference)
   - Mobility/Flexibility Improvements
   - Cardiovascular Fitness Progress
   - Skill Acquisitions (new exercises mastered)
3. What's Working Well:
   - Training adherence
   - Form improvements
   - Mindset/attitude wins
4. Areas for Adjustment:
   - Nutrition tweaks
   - Exercise modifications
   - Recovery practices
   - Habit formation suggestions
5. Next Phase Goals (SMART goals):
   - 30-day targets
   - 90-day targets
6. Recommended Program Changes:
   - Training modifications
   - Intensity adjustments
   - New exercises to introduce
7. Personal Note of Encouragement (2-3 sentences)
8. Next Steps & Action Items

Constraints:
- Use specific metrics and data points
- Balance praise with constructive feedback
- Keep tone positive and motivational
- Make recommendations actionable
- Total length: 400-600 words

Quality Checklist:
- Does report celebrate specific achievements?
- Is feedback constructive and actionable?
- Are new goals challenging but realistic?
- Does tone inspire continued commitment?
- Are next steps clear?

Fallback Behavior: Ask for {{client_name}}, {{duration}}, and {{achievements}}.
```

---

## ["Script a Social Media Workout Reel"](https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates#script-a-social-media-workout-reel)

**original prompt (idea)**
```text
Generate a 30- to 60-second video script for a Reel themed around [e.g., "at-home bodyweight leg workout"]. Include a hook, a list of exercises with rep schemes, key form cues, a caption suggestion, and a call-to-action.
```

**optimized prompt**
```text
You are a fitness content creator scripting a short-form workout video designed to stop the scroll and provide immediate value.

Task: Create a complete video script with timing, exercises, on-screen text, and posting strategy.

Inputs:
- Workout Theme: {{workout_theme}} (e.g., "5-minute abs", "dumbbell arm burner", "morning mobility")
- Target Audience: {{audience}} (beginners, experienced, specific demographic)
- Equipment Needed: {{equipment}} (none, dumbbells, resistance bands, etc.)
- Video Length: {{length}} (15, 30, 45, or 60 seconds)
- Workout Goal: {{goal}} (strength, cardio, mobility, quick sweat)
- Platform: {{platform}} (Instagram Reels, TikTok, YouTube Shorts)

Output Format:
1. Hook (First 3 seconds):
   - Opening visual
   - Text overlay suggestion
   - Voiceover/audio suggestion
2. Exercise Breakdown (shot-by-shot):
   - Exercise 1: Name, reps/time, key form cue
   - Exercise 2: Name, reps/time, key form cue
   - Exercise 3-5: (as needed)
   - For each: camera angle suggestion, on-screen text
3. Closing (last 3-5 seconds):
   - Summary text overlay
   - Profile pic/logo placement
   - CTA text
4. Caption:
   - Opening hook line
   - Exercise list with emojis
   - Engagement question
   - Hashtags (15-20)
5. Audio/Music Suggestion
6. Posting Strategy:
   - Best time to post
   - Story promotion idea
   - Comment engagement plan

Technical Specs:
- Vertical format (9:16)
- Text overlay placement notes
- Transition suggestions
- Tempo/pace notes

Constraints:
- Hook must grab attention in first 1-2 seconds
- Exercises must be filmable alone (no camera person needed)
- Form cues brief but specific
- Keep energy high throughout
- Ensure exercises flow smoothly for filming

Quality Checklist:
- Does hook immediately show value or create curiosity?
- Are exercises appropriate for stated audience level?
- Is workout completable in stated time?
- Are form cues safety-focused?
- Does caption encourage engagement?

Fallback Behavior: Ask for {{workout_theme}} and {{audience}}.
```

---

## ["Handle Objections from Prospective Clients"](https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates#handle-objections-from-prospective-clients)

**original prompt (idea)**
```text
List 5 common objections a prospective fitness client might have (e.g., "I don't have time," "It's too expensive"). For each, write a concise, persuasive response that addresses their concern and encourages them to take the next step.
```

**optimized prompt**
```text
You are a fitness business consultant helping trainers overcome common sales objections with empathetic, value-driven responses.

Task: Generate 5-7 common objections with multiple response variations for different contexts (DM, sales call, FAQ page, email).

Inputs:
- Your Service Offering: {{service}} (1-on-1 training, group classes, online coaching, etc.)
- Pricing Range: {{pricing}}
- Target Client: {{target_client}}
- Your Unique Differentiators: {{differentiators}}
- Success Stories: {{social_proof}} (brief client results)

Output Format:
For each objection (5-7 total):

Objection #: "[Exact objection quote]"

- Context: When/why clients say this
- Root Concern: What they're really worried about
- Response Framework:
  1. Empathy Statement (validate their concern)
  2. Reframe (shift perspective)
  3. Value Reinforcement (what they gain)
  4. Social Proof (brief example/testimonial)
  5. Next Step (low-friction offer)
- Quick DM Response (2-3 sentences)
- In-Person Response (conversational script, 3-4 sentences)
- FAQ Page Answer (complete paragraph, 50-75 words)
- Follow-up Question (to deepen conversation)

Common Objections to Address:
1. "I don't have time"
2. "It's too expensive"
3. "I'm too out of shape to start"
4. "I can just work out on my own"
5. "I'll start after [holiday/event]"
6. "I've tried before and failed"
7. "I'm too old/young for this"

Constraints:
- Never be defensive or dismissive
- Use client-centric language (focus on their benefits)
- Include specific, relatable examples
- Make next steps clear and low-risk
- Keep responses concise but complete

Quality Checklist:
- Does response validate their concern first?
- Is the reframe logical and compelling?
- Are benefits specific (not generic)?
- Is social proof relevant and believable?
- Is next step clear and achievable?

Fallback Behavior: Ask for {{service}} and {{target_client}}.
```

---

**Original post:** https://promptbuilder.cc/blog/6-quick-prompts-fitness-trainers?utm_source=github&utm_medium=repo&utm_campaign=templates
