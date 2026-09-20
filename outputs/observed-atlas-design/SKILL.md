---
name: observed-atlas-design
description: "Create, revise, or critique Observed Atlas System (OAS) posters, campaign graphics, key visuals, and visual frontends. Use when the user names OAS, requests an observational act, or gives an open-ended visual theme whose meaning depends on a transformable relation. Build a subject-grounded interpretation, controlled typography when needed, and a rendered review. Do not trigger from generic requests for geometric, technical, or HUD-like styling alone."
---

# Observed Atlas System

Interpret a subject by transforming its representation. The goal is a causal editorial image—not a literal subject surrounded by analytical decoration.

When the skill first applies, state why in one sentence and proceed. Ask only for missing information that would materially change the result.

## Routing

Apply OAS when the user names it, requests an operation such as tracing or sampling, or gives an open-ended theme whose meaning implies a relation that can drive the image. Infer that relation from the theme; the user need not supply method vocabulary.

Do not apply it to a plain style request, a fully specified documentary treatment, a routine UI or copy edit, a pure scene illustration, or work explicitly assigned to another visual language.

## Core model

Define one internal causal sentence:

> **subject → observation operation → structural response → evidence trail**

For expressive work, also define:

> **This is not primarily an image of the subject; it is an image of a relation or state change happening through the subject.**

Keep these sentences internal unless the user requests a concept statement. The second sentence must express a theme-specific tension, transition, force, interval, memory, or paradox—not list visible parts of the subject.

Build three coupled visual roles:

- **Semantic anchor:** enough recognizable subject material to orient the viewer.
- **Abstract carrier:** a subject-derived representation of the relation that cannot be photographed directly.
- **Evidence consequence:** a visible effect that connects the carrier back to the anchor.

The carrier may translate the relation across material, scale, time, or representational regime. It must inherit behavior from the subject; free decoration, a stock metaphor, or a stylized repetition of the same literal matter is insufficient.

Two optional roles may deepen a poster when the subject supports them:

- **Contextual substrate:** theme-specific cultural, historical, architectural, technical, or material fragments that give the subject a situated world. When transferring from a reference, replace its context with an equivalent for the new subject instead of deleting all concrete context.
- **Compositional scaffold:** a limited family of axes, arcs, blocks, frames, crops, or lines that creates hierarchy, counterweight, rhythm, tension, and long-range connection. It may organize the page without pretending to be scientific evidence.

## Subject and transformation choice

For an open-ended brief, choose the subject for emotional, cultural, and thematic fit before considering how convenient it is to segment, expose, or annotate. Prefer a subject whose silhouette, history, material, anatomy, or use can sustain the intended relation and mood. Do not default to insects, specimens, organs, machinery, exposed anatomy, or another easily analyzed object merely because its parts make the method visible. If a subject is likely to read primarily as clinical, entomological, repulsive, or novelty imagery, use it only when the user names it or when its specific relation is indispensable to the concept.

Derive the artistic distortion from the selected subject rather than importing a stock surreal effect. Time might warp, repeat, erode, or misregister a clock or building; mortality might let an animal pass from living contour into a hand-drawn skeletal study. Re-derive an equivalent transformation for every new subject. Bones, transparent cutaways, roots, wings, melting, and fragmentation are not universal shorthand.

When the requested tone is sacred, philosophical, or uncanny without becoming fully abstract, do not prescribe one structural trick. Determine where transformation belongs from the theme and subject: within one subject, between several subjects, in the subject–environment relation, or across a distributed field of scenes and fragments. Impossible coexistence, sequential panels, interrupted continuity, scale shifts, and material or representational changes are options rather than requirements. Keep enough recognizable content and theme-specific causality for the work to remain interpretable.

## Representation rules

- Preserve identity and essential anatomical, structural, topological, functional, and causal relationships. Transform representation, not ontology.
- Name the subject's familiar default depiction before production. Unless the brief requests that mode, keep it only as a reduced anchor rather than the whole composition.
- Surface treatment is not abstraction. Texture, collage seams, color grading, translucent overlays, and signal-color edges do not create interpretive distance when the default depiction still organizes the image.
- Unless documentary or cinematic realism is requested, treat a polished photographic or CG scene as source material rather than the finished spatial logic. A centered intact hero, dramatic weather, moon or cloud backdrop, wet reflective ground, volumetric rays, and warm window glow may create atmosphere, but they do not by themselves create an editorial or artistic transformation.
- Make the operation alter the subject representation before relying on labels, callouts, or evidence marks.
- Give every major geometric or signal-color element either a readable evidential role or a consistent compositional role. Geometry does not need a one-to-one scientific meaning, but it must form a deliberate system rather than simulate observation with generic HUD motifs.
- When geometry is an important part of the selected visual language, use both area-bearing geometry and line-based geometry: planes, blocks, masks, crops, or stepped fields must alter silhouette, overlap, depth, or negative space, while axes, arcs, or long lines establish direction and distant connection. A few hairline overlays on an otherwise complete scene do not count as a geometric scaffold.
- Keep metaphor readable through its origin, target, or consequence unless deliberate ambiguity belongs to the brief.
- When the subject has anatomy, mechanics, or load-bearing structure, preserve its defining connections and scale. Expressive recombination may exaggerate space, but must not introduce accidental dislocations, unsupported assemblies, or convenient invented interiors.

## Medium and composition

Choose representation strategy and production medium from the relation. For OAS posters and key visuals, the primary visual layer must be generated or assembled from raster, photographic, scanned, collage, or mixed-media material. Do not build the whole poster directly from primitive SVG paths, flat vector blocks, and text: that medium cannot reproduce the reference system's image depth, material variation, and interpenetration. SVG, HTML, CSS, or another deterministic layer may add exact typography, masks, geometric scaffolds, and final compositing only after the primary visual layer has been generated, opened, and accepted. Use a pure-vector or diagrammatic direction only when the user explicitly requests it; treat that as a different visual outcome rather than the default OAS poster style.

Raster does not mean photorealistic by default. For expressive work, choose a representation regime—such as print, engraving, drawing, scan, collage, flattened photography, material transfer, or a deliberate hybrid—and let it govern edges, depth, lighting, and surface. Photographic material may remain recognizable, but it must not automatically become a seamless cinematic scene with realistic illumination as the main source of visual interest.

When the chosen direction needs the credibility of classical drawing, engraving, anatomical study, or another visibly handmade process, preserve that production logic rather than only applying old paper, muted color, or geometric marks. Use variable line pressure, cross-hatching, construction lines, corrections, erasures, incomplete contours, and uneven detail where appropriate. Render structural or skeletal transitions as drawn studies when that is the selected mechanism, not as glossy CG anatomy, smooth digital transparency, or an x-ray effect under an archival filter.

For posters and key visuals without a user reference, read [positive-anchors.md](references/positive-anchors.md). Select one primary anchor by relational behavior and pass the asset as an actual image-generation reference when producing the primary visual layer; a prose description is not a substitute. Do not expect the user to re-upload a style reference already represented by the bundled anchors, and do not evade reference activation by choosing a code-drawn SVG.

Resolve large relationships before local notation:

- Decide what registers first: anchor, carrier, or intentionally ambiguous event.
- Let density rise and fall; give quiet space a role.
- Let the carrier organize the composition while the anchor remains sufficient for meaning.
- Derive tonal field and signal-color behavior from the intended relation and mood. Color need not be monochrome, but unless the brief requires vivid color, keep the dominant field low to moderate in chroma and prevent several bright colors from competing.
- Design geometry as a small set of related families with repeated behavior across the page. Give the system visible weight at thumbnail scale and distribute it across more than one scale: an area-bearing family should frame, mask, crop, interrupt, or counterbalance, while a line-based family may pace, connect, or expose the subject across distance. Geometry should enter the subject and negative space rather than sit only on top of them; detail windows and numbered samples are optional, not defaults.
- Use contextual material only when it strengthens the subject's world or tension. Do not default to European, archival, technical, or historical imagery; choose an equivalent specific to the new theme.
- Plan typography with the composition, but implement exact text separately and editably. Do not ask an image model to render final copy or pseudo-text.

## Poster and key-visual workflow

1. **Frame.** Establish the subject, why it fits the theme and emotional register, causal and interpretive sentences, default depiction to avoid, medium, mood, tonal range, geometric scaffold, useful contextual substrate, and role or absence of typography. Reject a convenient but emotionally mismatched subject before production.
2. **Explore.** For an open-ended poster, generate at least two actual text-free raster or mixed-media artifacts with different interpretive propositions or abstraction strategies. Open both before comparing them. When the subject is also open, do not lock both candidates to the first conveniently analyzable organism or object; compare subject fit and, unless one subject clearly carries the brief, vary the subject or semantic anchor as well as the visual treatment. When realism was not requested, at least one candidate must visibly break continuous photographic scene space through segmentation, flattening, material transfer, collage, drawing, print, or another representation-level transformation. A camera-angle or lighting variation, code-drawn SVG plan, prompt description, imagined alternative, or unopened file does not count as a second proposition.
3. **Build.** Describe the anchor, carrier, coupling rule, evidence consequence, contextual substrate when useful, geometric system, and default depiction to avoid. Keep literal subject material localized enough that it does not reclaim the whole image.
4. **Typeset.** After accepting a visual layer, add accurate, independently editable text and any precise geometric overlays only when they improve meaning, hierarchy, rhythm, or identity. This is the appropriate role for SVG or another deterministic layout medium.
5. **Review the render.** Open the final artifact at target size and inspect it at thumbnail scale, in grayscale, and with labels, callouts, surface effects, and cinematic lighting conceptually removed. Confirm that the representation change and geometric scaffold still organize the image, and inspect repeated architectural, anatomical, or mechanical details for obvious synthesis errors. Reject failed work instead of selecting the least-bad candidate or adding annotation.

Do not create audit artifacts merely to prove that stages happened. Deliver the final output, editable source when relevant, and concise review conclusions.

## Acceptance gates

Accept only when the actual render supports all relevant claims:

- The subject–operation–response–evidence relation remains legible without explanatory copy.
- The selected subject supports the requested emotional and cultural register; it does not read as a convenient specimen, anatomy carrier, or novelty choice that the theme never required.
- The work has interpretive lift: after removing title and surface styling, it is not merely the subject's default documentary, stock, or scientific representation.
- The artistic treatment is re-derived for the subject. A within-subject state change, a relation among several subjects, a subject–environment transformation, or a distributed narrative field can all pass; none is mandatory. Reject a device whose main justification is that it worked for a previous subject.
- Unless the brief requests documentary or cinematic realism, the work does not depend on a seamless photoreal scene, dramatic sky, weather, reflections, or glowing light as its primary artistic claim. Photographic material is reorganized across representation, scale, material, or geometry.
- The abstract carrier has a readable source and consequence and does not impersonate an unrelated physical material.
- The subject remains coherent; abstraction has not invented anatomy, structure, components, or unsupported interiors.
- When handmade or classical reference craft is part of the selected language, the subject remains credible at full size: line weight, hatching, underdrawing, correction, and incompleteness feel authored rather than uniformly synthesized. Reject glossy surfaces, smooth CG cutaways, repeated veins or ornaments, fused joints, and equal edge sharpness disguised by archival texture.
- Hierarchy, density variation, negative space, tonal mood, geometry, and signal color reinforce the relation. The palette may be chromatic, but uncontrolled vividness must not flatten the hierarchy.
- Major geometry has a stable evidential or compositional job; removing it would weaken framing, rhythm, scale, counterweight, connection, or interpretation. When geometric organization is central, it includes visible area-bearing structure and long-range connection at multiple scales, not only sparse hairlines or isolated circles. Optional detail windows appear only when comparison, sampling, or scale change benefits the subject.
- Contextual fragments, when used, are specific to the new theme and contribute history, place, material, or cultural tension rather than acting as borrowed scenery.
- The primary visual layer is not a primitive-only SVG substitute for image generation unless the user explicitly requested a pure-vector result. XML validity, editable paths, or structural checks do not establish visual acceptance.
- Removing major analysis would lose meaningful evidence; the analysis does not overwhelm the subject or externalize the workflow.
- Visible copy belongs to the subject, not to internal methodology or self-justification. Factual-looking metadata is sourced, reliably available, or unmistakably illustrative.
- Different subjects require re-deriving the operation, carrier, scaffold, density, evidence, geometry, and medium—not swapping assets in one template.
- The final composite was rendered and viewed. Structural checks, hashes, or a stated intention do not prove visual success.

When a gate fails, correct the earliest failed decision. Do not repair literalism with more texture, arbitrary surrealism, generic geometry, or labels.

## Frontend work

Translate the relation into real information architecture and behavior. Paths, nodes, frames, progress, and signal color must correspond to actual content or interaction. Use real DOM text and accessible controls; decorative notation must not impersonate functionality. Test desktop and narrow layouts, keyboard focus, and key interactions.

## References

- For poster production without a user reference, read [positive-anchors.md](references/positive-anchors.md).
- For historical provenance during a deep audit, read [design-language-spec.md](references/design-language-spec.md). It is non-normative unless a rule is promoted here.
- For implicit routing, transfer, or regression testing, read [test-plan.md](references/test-plan.md). Do not load it during ordinary production.
