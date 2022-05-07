# Hello HTML

Now we're ready to start do some coding and getting familiar with basics of HTML.

## Create a HTML file

so open your file explorer, and create a folder wherever you want. then open this folder in your text editor, and create a `.html` file and call it "index.html". (You can create a new file manually, if you're using simple text editors)

> "index.html" is a special name because generally when you are creating your first webpage, if index.html is located in your root directory, the browser will take this file as home page of your website.

then type this in your new file:

``` {HTML}
Hello, World!
```

then save this file and go back to your folder in your file explorer and open the file with your prefered browser.
You can see the pure text on your browser and now officially you wrote your first HTML file like a piece of cake.

![HelloHTML](/media/img01.png)

But we want to make our HTML file, like an official one and structured correctly, we need to add some extra code.

### Standard Structure

Now we should use `tags` to make layout for our webpages and those tags will shape our website look.

The first tag that we gonna cover is `doctype` and we're basically going to define what type, the document is gonna be.

``` HTML
<!DOCTYPE html>
```

So this tag is just gonna tell us that this is an HTML file.

Now after that we create `container tags`. There's a lot of tags which are called container and they are basically two tags as starting tag and ending tag and you can put other codes or tages inside them.

So the first container tag is `html tag`:

``` HTML
<!DOCTYPE html>
<html>
...
</html>
```

As you see starting tag and ending tag are basically the same but we use a forward slash before tag name to specify the ending tag.

This html tag is gonna be necessary for any HTML files that you have and this is the highest level tag on our web page.

Now it's time to create two sets of tags:

#### Head Tags

`Head tags` basically work as a command center for your HTML file. they control the media, define document title or description and they are used in importing any resources that we need into our HTML file.

We can create head by writing head tags:

``` HTML
<head>
...
</head>
```

Inside these head tags we can add a `title tag` which will be shown on the browser tab and it can be defined like:

``` HTML
<title>Yasin's Website</title>
```

![Title](/media/img02.png)

#### Body Tags

So the body is where we're gonna put the main content of the HTML page. So everything we write in the body it's gonna show up or at least be rendered by the browser.

and by the same formula we create our `body tags`:

``` HTML
<body>
    Hello, Friend!
</body>
```

So I'm defining all of these different tags and when I open this file in my web browser, so the web browser can parse through all these different tags and it can figure out, how to display the contents you write.

So this is what we have written so far:

``` HTML
<!DOCTYPE html>
<html>
    <head>
        <title>Yasin's Website</title>

    </head>
    <body>
        Hello Friend
    </body>   
</html>
```
