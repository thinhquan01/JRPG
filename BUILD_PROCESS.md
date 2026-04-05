# BUILD_PROCESS.md

## Build loop
1. Read `GAME_VISION.md`, `VOXEL_POC_SPEC.md`, `DECISIONS.md`, `ACTIVE_TASK.md`, `TEST_NOTES.md`, and `DONE_CRITERIA.md`.
2. Complete only the currently active task.
3. Write real files.
4. Run and verify the current pass where possible.
5. Update `TEST_NOTES.md` with:
   - what was tested
   - what worked
   - what broke
   - what is still unverified
6. Replace `ACTIVE_TASK.md` with exactly one next small task.

## Anti-drift rules
- Do not redesign the whole project mid-pass.
- Do not add unrelated systems because they seem useful later.
- If blocked, reduce scope and still ship a smaller working result.
- Prefer the smallest honest playable over a larger speculative one.
