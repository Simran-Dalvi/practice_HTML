List, Tables & Forms

Chapter 1. List Tag

1.1 Ordered Lists

1. Purpose: Used for creating lists with items that have a specific order.
2. Default: Items are automatically numbered.
3. Nesting: Can be nested within other lists.

1.2 Types of Ordered Lists

* Numeric: (1, 2, 3, ...) attribute: type="1"
* Upeercase letters: (A, B, C, ...) attribute: type="A"
* Lowercase letters: (a, b, c, ...) attribute: type="a"
* Uppercase Roman: (I, II, III, ...) attribute: type="I"
* Lowercase Roman: (i, ii, iii, ...) attribute: type="i"

1.3 Unordered Lists

1. Purpose: Used for lists where the order of items dosen't matter.
2. Default: Items are usually bulleted.
3. Nesting: Can be nested within other lists.

Chapter 2. Table Tag

2.1 `<tr>, <td>, <th>` tags

1. `<tr>` Table Row: Used to define a row in an HTML table.
2. `<th>` Table Header: Used for header cells within a row.
    Text is bold and centered by default.
3.  `<td>` Table Data: This holds the actual data. 

2.2 Captions

1. Purpose: Provides a title or description for a table
2. Placement: Must be inserted immediately after the `<table>` opening tag.
3. Alignment: Centered above the table by default
4. Accessibility: Helps screen readers understand the table's purpose.

2.3 Col Spans

1. Attribute: Uses the colspan attribute in `<td>` or `<th>` taags.
2. Purpose: Allows a cell to span multiple columns horizontally.
3. Alignment: takes the space of the specified number of columns.
4. Layout: Useful for combining cells to create complex table layouts.

Chapter 3. Forms

3.1 Input Tag

1. purpose: Used withing a `<form>` element to collect user input.
2. Self-Closing: The `<input>` tag is self-closing; dosen't require a closing tag.
3. Attributes: Common attributes are name, value, placeholder, and required.

3.2 Action attribute

1. Purpose: Specifies the URL to which the form data should be sent when submitted.
2. Default: If not specified, the form will be submitted to the current page's URL.
3. Server-Side: Usually points to a server-side script (like PHP, Python, etc.) that processes the form data.

3.3 Name and Value property

* 'name' property:
    * ID for Data: Identifies form elements when submitting.
    * Unique: Should be unique to each element for clarity.

* 'value' property:
    * Default Data: Sets initial value for input elements.
    * Sent to server: This is the data sent when form is submitted.

3.4 label Tag

1. Purpose: Adds a text description to form elements.
2. for attribute: Connects the label to a specific form element using the element's id.
3. Accessibility: Makes the form more accessible.
4. Readability: Enhances form readability and usability.

3.5 Input Type

* Date
* File
* Color
* Range
* Button
* Submit
* Radio
* Checkbox
* Select

* Text Area
1. Pupose: `<textarea>` is used for multi-line text input in forms.
    1. rows property: Specifies the visible number of lines in the textarea.
    2. cols property: Sets the visible width measured in average character widths.
2. Resizable: Some browsers allow users to manually resize the textarea.

Chapter 4. iFrame Tag

4.1 using iFrames

1. Embedded Content: Allows you to embed another webpage or multimedia content within a webpage.
2. src Attribute: Specifies the URL of the content to be embedded.
3. Dimensions: Width and Height can be set using width and height attributes.