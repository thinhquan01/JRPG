# VOXEL_POC_SPEC.md

## Proof-of-concept goal
Prove the hook with the smallest honest prototype.

## Required features
- first-person movement
- one tiny voxel chunk only
- place block
- remove block
- unsupported blocks fall
- one or two rotatable block types
- visible block rotation/orientation on placement
- reset world button

## Success criteria
The prototype is successful if:
- placing/removing blocks feels responsive
- removing support causes local structural collapse in a believable way
- rotation is visibly meaningful, not cosmetic nonsense
- it is fun to mess with for 5 to 10 minutes with no external goals

## Build order
1. movement + tiny voxel chunk + place/remove
2. gravity/support logic
3. rotatable blocks
4. reset + small polish

## Scope guardrails
Do not add:
- open world streaming
- procedural generation beyond a tiny test area
- crafting or inventory systems beyond bare minimum selection
- NPCs, enemies, quests, lore, dialogue
- multiplayer or save systems unless trivial and needed for the POC
