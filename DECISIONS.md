# DECISIONS.md

## Current decisions
- The project starts as a sandbox-first toybox, not an RPG-first game.
- The first milestone is a voxel-collapse proof of concept.
- The prototype should use the fastest sane stack for the machine, not the fanciest stack.
- The goal is to test the hook, not to imitate Minecraft feature-for-feature.
- RPG or action layers are deferred until the sandbox loop proves itself.
- The first playable should be small enough to verify quickly and discard quickly if it feels bad.

## Decision rule
Every added system must answer one of these:
- does it directly strengthen the core hook?
- does it make the prototype easier to evaluate?
If not, it does not belong in the current phase.
