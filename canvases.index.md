## 01. Intelligence Canvases


=== brand.audit.canvas ===
Brand Audit Canvas

 Purpose

To evaluate a brand's current state, strengths, weaknesses, and market positioning. This audit adapts dynamically based on project scope—whether clarifying, repositioning, or launching a brand—and integrates with Mosaic for insight generation.

---

 Method

1. Define Audit Scope

    Clarify intent: Launch readiness? Repositioning? Refresh?
    Select dimensions based on relevance to project (e.g., skip visual review if it's a tone-only engagement)

2. Audit Dimensions

    Brand Positioning – Unique value, competitive clarity
    Messaging Consistency – Internal vs external alignment
    Visual Identity – Logo, typography, palette
    Digital Presence – UX/UI, accessibility, social behavior
    Audience Resonance – Tone fit, cultural signals

3. Contextual Benchmarking

    Use Mosaic to:

      Surface competitor comparisons (via `competitor.audit`)
      Highlight brand gaps using audience tone, sentiment, or performance signals
    Pull optional frameworks from `reference.frameworks.canvas.md`, such as:

      SWOT for structural audit
      Brand Keys or Core/Periphery Model for equity mapping

4. Scoring Logic

    Use adaptable 1–5 scoring or qualitative tags (Strong, Incomplete, Mismatch)
    Normalize scoring based on scope (e.g., only 3 dimensions if a lean audit)

5. Recommendations by Priority

    Flag quick wins, structural gaps, and strategic opportunities
    Tie recs to Loop phase triggers (e.g., initiate `proposal.build` or `tone.of.voice`)

---

 Expected Outputs

 Audit Summary

   Context-specific review of key dimensions
 Scoring Table (Flexible)

   Dynamically scoped set of metrics
 Strategic Action Plan

   Clear recommendations with Loop triggers

---

 Loop Integration

 Phase: Intelligence → Strategy
 Trigger: Use during early engagements or pre-campaign calibration

---

 Notes

 Audit scope should flex with project maturity and client needs
 Use `reference.frameworks.canvas.md` to select interpretive models
 Outputs can be structured for Mosaic ingestion or human presentation


=== competitor.audit.canvas.canvas ===
Competitor Audit Canvas

 Purpose

To evaluate competitors’ strategies, positioning, and creative output to identify strategic gaps and opportunities for differentiation. This canvas dynamically adjusts based on brand category, campaign context, and depth of scan required.

---

 Method

1. Define Audit Scope

    Are we benchmarking for a campaign? A full rebrand? Messaging only?
    Determine direct vs. indirect competitors to assess (3–6 recommended)

2. Audit Dimensions

    Positioning – Market claims, value propositions, audience targeting
    Messaging – Taglines, headlines, tone, clarity, emotional hooks
    Visual Identity – Logos, type systems, design motifs, accessibility
    Digital Presence – UX/UI, clarity, mobile performance, SEO posture
    Content Strategy – Channel usage, creative cadence, brand voice

3. Mosaic + Framework Support

    Use Mosaic to:

      Summarize competitor brand narratives
      Identify recurring visual or tonal patterns
      Extract sentiment markers and market gaps
    Reference `reference.frameworks.canvas.md` for:

      Positioning Matrix
      SWOT Analysis
      Brand Keys

4. Strategic Gap Analysis

    What aren’t they doing well?
    Where is there whitespace in tone, audience, or execution?
    What traits can/should we challenge or co-opt?

5. Contextual Recommendation Layer

    Add insights tagged by:

      Target audience overlap
      Cultural resonance risk
      Platform advantage

---

 Expected Outputs

 Competitor Analysis Summary

   Structured comparison table and narrative takeaways
 Opportunity Matrix

   Visual or written grid highlighting strategic gaps
 Action Recommendations

   Framed by positioning goals and brand archetype

---

 Loop Integration

 Phase: Intelligence → Strategy
 Trigger: Use before messaging updates, brand positioning shifts, or campaign differentiation

---

 Notes

 Can be paired with `market.scan` and `trend.analysis` for full competitive context
 Outputs feed directly into `proposal.build` and `brief.write`


=== data_summarization.canvas ===
Data Summarization Canvas

 Purpose

To organize and synthesize unstructured data (e.g., Slack conversations, emails, meeting notes) into actionable insights and next steps. This canvas adapts based on project scope and desired Loop phase outcomes, with Mosaic support for parsing and prioritization.

---

 Method

1. Define Input Scope

    Identify project type and phase (e.g., preparing for campaign brief, post-project reflection, positioning refinement)
    Clarify the kinds of insight needed (e.g., blockers vs. trends vs. opportunity signals)

2. Ingest & Parse Data

    Feed Mosaic:

      Slack threads, transcripts, call summaries, stakeholder emails, internal docs
    Mosaic should:

      Detect key themes and recurring language
      Surface signals aligned to Loop phase goals

3. Contextual Summarization

    Based on scope, Mosaic generates:

      Objectives (e.g., launch clarity, message misalignment, partner bottlenecks)
      Blockers (e.g., slow approvals, unclear success metrics)
      Decisions (e.g., platform pivot, tone shift, scope reduction)

4. Tailored Next Steps

    Mosaic produces action steps categorized by:

      Loop phase (e.g., Strategy action, Creative prompt)
      Owner (PM, strategist, client)
      Urgency or priority

5. Optional Framework Overlay

    Pull in frameworks from `reference.frameworks.canvas.md` as needed to shape insights:

      Jobs To Be Done for customer statements
      Pirate Metrics for growth themes
      SWOT for internal team feedback

---

 Expected Outputs

 Insight Summary

   Condensed synthesis of relevant data by goal
 Action Plan

   Prioritized next steps, tagged by role + phase
 Strategic Tags (Optional)

   If applicable, frameworks used to interpret insight

---

 Loop Integration

 Phase: Intelligence → Insight → Strategy
 Trigger: Use at key inflection points (kickoff, mid-loop recalibration, post-project reflection)

---

 Notes

 Summarization logic must adapt based on project size, speed, and audience
 For framework tagging, reference `reference.frameworks.canvas.md`
 Mosaic-supported summarization should be human-reviewed before delivery


=== market.scan.canvas ===
Market Scan Canvas

 Purpose

To analyze the broader market landscape surrounding a brand—identifying category conventions, whitespace opportunities, substitute threats, and adjacent narratives. This canvas is ideal for early-stage brands, category challengers, or strategic repositioning.

---

 Method

1. Define Scan Type

    What is the brand trying to do?

      Enter a new category
      Create a new category (Category Design)
      Expand into adjacent verticals
      Reposition within an existing market

2. Scan Dimensions

    Category Norms – Visuals, tone, formats, offers
    Language + Positioning – Common claims, narrative tropes, archetypes
    Business Models – DTC, platform, hybrid, freemium, SaaS, etc.
    Adjacent Categories – Lookalike or lateral players
    Audience Overlaps – Shared or competitive segment focus
    Market Tension – Underserved needs, rising expectations, pricing cliffs

3. Threat and Substitute Mapping

    Identify indirect threats:

      Substitute products
      DIY or workaround solutions
      Cultural shifts that devalue the category

4. Opportunity Layering

    Identify whitespace using:

      Positioning Matrix (traditional vs challenger vs disruptor)
      Blue Ocean Strategy logic
      PESTLE for macro signals
    Layer brand archetype and tone fit against emerging gaps

5. Data Sources

    Industry reports, funding databases (Crunchbase, PitchBook)
    Consumer research, analyst decks, trend publications
    Mosaic can parse for thematic convergence, unmet needs, or rising language

---

 Expected Outputs

 Market Map

   Landscape of categories and players
 Threat Analysis

   Indirect/substitute risks and implications
 Whitespace Matrix

   Strategic gaps matched to brand potential
 Narrative Insight Layer

   Suggested tone or narrative opportunities

---

 Loop Integration

 Phase: Intelligence → Strategy
 Trigger: Use in foundational brand builds, category design projects, or market entry phases

---

 Notes

 Use alongside `competitor.audit` and `trend.analysis` for full strategy depth
 Pull frameworks as needed from `reference.frameworks.canvas.md`
 Mosaic outputs must be reviewed for nuance and market specificity


=== trend.analysis.canvas ===
Trend Analysis Canvas

 Purpose

To identify and prioritize relevant industry, cultural, audience, and technological trends. This canvas dynamically adjusts based on brand maturity, project type, and strategic need—enabling Mosaic and teams to spot forward-looking opportunities and shape strategic direction.

---

 Method

1. Clarify Trend Scan Scope

    Determine use case:

      Early-stage brand (category entry, whitespace)
      Brand evolution (tone/positioning recalibration)
      Campaign strategy (channel/format trends)
    Define which trend domains to explore:

      Industry, Audience, Technology, Cultural, Creative

2. Gather Input Sources

    Use Mosaic or human research to parse:

      Market reports (WGSN, McKinsey, CB Insights)
      Search/social listening data
      Cultural signals and meme cycles
      Thought leaders and competitor content

3. Map Trend Dimensions

    Classify trends using:

      Maturity (Emerging, Fast-Adoption, Peaking)
      Relevance (Direct, Adjacent, Indirect)
      Risk/Opportunity (Strategic vs. Tactical use)

4. Contextual Tagging

    Layer brand filters:

      Mission, audience segment, tone, archetype
      Project goals: awareness vs retention, launch vs pivot
    Tag trends that align or conflict with the brand's trajectory

5. Integrate Frameworks (Optional)

    For macro analysis:

      PESTLE or Cultural Branding overlays
    For audience-level trend activation:

      Jobs To Be Done, Micro-Moments, Empathy Mapping
    All available via `reference.frameworks.canvas.md`

---

 Expected Outputs

 Trend Summary

   Prioritized list of 5–10 trends with rationale
 Trend Mapping Grid

   Relevance × Maturity or Brand Fit Matrix
 Strategic Recommendations

   Suggested positioning shifts, creative ideas, or channel adjustments

---

 Loop Integration

 Phase: Intelligence → Strategy
 Trigger: Use in pre-brand build phases, campaign planning, or repositioning initiatives

---

 Notes

 Outputs can inform both `proposal.build` and `brief.write`
 Pair with `market.scan` and `competitor.audit` for full-context strategy work
 Can be run quarterly or annually for retainer clients


## 02. Strategy Canvases


=== commercial.scope.canvas ===
Commercial Scope Canvas

 Purpose

To define project scope, pricing structure, and production logistics based on The Loop methodology. This canvas supports fixed-fee quoting, modular deliverable mapping, contingency planning, and vendor coordination.

---

 Method

1. Scope Definition

    Identify which Loop phases the project will cover (e.g., Intelligence + Strategy)
    List expected outputs and formats from relevant canvases
    Clarify deliverables, volume, and versions per output (e.g., 3 visual directions, 1 refined concept)

2. Modular Pricing

    Use fixed-fee blocks aligned to each Loop phase or service unit:

      Brand Audit → $X
      Creative Brief + Mockups → $Y
      Rollout + QA → $Z
    Include optional add-ons or checkpoints for scope expansion

3. Timeline + Milestones

    Define delivery stages with expected turnaround times
    Include internal and client feedback loops (e.g., 2 rounds of revisions)

4. Contingency Buffers (Optional)

    Allocate buffer time (10–20%) for unforeseen complexity or iteration
    Price-in contingency bandwidth as either a set reserve or pay-as-used model

5. Vendor Coordination (If Applicable)

    Assign external production elements (e.g., motion, code, print) to vendors
    Include expectations, review workflows, and final delivery standards

6. Intelligence Usage Disclaimer

    Clearly state where embedded intelligence tools (e.g., Mosaic) are used for insight generation, summarization, or draft creation
    Clarify human oversight and final editorial responsibility
    Example clause:

     > "This scope includes outputs partially generated using intelligence-assisted workflows. All final deliverables are reviewed and refined by senior strategists and creative leads for accuracy, tone, and quality assurance."

---

 Expected Outputs

 Scope of Work (SOW) Summary

   Deliverables by phase
   Timelines and milestones
   Rounds of revision
 Pricing Table

   Modular fee breakdown with total estimate
   Optional buffer allocation noted
 Vendor Plan (Optional)

   Partner roles, tasks, and oversight structure
 Intelligence Usage Disclosure

   Transparency clause included in scope appendix or footnote

---

 Loop Integration

 Phase: Strategy → Activation
 Trigger: Use after proposal approval to prepare delivery logistics and pricing for internal or client sign-off


=== metrics_framework_canvas ===
Metrics Framework Canvas

 Purpose

To align project objectives with measurable outcomes, ensuring that success is defined, tracked, and optimized according to context. This canvas dynamically adapts metrics based on project scope, phase, and audience needs.

---

 Method

1. Clarify Objectives First

    Identify core goals (e.g., brand awareness, conversion, product validation, community growth)
    Match goals to the relevant Loop phase and deliverables

2. Select Metric Categories Dynamically

    Refer to `reference.frameworks.canvas.md` for measurement models
    Choose from:

      Financial – ROI, CAC, LTV, MRR, ARR
      Operational – Speed, iteration cycles, QA scores, Mosaic usage
      Audience – Engagement, reach, SOV, resonance
      Activation – CTR, CPM, open rate, conversion rate
      Retention – Repeat usage, CLTV, churn
      Brand Impact – Recognition, clarity, narrative adoption

3. Framework Matching by Context

    For brand activation: Pirate Metrics or Growth Loops
    For internal success: OKRs, NSM, Cohort Analysis
    For product validation: Jobs To Be Done, Micro-Moments, Funnel metrics
    For long-term impact: Post-Mortem + NSM tracking

4. Benchmarking

    Pull from past projects, competitor audits, or platform benchmarks
    Use current brand maturity and resource scope to calibrate expected impact

5. Feedback Loop Integration

    Define data collection cadence (weekly, per sprint, per milestone)
    Structure learning sessions to interpret results and feed into `loop.reflect`

---

 Expected Outputs

 Metrics Plan

   Clear mapping of KPIs to objectives and phases
 Tracking Dashboard Outline

   Metric category, frequency, owner, visualization model
 Optimization Loop Hook

   Specific data signals that trigger adjustment to strategy or creative

---

 Loop Integration

 Phase: Strategy → Insight → Activation
 Trigger: Use during proposal creation and again post-activation to evaluate performance

---

 Notes

 Do not assume static KPIs—metrics must be context-driven
 For framework selection, reference `reference.frameworks.canvas.md`
 This canvas is compatible with Mosaic for dynamic KPI mapping


=== proposal.build.canvas ===
Proposal Build Canvas

 Purpose

To translate insights from Intelligence into a structured, actionable proposal. This canvas adapts based on project scope, brand maturity, and market dynamics—ensuring strategy is clearly aligned with outcome engineering.

---

 Method

1. Clarify Project Context

    Is this a brand build, reposition, campaign, or retainer loop?
    What Loop phases will this proposal cover?

2. Define Objectives

    What must change, improve, or emerge?
    Pull from:

      `brand.audit`
      `trend.analysis`
      `market.scan`
      `competitor.audit`
      `loop.reflect` (if applicable)

3. Structure the Proposal

    Executive Summary – Context + ambition
    Key Insights – Trends, gaps, triggers
    Recommended Actions – What we’ll do, and why
    Deliverables – Modular by Loop phase
    Timeline + Scope – Milestones, owners, velocity

4. KPI + Measurement Logic

    Define KPIs using `metrics_framework`
    Tie outcomes to business model or campaign impact

5. Versioning + Flex Points

    Allow for modular entry points and scale-ups
    Clearly note items not in current scope (but available via checkpoint expansion)

---

 Expected Outputs

 Strategic Proposal

   Insight-backed, goal-oriented, and action-ready
 Loop Phase Map

   Visual or tabular breakdown of scope by phase
 Deliverables List

   Asset, milestone, and responsible team roles

---

 Loop Integration

 Phase: Strategy
 Trigger: Use after insights are synthesized and before moving into briefs or scoping

---

 Notes

 This canvas is often the bridge between `insight` and `brief.write`
 All framework references (SWOT, JTBD, etc.) can be pulled dynamically from `reference.frameworks.canvas.md`
 Proposal style should reflect tone defined in `archetype.mapping` if brand-level


## 03. Creative Canvases


=== archetype.mapping.canvas ===
Archetype Mapping & Narrative Personality Canvas

 Purpose

To define and align a brand’s narrative personality using archetypes, tone dimensions, and storytelling frameworks. This canvas dynamically adjusts based on project goals, market context, and audience—powering creative consistency and Mosaic alignment.

---

 Method

1. Clarify Narrative Intent

    Project objective:

      Foundational brand build
      Tone refresh or brand stretch
      Campaign-specific narrative expression
    Choose whether mapping is permanent (brand-level) or adaptive (project-level)

2. Select Archetypes

    Choose 1–2 dominant brand archetypes:

      Sage, Creator, Explorer, Hero, Rebel, Magician, Lover, Caregiver, Everyman, Ruler, Innocent, Jester
    Optional: Layer secondary or opposing archetypes for brand depth

3. Tone Alignment Mapping

    Translate archetype traits into tone sliders:

      E.g., Sage → Strategic + Clear
      Explorer → Curious + Inventive
    Reference `tone.of.voice.canvas.md` for consistency

4. Narrative Framework Integration

    If applicable, define project narrative arc:

      Hero’s Journey (for transformational brands)
      Cultural Branding (for zeitgeist alignment)
      Laddering Framework (for emotional benefits)
    Pull from `reference.frameworks.canvas.md`

5. Messaging Examples

    Draft:

      Tagline or value proposition
      Social post or web headline
      Tone-match vs tone-break samples

6. Mosaic Calibration

    Feed final personality profile to Mosaic for:

      Voice filtering
      Draft validation
      Tone matching

---

 Expected Outputs

 Archetype Profile

   Primary + secondary personality definition
 Tone Map Extension

   Narrative-to-tone alignment
 Sample Messaging Kit

   Applied examples and tone guidance

---

 Loop Integration

 Phase: Strategy → Creative
 Trigger: Use during creative strategy, brand development, or tone system creation

---

 Notes

 Revisit this canvas when a major audience, category, or mission shift occurs
 Ensure narrative structure aligns with desired emotional resonance and business model
 Always cross-reference tone logic and storytelling frameworks for depth


=== brief.write.canvas ===
Brief Write Canvas

 Purpose

To generate a creative brief that provides direction and clarity for the Creative phase. This brief adapts dynamically based on brand maturity, campaign goals, and strategic inputs—ensuring creative execution aligns with desired outcomes.

---

 Method

1. Pull from Strategic Inputs

    Ingest outputs from:

      `proposal.build`, `trend.analysis`, `market.scan`, and `brand.audit`
    Identify primary Loop goal: Awareness? Activation? Retention?
    Use Mosaic to distill key themes, messages, or narratives to carry forward

2. Define Deliverables & Goals

    Specify:

      Channels and formats (e.g., paid ads, social series, landing pages)
      Volume (e.g., 3 concepts, 1 flagship, 1 variant)
      KPIs aligned to `metrics_framework`

3. Tone, Voice & Archetype Context

    Reference:

      `tone.of.voice.canvas.md`
      `archetype.mapping.canvas.md`
    If tone is shifting or exploratory, define constraints and flex zones

4. Narrative Priorities

    Highlight key brand story elements to emphasize or evolve
    Optional: structure creative through a narrative framework (e.g., Hero’s Journey, Cultural Branding)

5. Constraints & Requirements

    Platform-specific rules
    Client approval structure or regulatory boundaries
    Creative guardrails (e.g., no AI imagery, inclusive language only)

---

 Expected Outputs

 Creative Brief Document

   Strategy-backed, context-aware, and execution-ready
 Alignment Checklist

   Clear tie-back to brand tone, objectives, and metrics
 Mosaic Brief Summary (Optional)

   Condensed 1-page version for high-speed use or AI generation

---

 Loop Integration

 Phase: Strategy → Creative
 Trigger: Use after proposal approval or intelligence sync to kick off creative production

---

 Notes

 Brief structure flexes based on scope (e.g., campaign vs. evergreen build)
 Tone and narrative must always be backed by contextual strategy
 For frameworks and story structure, see `reference.frameworks.canvas.md`


=== mockups.request.canvas ===
Mockups Request Canvas

 Purpose

To initiate mockups or concept drafts that align with strategic goals, creative briefs, and brand tone. This canvas adapts based on deliverable type, campaign scope, and creative context—ensuring Mosaic or teams request the right things, the right way.

---

 Method

1. Context Pull-In

    Pull from:

      `brief.write` (creative direction, messaging goals)
      `archetype.mapping` and `tone.of.voice` (style constraints)
      `metrics_framework` (target KPIs)
    Mosaic can summarize core messaging and visual tone in a mockup spec

2. Define Mockup Type(s)

    Specify required formats:

      Static (e.g., social post, web module)
      Motion (e.g., explainer, stories)
      Product (e.g., UI/UX component, packaging)
    Include version scope (e.g., 2 variants, 1 hero concept)

3. Input Reference Package

    Include:

      Text content or narrative beats
      Example visuals (inspiration or existing brand material)
      Color, typography, accessibility considerations

4. Timeline + Review Logic

    Set:

      Key deadlines
      Review milestones
      Feedback loop (rounds and format)

5. Optional Dynamic Prompting

    Allow Mosaic to generate early design descriptions or layout prompts
    Use brand archetype and platform context to generate layout hypotheses

---

 Expected Outputs

 Mockup Request Spec

   Clear brief for design or prototyping teams
 Reference Kit

   Files, visuals, and key verbal context
 Mosaic Draft Generator (Optional)

   Auto-generated visual structure ideas or layout prompts

---

 Loop Integration

 Phase: Creative
 Trigger: Use after creative brief is approved and aligned with campaign or product goals

---

 Notes

 Always flex the ask based on budget, timing, and deliverable priority
 For narrative guidance or voice alignment, reference `reference.frameworks.canvas.md`
 Mosaic can optionally produce a mockup description to jumpstart ideation


=== tone.of.voice.canvas ===
Tone of Voice Canvas

 Purpose

To define, adapt, or reaffirm the brand’s tone of voice based on project type, audience, and archetype. This canvas supports dynamic tone modeling using Mosaic and ensures consistency across all creative outputs.

---

 Method

1. Determine Scope of Voice Calibration

    Project context:

      Net new brand build
      Repositioning or tone refresh
      Campaign-level tone tailoring
    Platform specificity: does tone need to flex across formats?

2. Reference Brand Personality

    Pull from `archetype.mapping.canvas.md`

      Primary + secondary archetype(s)
      Narrative role (e.g., challenger, sage, rebel)

3. Map Tone Dimensions

    Use the 5 TESSERA tone dimensions:

      Intelligent & Strategic
      Witty & Understated
      Clear & Direct
      Confident & Authentic
      Creative & Balanced
    Rate each on a sliding scale (0–5) based on project needs

4. Platform or Audience Flex

    Define how tone should shift (if at all) across:

      B2B vs B2C
      Social vs Web vs Email
      Internal vs External messaging

5. Mosaic Integration (Optional)

    Mosaic can:

      Generate tone hypotheses based on prior messaging
      Suggest tone flex based on campaign archetype
      Validate tone match in copy samples

---

 Expected Outputs

 Tone Map

   Dimensions, examples, and sliders
 Platform Tone Guide (Optional)

   How voice changes by channel
 Alignment Check

   Sample messaging marked as "on-tone" vs "off-tone"

---

 Loop Integration

 Phase: Strategy → Creative
 Trigger: Use at start of campaign or when calibrating creative voice

---

 Notes

 Pull story-based or emotional cues from `reference.frameworks.canvas.md`
 Update tone mapping per major brand phase or market shift
 Ensure Mosaic calibration reflects final approved tone spec


## 04. Activation Canvases


=== output.prepare.canvas ===
Output Prepare Canvas

 Purpose

To finalize, package, and prepare creative assets for deployment. This canvas adapts based on channel strategy, asset type, and delivery constraints—ensuring rollout is sharp, brand-aligned, and measurable.

---

 Method

1. Define Deployment Scope

    Pull from `brief.write` and `metrics_framework`
    Confirm:

      Which platforms and formats?
      Which KPIs matter?
      What’s the campaign arc or rollout logic?

2. Asset Review + QA

    Conduct final checks:

      Brand consistency (voice, tone, visuals)
      Platform formatting (aspect ratios, file specs)
      Mosaic-generated vs. human-reviewed content

3. Rollout Planning

    Sequence by:

      Channel priority
      Messaging escalation
      Day/time/region logic if global
    Include fallback assets if approvals stall

4. Deployment Package Build

    Package includes:

      Assets (visuals, copy, code if applicable)
      Briefing doc or campaign outline
      Platform instructions or pre-flight checklist

5. Mosaic-Driven Optional Support

    Mosaic can:

      Generate rollout timelines based on brief scope
      Create checklist for asset requirements
      Auto-format for common platforms (if specs exist)

---

 Expected Outputs

 Deployment Kit

   Final-ready creative assets and guides
 Rollout Plan

   Calendar, sequence, and platform logic
 QA & Approval Checklist

   Internal and client-facing where needed

---

 Loop Integration

 Phase: Creative → Activation
 Trigger: Use after creative sign-off and before campaign or asset launch

---

 Notes

 Scale the rigor based on campaign size (e.g., fast-turn vs. flagship)
 For strategic context, tie back to `metrics_framework` and `reference.frameworks.canvas.md`
 Output Kit can serve as handoff to internal or client-side media teams


## 05. Insight Canvases


=== loop.reflect.canvas.canvas ===
Loop Reflect Canvas

 Purpose

To synthesize learnings, performance data, and feedback into actionable insight. This canvas integrates dynamic optimisation logic based on the Loop phase and project goals—enabling better outcomes every cycle.

---

 Method

1. Collect Multiphase Inputs

    Pull data and feedback from:

      `metrics_framework`
      Team retrospectives
      Audience reactions (engagement, sentiment)
      Client inputs or escalation logs

2. Evaluate Performance by Objective

    Assess:

      Were goals met, exceeded, or missed?
      Which metrics drove success?
      Which blockers slowed momentum?

3. Categorize Learning Types

    Sort insights into:

      Strategic (e.g., wrong audience, unclear positioning)
      Tactical (e.g., channel mismatch, creative fatigue)
      Structural (e.g., timing gaps, unclear roles)

4. Propose Optimisations

    Recommend:

      What to improve, retire, or repeat
      Which Loop phase(s) should be re-entered or rebooted
      How future work should flex (scope, tone, format)

5. Framework & Mosaic Support (Optional)

    Apply:

      Post-Mortem or Growth Loop model from `reference.frameworks.canvas.md`
    Mosaic can:

      Surface patterns across retrospectives
      Generate insight summaries or next-step recommendations

---

 Expected Outputs

 Insight Report

   Synthesized findings by goal and metric
 Optimisation Plan

   Tactical and strategic recommendations
 Loopback Map

   Suggested re-entry point(s) and next actions

---

 Loop Integration

 Phase: Insight
 Trigger: Use at the end of every Loop cycle to feed forward learning

---

 Notes

 Insight depth should flex based on project scale
 Use Mosaic to streamline large dataset analysis
 Frameworks like AARRR, OKRs, and Cohort Analysis may support analysis


=== reference.frameworks.canvas.canvas ===
Reference Frameworks Canvas

 Purpose

To provide a structured, searchable index of strategic, narrative, design, activation, and optimisation frameworks used across the TESSERA Brand OS. This canvas supports dynamic routing, training logic in Mosaic, and strategic decision-making in human workflows.

---

 Usage Guidelines

 This is a reference canvas, not a workflow canvas
 Use it to determine which frameworks are relevant based on:

   Loop phase
   Project type or goal
   Brand maturity or audience needs

---

 1. Strategy + Positioning

Frameworks to support market differentiation, clarity, and strategic alignment:

 Blue Ocean Strategy – Uncontested market space
 Good Strategy Bad Strategy – Action vs. fluff
 Brand Keys – Brand equity mapping
 Positioning Matrix – Competitive orientation
 Jobs To Be Done (JTBD) – Customer motivation
 Core-Periphery Model – Brand architecture
 Porter’s Five Forces – Competitive analysis
 SWOT Analysis – Strengths, weaknesses, etc.
 Category Design – Market leadership creation
 Business Model Canvas – Align ops + brand
 PESTLE Analysis – Macro-environment scan

---

 2. Narrative + Identity

Frameworks that guide brand story, tone, and emotional connection:

 Narrative Theory (McKee) – Story arcs
 The Brand Gap – Strategy → Creative bridge
 Brand Archetypes – Personality systems
 Laddering Framework – Benefit hierarchy
 Hero’s Journey – Transformation narrative
 Cultural Branding – Zeitgeist alignment
 Primal Branding – Iconic brand structure
 Brand DNA Framework – Purpose/vision/values
 Semiotic Analysis – Cultural resonance

---

 3. Design + Communication

Frameworks that shape how brands express themselves visually and functionally:

 Modernist Design (Swiss/Bauhaus/Brutalism) – Clean systems
 Landa’s Visual Grammar – Compositional theory
 Gestalt Principles – Perceptual psychology
 Visual Semiotics – Symbolic meaning
 Human-Centered Design – User-first process
 Emotional Design – Feelings + UX
 Behavioral Design – Design that nudges
 Responsive Design – Adaptive UI/UX
 Typography Systems – Type clarity + hierarchy
 Color Psychology/Theory – Mood + perception
 Universal Design – Accessibility + inclusion
 Storytelling in Design – Narrative visuals
 Neuroscience in Design – Brain-based UX
 Systemic Design – Scalable ecosystems

---

 4. Audience + Activation

Frameworks for understanding, segmenting, and activating audiences:

 Customer Journey Mapping – Experience phases
 Voice of Customer (VoC) – Real feedback
 Behavioural Economics – Irrational behaviors
 Platform-Native Content Strategy – Channel fit
 Empathy Mapping – Emotional insight
 Segmentation Models – Psychographic targeting
 Customer Lifetime Value (CLTV) – Value focus
 Micro-Moments – Key decision points
 Omnichannel Strategy – Seamless experience

---

 5. Optimisation + Insight

Frameworks to measure performance, learn, and grow:

 Attribution Models – Channel contribution
 Post-Mortem Templates – Learning from failure
 Growth Loops – Self-reinforcing systems
 Testing Models – A/B and multivariate
 OKRs – Outcomes that align teams
 Cohort Analysis – Longitudinal behavior
 Pirate Metrics (AARRR) – Growth stack
 North Star Metric (NSM) – Single point of focus

---

 Loop Integration

 Use this canvas across ALL phases
 Mosaic uses this to match frameworks to project context
 Humans can reference it in:

   `brief.write`
   `proposal.build`
   `metrics_framework`
   `mosaic.training`
   Any strategic or narrative module

---

 Change Protocol

 All additions, removals, or updates to this canvas must be versioned
 Changes should be reflected in Mosaic’s routing logic

---

 Status: Living Document

This canvas is foundational to both human and machine decision-making.
Update it when new frameworks prove effective—or old ones lose relevance.


