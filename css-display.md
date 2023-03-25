Block: It is used to display the elements like block elements. They are placed one below the other. It is the default value of the <div> element. Here, the height and width can be changed but if unspecified, it will take the width of the container.

Inline: It is used to display an element as an inline element. The inline elements are displayed in a single line, i.e., horizontally, and it will take as much width as is necessary. The inline property ignores the height and the width set by the user.
Examples of inline elements are the <span>, <a>, <i>, and <img> tags.

Inline-block: As the name suggests, this renders the properties of both inline and block. We have seen above that the inline elements are placed next to each other, and their height and width that are explicitly set don't get rendered. In contrast, the block elements render the height and width set by us.

Inherit: It is used to inherit the property of the element from its parent elements. Many times we create nested elements, i.e., a <div> inside a <div>, so instead of specifying its CSS every time, we can simply inherit it from its parent's CSS.


Or 

display: block: This property sets an element to display as a block-level element, which means that it takes up the full width of its parent container by default and begins on a new line. Block-level elements can also have padding, margins, and borders, and can contain other elements inside them.

display: inline: This property sets an element to display as an inline-level element, which means that it does not start on a new line and only takes up as much width as necessary for its content. Inline-level elements cannot have padding, margins, or borders applied to them, but can be nested inside other inline-level elements or block-level elements.

display: inline-block: This property sets an element to display as an inline-level element, but also allows it to have padding, margins, and borders applied to it like a block-level element. This is useful for creating elements that need to be positioned within a line of text, but also require some extra spacing or formatting.

display: inherit: This property sets an element to inherit its display property from its parent element. This is useful when you want to ensure that a child element has the same display behavior as its parent element, without having to explicitly set the display property for each child element.

