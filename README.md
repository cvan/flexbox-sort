# flexbox-sort

Sort a list of nodes without changing the DOM (thank you, flexbox).

The perfect use case: rendering filtered data, such as client-side search
results, without having to reconsistute the DOM based on sort order.

Instead of physically rearranging the existing DOM nodes,
or destroying the existing nodes and re-rendering new ones, we
can simply change them using one CSS property (flexbox's `order`).


## Caveat

If you copy the entire document to your clipboard, you'll notice that the
pasted text appears in the order in which the text is represented in the DOM,
not in the visual order set by flexbox.

You can still select the text content of each flexbox-ordered item - just not
text that overlaps to another flexbox-ordered item.

If you print the document, the visual order set by flexbox order is
preserved. But why are you printing this? And why do you still own a printer?


## Browser support

* Chrome (any)
* Firefox (any)
* Safari (any)
* Opera 12.1+
* IE 10+
* iOS (any)
* Android (any)


## Closing remark

Sic transit gloria.
