# Lesson 06 Materials Summary

## Lesson Context
- Lesson: 06
- Title: Navigation Fundamentals
- Module: 02 Core UI and Navigation
- Source plan: `lessons/raw_lesson_plans/lesson_06.yml`

## Delivery Goals
This lesson moves students from a single styled screen into a simple multi-screen app. The bundle is designed to help students understand why navigation is needed, how Expo Router turns files into routes on the SDK 56 course scaffold, how a stack layout controls screen flow, and how to leave class with either a working two-screen app or a documented recovery path.

## Required Materials
### `slides.md`
A Sli.dev deck for the instructor that:
- reconnects lesson-05 screen structure to the need for multiple screens
- introduces routes, stack layouts, screen flow, and basic navigation actions
- explains the `configured` / `partial` / `blocked` recovery model
- supports a guided build, screen-flow analysis, checkpoint, and lesson-07 handoff

### `example/navigation-fundamentals-reference/`
A lightweight Expo Router reference app and instructor notes that:
- align to the course Expo SDK 56 scaffold
- use `src/app/_layout.tsx`, `src/app/index.js`, and `src/app/details.js`
- demonstrate a simple two-screen stack with `router.push()` and `router.back()`
- provide a known-good instructor-guided reference path for students whose own project is not ready

### `exercise.md`
A take-home exercise that reinforces the lesson by asking students to:
- explain why navigation is needed
- identify how the route files and stack layout work together
- describe one navigation action they tested
- document one troubleshooting or recovery step if setup was incomplete

### `navigation-build-checklist.md`
A student-facing in-class checklist for converting the lesson-05 screen into a small multi-screen app in a controlled order.

### `starting-state-reference.md`
A student-facing reminder of the expected lesson-05 baseline before navigation work begins.

### `screen-flow-reference.md`
A student-facing explanation of routes, stack layouts, screen flow, and the specific two-screen pattern used in this lesson.

### `starter-snippets.md`
A student-facing syntax guide for the minimum Expo Router patterns used in the lesson.

### `navigation-status-tracker.md`
A short student/instructor tracker for `configured`, `partial`, and `blocked` navigation outcomes.

### `troubleshooting-checklist.md`
A short triage guide for common route, layout, and navigation-action issues in this lesson.

## Version Note
Verified against official Expo documentation on `2026-06-04T20:47Z`.

- Current Expo guidance says Expo Router is the recommended navigation approach for Expo projects.
- New Expo SDK 56 default projects include Expo Router by default.
- Expo Router uses file-based routing, where route files become screens.
- Expo Router stack navigation uses `Stack` layouts and router actions such as `navigate`, `push`, and `back`.

## Instructor Use Notes
- Teach navigation through the current course scaffold rather than older direct `@react-navigation/*` imports in app code.
- Keep the route structure simple: one stack layout and two screens only.
- Treat the lesson as screen-flow setup, not as a deep routing lesson.
- Require every student to leave with either a working navigation path or a documented next action.

## Review Requirement
When the full lesson package is complete, it must be reviewed by:
- `lds-reviewer` for learning-design quality
- `student-reviewer` for clarity and student friction
