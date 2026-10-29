# Canvas Tray Frames: Cowork review handoff

This is a dated, read-only evidence snapshot authorised by Philip for public disclosure, including supplier photographs. It is not an app deployment, installation or product change. Start at ../manifest.json. All asset paths in JSON are relative to the repository root. Source attribution URLs are not download dependencies.

## Section 7 — review procedure

1. Load each candidate GLB, its extracted textures and its own supplier images from this cloned repository. The GLBs also embed their textures.
2. Check the agreed rules: material response follows appearance; colour-picked versus photo texture is appropriate; no upscaling, baked edges or broken stripes; repeat length is plausible; profile agrees with the appropriate Larson-Juhl dimensions.
3. Render front, back and close-up views against the supplied reference evidence and approved prototypes. Record camera and lighting conditions. Inspect both Draco delivery and decoded copies where useful.
4. Report findings and suggested fixes per moulding, with exact version/hash, evidence, confidence and severity. Send fixes back to Replit Agent only for unapproved models within the hard rules. Do not edit files or approve models here. List observations about approved versions separately as flags, not authorised corrections.

## Approval and scope rules

- approved/ contains current approved delivery identities; candidate/ contains current versions without matching appearance approval; archived/ contains only superseded historically approved deliveries. Archived does not mean currently approved or a correction target.
- Profile approval and appearance approval are independent. A family shape approval never approves all colour siblings.
- Current MLDA4015 black and MLDA4016 ivory distressed-driftwood replacements require appearance re-approval. Philip specifically authorised those replacements, preserving the profile and archiving older deliveries. This does not authorise changing other approved models.
- MLDA1864 warm ivory is approved and protected. Its earlier comparison remains a separate version.
- Two-tone finishes remain excluded from automatic single-material correction. An older excluded study may still be present in the complete review inventory; inclusion is not approval.
- No app publishing, production changes, Shopify/product changes, flag changes, deletions or installation. The sole publishing exception is this dedicated public evidence repository. No automatic inbound sync or GitHub Actions.

## Profiles, dimensions, geometry and hardware

- These are empty made-to-order canvas tray frames; the customer provides a stretched canvas. Any sample canvas/artwork in a GLB is demonstration geometry, not merchandise.
- Larson-Juhl own-colour specification tables take precedence over conflicting rounded supplier summaries. Preserve approved profile geometry and record disagreements rather than stretching a model to fit labels.
- lipDerived = itemWidth minus rebateWidth. floorThicknessDerived = itemDepth minus rebateDepth. faceWidth is reference only, not a replacement for the derived lip. Supplier dimensions, fitted drawing targets and actual outline coordinates are separate evidence. No independent contour measurements were regenerated for this export.
- Dimension-drawn profiles and intentionally shaped/photo-derived profiles have different provenance. Do not mistake finish boundaries, trace noise or small chips for deliberate retaining lips. Intentional slopes/shoulders must not be flattened. Typical exposed-edge rounding is approximately 1 mm with 2–3 facets unless the evidence supports another radius.
- Check canvas clearance, lip, floor, corners/mitres and the back construction against the exact supplied model/profile. Do not invent a universal gap or depth where the record does not specify one. Dual-depth profiles require the recorded orientation.
- Preserve the existing pine stretcher construction and strap hardware. Check their orientation, texture scale and placement in front/back views. Do not substitute generic hardware or rewrite geometry to hide a material issue.
- GLB scene units are metres. Manifest dimensions and canvas sizes are millimetres. Canvas width/height are not moulding section width/depth.

## Textures

- Use each moulding/colour own photographs; never substitute a sibling colour. Supplier files are the original cached downloaded bytes, not necessarily original camera-resolution photographs.
- No upscaling. A low-resolution source is a limitation, not permission to invent recovered detail. Calibration from a transverse face applied along the rail is advisory where the square-on assumption is unverified.
- Preserve real wood grain, distressing, ageing or pattern. De-light source lighting without turning deliberate surface detail into a flat colour. Use native stitched repeat textures; inspect continuity, offsets, baked outlines, edge contamination and visible repeat seams.
- Plain paint/lacquer without real pattern uses one colour sampled from the median of its own evenly lit de-lit crop, not a photo-textured surface.
- Metal photographs are not metal albedo. Use a declared clean typical metal base; the photo may supply only subtle variation or genuine pattern. Do not retain grey mottling as the base for clean silver.
- Micrograin, brushed lines and orange peel may be declared synthetic normal detail. They are not recovered photographic relief. Albedo/normal files here are extracted byte-identically from actual GLBs; allMaterialTextures includes supporting materials. Empty tray texture lists can be correct for a flat base colour or no normal.

## Finish presets — intended rules, not a claim every historical asset complies

| Appearance | Metallic | Roughness | Coat / coat roughness | Colour and normal |
|---|---:|---:|---|---|
| Natural/raw/wood veneer | 0 | 0.75 | 0 | Own wood photo; subtle wood detail |
| Stained wood | 0 | 0.6 | 0 | Own wood photo; subtle wood detail |
| Foil wood | 0 | about 0.55 | 0 | Own wood photo; no metallic foil brushing |
| MLDA4015 / MLDA4016 distressed driftwood | 0 | 0.6 | 0 | Own de-lit stitched photo; wood micrograin strength 0.15 |
| Plain matte paint | 0 | about 0.7 | 0 | Colour-picked flat base; no wood micrograin |
| Plain satin | 0 | about 0.5 | 0 | Colour-picked flat base unless real texture/pattern |
| Plain lacquer/gloss | 0 | 0.3 | 1.0 / 0.05 | Colour-picked; subtle orange peel on base and coat |
| Metal appearance | 1 | about 0.3–0.4 | 0 unless evidenced | Clean metal base; longitudinal brushing for metal foil |
| Metal leaf | 1 | about 0.25 | 0 | Clean appropriate metal base |
| Aged/distressed metal | 1 | about 0.45 | 0 | Preserve real pattern, not baked lighting |

Metallic is decided by metallic appearance/colour attributes (silver, gold, champagne, pewter, bronze, brass, copper, steel, gunmetal, leaf, gilt, metallic), not the manufacturing word Foil or Paint. Black foil and oak foil are not inherently metallic; silver Paint is metallic. Typical sRGB metal bases: silver 200/200/205; champagne 222/201/160; gold 212/175/90; pewter 150/150/150. Brushing follows rail length. Lacquer orange peel is subtle (approximately 0.5–1 degree mean tilt) and physically scaled.

The requested colourMode vocabulary only includes photo-texture and colour-picked. A declared clean-metal constant is neither: such records use null with a reason and identify the actual representation separately. Do not misclassify these as missing colours.

## Delivery and evidence interpretation

- delivery.glb is the unchanged original delivery. decoded-from-delivery.glb is a separate Draco decode, NOT a canonical high-precision source; lost quantisation precision is not restored. Geometry attributes, indices, transforms, core material factors and referenced albedo/normal image bytes were compared after decoding.
- delivery.usdz is copied unchanged. USDZ read-back verifies shader/texture values, not appearance on an iPhone. Neither file compliance nor a browser render certifies physical-device AR scale/placement.
- Textures have not been resized/re-encoded; compression history remains whatever the original delivery contained. Archive files remain byte-identical.
- Nulls have per-field reasons. liveOnShopify was not queried. lineContinuity has no independent current-version measurement and needs visual review. Do not fabricate PASS results.
- Four own-reference LJ _2 section images are absent: MLDA1866, MLDA3240, MLDA4039 and MLDA4040. Missing imagery is not replaced with another reference.
- checksums/index.json points to small checksum partitions; all JSON records are under 100 KB. Original supplier URLs are attribution only. No credentials, approval free-text notes or application source are included.

## Suggested findings format

For each finding: eframeCode, family, immutable version/hash, current status, camera/view, evidence file, issue, severity, confidence, suggested fix and unresolved evidence. Separate measured facts from visual inference. Approved-model concerns go in a distinct flag-only list.
