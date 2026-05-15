HTML and Project Structure

Chapter 1. Semantic Tags

1.1 Semantic / Non- Sematic Tags

Semantic Tags

* Meaningful: Describe content.
* SEO: Good for search engines.
* Accessibility: Useful for screen readers.
* Example: `<header>, <footer>, <article>, <section>, <nav>`

Non-Semantic Tags

* Generic: No specific meaning
* For styling: Used for layout
* No SEO: Not SEo-friendly
* Example: `<div>, <i>, <span>, <b>`

Chapter 2. Body Tags

![image](../images/img6.png)

2.1 Header Tag

1. Purpose: Used to contain introductory content or navigation links
2. Semantic: It's a semantic tag, providing meaning to the enclosed content.
3. Location: Commonly found at the top of web pages, but also appears within `<article>` or `<section>` tags.
4. Multiple Instances: Can be used more than once on a page within different sections.

2.2 Main Tag

1. Purpose: Encloses the primary content of a webpage
2. Semantic: Adds meaning, indicating the main content area.
3. Unique: Should appear only once per page
4. Accessibility: Helps screen readers identify key content
5. Not for Sidebars: Excludes content repeated across multiple pages like site navigation or footer.

2.2.1 Section Tag

1. Purpose: Groups related content in a distinct section.
2. Semantic: Adds structure and meaning
3. Header: Often used with a heading `<h1>` to `<h6>` to indicate section topic.
4. Nested: Can be nested within other `<section>` or `<article>` tags.

2.2.2 Article Tag

1. Purpose: Encloses content that stands alone, like a blog post or news story.
2. Semantic: Provides contextual meaning.
3. Independence: Content should make sense even if taken out of the page context.
4. Multiple Instances: Can be used multiple times on the same page.

2.2.3 Aside Tag

1. Purpose: Contains sidebar or supplementary content.
2. Semantic: Indicates content tangentially related to the main content.
3. Not crucial: Content is not essential to undestanding the main content.
4. Examples: Could hold widgets, quotes, or ads.

2.3 Footer Tag

1. Purpose: For footer content like extra info or links.
2. Semantic: Provides meaning to enclosed content.
3. Location: Typically at the bottom of pages or sections.
4. Content: Includes copyrights, contact info, and social links.
5. Multiple Instances: Can be used more than once on a page.

Chapter 3. Folder Structure

1. Root Directory: Main folder containing all website files.
2. HTML files: Store main.html files at the root level for easy access.
3. CSS Folder: Create a css/ folder for all Cascading Style Sheets/
4. JS Folder: Use a scripts/ folder for Javascript files.
5. Images Folder: Store images in an images/ or image/ folder.
6. Assets: Other assets like fonts can go in an assets/ folder.
7. Sub-directories: For multiple-page websites, use sub-folders to categorize content.

Chapter 4. More Tags

4.1 Navigation Tag

1. Purpose : Encloses navigation links or menus.
2. Semantic: Signals that the content is meant for navigating the site.
3. Common Content: Usually contains lists `<ul>`, `<ol>` of links `<a>`.
4. Accessibility: Aids screen readers in identifying site navigation.

4.2 Block / Inline Elements

Block Elements

* New Line: Start on a new line.
* Full Width: Take up all horizontal space.
* Styling: Can have margins and padding.
* Size: Width and height can be set.
* Examples: `<div>, <p>, <h1>, <ul>, <li>`

Inline Elements

* Flow: Stay inline with text.
* Width: Just as wide as the content.
* No break: No new line between elements.
* Limited styling: Can't set size easily.
* Examples: `<span>, <a>, <strong>, <em>, <img>`

4.3 Div Tag

1. purpose: Acts as a container for other HTML elements.
2. Non-Semantic: Dosen't provide inherent meaning to enclosed content.
3. Styling: Commonly used for layout and styling via css
4. Flexibility : Highly versatile and can be customized using classes or IDs.

4.4 Span Tag

1. Purpose: Used for inline elements to style or manipulate a portion of text.
2. Non- Semantic: Dosen't add specific meaning to the enclosed text.
3. Styling: Commonly used for changing color, font, or adding effects via CSS.
4. Inline Nature: Dosen't break text flow or create a new block-level element.