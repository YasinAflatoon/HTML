# Links

In this tutorial, we're gonna talk about using links in HTML. Links are one of the most commonly used elements on web pages and we can use them to create a connection between web pages. So it's essential to know how they are created.

We can create links to sites or elements which are in or out of our website.

To create a link to an external element, we need to use a tag called `a`. and then we use the`href` attribute.

``` HTML
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="This is how we link to external pages.">
        <meta name="keywords" content="Front-end, HTML">
        <meta name="author" content="Yasin Aflatoon">
        <title>Yasin's Website</title>
    </head>
    <body>
        <a href="https://www.Google.com">Google's Homepage</a>
    </body>   
</html>
```

> * When you create an external link, remember to use `https://` or `http://` phrases because you need to be specific about them.
> * The text you type inside \<a\> tag, will be shown as the links' name.

![ExternalLinkExample](/media/img06.png)

In the example above, if we click on the link, it will open google in the tab we're already browsing, to prevent this and open our link in a new tab we need to add an extra attribute to our \<a\>:

``` HTML
<body>
    <a href="https://www.Google.com" target="_blank">Google's Homepage</a>
</body>
```

* To create a link to pages that are in the same directory as your index file, all you need to do, is to type the file name with the format.

``` HTML
<body>
    <a href="page2.html"><h1>Page 2</h1></a>
</body>
```

* To create a link to pages that are in the same root directory but a different folder, you need to specify the folder's name first, then the file name with the format.

``` HTML
<body>
    <a href="dir1/page3.html"><h1>Page 3</h1></a>
</body>
```

* To add files to your document, you can use the same formula and write the file name with the format.

![Links](/media/img07.png)
