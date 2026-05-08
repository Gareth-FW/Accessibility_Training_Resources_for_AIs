Accordion prompt (framework-agnostic component)

Prompt:
Generate an accessible Accordion component in [INSERT FRAMEWORK] using the [INSERT DESIGN SYSTEM] design system (vanilla, design-system agnostic). 

Requirements:
•	Accordion consists of multiple sections; each section has a control with a clear visible label and a content panel.
•	The accessible name of each control must match/include the visible label (supports voice control ‘Click [label]’).
•	Keyboard: Tab reaches the first control; Tab order moves through controls logically; Enter and Space toggle the focused section; no keyboard trap.
•	Screen reader: Each control has a programmatically determinable name/role/state and announces expanded/collapsed; state changes update correctly.
•	Collapsed panels: content is visually hidden and hidden from assistive tech and keyboard navigation (no focusable elements inside collapsed panels).
•	Visuals: provide a visible focus indicator on controls; provide a state indicator (e.g., caret/chevron) that updates on expand/collapse.
•	Layout resilience: content remains readable/usable at 200% text size on narrow viewports.
•	Grouping: group the accordion as a semantic region with an accessible name (e.g., labelled by a heading).
•	No-JS fallback: if JS is unavailable, ensure all accordion content (or a comparable alternative such as a list) is available.

Output: component code + minimal styles needed for focus and hidden/collapsed states, plus brief notes mapping each requirement to the implementation.

Binary tests (desired outcome = Yes) for a human to evaluate what the LLM produces...
1.	Keyboard reachability: Using Tab, focus can move to the first accordion control.
2.	Logical focus order: Tabbing through controls proceeds in a logical reading order with no unexpected jumps.
3.	Keyboard toggle: With a control focused, Enter toggles the panel.
4.	Keyboard toggle: With a control focused, Space toggles the panel.
5.	Focus visible: Each accordion control shows a clearly visible focus indicator.
6.	Screen reader state announcement: Screen reader announces the control label and whether it is expanded/collapsed.
7.	Name includes label: The accessible name of each control matches or includes its visible label text. 
8.	Collapsed content hidden from AT: When collapsed, panel content is not reachable by screen reader navigation.
9.	Collapsed content not keyboard-focusable: When collapsed, interactive elements inside the panel are not reachable by Tab.
10.	200% text size: At 200% font size (including narrow viewport), all accordion content remains readable/usable.
11.	Voice control operation: “Click [visible control label]” toggles the correct panel.
12.	No-JS fallback: With JavaScript disabled, all accordion content (or a comparable alternative) is available.
