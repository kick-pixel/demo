# Changelog

## [0.1.1.0] - 2026-04-15

### Changed
- Upgraded design system: blue-teal gradient background, particle celebration animation on task completion, modern card-based layout
- Enhanced stats display: shows pending vs completed counts, clear-completed button disabled when none
- Character counter with live tracking and warning color at 150+ chars

### Fixed
- Implicit global variable declaration (`angle` was missing `var`)
- localStorage key migration from `todos:v1` to `todos` with safe fallback
- Accessibility: added `role="checkbox"`, `aria-checked`, and keyboard support for checkboxes
- Font sizing: increased base font to 16px, proper heading hierarchy

## [0.1.0.0] - 2026-04-14

### Added
- Minimal single-file todo app — add tasks via Enter or Add button, delete with X, persist in localStorage
- XSS-safe rendering (textContent only), error handling for corrupted data and storage quota
- Keyboard accessible (Enter to add, tab navigation, visible focus outlines)
- 44px touch targets, system fonts, grayscale-only design
- gstack skill routing in CLAUDE.md
