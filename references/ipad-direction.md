# iPad Art-Direction and Experience Checklist

Read this reference only when the task includes iPad, universal layouts, large-screen adaptation, Apple Pencil, keyboard, pointer, or multiwindow behavior.

## Start With Window Behavior

- Design for the available window rather than assuming a device model or full-screen size.
- Define what changes at compact and regular widths: navigation structure, column count, inspector placement, toolbars, and content density.
- Preserve the selected object, draft, scroll position, and task context when the window resizes or the interface changes structure.
- Avoid filling space with decorative cards or stretching reading and editing content beyond a comfortable measure.

## Choose an Information Architecture That Earns the Space

- Use a sidebar or split view when persistent navigation or selection materially reduces backtracking.
- Add a supplementary column or inspector only when simultaneous context improves the task.
- Keep the primary canvas or content visually dominant; secondary columns should support it rather than compete with it.
- Prefer popovers for anchored, lightweight choices and sheets for focused tasks that need more room or commitment.
- Decide how each column collapses, how the user returns to it, and what remains selected at narrow widths.

## Support iPad Input Without Creating Separate Products

- Ensure every essential action works through touch.
- Add pointer affordances, hover feedback, keyboard focus, contextual menus, and shortcuts where they improve repeated or precision work.
- Use drag and drop when the source, destination, preview, and cancellation behavior are understandable.
- Use Apple Pencil for precision, annotation, drawing, or handwriting only when it improves the core task; provide discoverable alternatives for essential actions.
- Keep feedback consistent across touch, keyboard, pointer, and Pencil so the product retains one interaction model.

## Treat Multitasking as a Normal State

- Check narrow split-screen windows, full-screen portrait and landscape, external keyboard use, and repeated resize transitions.
- Decide whether multiple windows represent independent documents, views of shared state, or unsupported duplication; preserve user work in every case.
- Make toolbars and primary actions remain legible without crowding when the window narrows.
- Avoid orientation locks unless the task has a concrete physical or media requirement.

## Validate

At minimum, inspect:

1. compact and regular widths;
2. portrait and landscape;
3. the largest supported Dynamic Type sizes;
4. keyboard-only traversal and shortcuts where relevant;
5. pointer hover and contextual actions;
6. live resizing without lost selection, drafts, or navigation context;
7. light, dark, and increased-contrast appearances;
8. long localized copy and right-to-left layout when the product ships them.

Report what was actually exercised. Static screenshots cannot prove resize continuity, keyboard behavior, drag and drop, or state preservation.
