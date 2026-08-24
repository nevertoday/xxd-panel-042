# XXD Panel 042 | Isometric Structural Watercolour Study Production Prompt

## Runtime complete-canvas contract — highest priority

- `TOP_BOTTOM` and `LEFT_RIGHT` default to one complete finished generation using the current source as a high-fidelity edit/reference input. Do not pre-split the job into photographic and design halves.
- Top-bottom keeps the faithful source in approximately the upper 50% and performs this style transformation below; left-right uses the faithful source in approximately the left 50% and the transformation on the right. Unify both regions through colour, light, rhythm, typography, and meaning.
- `DESIGN_ONLY` and `WALLPAPER_PACK` use the complete canvas while the source remains an invisible identity/content reference. Recompose every wallpaper separately for its device.
- `FINAL CANVAS` means the ratio/pixels of the whole finished artwork and must be explicitly resolved before generation; never apply source dimensions silently. `DESIGN FRAME` is used only if a failed complete-canvas retry triggers deterministic composition fallback.
- Retry a failed complete canvas once against the failed constraint only. Scripted composition is allowed only after that retry still fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless pixel calibration.

### Model priority and credentials

- **Prefer GPT Image 2.** When GPT Image 2 is available through the current built-in image tool or a configured compatible route, use it first for the high-fidelity reference/edit and complete-canvas generation required by this prompt.
- Also support Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model only when the actual route can preserve the source, realise the whole finished canvas, render the target-language text, and accept the multiple references needed by a linked wallpaper pack.
- An alternative model changes only the generation route. It must not change this prompt's modes, canvas, source visibility, copy, locale, wallpaper relationship, or complete-canvas-first / composition-fallback-only logic. Do not silently downgrade a hard requirement.
- If no suitable route is available, ask the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task, but never echo, display, log, or expose their value in chat, prompts, or diagnostics. Do not persist them or modify global route configuration unless explicitly requested.
- Judge availability by actual image capability, not by a provider name or one missing environment variable.

Process only the source photograph explicitly supplied for this fresh task. Privately lock identity, structure, pose, direction, action, function, opening, relation, emotional implication, and source colour. Preserve at least three source-specific cues and never borrow from another input, old output, or sample.

## Aesthetic transformation

Analyse the source's real axis, viewpoint, foreground–middle–background relation, scale clues, defining features, and colour, then separate it into two to five meaningful, reassemblable structural layers rendered as a precise yet warm watercolour study.

Use this causal sequence: audit original viewpoint and structure → lock 3–7 defining features and 4–6 main colours → identify one stable base or anchor → separate only 2–5 meaningful complete layers along real axes → preserve shared centre and moderate spacing → render clear line plus translucent watercolour on ivory paper → add restrained structural annotations.

## Hard visual requirements

- The source is the only evidence. Preserve identity, overall contour, proportion, original observation direction, symmetry/asymmetry, key component relation, defining detail, material colour, and scale cues.
- Separate only two to five meaningful complete layers or components along real axes with moderate even spacing and one stable, detailed base or anchor that lets the viewer mentally reassemble the subject.
- Buildings and objects may separate by roof, floor, shell, frame, base, module, or connector; spaces by depth layers. People, animals, and plants stay bodily complete and are never dissected or mechanised.
- Use warm ivory watercolour paper, clear controlled line, translucent washes, paper tooth, fine brushwork, a few structural guides, and clean source-derived colour.
- Keep professional editorial restraint and generous whitespace; avoid dramatic explosion, arbitrary fragments, technical UI, or engineering-manual density.

## Copy and locale

Obey the resolved automatic, exact-user, or text-free copy mode and target locale. Use one concise identity, theme, action, state, or symbolic title with only supported structural markers, material words, state words, or micro-notes. Numbers appear only when supplied or reliably established. Align native type to real axes, layer direction, whitespace edges, or annotation points. Preserve exact user wording verbatim. In text-free mode render no letters, numbers, captions, labels, or pseudo-text.

## Mode and acceptance


Reject: template exploded view, invented internal structure, dramatic fragmentation, anatomy or dismemberment, mechanical conversion of living subjects, technology UI, heavy rendering, cheap CG, cartoon axonometric view, ordinary poster title, engineering manual. Also reject logos, watermarks, swatches, UI, device mockups, unsupported facts, fake foreign text, and unreadable copy.

If any hard condition fails, correct the generated bitmap. Never fake the artwork with programmatic drawing, SVG, HTML, Canvas, 3D code, or a post-composited type overlay.
