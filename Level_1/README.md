HTML Basics

<!-- Images not rendering -->

Chapter 1. Starting up

1.1 First file using Text Editor

1. Create a folder with name First Project.
2. Open Notepad.
3. Create a file and save it as index.html
4. Copy Sample code
5. Open Browser and Check.

1.2 File Extension

HTML
1. Most commonly used.
2. Works across all browsers.
3. Widely recognized and supports.
4. Typically saved as .html.

HTM
1. Less commonly used.
2. Originated for compatibility with older systems.
3. Works same as .html.
4. Typically saved as .htm.

1.3 Open with Live Server (VsCode)

http://127.0.0.1/ is the local host
5500 is the port number

1.4 Importance of index.html

![image](practice_HTML\images\img2.png)

1. Default name of a website's homepage.
2. First page users see when visiting a website
3. Important for SEO (Search Engine Optimization).
4. Provides uniform starting point across servers.
5. Serves as fallback when no file is specified in URL.

(You can also tell the browser to use a file with a different name as the homepage, but no one does that. Everybody uses the default naming convention. )

Chapter 2. Basics of HTML

2.1 What are Tags

![image](images\img3.png)
1. Elements that are used to create a website are called HTML Tags.
2. Tags can contain content ot other HTML tags.
3. Define elements like text, images, links.

2.2 Using Emmet ! to generate code

Type ! and wait for suggestions.

2.3 Basic HTML Page

```bash
<!DOCTYPE html>  --> Defines the HTML Versio
<html lang="en"> --> Parent of all HTML tags / Roo element
<head> --> Parent of meta data tags
    <meta charset="UTF-8"> 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title> --> Title of the web page
</head>
<body> --> Parent of content tag
    <h1> Hello World! </h1> --> Heading tag
</body>
</html>
```