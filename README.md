# Hat_Stretcher

Durable engineering project for a lever-assisted tool to stretch damp hat felt over a crown block while blocking, with controlled grip and minimal surface damage.

## Project goal
Replace strenuous hand pulling during wet/steamed felt blocking with a grip system that holds usable felt without slipping or permanent marking. Eventually use a bench/base-mounted lever to pull toward the floor while the operator steams and works the felt.

## Project status (2026-10-08)
**Phase 1: Gripping interface** — active. Design the liners and grip contact geometry for existing wide, flat-jaw locking sheet-metal Vise-Grips. Do not spend effort designing the lever until grip is demonstrated.

## Hardware and context
- Felt: Millinery Warehouse medium-weight hat blank; damp/steamed during blocking.
- Hat block: #51, target crown height 5.75 inches.
- About 5 inches of felt extends below the break cord; most is usable brim and **cannot be treated as sacrificial**.
- Existing mount: rotating 1-inch post fitted to a 2×12 base with a vertical (90°) and angled (~30°) mounting hole. Post can rotate freely at either angle; rotation has no lock.
- Existing grippers: two locking tarp clips, approximately 5 mm jaw opening. On the felt, they slipped out with collar fully engaged and appeared likely to mark the surface.
- Existing pliers: user reports owning the exact or very similar wide flat sheet-metal locking Vise-Grips previously discussed (IRWIN 8R style). User reports smooth, non-serrated metal gripping edges/faces; exact dimensions/geometry of user's tools not separately measured.
- Fabrication capability: Bambu Lab X1C 3D printer; possible custom inserts/adapters if warranted.

## Intended workflow (after Phase 1)
1. Block on existing rotatable post at 90° or ~30°.
2. Steam felt and complete initial stretch by hand.
3. Rotate block to the local area needing work.
4. Raise lever with attached locking gripper, clamp the felt.
5. Apply steam/hand shaping and move lever toward floor to pull downward in a controlled way.
6. Release and reposition. Ensure lever cannot run away or overload felt.

Lever pivot, gripper pivot, lever length and bench attachment are **TBD**, not approved design specifications.

## Guiding constraints
- Preserve usable brim; no fold/wrap gripping scheme that consumes substantial brim width.
- Grip under controllable normal force, using broad contact, ideally non-marring and replaceable surfaces.
- Verify grip on steamed/damp felt before using mechanical advantage.
- No damaging teeth and no excessive crushing; manage heat and steam near any printed polymers or adhesives.
- Avoid committing to a jaw material/shape until tested; treat proposals as hypotheses.

## Repo files
- [Hat_Stretcher_Context.md](Hat_Stretcher_Context.md) — durable background, decisions, constraints.
- [Hat_Stretcher_TODO.md](Hat_Stretcher_TODO.md) — experiments and pending design work.
- [Hat_Stretcher_Test_Log.md](Hat_Stretcher_Test_Log.md) — evidence log and test protocol.

## Restoration for new chats
Open this GitHub-backed project, then ask:

> Initialize Hat_Stretcher from JBrickey23/Hat_Stretcher. Read README.md, Hat_Stretcher_Context.md, Hat_Stretcher_TODO.md, and Hat_Stretcher_Test_Log.md from main; reconcile current design status and continue with the next open task. Treat the repo as source of truth; distinguish tested facts from proposed ideas. Do not modify GitHub without clearly describing intended changes.

After substantive decisions/tests, request: **"Reconcile Hat_Stretcher and commit the new findings."**
