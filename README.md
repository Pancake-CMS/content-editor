# content-editor
A web component that lets users edit the content in their elements.

### Installation

```shell
bower install --save pancake-cms-content-editor
```

### Usage

While creating your element, you will need to append the `ContentEditorBehaviour` to your code.

```javacript
Polymer({
    is: 'my-element',
    behaviors: [ContentEditorBehaviour]
});
```
