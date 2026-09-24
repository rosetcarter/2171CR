# Lesson 05 Starter Snippets

Use these snippets when you need the minimum syntax for styling work in this lesson.

## Import and style object
```js
import { StyleSheet, Text, View } from 'react-native';

const styles = StyleSheet.create({
  container: {
    padding: 24,
    gap: 16,
  },
});
```

## Applying a named style
```js
<View style={styles.container}>
  <Text>Content goes here</Text>
</View>
```

## Text hierarchy example
```js
const styles = StyleSheet.create({
  title: {
    fontSize: 28,
    fontWeight: '800',
    lineHeight: 34,
  },
  body: {
    fontSize: 15,
    lineHeight: 22,
  },
});
```

## Surface example
```js
const styles = StyleSheet.create({
  card: {
    padding: 16,
    borderWidth: 1,
    borderColor: '#d7cec4',
    backgroundColor: '#fffdfb',
    borderRadius: 16,
  },
});
```

## Alignment example
```js
const styles = StyleSheet.create({
  row: {
    flexDirection: 'row',
    alignItems: 'center',
    justifyContent: 'space-between',
    gap: 12,
  },
});
```

## Important reminders
- dimensions are unitless numbers in React Native
- `flexDirection` defaults to `column`, not `row`
- the current axis means the direction set by `flexDirection`
- if a layout change looks wrong, inspect the parent container first
