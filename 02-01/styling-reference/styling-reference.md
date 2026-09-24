# Lesson 05 Styling Reference

Use this guide during class and while completing the exercise.

| Purpose | Common properties | Common beginner mistake |
| --- | --- | --- |
| Spacing | `padding`, `margin`, `gap` | changing spacing everywhere at once |
| Text hierarchy | `fontSize`, `fontWeight`, `lineHeight`, `color` | making text bigger without improving line spacing |
| Alignment | `flexDirection`, `alignItems`, `justifyContent` | changing alignment without checking the current axis |
| Surfaces | `backgroundColor`, `borderWidth`, `borderColor`, `borderRadius` | adding too many visual treatments at once |

## Spacing
- Use spacing to separate sections and reduce crowding.
- Start with the main container and one or two sections before styling everything else.

## Text hierarchy
- Use larger, heavier text for headings and calmer body text for details.
- Line spacing matters when paragraphs wrap.

## Alignment
- `flexDirection` changes the main axis.
- `alignItems` and `justifyContent` behave differently depending on that axis.
- Parent container styles often control why child elements appear where they do.

## Surfaces
- Use simple section surfaces to group related content.
- A light background, border, or rounded corner is enough for this lesson.

## Simple comparison rule
- React Native styling is similar to CSS in concept, but the syntax is JavaScript objects.
- React Native layout still uses Flexbox, but defaults differ from the web.
