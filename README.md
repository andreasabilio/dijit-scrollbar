# dijit-scrollbar
Scrollbar for Dojo's Dijit widget toolkit.

This scrollbar implementation will only render on windows and linux, falling back to native on android and osx.

## Usage
```javascript
this.scrollbars = new ScrollBars({
    containerNode: this.domNode,
    contentNode:   this.containerNode
}).render();
```
This will typically be done in the container's `startup()` method. CSS styling is not included and must be done to see the scrollbars.
