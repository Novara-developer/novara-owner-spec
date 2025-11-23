# Novara Owner Spec / Driver Profile (Hinata v0.1)

This repository stores the **owner-level specification** for Novara –  
not the technical protocol itself, but the values, drives, and narratives of its creator (Hinata).

It is meant to be a small, versioned snapshot of:

- What kinds of *gaps* (misalignments) Hinata reacts to
- How those reactions are structured across four layers
- How this will later connect to Novara’s task and governance interfaces (NUTI, ABL, UPP, etc.)

---

## Concept

### 1. Four-Layer Model

Hinata’s “what do I care about?” is modeled as four layers:

1. **Physical**  
   Brain wiring, reward system, cognitive style.  
   (For example: strong sensitivity to structure, rules, and long-term consistency.)

2. **Experience**  
   Real-world signals that shaped the value function, such as:
   - The feeling of Japan slowly declining
   - Irresponsible AI/tech hype
   - How often “stories without evidence” can still move the world

3. **Narrative**  
   The current self-story:

   > “I will lock civilization to evidence.  
   > I will redesign AI-era decisions and responsibility around verifiable proof.”

4. **Meta-Choice**  
   The layer that asks:

   > “Is this story still valid if I look from 2060, or even from the year 3000?”

   This is where Hinata tries to *rewrite* or *refine* their own story instead of treating it as absolute.

---

### 2. “Resolution of Free Will”

Instead of a binary “free will exists / does not exist”,  
this repo uses the idea of **free-will resolution**:

> How much can I consciously choose and revise  
> the values and narratives that drive me?

Low resolution → just running on biology + past experience.  
Higher resolution → able to inspect and edit the narrative & meta layers.

This repo is **Hinata’s free-will snapshot v0.1**:  
which gaps they choose to care about, and how explicitly.

---

## Files

### `owner_profile/owner_driver_profile.v0.1.json`

Core “fuel” / drivers in JSON form, including for example:

- Refusal of bad rules that hurt people
- Pleasure in hacking the world through structure and evidence
- Desire to protect people who are close
- Desire to treat civilization as a “cosmic-scale game” and rewrite its rules

Also includes:

- A numeric `free_will_resolution.scale`
- A life check question:  

  > “Which gaps would I still be proud to care about  
  > when I look back at my life right before death?”

---

### `owner_profile/owner_layers.v0.1.json`

Current self-assessment of the four layers:

- Physical: what kind of brain this seems to be
- Experience: which events became strong teacher signals
- Narrative: current main story (with a “soft lock” – can still change)
- Meta-Choice: commitment to periodically re-evaluate the story itself

---

## Future Use (Ideas)

This owner spec is intended to eventually feed into:

- **NUTI** (Novara Universal Task Interface)  
  → default goals / constraints based on Hinata’s drivers

- **ABL** (Action Boundary Language)  
  → default safety / responsibility boundaries informed by the owner’s values

- **UPP** (proof-token prerequisites)  
  → how “demand for proof” is treated as a first-class condition

Versioning (v0.1, v0.2, …) will also let Novara track  
**how the owner’s values and narratives evolve over time**,  
as part of a broader “evidence OS” for both systems *and* people.