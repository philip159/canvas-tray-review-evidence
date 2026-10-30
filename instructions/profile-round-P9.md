# CT-23 / MLDA2961 — P9 plain-L candidate

## Change

Philip: “the bottom face is angled still, it should be flat.”

New profile: **CT-23 P9-59347e10c16f4bc1**. The provisional P1 rear/bottom slope is removed completely. Its six-corner skeleton is `(0,0), (51,0), (51,45), (10,45), (10,70), (0,70)` mm. The bottom face is horizontal and square to the back.

Exact Larson-Juhl virtual datums: Item Width **70**, Item Depth **51**, Rebate Depth **41**, Rebate Width **25** mm. Derived lip 45 mm; floor thickness 10 mm.

All six structural runs are axis-aligned; all six structural turns are 90°. Each corner uses a 1 mm radius approximated by three facets. Rounded-corner chords necessarily include diagonals; the orthogonality requirement applies to the six structural runs, not those explicitly grouped chords.

Checks passed: explicit closure, counterclockwise winding, no self-intersection/backtracking, exact outer envelope, six orthogonal structural edges and no long-edge turn below 20°.

## New model — no approval

**MLDA2961-P9-465427a37f66a11b**, 400 × 500 mm, built on the P9 profile.

The P6 finish plan and exact texture source were reused without retuning. Comparison against the actual P6 delivery verifies identical material JSON, texture/sampler bindings and SHA256 of every embedded image. Geometry is intentionally different.

Direct USDZ read-back passes. Native-file compliance passes for the new delivery. A real phone appearance check remains required; no phone pass is claimed.

## Paths

Evidence repository:

- `profiles/CT-23/P9-59347e10c16f4bc1/outline.json`
- `profiles/CT-23/P9-59347e10c16f4bc1/section-overlay.png` — P9 green over the original calibrated photo
- `profiles/CT-23/P9-59347e10c16f4bc1/old-new-overlay.png` — P1 grey / P9 green
- `candidate/MLDA2961/P9-465427a37f66a11b/` — GLB, decoded preview, USDZ, construction/material checks and parity record

Workspace evidence: `generated-artifacts/canvas-profile-texture-P9/`.
Model registry entry and immutable review assets were appended in development. P1/P6 and their original assets and decisions remain unchanged.

## Review URLs

On the running development origin:

- `/canvas-tray-review#profile-CT-23`
- `/canvas-tray-review/phone-check#profile-CT-23`
- `/canvas-tray-review?ref=MLDA2961-P9-465427a37f66a11b`
- `/canvas-tray-review/phone-check?ref=MLDA2961-P9-465427a37f66a11b&variant=MLDA2961-P9-465427a37f66a11b-400x500`

P9 is the newest CT-23 profile on both pages. P1 remains in the closed **Superseded versions** section. The new MLDA2961 model is first in the model registry and selected as the phone page's current MLDA2961 candidate. P6 remains available in the main review's model selection.

## Boundaries

No approvals or rejections, no deletions, no installation or publication, and no production, Shopify or flag changes. AR_USD_DIRECT untouched. Evidence repo publication is source/evidence sharing only, not application publication.
