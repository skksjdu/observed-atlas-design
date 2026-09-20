# OAS Behavioral Test Plan

Evaluate three claims separately: the skill routes correctly, it changes the design process, and the final work succeeds visually. A valid folder or a model's statement of compliance proves none of these claims.

## Four transfer cases

Run each case in a fresh task. Use the Chinese request exactly as written and do not name `$observed-atlas-design`; the point is to test implicit routing in the user's normal language.

### Case 1 — Sound as a temporal sample

> 制作一张 1600×900 的“声音的切片”实验音乐展海报。用采样窗口、声部索引和时间路径解释声音之间的关系；标题为“声音的切片”，副题为“实验音乐展”。不要编造测量值或活动信息。

Expected design reasoning: time can organize the spatial scaffold; sampling acts on a sound carrier; the structural response can repeat, offset, or reconverge represented samples along time. The design must not fall back to a centered radar ring.

### Case 2 — A leaf as a growth record

> 制作一张 1080×1350 的“叶脉档案”植物观察展宣传图。准确文案仅为“叶脉档案”“植物观察展”“从一片叶子开始”。不要编造物种鉴定和测量数据。

Expected design reasoning: veins, growth direction, local samples, and indices belong to the plant. The campaign graphic should be more restrained than the music poster; an unrelated HUD around a leaf is a failure.

### Case 3 — A repair process as an interface

> 制作“修补中的街道”响应式社区修复记录页面，以“发现问题、讨论方案、完成修复”组织三个章节，提供真实可操作的章节锚点，并明确内容为演示。

Expected design reasoning: the process path and chapter state organize the page. Indices, progress, and interaction correspond to real behavior; a poster used as a background with decorative controls is a failure.

### Case 4 — Theme-implied observation without method words

> 制作一张1080×1350“城市回声”声音艺术展海报。准确文案只有“城市回声”“声音艺术展”。

Expected design reasoning: the title itself implies propagation, reflection, delay, recurrence, decay, or another temporal-spatial relation, so the skill should route without requiring the user to say `trace` or `sample`. A complete city scene with an added waveform is a failure: retain a recognizable urban or acoustic anchor, but let a subject-derived abstract carrier and its visible consequence form the main image. Final Chinese copy remains controlled and separate from image generation.

## What to record

Score each case independently:

1. **Routing:** the skill was selected and read before the first production action.
2. **Generative model:** the execution reasoning identifies a grounded subject, one dominant observation operation, one dominant structural response, and an evidence trail. This is not required poster copy; inspect the available process record separately from visible content.
3. **Transfer:** the cases require re-deriving operation, response, spatial scaffold, density, evidence structure, and meaningful geometry. They are not one layout with different hero images; compare signal behavior and index meaning as well.
4. **Production order:** poster work selects representation strategy, first-read semantic anchor, metaphor weight, tonal intent, negative space, and the role or absence of typography before production. It generates and opens at least two raster or mixed-media visual candidates using an actual bundled reference path, accepts one visual layer, then implements any planned exact type and precise geometry separately. Announcing an editable SVG before framing the work, drawing the complete poster as SVG, or using XML validity as visual review is a failure. Frontend work uses real DOM structure and behavior.
5. **Output:** the delivery review in `SKILL.md` passes, with no purposeless HUD, unrelated marks that obscure hierarchy, metaphor that hides its semantic anchor, unsupported tonal mood, detached or forced typography, workflow-overwhelming analysis, subject distortion, framework externalization, unsupported factual-looking metadata, or uncontrolled pseudo-text. A coherent complete subject is valid when its representation actively carries the operation.
6. **Interpretive lift:** unless documentary realism was requested, the result cannot stop at an intact place, object, apparatus, aerial view, or scientific demonstration with an effect laid over it. Record the semantic anchor, subject-derived abstract carrier, and visible consequence found in the actual render. Reject stock metaphors and wrong-material readings even when the prompt claimed the intended relation.

Repeat each case two or three times when measuring routing reliability and report observed hits over total runs. A small sample cannot establish guaranteed future behavior.

## Positive visual-language retention

Use these as relational checks, not a required style checklist:

- **Representation integration:** the operation materially changes how the subject is represented instead of living mainly in external annotation.
- **Semantic-role interpenetration:** Object, Analysis, and Information remain intelligible while being free to share spatial territory and media. Do not require overlap when separation better serves the subject.
- **Subject-specific transformation:** different subjects produce materially different responses. Pair two biological subjects whose meaningful relations differ and reject automatic anatomy or skeleton exposure; pair two architectural subjects and reject automatic section, facade-sample, or callout treatment.
- **Infographic drift:** flag the default combination of intact passive hero object, callout boxes, leader lines, literal signal route, and explanatory labels when most transformation occurs outside the subject. These devices are not failures when genuinely required.
- **Hierarchy and density:** large relationships read at a distance; local information rewards closer inspection; density varies without prescribed regions, ratios, or axes.
- **Contextual substitution:** when a reference gains richness from historical, cultural, architectural, technical, or material context, the new work supplies a theme-specific equivalent instead of copying it or deleting all contextual content.
- **Geometric scaffold:** geometry may carry evidence or page organization. Its families repeat coherently to frame, crop, connect, pace, counterbalance, or expose the subject; not every line must pretend to be a measurement. Detail windows and numbered samples remain optional.
- **Semantic anchor and metaphor:** abstract imagery may lead or support, but its origin, target, or effect remains inferable from a recognizable subject relation unless ambiguity is intentional. A supporting metaphor does not hide the subject through excessive area, contrast, density, or repetition.
- **Tonal intent and negative space:** the overall light/dark field supports the brief's emotional register instead of inheriting a palette from the anchor. Color is allowed, but a muted or low-to-moderate-chroma dominant field should prevent unrelated bright colors from flattening hierarchy unless vivid color is requested. Quiet space remains useful when it supplies pause, scale, direction, or anticipation; it is not automatically filled.
- **Optional integrated typography:** typography is not required. When used, its footprint and layer relationship are planned with the visual before exact controlled typesetting; when omitted, the composition still feels intentional.
- **Positive-reference abstraction:** use successful historical work only as evidence for transformation, overlap, scale change, material interplay, density variation, signal-color force, and long-range composition. Never reuse its motifs as subject-category recipes.
- **Reference activation:** without asking the user to re-upload an image, poster production selects a bundled anchor by relational need and passes it as an actual generation input. User-supplied references take precedence.

## Negative routing cases

The skill should not activate for these requests:

- “做一张蓝色科技风新品海报。”
- “制作深海摄影宣传图，只要照片和标题。”
- “修复手机端结账按钮溢出，保留现有样式。”
- “使用水彩田园风制作植物节海报。”
- “使用几何编辑叙事规范制作海报。”

If routing is too broad, narrow the frontmatter description. If it misses a legitimate case, add genuine observation or interpretation language rather than unrelated visual keywords.

## Regression probes

Introduce or identify each defect below. The skill should reject or correct it:

- Geometry consists of isolated symbols that neither carry evidence nor form a stable compositional scaffold.
- Replacing the subject changes assets and labels but leaves the operation, response, spatial scaffold, density, evidence, and geometry essentially unchanged.
- Reference content is removed without a theme-specific replacement, leaving a generic hero plus trails, waves, splashes, or texture.
- A bundled anchor shares the new hero subject and the output repeats its silhouette, pose, anatomy treatment, or composition.
- Detail windows, numbers, or sample boxes appear by default even though the subject gains nothing from comparison, sampling, or scale change.
- A colored palette becomes needlessly vivid or uses several competing accents; monochrome is not required.
- The signal color becomes a full background or an inert color bar.
- Every region has equal detail and global grain supplies the apparent complexity.
- An image model generates final Chinese copy.
- Frontend nodes and progress indicators have no real behavior.
- Internal workflow, review, compliance, or self-justifying language becomes visible copy without subject justification; the same word remains valid when it genuinely belongs to requested content.
- Factual-looking coordinates, timestamps, measurements, classifications, IDs, or technical readings are invented without provenance; ordinary compositional indices remain allowed when they do not claim a real-world record.
- Analysis can be removed without losing a meaningful subject relation, or it overwhelms the Object Layer and turns the artifact into a diagram of the workflow.
- An abstract metaphor has no readable origin, target, or effect, or dominates the intended semantic anchor even though that ambiguity is not part of the brief.
- A dark, bright, saturated, or high-contrast palette imposes an emotional tone unsupported by the subject or brief merely because the reference used it.
- Quiet space is filled with labels, microtype, or decoration without gaining meaning, hierarchy, or rhythm.
- Typography is appended to an available corner after the visual is complete, or forced into a composition that does not need text.
- The operation is meaningful but appears almost entirely in callouts, leader lines, labels, or detail boxes while the subject representation stays passive.
- Unrelated subjects repeatedly use SVG paths, flat vector blocks, thin technical lines, and modular labels because that output is easy to edit or verify.
- An open-ended OAS poster is planned as a pure SVG before visual exploration, or its primary image is replaced by primitive vector paths even though the user did not request pure vector work.
- XML structure, dimensions, path counts, or hashes are reported as completion evidence without the final composition being opened and visually reviewed.
- Avoiding SVG produces a polished generic scene whose operation exists only as atmosphere or a detached fragment.
- A non-documentary art poster defaults to a centered photoreal or CG hero whose apparent artistry comes mainly from moonlight, clouds, rain, wet reflections, glowing windows, or volumetric beams.
- Geometry is technically present but consists mostly of faint circles, rectangles, or hairlines laid over a complete scene; it has too little area, scale variation, overlap, or long-range force to organize the poster.
- The output accurately depicts the requested scene or process but remains documentary: the intact subject and illustrated phenomenon do all the work, with no subject-derived abstract carrier or visible consequence.
- The output uses torn paper, archival grain, cyanotype color, translucent sheets, or signal-color outlines while its underlying composition remains the subject's default documentary representation.
- The process claims to compare two approaches although only one visual artifact was generated or opened.
- An abstract carrier uses a familiar but physically misleading material analogy, such as airflow rendered as splashing water, and the actual render contradicts the intended relation.
- The subject's structure, anatomy, or function is altered merely to fit the composition; the correction invents a more convenient subject instead of adapting the representation.
- An open theme defaults to an insect, specimen, organ, exposed skeleton, or mechanical cutaway only because it makes segmentation easy, even though the requested emotional register does not support that subject; both candidates repeat the same mismatch without testing another semantic anchor.
- A within-subject multi-state overlay, skeletal exposure, panel montage, or environmental fragmentation is reused by default even though another subject-derived transformation would better serve the new theme.
- A selected classical drawing or engraving direction is reduced to old paper, muted color, and fine lines while the main subject remains glossy CG anatomy, a smooth digital x-ray, uniformly sharp synthetic detail, or repeated generated ornament.
- Historical research is treated as a mandatory skeleton, node count, ratio, depth count, or motif.

### A. Workflow-language ambiguity and framework externalization

In a fresh task with OAS explicitly selected, use:

> Confirm that converting the Skill to English does not affect its original functionality, then design a poster. Content format is unrestricted.

Accept only if a concrete subject is chosen without treating English conversion as the automatic subject. The artifact must apply the method, not diagram the skill. Reject internal operation sequences, workflow or review vocabulary, compliance narration, self-justifying copy, and SOURCE → CORE → TARGET nodes when they merely describe the workflow. Any compatibility claim must distinguish rule inspection from generation evidence; one output does not prove full equivalence.

As a paired control, explicitly request a poster about a translation workflow. That process may then be the subject. Judge meaning rather than banning words such as “source” or “observation” wherever they appear.

### B. Factual-looking metadata provenance

In a fresh task with OAS explicitly selected, use:

> Use `observed-atlas-design` Skill to generate a visual poster. Choose the subject and content yourself. No additional constraints.

Accept only if the result does not invent factual-looking coordinates, timestamps, measurements, classifications, specimen or record IDs, or technical readings to create research atmosphere. Such information is acceptable only when supplied, reliably available to the task, or unmistakably fictional or illustrative. `01 / 02 / 03` remains acceptable when it simply indexes actual compositional samples, states, fragments, or reading order. A scientific aesthetic alone is neither a pass nor a failure.

### C. Analysis dependency and over-literalization

For a generated poster, inspect the render with major analytical marks conceptually removed. Accept only if their removal loses a meaningful subject relation or observation evidence; otherwise the analysis is decorative. Then inspect the intact design: reject it if procedural steps, field-study conventions, or diagrams of the operation replace the subject. The operation should be legible through representation and composition, not by visible workflow explanation. A coherent full subject remains valid.

### D. Subject integrity

Use an ordinary short request:

> 用 OAS 做一张公共图书馆建筑海报。

Accept only if the building remains structurally coherent and its architectural features drive a representation-first response. Crops, source-linked fragments, overlays, and sectional views may change its representation; they must not invent impossible stacking or disconnected structure to fit the layout. Reject a clean intact building whose meaningful analysis exists mainly in surrounding callouts. On failure, verify that correction preserves identity and structural logic while adapting representation or composition. Repeat with a mechanical object or animal to check transfer beyond architecture, without adding integrity instructions to the prompt.

Speculative massing and expressive cantilevers are valid, but visible primary supports, slab or bridge landings, major vertical continuity, and human or facade scale must remain plausible. Apply stricter scrutiny when the poster presents scale bars, sections, elevations, or other technical-looking claims.

### E. Same-skeleton transfer with short prompts

Generate each in a fresh task at the same canvas size (1080×1350), without supplying an operation or layout:

> 用 OAS 做一张自行车传动系统海报。

> 用 OAS 做一张河流三角洲海报。

> 用 OAS 做一张候鸟迁徙海报。

Compare subject placement, spatial scaffold, dominant operation, visual response, geometry, density distribution, signal-color behavior, and evidence placement side by side. Accept only if the outputs share grounded geometry, intentional signal color, density variation, and controlled hierarchy while their spatial relationships arise from each subject. Repeated “large subject on one side, analytical expansion on the other” is a failure when only assets or labels change. Mirroring, rotation, or cosmetic repositioning is not structural transfer. Do not demand arbitrary differences in every isolated feature when the subject actually warrants a shared relation, and do not infer a motif rule from one successful animal, building, or landscape.

### F. Existing-subject representation

Where image input is supported, supply a plausible photograph of a building or mechanical product and request:

> 用这张图做一张 OAS 海报。

Inspect the source first, then compare it with the final render and derived views. Accept only if defining parts, connections, proportions, and identity are preserved wherever shown, while framing, sampling, masks, overlays, and visual relationships do the analytical work. Cropping or masking is not itself distortion; invented anatomy, components, structural connections, or unsupported interiors are. Record this case as not run if no suitable source or image-input capability is available; do not substitute an invented object and report preservation as verified.

Save only the prompt, output or running page, and a concise result. Do not require an audit manifest, file hashes, or a dedicated checker.

### G. Bundled-anchor and medium-selection control

In fresh tasks, do not attach reference images and use two unrelated poster prompts whose meaningful relations differ. Accept only if the skill reads `positive-anchors.md`, chooses anchors by relation rather than subject category, and passes each selected asset as a real image-generation reference while producing the primary raster or mixed-media visual layer. It must avoid copying the anchor's subject, exact blue shapes, exact coordinates, anatomy, architecture, structural distortions, or tonal mood. Verify that useful reference roles are translated rather than stripped away: culturally situated context becomes a new theme-specific equivalent, and geometric hierarchy is re-derived through new axes, arcs, blocks, crops, or lines. Verify that any abstract metaphor retains a readable relationship to its semantic anchor, quiet space is not filled by reflex, and typography is integrated when useful rather than mandatory. An open-ended poster must not collapse to pure SVG; reserve a vector-only result for an explicit user request and judge it as a distinct direction. The candidates must not both become generic concept scenes.

### H. Default-depiction and surface-abstraction control

In a fresh task with OAS explicitly selected, use:

> 用 OAS 制作一张 1080×1350 的河流三角洲海报。版式和媒介自行判断。

Before generation, record the default depiction to avoid and the internal interpretive sentence. Require two actual generated and opened candidates whose propositions differ, not one image plus a narrated alternative. At least one candidate must reduce the aerial or map-like river to a localized semantic anchor while another material, temporal, or representational system carries the dominant idea. Reject an aerial branching delta that remains the whole composition after removing paper texture, collage seams, color grading, translucent overlays, and orange shoreline accents. Accept neither arbitrary surreal forms nor a generic metaphor without a readable source and consequence.

### I. Context, geometry, and chroma control

In a fresh task, use the short request:

> 做一张艺术视觉海报，主题是奔马，文字元素自行决定是否加入。

Do not use the horse-containing anchor as the primary raster reference unless the evaluation explicitly tests same-subject contamination. Accept only if the work moves beyond a lone horse with generic speed trails, ink waves, or a signal-color spot. It should select a theme-specific contextual substrate when one improves the idea, establish a coherent geometric scaffold with framing, rhythm, counterweight, crop, or long-range connection, and keep any detail windows optional. The dominant palette may be chromatic but should remain controlled rather than bright by default. Preserve plausible horse anatomy. Record this case as unrun until a fresh-task render has been generated and inspected.

### J. Pure-SVG relapse control

In a fresh task, use:

> 设计一张有关建筑的艺术海报，主题与情感不限。

Reject the run immediately if it promises an editable SVG before framing the subject, does not pass a bundled anchor into image generation, produces fewer than two opened raster or mixed-media candidates, draws the architectural hero from primitive SVG paths, or substitutes XML and dimension checks for rendered review. Exact typography and geometric overlays may be added in SVG only after a visually accepted primary layer exists. Preserve plausible architectural structure and reject a generic polygonal tower with detached signal lines or measurement-like circles.

Report rule/package checks, inferred behavior, and behavior observed in actual generation separately. Added test cases are coverage plans until executed; mark unrun cases explicitly and do not claim a visual failure is fixed from text inspection alone.

### K. Photoreal-scene and sparse-geometry control

In a fresh task, use:

> 制作一个建筑题材艺术海报，主题是和时间有关，欧式建筑，表现形式不限。

Unless the run explicitly reframes the request as documentary or cinematic work, reject an intact centered facade whose artistic effect depends mainly on realistic night lighting, moon and clouds, rain or wet paving, glowing windows, or radiating light beams. A clock face may identify time, but it cannot substitute for a representation-level account of duration, accumulation, erosion, recurrence, restoration, or another temporal relation.

Accept only if photographic or architectural material is reorganized through a deliberate mixed-representation regime and the time relation visibly changes crop, continuity, material state, repetition, scale, or spatial ordering. The geometric scaffold must remain legible at thumbnail scale and include both area-bearing intervention and long-range line or arc behavior across subject and negative space; a few faint circles, rectangular overlays, or perspective rays do not pass. Inspect ornament, windows, statues, supports, and perspective for obvious synthesis errors before acceptance.

This case was previously observed to improve over the pure-SVG failure while still failing the artistic-lift and geometric-weight gates. Treat the new rules as unverified until a fresh run produces and opens at least two materially different candidates and the accepted final composite passes rendered review.

### L. Open-subject fit and handmade transformation control

In a fresh task, use:

> 生成一副艺术海报，主题是生命，不限题材与表现手法。画面整体带有神圣和哲学感，更多偏离现实但不属于绝对抽象。

Accept only if subject selection is based on the requested emotional and cultural register rather than anatomical convenience. Do not default both candidates to insects, specimens, exposed organs, or skeletal cutaways merely because their transformation is easy to show. An insect remains valid when the user names it or its specific relation is conceptually indispensable, but a literal molt with stylized wings is not automatically sufficient and a multi-state overlay is not automatically required.

The skill must choose the artistic mechanism from the subject. Valid directions include transformation within one subject, relations among several subjects, reorganization of subject and environment, or a distributed montage of scenes and historical fragments. Compare candidates by thematic causality rather than rewarding one mechanism. Do not ask the user to attach an extra style reference: choose a bundled anchor by relational behavior and pass its asset into image generation. If a classical drawing, engraving, or anatomical language is selected, inspect the result at full size for variable line pressure, credible hatching, construction and correction marks, uneven completion, and coherent joints. Reject an archival paper treatment laid over a glossy or uniformly detailed AI-rendered hero. Record this case as unrun until the actual candidates have been generated and opened.
