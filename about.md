## About ##
# Markdown Example
Markdown allows you to easily include formatted text, images, and even formatted
 Dart code in your app.

## Styling
Style text as _italic_, __bold__, or `inline code`.
- Use bulleted lists
- To better clarify
- Your points

## Links
You can use [hyperlinks](https://flutter.dev) in markdown

## Images
You can include images:
![Flutter logo](https://upload.wikimedia.org/wikipedia/commons/1/17/Google-flutter-logo.png)

## Markdown widget
This is an example of how to create your own Markdown widget:

`new Markdown(data: 'Hello _world_!');`


## Code blocks
Formatted Dart code looks really pretty too:
```dart
void main() {
  runApp(new MaterialApp(
    home: new Scaffold(
      body: new Markdown(data: markdownData)
    )
  ));
}
```

## Tables: 

| foo | bar |
| --- | --- |
| baz | bim |

Enjoy!
