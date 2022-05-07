# Basic Tags

In this tutorial, we're going to cover basic and common HTML tags that you'll probably need a lot in your code, in the previous tutorial we learned about the main structure of an HTML file and now we're going into details.

## Meta Tags

The \<meta\> tag defines metadata about an HTML document. Metadata is data (information) about data. \<meta\> tags always go inside the \<head\> element, and are typically used to specify the character set, page description, keywords, author of the document, and viewport settings.

### Attributes

| Attribue | Value                                                                               | Description                                                          |
| -------- | ----------------------------------------------------------------------------------- | -------------------------------------------------------------------- |
| name     | application-name</br>author</br>description</br>generator</br>keywords</br>viewport | Specifies a name for the metadata                                    |
| content  | text                                                                                | Specifies the value associated with the http-equiv or name attribute |

#### charset

In our meta tag we can define the encoding of our HTML file using the `charset` attribute in a meta tag:

``` HTML
<meta charset="UTF-8">
```

#### description

A meta `description` provides a summary of a web page. and displayed as part of the search snippet in a search engine results page (SERP) and is meant to give the user an idea of the content that exists within the page and how it relates to their search query:

``` HTML
<meta name="description" content="This is how meta tags work">
```

#### keywords

Meta `keywords` are meta tags that you can use to give search engines more information about a page's content. They're found in a webpage's HTML source code, and are not visible to visitors:

``` HTML
<meta name="keywords" content="Front-end, HTML, Tags, Meta">
```

#### author

In our meta tag we can specify the author of the HTML file in a meta tag:

``` HTML
<meta name="author" content="Yasin Aflatoon">
```

> We'll discuss the viewpoint attribute later on.

So up to now we learned about meta tags and we can add them to our HTML file:

``` HTML
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <meta name="description" content="This is how meta tags work">
        <meta name="keywords" content="Front-end, HTML, Tags, Meta">
        <meta name="author" content="Yasin Aflatoon">
        <title>Yasin's Website</title>
    </head>
    <body>
        Hello Friend
    </body>   
</html>
```

Now we head to tags used in body tags.

## Heading Tags

In HTML, we can have 6 heading styles specified by `h`, from h1 to h6:

``` HTML
<body>
    <h1>Yasin's Website</h1>
</body>
```

h1 is the largest heading style and as you move to h6 you can see that the heading text will be shrink.

## Paragraph Tags

Paragraph tags are the easiest to write and they are used for writing a paragraph in our body.

``` HTML
<body>
    <p>This is how we specify a paragraph tag, nice and easy!</p>
    <p>This is another paragraph</p>
</body>
```

The cool thing about paragraphs is that they automatically format themselves. if you add another paragraph tag, HTML will specify them with an empty line.

## Styling Tags

We can also style some words inside this paragraph tags:

### Bold Tag

Inside the paragraph tag, you can put an element in a `Bold` tag, just like this:

``` HTML
<body>
    <p>This is how we specify a <b>paragraph</b> tag, nice and easy!</p>
    <p>This is another paragraph</p>
</body>
```

Now the word "paragraph" will be bolded in our browser.

### Italic Tag

You can also put an element in an `Italic` tag, just like this:

``` HTML
<body>
    <p>This is how we specify a <i>paragraph</i> tag, nice and easy!</p>
    <p>This is another paragraph</p>
</body>
```

Now the word "paragraph" will be italicized.

> We can use these styling tags together to make a word bolded and italicized.

### Big and Small

We have two other tags which we can apply to our paragraph words to make them big, or smaller than normal size.

``` HTML
<body>
    <p>This is how we make a <big>word</big> bigger!</p>
    <p>and another <small>word</small> smaller!</p>
</body>
```

> We can use more than one big/small tag to an element to change its size.

### Break Lines

HTML ignores the white spaces you create in your code so if you tap some "enter"s you'll see any differences. to create that lines, we use a tag called `Break Line`

``` HTML
<body>
    <p>This is how we specify a paragraph tag,<br/> nice and easy!</p>
    <p>This is another paragraph</p>
</body>
```

> Break tag can be written without forward slash too.

and the output will be like:

``` Batch
This is how we specify a paragraph tag,
nice and easy!

This is another paragraph
```

### Horizontal Rule

There is another tag that creates a line that can be used as a Separator. if you wanna have a clear image of this, scroll up to the top of this page. under the "Basic Tags" you can see that line that separates the heading from the rest of the article.

``` HTML
<body>
    <h1>Basic Tags</h1>
    <hr/>
    <p>In this tutorial we're going to cover basic and comman HTML tags that you'll probably need them a lot in your code, in prevoius tutorial we learned about main structure of an HTML file and now we're going in detials.</p>
</body>
```

### Subscript and Superscript

We can also make subscripts and superscripts using tags to style our texts:

``` HTML
<body>
    <p>Chemical formula for water is: H<sub>2</sub>O</p>
    <p>6 square can be shown like: 6<sup>2<sup></p>
</body>
```

The output will be like this:

![SubSupScript](/media/img03.png)
