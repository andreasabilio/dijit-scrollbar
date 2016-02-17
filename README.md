# dijit-scrollbar
Scrollbar for Dojo's Dijit widget toolkit.

This scrollbar implementation will only render on windows and linux, falling back to native on android and osx.

## Usage
![usage](http://www.abilio.dk/wp-content/uploads/2016/02/scrollbar-nodes.png)

```javascript
this.scrollbars = new ScrollBars({
    containerNode: this.domNode,
    contentNode:   this.contentNode
}).render();
```
This will typically be done in the container's `startup()` method. CSS styling is not included and must be done to see the scrollbars.
