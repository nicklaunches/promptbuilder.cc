# 6 Quick Prompts Every SaaS Founder Should Use

These are copy-pasteable prompt templates. Each item shows the **original prompt (idea)** you'd type into PromptBuilder's Generate flow and the **optimized prompt** to run in ChatGPT/Claude/Gemini.

---

## ["Craft a High-Converting Homepage Hero Section"](https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates#craft-a-high-converting-homepage-hero-section)

**original prompt (idea)**
```text
Create 3 headline options, a subheadline, bullet points, and a call-to-action for a SaaS homepage that solves [customer pain point] for [ideal customer profile]. The tone should be confident and clear.
```

**optimized prompt**
```text
You are a conversion copywriter tasked with creating a high-converting homepage hero section for a SaaS product.

Task: Generate 3 headline options, a compelling subheadline, benefit-driven bullet points, and a strong call-to-action.

Inputs:
- Customer Pain Point: {{pain_point}}
- Ideal Customer Profile: {{customer_profile}}
- Key Product Benefits: {{benefits}}
- Tone: {{tone}} (e.g., confident, clear, professional)

Output Format:
- 3 Headline Options (each 6-10 words, benefit-focused)
- Subheadline (15-20 words, elaborates on core benefit)
- 3-5 Bullet Points (each highlighting a key feature/benefit)
- Primary CTA Button Text (2-4 words)
- Secondary CTA (optional alternative action)

Constraints:
- Headlines must immediately communicate value
- Avoid jargon; use clear, accessible language
- Focus on outcomes, not just features
- CTA should be action-oriented and specific

Quality Checklist:
- Do headlines pass the "5-second test"?
- Does copy address the customer's main pain point?
- Are benefits clear and compelling?
- Is the CTA specific and low-friction?

Fallback Behavior: If inputs are missing, ask:
1) What is the main customer pain point?
2) Who is your ideal customer?
3) What are your top 3 product benefits?
```

---

## ["Announce a New Feature with a Product Update Email"](https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates#announce-a-new-feature-with-a-product-update-email)

**original prompt (idea)**
```text
Write a product update email for our new feature, [feature name]. The email should include sections explaining why this feature matters to the user, a simple guide on how to use it, a link to the documentation, and a clear call-to-action.
```

**optimized prompt**
```text
You are a product marketing manager crafting a product update email to announce a new feature to existing users.

Task: Write a complete email that explains the feature's value, provides usage guidance, and encourages adoption.

Inputs:
- Feature Name: {{feature_name}}
- User Benefit: {{user_benefit}} (what problem does it solve?)
- How to Use: {{usage_steps}} (2-4 key steps)
- Documentation Link: {{docs_link}}
- Target Audience: {{user_segment}} (all users, pro tier, etc.)

Output Format:
- Subject Line (3 options, curiosity-driven, <50 chars)
- Preview Text (<90 chars)
- Email Body:
  - Opening: Hook with the benefit
  - "Why This Matters" section
  - "How to Use It" section (numbered steps)
  - Visual/Screenshot placeholder note
  - Link to documentation
  - Call-to-action button
  - Closing with support contact

Constraints:
- Keep total length under 250 words
- Use benefit-first language
- Include specific, actionable steps
- Maintain friendly, helpful tone

Quality Checklist:
- Does subject line spark curiosity without being clickbait?
- Is the user benefit clear in first paragraph?
- Are instructions simple enough for any user skill level?
- Is there a clear next action?

Fallback Behavior: If inputs missing, ask for {{feature_name}} and {{user_benefit}}.
```

---

## ["Design an Effective User Onboarding Email Sequence"](https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates#design-an-effective-user-onboarding-email-sequence)

**original prompt (idea)**
```text
Create a 3-part onboarding email sequence (Day 1, 3, and 7) for a new [user persona]. The primary goal is to drive activation for our key action: [aha! action]. The tone should be friendly, concise, and use checklists to guide the user.
```

**optimized prompt**
```text
You are an onboarding specialist designing a 3-email sequence to guide new users to their "aha!" moment.

Task: Create a complete 3-email onboarding sequence with clear progression and activation goals.

Inputs:
- User Persona: {{user_persona}}
- Aha! Moment/Key Action: {{key_action}}
- Product Name: {{product_name}}
- Main Value Proposition: {{value_prop}}
- Tone: {{tone}} (e.g., friendly, professional, encouraging)

Output Format:
For each email (Day 1, Day 3, Day 7):
- Subject Line (2 options)
- Preview Text
- Email Body:
  - Personalized greeting
  - Context-setting intro
  - Primary content (checklist, tip, or feature spotlight)
  - Clear CTA button
  - P.S. with support/help offer
- Success Metric to Track

Email 1 (Day 0): Welcome + First Critical Step
Email 2 (Day 3): Feature Introduction + Use Case
Email 3 (Day 7): Encouragement + Deeper Engagement

Constraints:
- Each email under 150 words
- One primary CTA per email
- Progressive disclosure (don't overwhelm)
- Checklist format where applicable

Quality Checklist:
- Does Day 1 get users to complete one action?
- Does sequence build momentum toward activation?
- Are emails varied in content but consistent in voice?
- Is there a clear path to value?

Fallback Behavior: Ask for {{user_persona}} and {{key_action}}.
```

---

## ["Outline a Compelling Customer Case Study"](https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates#outline-a-compelling-customer-case-study)

**original prompt (idea)**
```text
Develop a case study outline based on the success of [customer name], who achieved [specific metric result]. The outline should include a powerful hook, a clear problem statement, the solution your SaaS provided, measurable outcomes, and ideas for quotable lines.
```

**optimized prompt**
```text
You are a content marketer creating a customer success case study to build trust with prospects.

Task: Develop a complete case study outline with narrative structure, data points, and interview question suggestions.

Inputs:
- Customer Name/Company: {{customer_name}}
- Industry: {{industry}}
- Problem They Faced: {{problem}}
- Solution Provided: {{solution}}
- Measurable Results: {{results}} (e.g., "increased conversion by 45%")
- Timeline: {{timeline}}

Output Format:
- SEO-Friendly Title (3 options)
- Executive Summary (2-3 sentences)
- Main Sections:
  1. Company Background (50 words)
  2. The Challenge (100 words)
     - Initial situation
     - Pain points
     - What they tried before
  3. The Solution (150 words)
     - Why they chose your product
     - Implementation process
     - Key features used
  4. The Results (100 words)
     - Quantitative metrics
     - Qualitative benefits
     - ROI/Impact
  5. Looking Forward (50 words)
- Pull Quote Ideas (3-5 powerful statements)
- Interview Questions to Ask Customer (10 questions)
- Visual Suggestions (graphs, screenshots)

Constraints:
- Lead with the most impressive metric
- Use specific numbers and percentages
- Include both data and emotional story
- Keep total case study under 800 words

Quality Checklist:
- Does the hook grab attention with specific results?
- Is the problem relatable to your target audience?
- Are results credible and well-documented?
- Do quotes sound authentic?

Fallback Behavior: Ask for {{customer_name}}, {{results}}, and {{problem}}.
```

---

## ["Create a 'Before and After' LinkedIn Carousel"](https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates#create-a-before-and-after-linkedin-carousel)

**original prompt (idea)**
```text
Generate a 7-slide LinkedIn carousel post with the theme "Before/After with [feature name]." Each slide should have a title and short text. Include ideas for simple visuals and a final slide with a call-to-action to start a free trial.
```

**optimized prompt**
```text
You are a social media content creator crafting an engaging LinkedIn carousel that demonstrates product value through before/after storytelling.

Task: Create a complete 7-slide carousel script with visual suggestions and engagement hooks.

Inputs:
- Feature/Product Name: {{feature_name}}
- Target Audience Pain: {{pain_point}}
- Key Transformation: {{transformation}}
- Brand Voice: {{voice}} (e.g., professional, conversational, bold)
- CTA: {{cta}} (e.g., "Start Free Trial", "Book Demo")

Output Format:
For each slide (1-7):
- Slide Number & Purpose
- Title/Headline (5-8 words, bold)
- Body Text (15-25 words)
- Visual Suggestion (simple description)
- Design Notes (color, layout hints)

Slide Structure:
- Slide 1: Hook (state the problem dramatically)
- Slide 2: "Before" - Pain Point #1
- Slide 3: "Before" - Pain Point #2
- Slide 4: The Turning Point (introduce your solution)
- Slide 5: "After" - Benefit #1 (with metric if possible)
- Slide 6: "After" - Benefit #2 (with metric if possible)
- Slide 7: CTA with clear next step

Additional Elements:
- Carousel Cover Image concept
- Opening Post Caption (100-150 words)
- Hashtag Strategy (5-8 hashtags)
- Comment Prompt Question

Constraints:
- Use contrasting language (struggle vs. success)
- Include at least one specific metric or time saved
- Keep slides scannable (large text, minimal words)
- Make CTA specific and low-friction

Quality Checklist:
- Does Slide 1 stop the scroll?
- Is there a clear narrative arc?
- Are benefits concrete and believable?
- Does CTA have urgency or incentive?

Fallback Behavior: Ask for {{feature_name}} and {{pain_point}}.
```

---

## ["Build a Persuasive Competitor Comparison Page"](https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates#build-a-persuasive-competitor-comparison-page)

**original prompt (idea)**
```text
Create content for a webpage comparing our product against [competitor name]. Include a feature comparison table, notes on pricing differences, a section on when to choose each product, and an FAQ section addressing common questions.
```

**optimized prompt**
```text
You are a product marketer creating an honest, helpful comparison page that builds trust while highlighting your competitive advantages.

Task: Develop complete content for a "[Your Product] vs [Competitor]" landing page.

Inputs:
- Your Product Name: {{your_product}}
- Competitor Name: {{competitor_name}}
- Your Key Differentiators: {{differentiators}}
- Target Buyer Persona: {{buyer_persona}}
- Pricing Structure: {{pricing}}
- Competitor's Strengths (be honest): {{competitor_strengths}}

Output Format:
1. Page Title & Meta Description
2. Hero Section:
   - Headline
   - Subheadline
   - Summary paragraph (100 words)
3. Feature Comparison Table:
   - 10-15 features
   - 3 columns: Feature | Your Product | Competitor
   - Use checkmarks, X's, and brief notes
4. Detailed Comparison Sections:
   - Pricing Comparison (when you're better value)
   - Use Case Fit (when each is appropriate)
   - Support & Documentation
   - Integration Ecosystem
5. "When to Choose [Competitor]" Section (build trust)
6. "Why Teams Switch to [Your Product]" (testimonials)
7. FAQ Section (8-10 questions):
   - Migration questions
   - Feature parity questions
   - Pricing questions
8. Final CTA Section

Constraints:
- Be factually accurate and fair
- Focus on differentiation, not disparagement
- Use specific examples and use cases
- Acknowledge competitor's strengths where genuine
- Lead with value, not just features

Quality Checklist:
- Does comparison feel honest and balanced?
- Are your unique strengths clear?
- Is there social proof (testimonials, logos)?
- Does FAQ address real objections?
- Is there a clear migration path for switchers?

Fallback Behavior: Ask for {{your_product}}, {{competitor_name}}, and {{differentiators}}.
```

---

**Original post:** https://promptbuilder.cc/blog/6-quick-prompts-saas-founders?utm_source=github&utm_medium=repo&utm_campaign=templates
