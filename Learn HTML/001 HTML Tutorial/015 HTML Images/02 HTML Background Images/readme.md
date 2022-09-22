HTML Background Images
---


A background image can be specified for almost any HTML element.

Background Image on a HTML element
---
To add a background image on an HTML element, use the HTML `style` attribute and the CSS `background-image` property:

Example
Add a background image on a HTML element:

```
<p style="background-image: url('img_girl.jpg');">
```


You can also specify the background image in the `<style>` element, in the `<head>` section:

Example
Specify the background image in the `<style>` element:

``` 
<style>
p {
  background-image: url('img_girl.jpg');
}
</style>
```

  
Background Image on a Page
---
If you want the entire page to have a background image, you must specify the background image on the `<body>` element:

Example
Add a background image for the entire page:
```
<style>
body {
  background-image: url('img_girl.jpg');
}
</style> 
```  
  
  
Background Repeat
---
If the background image is smaller than the element, the image will repeat itself, horizontally and vertically, until it reaches the end of the element:

![image](https://user-images.githubusercontent.com/47166768/191812204-14849d49-fb13-41fe-80cd-65931ba7c5ec.png)


Example
``` 
<style>
body {
  background-image: url('example_img_girl.jpg');
}
</style>
```  
  
To avoid the background image from repeating itself, set the `background-repeat` property to `no-repeat`.

Example
```
<style>
body {
  background-image: url('example_img_girl.jpg');
  background-repeat: no-repeat;
}
</style>
```




