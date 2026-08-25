# Behavioral Evaluation Cases

Use these cases to compare revisions of the skill. Judge decisions and observable output behavior, not exact headings or wording.

| Case | Prompt shape | Expected behavior | Failure signal |
| --- | --- | --- | --- |
| Compact critique | “Quickly critique this iPhone settings screenshot.” | Gives a compact verdict, evidence limits, and no more than three high-impact changes. | Produces the full eight-section report or invents interaction behavior. |
| Formal screenshot review | “Score this onboarding from these three screenshots.” | Scores only observable dimensions, marks others `N/A`, and reports an observed subtotal. | Fabricates a 100-point score or claims accessibility compliance. |
| Unrendered concept | “Design a calm medication reminder app and score it.” | Produces a thesis and direction, declines numeric scoring until rendered evidence exists, and explains validation. | Awards its own proposal a high score. |
| Existing design system | “Redesign this screen in our existing app.” | Inspects and preserves existing tokens and conventions before proposing changes. | Invents a replacement design system without evidence. |
| Routine implementation | “Fix this SwiftUI compile error.” | Does not implicitly route as an art-direction task unless visual/product judgment is also requested. | Turns a code fix into a design audit. |
| iPad adaptation | “Make this editor excellent on iPad.” | Uses window-size, sidebar/inspector, input, multitasking, and state-preservation reasoning. | Merely scales up the iPhone layout. |
| Accessibility evidence | “Is this screenshot accessible?” | Identifies visible risks and required tests without claiming conformance. | Treats a screenshot or automated audit as proof. |
| Current Apple language | “Update this navigation for the latest Liquid Glass guidance.” | Checks current official Apple sources, cites them, and uses glass only for justified hierarchy. | Relies only on the bundled baseline or adds ornamental glass. |
| Sensitive health flow | “Art-direct a symptom-tracking permission flow.” | Prioritizes honest permissions, privacy, denied states, user control, and humane language. | Optimizes conversion at the expense of informed consent. |
| Chinese review | “请评审这个 iOS 首页，给出最高优先级的三个修改。” | Responds naturally in Chinese with a compact, evidence-limited critique. | Switches to English or emits a full formal audit. |

## Acceptance Criteria

A revision is ready when it:

- routes the design cases and avoids the routine implementation case;
- keeps compact requests compact;
- never converts missing evidence into invented certainty;
- preserves user and repository constraints;
- treats innovation and Apple technology as contextual rather than mandatory;
- produces changes that are specific enough to implement and validate.
