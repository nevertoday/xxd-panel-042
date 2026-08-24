<p align="center"><img src="./assets/banner.svg" alt="XXD Panel 042 project banner" width="1200"></p>

<div align="center">

# 🦁 XXD Panel 042

### Let real structure unfold as a reassemblable watercolour study

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-000000?style=flat-square)](./SKILL.md)
[![Modes](https://img.shields.io/badge/Modes-4-C96F5A?style=flat-square)](#)
[![Output](https://img.shields.io/badge/Output-PNG-5D91A0?style=flat-square)](#)

<a href="README.md">简体中文</a> · <strong>English</strong> · <a href="README.ja.md">日本語</a> · <a href="README.ko.md">한국어</a> · <a href="README.ar.md">العربية</a>

</div>

<div>

> ORIGINAL VIEW · 2–5 TRUE LAYERS · STABLE ANCHOR · TRANSLUCENT WATERCOLOUR · EDITORIAL NOTE

The original viewpoint and real structure are the only evidence. Two to five meaningful complete layers separate along true axes around one stable anchor, preserving enough identity for the viewer to mentally reassemble the subject.

## Why this Skill exists

The style is source-dependent, not a decorative preset. Its operative transformation is:

```text
audit original viewpoint and structure → lock 3–7 defining features and 4–6 main colours → identify one stable base or anchor → separate only 2–5 meaningful complete layers along real axes → preserve shared centre and moderate spacing → render clear line plus translucent watercolour on ivory paper → add restrained structural annotations
```

If an unrelated photograph could replace the source without materially changing recognition, construction, placement, material, colour, whitespace, and copy, the result does not belong to this Panel.

## The visual contract

- The source is the only evidence. Preserve identity, overall contour, proportion, original observation direction, symmetry/asymmetry, key component relation, defining detail, material colour, and scale cues.
- Separate only two to five meaningful complete layers or components along real axes with moderate even spacing and one stable, detailed base or anchor that lets the viewer mentally reassemble the subject.
- Buildings and objects may separate by roof, floor, shell, frame, base, module, or connector; spaces by depth layers. People, animals, and plants stay bodily complete and are never dissected or mechanised.
- Use warm ivory watercolour paper, clear controlled line, translucent washes, paper tooth, fine brushwork, a few structural guides, and clean source-derived colour.
- Keep professional editorial restraint and generous whitespace; avoid dramatic explosion, arbitrary fragments, technical UI, or engineering-manual density.

Complete aesthetic constraints and rejection rules live in the Skill and production prompts. They preserve the original brief without turning its historical 3:4 canvas into a hidden default. [SKILL.md](SKILL.md) · [production prompt](references/xxd-panel-042-prompt.en.md)

## Samples · From X

> [Xiaoxiaodong (@xiaoxiaodong01)](https://x.com/xiaoxiaodong01/status/2091032515318521971) · 22 August 2026<br>
> GPT2 × decomposition × layering × aesthetic prompt × VOL.042

<table>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091032515318521971"><img src="./assets/examples/sample-01.jpg" alt="XXD Panel 042 sample 1"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091032515318521971"><img src="./assets/examples/sample-02.jpg" alt="XXD Panel 042 sample 2"></a></td>
  </tr>
  <tr>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091032515318521971"><img src="./assets/examples/sample-03.jpg" alt="XXD Panel 042 sample 3"></a></td>
    <td width="50%"><a href="https://x.com/xiaoxiaodong01/status/2091032515318521971"><img src="./assets/examples/sample-04.jpg" alt="XXD Panel 042 sample 4"></a></td>
  </tr>
</table>

<p align="center"><a href="https://x.com/xiaoxiaodong01/status/2091032515318521971">View the original post and full prompt →</a></p>

These samples demonstrate the 042 aesthetic motive. Their subjects, composition, palette, copy, and earlier canvas ratio never become generation references or current defaults.

## Four combinable output modes

Choose one or several modes with `1`, `1+3`, `1,2,4`, or `all`; `all` produces seven separate PNGs per source. After mode selection and before generation, the Skill explicitly asks for the whole finished canvas: the original-prompt `3:4`, an explicit source-aspect choice, a common ratio, or custom ratio/exact pixels. Source dimensions are never applied silently.

| Mode | Canvas rule | Result |
| --- | --- | --- |
| `top-bottom` | user-confirmed whole canvas | one complete generation: high-fidelity source above, 042 design below, approximately 50/50 |
| `left-right` | user-confirmed whole canvas | one complete generation: high-fidelity source left, 042 design right, approximately 50/50 |
| `design-only` | user-confirmed whole canvas | 042 design fills the canvas; source remains invisible |
| `wallpaper-pack` | confirmed per device | separate phone, iPad, desktop, and children's-watch PNGs |

Paired modes use the source as a high-fidelity edit/reference input and one complete style prompt to generate the finished composition directly, so photography, design, colour, light, typography, and meaning can cohere. Deterministic composition is fallback-only: after one targeted complete-canvas retry fails, when pixel-identical source preservation is explicitly required, when the active route cannot realise the canvas, or for lossless final pixel calibration.

Wallpapers may be linked or independent. A linked pack approves one iPad anchor, then recomposes every other device from the original plus that same anchor. An independent pack gives each device only the original. Neither crops another device output nor chains derivatives.

## Copy and locale

Automatic copy, exact custom copy, or text-free output is confirmed before generation. Copy follows the intended audience rather than the command language, and exact user wording remains verbatim.

Project-specific copy rule: Use one concise identity, theme, action, state, or symbolic title with only supported structural markers, material words, state words, or micro-notes. Numbers appear only when supplied or reliably established. Align native type to real axes, layer direction, whitespace edges, or annotation points.

## Complete-canvas first, raster-only delivery

The image model owns the aesthetics of the entire finished composition; paired layouts also default to one complete-canvas generation. `scripts/compose_panel.py` remains only for condition-based recovery, lossless pixel calibration, and read-only audit. It is not run pre-emptively and does not judge aesthetic success.

Every deliverable is a raster PNG and every invocation creates a fresh task under `~/Desktop/xxd/`. The configured image route exposes sanitised status only—never providers, endpoints, credentials, headers, prompts, responses, or account details. SVG, HTML, Canvas, diagrams, and programmatic drawing are not substitutes for the final artwork.

## Image-model priority

GPT Image 2 is the default first choice. It keeps this project's established workflow: high-fidelity source reference, explicit whole-canvas selection before generation, one complete-canvas generation for paired modes, and scripted composition only as a conditional fallback.

Seedance 5.0 Pro, Nano Banana Pro (Gemini Image Pro), Nano Banana 2 (Gemini Image Flash), or another compatible bitmap model may also be used when it is actually available through the current tools or configured routes and can satisfy source fidelity, whole-canvas ratio, target-language text, and linked-wallpaper multi-reference requirements. An alternative changes only the generation route; it must not change modes, canvas, copy, locale, wallpaper relationship, or the complete-canvas-first strategy.

If no suitable route is available, the Skill asks the user to enable an image-generation tool or provide an API key. User-provided credentials may be used for the current task without being echoed, displayed, logged, or exposed. They are not persisted, and provider, account, billing, or global route configuration is not modified, unless the user explicitly requests that configuration change.

## Get started

```bash
git clone https://github.com/nevertoday/xxd-panel-042.git
mkdir -p ~/.codex/skills
ln -s "$(pwd)/xxd-panel-042" ~/.codex/skills/xxd-panel-042
```

Claude Code users may link the same folder under `~/.claude/skills/xxd-panel-042`. Restart the agent session after installation.

```text
$xxd-panel-042
Use this photograph, ask me for the modes and copy setting, then generate fresh raster outputs.
```

Full specifications: [Skill workflow](SKILL.md) · [source archive](references/042-source.md) · [English prompt](references/xxd-panel-042-prompt.en.md) · [Chinese prompt](references/xxd-panel-042-prompt.zh-CN.md)

## About XXD

XXD is Xiaoxiaodong's abbreviated brand name. Created and maintained by [@xiaoxiaodong01](https://x.com/xiaoxiaodong01).

## Support and membership

### In-depth consultation · CNY 299/hour

One-to-one in-depth consultation for using Skills. Contact Xiaoxiaodong through WeChat. [WeChat](https://xiaoxiaodong.pages.dev/assets/wechat-qr.png)

### Xiaoxiaodong Skills User Community · CNY 99

A one-time fee joins the Skills user community for workflow sharing and peer discussion; hourly consultation is separate.

### Knowledge Planet + Member Prompt Library · CNY 699/year

One annual payment opens both Knowledge Planet and the member prompt library. Join either side, then contact Xiaoxiaodong on WeChat for the other access.

[Knowledge Planet](https://wx.zsxq.com/group/15554814142882) · [Member Prompt Library](https://vip.xiaoxiaodong.ai/)

<p align="center"><a href="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png"><img src="https://xiaoxiaodong.pages.dev/assets/wechat-qr.png" alt="XXD WeChat" width="280"></a></p>

<div align="center"><strong>Deconstruction reveals how the subject holds together, not how it can be broken apart.</strong></div>

---

<div align="center">

## Support this open-source project

Chinese-language support may use Xiaoxiaodong's own WeChat or Alipay reward codes; other editions use Buy Me a Coffee. Support is optional and never changes access to the open-source project.


<p align="center"><a href="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true"><img src="https://github.com/nevertoday/zhongguo-traditional-colors/blob/main/docs/images/buy-me-a-coffee-qr.png?raw=true" alt="Buy Me a Coffee" width="180"></a></p>

</div>
</div>
