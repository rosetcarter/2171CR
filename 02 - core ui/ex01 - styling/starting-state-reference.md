# Lesson 05 Starting State Reference

Use this reference if you are unsure what “start from the lesson-04 project” means.

## Expected shared baseline
Before lesson 05, the student project should already have:
- a working Expo app from lesson 04
- a screen using `View`, `Text`, `Image`, `ScrollView`, and `TextInput`
- a working `src/app/App.js` that still runs
- at least two visible content sections and one possible row or grouped block
- rough structure, but only basic or incomplete styling

## Mental model
Lesson 04 established:
- which components belong on the screen
- how sections are nested
- one working screen structure

Lesson 05 adds:
- clearer spacing
- text hierarchy
- surface styling
- layout alignment

## More realistic baseline example
This is not a full copy target. It is only a reminder of the kind of screen state students are starting from before styling:

```js
<ScrollView>
  <View>
    <Text>Lesson 04 heading</Text>
    <Text>Intro text for the screen</Text>

    <View>
      <Text>Section one</Text>
      <Text>Some supporting details</Text>
    </View>

    <View>
      <Image source={{ uri: 'https://reactnative.dev/img/tiny_logo.png' }} style={{ width: 64, height: 64 }} />
      <View>
        <Text>Section two</Text>
        <Text>Image and text can become a row later</Text>
      </View>
    </View>

    <TextInput placeholder="Type here" />
  </View>
</ScrollView>
```

This baseline matters because lesson 05 asks you to:
- separate sections with spacing
- make headings and body text look different
- style at least one grouped surface
- improve one alignment area
- leave two clear sections that lesson 06 can later split into screens

## If your project is not in this state
- If your app runs and already has this structure, keep working in your own project.
- If `src/app/App.js` is broken, restore your last working lesson-04 version first.
- If the project will not launch in time for class progress, open `example/styling-reference/` and complete the lesson work there.
- Record which project you used and what your next step is before lesson 06.
