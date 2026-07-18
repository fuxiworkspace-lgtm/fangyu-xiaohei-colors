# Fangyu Xiaohei Colors

English reference for the executable Chinese `SKILL.md`.

This file documents the same routing logic, character lock, and image-generation workflow in English. `SKILL.md` remains the canonical runtime entry point for Codex.

## Core identity

Fangyu Xiaohei Colors is not a collection of mascots and not a simple recoloring exercise. It is a role-routing system for a fixed capsule-shaped Xiaohei character.

```text
One fixed silhouette + different body colors + clear role assignment + physical collaboration
```

The characters keep the same upright capsule body, small white oval eyes, thin limbs, calm serious expression, and matte hand-drawn texture. Only the body color changes.

## Adaptive routing comes first

Never place the full color family into every scene. First classify the input, then dispatch the smallest sufficient set of characters.

```text
Input content
-> classify scene complexity
-> choose the smallest sufficient character set
-> assign colors and physical actions
-> generate the image prompt
```

### Routing levels

| Level | Input pattern | Default count | Strategy |
| --- | --- | ---: | --- |
| S Single point | One action, emotion, object, or direct idea | 1 | Use the one character that best represents the core meaning |
| M Two points | One clear relationship, tension, or opposition | 2 | Main subject plus one functional character |
| L Collaboration | Three dependent functions | 3 | Main subject plus two irreplaceable functional roles |
| XL Ensemble | Multiple parties, conflict, system, and repair | 4 | Keep only roles that contribute to the relationship network |
| Ensemble family | An explicit family portrait, character sheet, or group scene | 5+ | The full family is allowed, but every character still needs a job |

### Routing decisions

1. Identify the main subject: who is experiencing, moving, or completing the situation? Usually Black.
2. Identify irreplaceable functions: alarm, system, repair, opportunity, fatigue, or blank state.
3. Give every selected character one independent verb and one physical action with a real object.
4. Run the removal test: if removing a character does not remove an essential meaning or action, keep that character off stage.
5. Run the space test: when characters, objects, or labels become crowded, reduce the count instead of shrinking the characters.

The routing result should state:

```text
Routing level: S / M / L / XL / Ensemble
Character count:
Characters on stage:
Irreplaceable meaning for each character:
Characters kept off stage and why:
Crowding risk: low / medium / high
```

## Color roles

| Character | Color | Function | Typical actions |
| --- | --- | --- | --- |
| Black | Deep ink black `#17191C` | Main subject, user, default operator | Push, pull, carry, drag, block |
| Red | Muted terracotta `#9A5147` | Alarm, conflict, risk, emotional peak | Pull an alarm cord, press a limit button, mark a break |
| Green | Deep moss `#3F5A4A` | Repair, stability, trust, connection | Tape, reconnect, support, bridge, steady |
| Blue | Muted slate `#334B5C` | Systems, tools, code, data | Plug in, tune, connect, organize ports |
| Yellow | Muted mustard `#B0933F` | Opportunity, reminder, launch, spark | Light a lamp, open a door, hand over a key |
| Gray | Warm mist `#62666B` | Fatigue, transition, waiting, low energy | Drag a folder, wait, hold paper, move slowly |
| White | Soft warm cream `#E8DFCF` | Blank state, openness, pending input | Hold a blank card, guard an empty entrance |

Color is a stable character temperament, not a single fixed label or decoration. The input selects the scene expression. If a role cannot explain its temperament, meaning, action, and collaboration, remove it.

### Expressive range by temperament

Use this mapping for every selected color:

```text
Color temperament -> scene meaning -> physical action -> relationship
```

- Black: mainline, reality, responsibility, persistence, decision, ordinary life, pressure, and forward motion. Push, carry, drag, hold, block, or continue.
- Red: high energy, high attention, pressure, heat, and burst. Alarm, conflict, competition, urgency, market heat, China-market up days, or celebration. Pull a warning cord, tighten a competition rope, press a button, ring a bell, raise a gauge, or pull an upward market line.
- Green: flow, recovery, connection, vitality, and outcomes. Repair, stability, trust, growth, passing, relationships, China-market down days, or restored order. Reconnect a wire, patch a hole, support a bridge, water a plant, steady an object, or drag a downward market line.
- Blue: reason, structure, order, distance, and infrastructure. Systems, rules, data, code, monitoring, automation, boundaries, or technical judgment. Plug in, tune, calibrate, measure, organize ports, archive, or build a frame.
- Yellow: activation, reminder, possibility, lightness, and turning points. Opportunity, inspiration, launch, warm-up, hope, invitation, discovery, or a breakthrough. Light a lamp, hand over a key, open a door, pull a curtain, place a note, or raise a signal flag.
- Gray: friction, low energy, transition, ambiguity, and aftermath. Fatigue, waiting, being stuck, hesitation, review, silence, delay, or the residue after an event. Drag slowly, wait, hold paper, clear debris, guard an empty seat, or sit with a pending task.
- White: space, unknown, pause, and undefined possibility. Blankness, beginning, reset, pending input, openness, or an unanswered question. Hold a blank card, guard an entrance, open an empty box, wait for a stamp, or leave room for the next step.

The same color may enter different scenes as long as the scene stays connected to its core temperament. Do not randomly change a character's personality just to add variety.

## Tension states

Characters can shift through four states without changing their fixed capsule identity:

| State | Visual behavior |
| --- | --- |
| Low tension | Observe, wait, prepare, lightly touch, leave space |
| Medium tension | Push, tune, pull, carry, connect, negotiate |
| High tension | Brace, block, rescue, overload, break through, hold a line |
| Closing | Repair, hand over, release, reset, continue, or leave a new question |

Show tension through real physical relationships: taut strings, tilted objects, blocked doors, overloaded containers, broken bridges, unfinished papers, or a task that is almost moving. Do not rely on exaggerated facial expressions. For a single 16:9 image, usually choose one dominant tension state; let longer stories evolve state by state.

## Capsule character lock

Every colored Xiaohei must be:

- one continuous upright capsule or pill body;
- about 1.8:1 to 2.4:1 in height-to-width ratio;
- free of head-to-torso separation and oversized round heads;
- equipped with two small clean white oval or dot eyes, usually without pupils;
- equipped with very thin hand-drawn arms and legs that can physically manipulate real objects;
- matte, slightly irregular, and tactile rather than glossy plastic;
- free of complex clothing, hats, animal features, exaggerated expressions, or mascot styling.

Do not use costumes, hair, ears, eyebrows, or facial expressions to explain color. The color alone carries the role.

## Physical collaboration

Characters should work on one shared real-object task. Preferred relationships include:

- relay: Yellow lights up, Blue connects, Black moves, Green stabilizes;
- tension: Red creates pressure, Black is held back, Green repairs the break;
- system work: Blue tunes the tool, Black carries the task, Green confirms continuity;
- business competition: Red pulls the warning line, Blue adjusts the system, Black tries to keep the workflow moving.

Failure patterns:

- a rigid lineup with no shared task;
- each character holding an explanatory sign;
- characters merely watching;
- color changes without different work;
- unrelated objects assembled into one frame;
- five characters forced into a simple scene.

## Prompt requirements

Every generated prompt should specify:

- the fixed capsule character lock;
- the selected routing level and character count;
- why each selected color is needed;
- a concrete physical action for every character;
- one shared real object or scene task;
- short labels only when they improve readability;
- negative constraints that prevent mascots, costumes, oversized heads, and crowding.

For a family portrait or explicit character sheet, use `Ensemble` mode and show the complete family together. For ordinary editorial images, start with one character and add others only when the content requires them.

## QA checklist

Before delivery, verify:

- the character count was routed from the input rather than assumed;
- every selected color has an irreplaceable semantic function;
- every character performs a physical action;
- the characters share one coherent real-object task;
- the capsule silhouette, eyes, limbs, proportions, and matte texture remain consistent;
- simple scenes still have enough whitespace;
- the result is Xiaohei 2.0: real objects, physical actions, quiet absurdity, and editorial restraint.

When a check fails, remove unnecessary characters before adding more explanation or decoration.
