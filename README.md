# iOS Design Art Director

[简体中文](#简体中文) · [English](#english) · [日本語](#日本語) · [한국어](#한국어) · [Español](#español) · [Français](#français)

An open-source Codex skill for evidence-led iOS product direction, experience design, art direction, and critique.

> Independent community project. Not affiliated with or endorsed by Apple Inc. or OpenAI.

## Before & After

The same iOS mood-journaling brief, approached with and without the skill:

![Before and after comparison of the Still iOS app](assets/before-after.png)

| Without the skill | With `ios-design-art-director` |
| --- | --- |
| Features compete for attention | One meaningful action defines the experience |
| Dashboard cards and upgrade chrome dominate | Content and emotional context lead the hierarchy |
| Generic gradients, shadows, and crowded controls | Restrained materials, semantic color, and native behavior |
| Accessibility and edge states are deferred | Legibility, touch comfort, agency, and resilience shape the concept |

**Design thesis:** Help a busy person close the day with one honest sentence, creating a quiet sense of reflection rather than another performance dashboard.

This is an illustrative art-direction comparison, not a measured usability result or evidence that the skill causes a specific score improvement. Reproducible behavioral cases live in [`evals/cases.md`](evals/cases.md).

## 简体中文

`ios-design-art-director` 是一个面向原生 iPhone 与 iPad 体验的 Codex 技能。它让 Codex 以产品设计师和艺术总监的视角工作，不只判断界面是否“好看”，还会审视产品目的、信息架构、原生交互、视觉系统、情绪表达、无障碍、隐私责任与完整状态。

它适合用于：定义 iOS 产品方向；设计或重构页面与流程；评审截图与原型；以及建立视觉与交互系统。只有在证据足够时才会进行正式评分；不会给未渲染的概念或证据不完整的截图编造百分制分数。

这个技能强调基于证据做判断：涉及最新 Apple 设计语言时核验官方资料；从 Apple Design Award 获奖作品中提炼可迁移的方法，但不复制作品的视觉身份或标志性交互。

## English

`ios-design-art-director` helps Codex think like a product designer and art director for native iPhone and iPad experiences. It goes beyond surface polish to examine product purpose, information architecture, native interaction, visual systems, emotional character, accessibility, privacy, resilience, and edge states.

Use it to shape an iOS product direction, design or redesign screens and flows, critique screenshots and prototypes, establish a coherent art direction, and produce prioritized improvements. Formal scoring is available only when the observed evidence supports it; unrendered concepts and incomplete screenshots are not given invented 100-point scores.

The skill is evidence-led: it checks current official Apple guidance when recency matters, treats award-winner lessons as design inferences rather than requirements, and prohibits copying a winner's visual identity or signature interactions.

## 日本語

`ios-design-art-director` は、Codex がネイティブな iPhone／iPad 体験をプロダクトデザイナー兼アートディレクターの視点で考えるためのスキルです。見た目の美しさだけでなく、製品の目的、情報設計、iOS らしい操作、ビジュアルシステム、感情的な個性、アクセシビリティ、プライバシー、例外状態まで評価します。

iOS 製品の方向性策定、画面やフローの設計・再設計、スクリーンショットやプロトタイプの講評、一貫したアートディレクションの構築に利用できます。正式な採点は観察可能な根拠が十分な場合に限ります。

## 한국어

`ios-design-art-director`는 Codex가 네이티브 iPhone 및 iPad 경험을 제품 디자이너이자 아트 디렉터의 관점에서 설계하도록 돕는 스킬입니다. 단순한 시각적 완성도를 넘어 제품 목적, 정보 구조, iOS다운 상호작용, 시각 시스템, 감성, 접근성, 개인정보 보호, 오류 및 예외 상태까지 검토합니다.

iOS 제품 방향 수립, 화면과 플로우의 설계·리디자인, 스크린샷과 프로토타입 비평, 일관된 아트 디렉션 구축에 사용할 수 있습니다. 정식 점수는 관찰 가능한 근거가 충분할 때만 제공합니다.

## Español

`ios-design-art-director` ayuda a Codex a trabajar como diseñador de producto y director de arte para experiencias nativas de iPhone y iPad. Va más allá del acabado visual y analiza el propósito, la arquitectura de información, la interacción propia de iOS, el sistema visual, el carácter emocional, la accesibilidad, la privacidad y los estados límite.

Sirve para definir la dirección de un producto iOS, diseñar o rediseñar pantallas y flujos, evaluar capturas y prototipos y crear una dirección artística coherente. La puntuación formal solo se utiliza cuando existe evidencia observable suficiente.

## Français

`ios-design-art-director` aide Codex à agir comme designer produit et directeur artistique pour des expériences natives iPhone et iPad. Il ne se limite pas à l'esthétique : il examine la finalité du produit, l'architecture de l'information, les interactions propres à iOS, le système visuel, l'émotion, l'accessibilité, la confidentialité et les cas limites.

Il permet de définir la direction d'un produit iOS, concevoir ou repenser des écrans et des parcours, critiquer des captures et prototypes et construire une direction artistique cohérente. Une note formelle n'est donnée que lorsque les éléments observables sont suffisants.

## Install

Clone the repository into the current user-level Codex skills directory:

```bash
git clone https://github.com/feiou/ios-design-art-director.git ~/.agents/skills/ios-design-art-director
```

Some older Codex installations also scan `~/.codex/skills`. Restart Codex if the skill does not appear immediately.

## Use

Invoke it explicitly:

```text
$ios-design-art-director Review this iOS onboarding flow and give me an evidence-limited score.
```

Or describe a matching iOS product-design task and let Codex select the skill automatically.

## What is included

- `SKILL.md` — core workflow, design lens, scoring rubric, and deliverable format.
- `references/ada-intelligence.md` — a dated synthesis of official Apple guidance and recent Apple Design Award patterns.
- `references/ipad-direction.md` — iPad windowing, information architecture, input, multitasking, and validation guidance loaded only for relevant work.
- `evals/cases.md` — behavioral cases for trigger scope, evidence discipline, proportional output, and platform adaptation.
- `agents/openai.yaml` — display metadata and a default invocation prompt.

## License

Released under the [MIT License](LICENSE).
