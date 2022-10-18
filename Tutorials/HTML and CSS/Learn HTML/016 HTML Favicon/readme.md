HTML Favicon
---

A favicon is a small image displayed next to the page title in the browser tab.

A favicon is a small image displayed next to the page title in the browser tab.

How To Add a Favicon in HTML
---
You can use any image you like as your favicon. You can also create your own favicon on sites like https://www.favicon.cc.

<pre>
<b>Tip:</b> A favicon is a small image, so it should be a simple image with high contrast.
</pre>


A favicon image is displayed to the left of the page title in the browser tab, like this:

![img_favicon](https://user-images.githubusercontent.com/47166768/194711547-13da3915-f4a0-45c3-a4c3-94653038bb14.png)



Example of favicon
To add a favicon to your website, either save your favicon image to the root directory of your webserver, or create a folder in the root directory called images, and save your favicon image in this folder. A common name for a favicon image is "favicon.ico".

Next, add a `<link>` element to your "index.html" file, after the `<title>` element, like this:

    Example

```
<!DOCTYPE html>
<html>
<head>
  <title>My Page Title</title>
  <link rel="icon" type="image/x-icon" href="/images/favicon.ico">
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

Now, save the "index.html" file and reload it in your browser. Your browser tab should now display your favicon image to the left of the page title.


Favicon File Format Support
---
The following table shows the file format support for a favicon image:

|Browser|	ICO|	PNG|	GIF|	JPEG|	SVG|
|-|-|-|-|-|-|
|Edge|	Yes|	Yes|	Yes|	Yes|	Yes|
|Chrome|	Yes|	Yes|	Yes|	Yes|	Yes|
|Firefox|	Yes|	Yes|	Yes|	Yes|	Yes|
|Opera|	Yes|	Yes|	Yes|	Yes|	Yes|
|Safari|	Yes|	Yes|	Yes|	Yes|	Yes|



Chapter Summary
---
Use the HTML `<link>` element to insert a favicon

HTML Link Tag
---
|Tag|	Description|
|-|-|
|`<link>`|	Defines the relationship between a document and an external resource|





