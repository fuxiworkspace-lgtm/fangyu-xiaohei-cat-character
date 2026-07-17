---
name: fangyu-xiaohei-character
description: |
  Generate Xiaohei scenes with real objects, physical actions, whitespace narrative, and semantic colored work shirts. Route one or more identical black cat-eared Xiaohei characters from the input's topic, emotion, workflow, and core action. Supports standard 16:9 illustrations, 4:5 social cards, and 3:1 story scrolls.
when-to-use: |
  Use when the user wants an article illustration, editorial visual, project retrospective, event workflow, product story, personal journey, or a Xiaohei scene with real objects and physical action. Trigger terms include Xiaohei, Fangyu Xiaohei, colored Xiaohei, real-object scene, Xiaohei 2.0, story scroll, project retrospective, event flow, and visual metaphor.
allowed-tools:
  - Read
  - Write
  - Edit
  - Bash
context: fork
---

# Fangyu Xiaohei Character

## Positioning

This Skill is the clothing-first Fangyu version of the Xiaohei Scenes workflow:

```text
Xiaohei + real object + physical action + short Chinese labels + whitespace narrative
```

It inherits the original [ian-xiaohei-scenes](https://github.com/helloianneo/ian-xiaohei-scenes) rules for content extraction, physical metaphor, object realism, restraint, master selection, and QA. The only deliberate IP override is the fixed black cat-eared body and the five semantic work-shirt colors.

## Fixed Character Canon

All variants share:

- solid matte-black body
- small triangular cat ears
- almost-round oversized head
- white oval eyes with tiny black pupils
- compact torso and thin limbs
- blank, calm, serious, slightly clumsy personality
- no realistic animal details, tail, whiskers, paw pads, logos, or complex clothing patterns

Only the simple matte work-shirt color changes. Do not change the body color, face, eyes, limbs, proportions, or personality to explain a role.

## Shirt Semantics

- **Black shirt:** default narrative anchor, everyday work, main operator.
- **Terracotta red shirt:** alarm, risk, conflict, emotional peak, Chinese stock-market rise.
- **Moss green shirt:** repair, recovery, connection, Chinese stock-market fall.
- **Slate blue shirt:** system, tools, code, data, AI workflow, rational operation.
- **Mustard yellow shirt:** opportunity, reminder, warm-up, launch, illumination.

The input must justify every non-black shirt. Color is semantic routing, not decoration.

## Required Workflow

### 1. Extract the situation

Identify the reader's situation, the central tension, the main object, the core verb, the emotional state, the participants, and any stages or outcomes. Convert abstract ideas into one physical action: pushing, pulling, blocking, repairing, dragging, connecting, bracing, sorting, or being affected by an object.

### 2. Anchor facts

Use only facts supplied by the user or source material. Do not invent names, brands, dates, numbers, achievements, or personal history. Replace uncertain facts with neutral labels or mark them as pending.

### 3. Route colors

Read `references/color-characters.md`. Select the default black shirt unless the input has clear risk, repair, system, opportunity, or market-color semantics. The character must remain the same black cat-eared form regardless of shirt color.

### 4. Route collaboration

Read `references/character-routing.md` whenever the content has multiple stages, parties, functions, or actions. Decide:

```text
Main role:
Main role meaning:
Supporting role(s): none / red / green / blue / yellow
Why each appears:
Main action:
Supporting action(s):
Continuity link: shared object, cable, force, or result
Composition: visual center, force end, obstacle end, result end
Excluded roles:
```

If the input does not prove a relationship, use one character. Never use all five only to display the color family.

### 5. Build the shot list

Before generation, define the master, invariant quality traits, current mutations, three-second reading sentence, reader situation, physical action, real object, character routing, labels, and failure signals. Standard mode normally uses one character and one core physical conflict. Use two only for clear division of labor; three is exceptional.

### 6. Select the format

- Standard 16:9: one compact real-object scene.
- 4:5: one strong social-card moment.
- 3:1 story scroll: 5-8 unnumbered real-object nodes connected by an organic route. Keep black-shirt Xiaohei as the narrative anchor and change colors only at true semantic turns.

### 7. Generate and QA

Read `references/prompt-template.md` and the selected master before generation. After generation, compare the candidate with the master. Check character canon, shirt semantics, physical contact, one core action, object realism, whitespace, label legibility, layout relationships, and originality. Reject lineups, decorative characters, arbitrary color changes, and master-image tracing.

## Expressive Constraints Inherited from Xiaohei Scenes

- Xiaohei performs the core physical action; it does not stand beside the metaphor.
- Actions show contact, force, tension, blocking, repair, pulling, dragging, or consequence.
- Slight deformation is allowed only when it serves the action.
- The personality is blank, calm, serious, and slightly clumsy.
- The charm comes from seriously doing an absurd task, not from exaggerated cuteness.
- If removing Xiaohei leaves the metaphor fully intact, the action design has failed.

## Layout Logic

- Single character: one clear contact point and one visual center.
- Main plus support: main character at the center; support at the tool, force, obstacle, or result end.
- Opposition: put characters at opposite ends of the same object and show the force.
- Tool chain: blue upstream, green downstream, connected by the same cable or machine.
- Opportunity: yellow must change the next action through a door, light, clue, or object.
- Story scroll: black anchors the main line; yellow starts, blue systems, red turns, and green recovery only when the content supports them.

## Reference Map

- `references/xiaohei-character-lock.md`: fixed IP and negative constraints.
- `references/character-routing.md`: multi-character routing, continuity, and composition.
- `references/color-characters.md`: semantic shirt roles.
- `references/story-extraction.md`: input decomposition and shot lists.
- `references/prompt-template.md`: generation prompts.
- `references/qa-checklist.md`: delivery checks.
- `assets/examples/`: visual anchors and quality masters.

## Delivery Standard

A successful image should feel clean, slightly strange, physically legible, and emotionally accurate. The viewer should first notice a real object and a serious Xiaohei action, then understand the article's situation from a few short labels. It should never look like a PPT, a mascot lineup, a generic infographic, or a decorated prompt checklist.
