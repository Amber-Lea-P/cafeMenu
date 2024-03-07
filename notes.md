You now have three type selectors with the exact same styling. You can add the same group of styles to many elements by creating a list of selectors. Each selector is separated with commas like this:

selector1, selector2 {
  property: value;
}

Comments in CSS look like this:

/* comment here */

A class selector is defined by a name with a dot directly in front of it, like this:

.class-name {
  styles
}

article elements commonly contain multiple elements that have related information.

 p elements are block-level elements, so they take up the entire width of their parent element
 To get them on the same line, you need to apply some styling to the p elements so they behave more like inline elements

 The p elements are nested in an article element with the class attribute of item. You can style all the p elements nested anywhere in elements with a class named item like this:

  .item p { }

  The typography of heading elements (e.g. h1, h2) is set by default values of users' browsers.

  Note that hr elements are self closing.
  The default properties of an hr element will make it appear as a thin light grey line. You can change the height of the line by specifying a value for the height property.

  o make the image behave like heading elements (which are block-level), create an img type selector and use the value block for the display property and use the applicable margin-left and margin-right values to center it horizontally.

  add a negative top margin to the img elements to pull them up from their current positions. Negative values are created using a - in front of the value.