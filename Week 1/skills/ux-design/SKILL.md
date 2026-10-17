---
name: ux-design
description: Apply UX design principles when building or changing any user-facing screen, page, component, form, or flow. Use when writing UI code, laying out pages, writing interface text (buttons, labels, messages), or reviewing a screen for usability.
---

# UX Design

Based on Nielsen's 10 Usability Heuristics and the Laws of UX.

## Core rules

1. Every screen handles all its states: loading, empty, error, and success. Never leave a blank screen.
2. Show system status: every user action gets visible feedback, and anything taking longer than 1 second shows a loading indicator. (Nielsen #1)
3. Use the user's language, not technical terms. No internal codes, database field names, or developer jargon in the interface. (Nielsen #2)
4. Give users control: destructive actions (delete, remove, cancel subscription) need a confirmation or an undo, and every flow or modal has a visible way out (Cancel, Back, or Close). (Nielsen #3)
5. Be consistent: reuse existing components and patterns from the design system, and the same action has the same label everywhere. Follow common web conventions users already know. (Nielsen #4, Jakob's Law)
6. Prevent errors before they happen: use constraints (date pickers, dropdowns), sensible defaults, and inline validation instead of only validating on submit. (Nielsen #5)
7. Recognition over recall: don't make users remember information from a previous screen. Form labels stay visible; never use placeholder text as the only label. (Nielsen #6)
8. One primary action per screen, visually emphasized. Limit the number of choices shown at once; group or hide secondary options. (Hick's Law, Nielsen #8)
9. Primary buttons are large and placed close to the content they act on. (Fitts's Law)
10. Button labels start with a verb that says what happens: "Save changes", not "OK".

## Checklist before finishing

- [ ] Loading, empty, error, and success states are all designed
- [ ] Every action shows feedback; slow actions show a loading indicator
- [ ] No technical jargon or internal codes visible to users
- [ ] Destructive actions have a confirmation or undo
- [ ] Every modal and flow has a visible Cancel, Back, or Close
- [ ] Uses existing design system components; labels are consistent
- [ ] Form labels are always visible (not placeholder-only)
- [ ] Only one primary action per screen
- [ ] Every button label starts with a verb

## Example

Bad: A form with one button labeled "Submit" and no feedback after clicking.
Good: A button labeled "Create account" that shows "Creating..." while working, then a success message with a clear next step.