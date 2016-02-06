# dijit-scrollbar
Scrollbar for Dojo's Dijit widget toolkit

## Usage
```javascript
this.scrollbars = new ScrollBars({
    containerNode: this.domNode,
    contentNode:   this.containerNode
}).render();
```
This will typically be done in the container's `startup()` method.
