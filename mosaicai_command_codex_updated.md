---
version: 2025.06.15-a
last_updated: 2025-06-15
verified: true
---

# MosaicAI Command Codex (with Plain English Equivalents)


##  Intelligence

### `persona.generate(industry, intent)`
**Command:**
```python
persona.generate(industry="fintech", intent="B2B SaaS for CFOs")
```
**Plain Language:**
> Create a detailed persona for a fintech company offering a B2B SaaS tool for CFOs.

### `market.scan(category, region)`
**Command:**
```python
market.scan(category="luxury skincare", region="APAC")
```
**Plain Language:**
> Research luxury skincare market trends in APAC.

### `audience.profile(segment, need_state)`
**Command:**
```python
audience.profile(segment="Millennials", need_state="eco-conscious buying")
```
**Plain Language:**
> Profile eco-conscious Millennial buyers.

### `competitive.landscape(brand_list)`
**Command:**
```python
competitive.landscape(brand_list=["Apple", "Samsung", "Google"])
```
**Plain Language:**
> Compare branding and tone of Apple, Samsung, and Google.

### `messaging.framework.create(input)`
**Command:**
```python
messaging.framework.create(input="mental wellness brand for Gen Z")
```
**Plain Language:**
> Create a messaging framework for a Gen Z mental wellness brand.

### `insight.codify(data_inputs)`
**Command:**
```python
insight.codify(data_inputs="survey results, interviews, reviews")
```
**Plain Language:**
> Turn survey, interview, and review data into key insights.

## 🎨 Creative

### `name.generate(inputs)`

**Command:**
```python
name.generate(inputs={
  "industry": "wellness",
  "audience": "Millennials",
  "tone": "minimalist, calming",
  "style": "evocative",
  "archetype": "Caregiver"
})
```

**Plain Language:**
> Generate name options for a brand, product, or service based on desired tone, style, and archetype.

**Inputs:**
- `industry` (e.g., fintech, skincare)
- `audience` (e.g., Gen Z founders, solo parents)
- `tone` (e.g., bold, elegant, playful)
- `style` (e.g., descriptive, abstract, evocative)
- `archetype` (optional: to align emotional resonance)

**⚠ Safeguard:**  
> If the project already has a confirmed name, MosaicAI must not suggest new names unless explicitly asked to **rename**, **extend**, or **explore variants**.



### `narrative.build(brand_inputs)`
**Command:**
```python
narrative.build(brand_inputs="daily AI coaching for productivity")
```
**Plain Language:**
> Build a brand story for a daily productivity AI coach.

### `tagline.variants(theme)`
**Command:**
```python
tagline.variants(theme="unstoppable mornings")
```
**Plain Language:**
> Generate tagline options around the theme 'unstoppable mornings'.

### `visual.style.guide(inputs)`
**Command:**
```python
visual.style.guide(inputs="modern, elegant, calm")
```
**Plain Language:**
> Develop a visual identity with a modern, elegant, calm vibe.

### `moodboard.prompt.dalle(keywords)`
**Command:**
```python
moodboard.prompt.dalle(keywords="sunrise, optimism, clarity")
```
**Plain Language:**
> Create a DALL·E moodboard prompt for sunrise, optimism, and clarity.

### `tone.calibrate(mode)`
**Command:**
```python
tone.calibrate(mode="luxury")
```
**Plain Language:**
> Calibrate the tone to sound high-end and premium.

### `concept.brainstorm(theme, strategy)`
**Command:**
```python
concept.brainstorm(theme="wellbeing", strategy="partnership with fitness creators")
```
**Plain Language:**
> Brainstorm campaign concepts focused on wellbeing and fitness influencers.

## 🚀 Activation

### `campaign.matrix.build(goal, channels)`
**Command:**
```python
campaign.matrix.build(goal="lead gen", channels=["email", "instagram"])
```
**Plain Language:**
> Create a campaign matrix for email and Instagram to drive lead generation.

### `asset.map.generate(touchpoints)`
**Command:**
```python
asset.map.generate(touchpoints=["homepage", "LinkedIn", "newsletter"])
```
**Plain Language:**
> Plan required content assets for homepage, LinkedIn, and newsletter.

### `channel.strategy.plan(audience, budget)`
**Command:**
```python
channel.strategy.plan(audience="Gen Z", budget="$10,000")
```
**Plain Language:**
> Recommend best digital channels for Gen Z with a $10K budget.

### `launch.timeline.build(phase_inputs)`
**Command:**
```python
launch.timeline.build(phase_inputs="3-phase awareness to conversion")
```
**Plain Language:**
> Build a 3-phase rollout plan from awareness to conversion.

## 🔧 Optimisation

### `copy.feedback.analyse(input)`
**Command:**
```python
copy.feedback.analyse(input="Level up your workflow. Instantly.")
```
**Plain Language:**
> Review and improve the clarity and CTA strength of ad copy.

### `brand.audit.run(scope)`
**Command:**
```python
brand.audit.run(scope="narrative")
```
**Plain Language:**
> Audit a brand’s narrative for tone and consistency.

### `performance.review(metrics)`
**Command:**
```python
performance.review(metrics={"CTR": 1.2, "open_rate": 22})
```
**Plain Language:**
> Review campaign performance and suggest improvements.

### `variant.write(base_input)`
**Command:**
```python
variant.write(base_input="Unlock focus with mindful alerts")
```
**Plain Language:**
> Suggest alternative versions of the copy 'Unlock focus with mindful alerts'.

## 📈 Insight

### `loopback.memo.create(campaign_data)`
**Command:**
```python
loopback.memo.create(campaign_data="3-part nurture email series")
```
**Plain Language:**
> Summarise campaign learnings from a 3-part nurture email series.

### `retrospective.summary(phase)`
**Command:**
```python
retrospective.summary(phase="activation")
```
**Plain Language:**
> Summarise what worked and didn’t during the activation phase.

### `learning.extract(data)`
**Command:**
```python
learning.extract(data="user interviews and A/B tests")
```
**Plain Language:**
> Pull insights from user interviews and A/B testing results.

##  Cross-Cutting


### `style.configure(locale, spelling, punctuation_rules, date_format)`

**Command:**
```python
style.configure(locale="en-GB", spelling="British", punctuation_rules="no em dashes", date_format="DD MMM YYYY")
```

**Plain Language:**
> Configure MosaicAI to follow British English spelling, short date format, and avoid em dashes.

Use this to establish baseline stylistic rules for all outputs.


### `proposal.generate(scope)`
**Command:**
```python
proposal.generate(scope="visual identity and launch")
```
**Plain Language:**
> Generate a proposal for a visual identity and launch scope.

### `brief.write(type)`
**Command:**
```python
brief.write(type="creative")
```
**Plain Language:**
> Write a creative brief.

### `tone.switch(target_audience)`
**Command:**
```python
tone.switch(target_audience="investors")
```
**Plain Language:**
> Change messaging tone to suit investor audience.

### `diagnostics.run(scope)`
**Command:**
```python
diagnostics.run(scope="site", url="https://eltham-exchange.webflow.io/")
```
**Plain Language:**
> Run a brand/UX/messaging diagnostic for the Eltham Exchange website.

##  Meta Commands

### `brand.build.full(inputs)`
**Command:**
```python
brand.build.full(inputs={
  "brand_name": "Aeon Health",
  "industry": "Healthtech",
  "target_audience": "Busy urban professionals",
  "archetype": "Caregiver"
})
```

**Plain Language:**
> Generate a full end-to-end brand system based on provided inputs.

**Internal Workflow (Loop-Aligned):**
- Intelligence → `persona.generate(...)`, `market.scan(...)`, `insight.codify(...)`
- Creative → `narrative.build(...)`, `tone.calibrate(...)`, `visual.style.guide(...)`
- Activation → `asset.map.generate(...)`, `launch.timeline.build(...)`
- Optimisation → `copy.feedback.analyse(...)`, `brand.audit.run(...)`
- Insight → `loopback.memo.create(...)`, `learning.extract(...)`

---

### `brand.audit.full(scope)`
**Command:**
```python
brand.audit.full(scope="system")
```

**Plain Language:**
> Perform a full audit of brand assets and structure.  
**Scope options:** `"visual"`, `"verbal"`, `"system"`

**Includes:** Narrative consistency, messaging, visual clarity, and asset usability.

---

### `site.audit.full(url)`
**Command:**
```python
site.audit.full(url="https://example.com")
```

**Plain Language:**
> Run a complete website audit for UX, messaging, structure, CTA flow.

**Includes:** Brand voice alignment, hierarchy checks, conversion performance, mobile experience.

---

### `campaign.audit.full(inputs)`
**Command:**
```python
campaign.audit.full(inputs="Q2 email nurture sequence")
```

**Plain Language:**
> Analyse strategy, creative, and performance of a campaign.

**Uses:** `insight.codify(...)`, `copy.feedback.analyse(...)`, `performance.review(...)`

---


---

### `campaign.strategy.canvas()`

**Command:**
```python
campaign.strategy.canvas()
```

**Plain Language:**
> Launch the full Strategy Canvas workflow to gather brand, offer, audience, and channel inputs prior to campaign creation.

**Used For:**  
Campaign planning during the **Intelligence** and **Creative** phases.

**Includes:**
- Brand Readiness check (with fallback brand identity intake)
- Business & Differentiators
- Offer & Goals
- Audience & Competitors
- Channels & Success Metrics

**User Commands:**
- `restart` → Reset the Strategy Canvas
- `show my canvas` → Summarise collected inputs
- `edit section [#]` → Revise specific section
- `generate campaign` → Trigger campaign asset generation

**Safeguard:**  
Do **not** proceed with content generation until the Strategy Canvas is complete and confirmed by the user.

### `loop.init(project_type)`
**Command:**
```python
loop.init(project_type="early-stage SaaS launch")
```

**Plain Language:**
> Scaffold a modular Loop-based brand project for your business type.

**Outputs:** Suggested command roadmap, recommended inputs, pacing structure.

---

### 🎯 `proposal.build.canvas`

**Trigger Syntax**: `proposal.build(canvas=True)`  
**What it Does**: Builds a structured proposal document using upstream intelligence from prior audits, briefs, or strategy work.  
**Loop Phase**: Optimisation → Assembly  
**Typical Prompts**:
- “Can you draft a proposal for this?”
- “Summarise the audit into a scoped proposal.”
- “What deliverables should we propose to the client?”
**GPT Notes**: Pulls context from prior modules (e.g. `brand.audit.canvas`, `output.prepare.canvas`) and frames deliverables, timeline, and investment using client-facing language.


---

### 🪞 `loop.reflect.canvas`

**Trigger Syntax**: `loop.reflect(canvas=True)`  
**What it Does**: Captures learnings, performance feedback, and post-campaign insights. Closes the loop and feeds findings back into the Intelligence phase.  
**Loop Phase**: Insight → Intelligence  
**Typical Prompts**:
- “What did we learn from this project?”
- “Do a post-campaign reflection.”
- “Should we evolve anything from this?”
**GPT Notes**: Optionally triggers a new `proposal.build.canvas` if sufficient insight is captured and follow-up action is needed.
