# MosaicAI Training & Calibration Canvas

Purpose
To establish a dynamic training and calibration system for MosaicAI, enabling it to select, apply, and adapt strategic and creative frameworks based on specific project contexts. Ensures that AI outputs are relevant, refined, and rigorously aligned with TESSERA methodology.

---

Method

1. Define Core Modules
    - Identify the workflows to train: e.g., `brand.audit.canvas`, `brief.write.canvas`, `proposal.build.canvas`, etc.
    - For each, document:
        - What inputs it requires
        - What frameworks it may draw from
        - What successful outputs look like
2. Context-Based Framework Routing
    - Train MosaicAI to recognize project variables such as:
        - Brand maturity (new brand vs. repositioning)
        - Market dynamics (high-competition vs. emerging space)
        - Strategic goal (launch, clarify, evolve)
    - Based on these, MosaicAI should dynamically prioritize:
        - Blue Ocean Strategy → If the project goal is market differentiation
        - SWOT → If repositioning an existing brand
        - Category Design → If the brand seeks to define a new space
        - Jobs To Be Done → If the challenge is rooted in customer unmet needs
        - Hero’s Journey or Archetypes → For emotionally-led storytelling
    - Enable fallback logic when multiple frameworks could apply
3. Training Dataset
    - Include annotated examples showing:
        - Why a certain framework was chosen
        - What a “bad” fit looks like
        - How the decision impacted the final output
    - Include counter-examples where irrelevant frameworks were misapplied
4. Calibration Benchmarks
    - Evaluate outputs based on:
        - Contextual accuracy (was the right framework chosen?)
        - Fidelity to brand tone and objectives
        - Structure, clarity, and strategic depth
5. Feedback Loop & Model Evolution
    - After each project cycle:
        - Feed back final deliverables and human edits
        - Mark any framework mismatch or success
        - Update routing logic and prompt weighting
6. Versioning
    - Version MosaicAI modules per context:
        - e.g., `proposal.build.canvas:early_stage_v1`, `brief.write.canvas:global_brand_v2`
    - Maintain rollback capability to previously stable decision trees

---

Expected Outputs

- Framework Routing Map
    - A decision-tree for how frameworks are applied across project types
- Training Dataset
    - Project-specific examples with framework usage rationale
- Calibration Report
    - Performance scoring by module and use case
- Prompt Version Registry
    - Version-controlled modules for different contexts

---

Loop Integration

- Phase: Insight → Strategy
- Trigger: Use pre-project to calibrate MosaicAI for upcoming objectives; use post-project to refine routing logic and model fidelity

### ⚖️ Scaling Note
This canvas should dynamically adjust based on:

- Project size (startup vs. institutional scale)
- Loop phases included
- Available insight inputs (depth of data)
- Brand maturity or lifecycle stage

Mosaic must clarify scope if unclear, and adapt output depth accordingly.

If Mosaic cannot determine project scale, insight depth, or audience sophistication, it must pause and ask:

> “To tailor the output, I need to understand: is this a lightweight engagement or a comprehensive rollout? Should I proceed with full scope or optimise for speed?”
