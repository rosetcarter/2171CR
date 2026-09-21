# Lesson 04 Component Reference

Use this guide during class and while completing the exercise.

| Component | Main job | Rough web analog | Common beginner mistake |
| --- | --- | --- | --- |
| `View` | groups and structures UI | non-scrolling `div` | using it for visible text instead of as a container |
| `Text` | displays readable text | `p` or `span` | placing visible strings outside `Text` |
| `Image` | displays an image | `img` | forgetting width and height |
| `ScrollView` | lets the screen scroll | scrollable `div` | using it without enough content to notice the effect, or treating it like a long-list solution |
| `TextInput` | collects typed input | `input` or `textarea` | forgetting to import it or confusing it with static text |

## `View`
- Use `View` for sections, rows, cards, and grouping.
- It helps create structure, but it does not display text by itself.
- Plain-language backup: think “container.”

## `Text`
- Use `Text` for headings, labels, instructions, and body content.
- In React Native, visible text belongs inside `Text`.
- Plain-language backup: think “visible words on screen.”

## `Image`
- Use `Image` when the screen needs a visual asset or media block.
- A valid source is not enough by itself; the component also needs size.
- In this lesson, use the shared remote URL from [starter-snippets.md](starter-snippets.md) unless the instructor gives another source.
- Plain-language backup: think “picture block.”

## `ScrollView`
- Use `ScrollView` when the content may extend beyond one screen.
- For this lesson, it is acceptable because the screen is small and simple.
- For very long data collections, a list component is usually a better choice later.
- Plain-language backup: think “the screen can move vertically.”

## `TextInput`
- Use `TextInput` when the user needs to type something.
- It is interactive, unlike a `Text` block.
- Plain-language backup: think “the user can type here.”

## Simple comparison rule
- Web analogs are orientation tools, not exact replacements.
- React Native components are designed for mobile UI structure, not browser document structure.
