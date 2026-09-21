# Lesson 04 Starter Snippets

Use these snippets when you need the minimum syntax for the new components in this lesson.

## Imports
```js
import { Image, ScrollView, TextInput, View, Text } from 'react-native';
```

## `ScrollView`
```js
<ScrollView>
  <View>
    <Text>Content goes here</Text>
  </View>
</ScrollView>
```

## `Image`
The shared lesson image uses a remote URL:

```js
<Image
  source={{ uri: 'https://reactnative.dev/img/tiny_logo.png' }}
  style={{ width: 64, height: 64 }}
/>
```

Why this matters:
- `source` must be valid
- width and height must be visible
- if the network blocks the remote image, skip the image temporarily and continue the rest of the build

## `TextInput`
```js
<TextInput placeholder="Type here" />
```

Multiline example:
```js
<TextInput
  placeholder="Type a short note here"
  multiline
  style={{ minHeight: 80, borderWidth: 1, padding: 12 }}
/>
```

## Small combined example
```js
<ScrollView>
  <View>
    <Text>My new section</Text>
    <Image
      source={{ uri: 'https://reactnative.dev/img/tiny_logo.png' }}
      style={{ width: 64, height: 64 }}
    />
    <TextInput placeholder="Type here" />
  </View>
</ScrollView>
```
