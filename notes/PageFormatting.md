# Page Formatting

In this tutorial, we're going to view some HTML tags to lay out the structure of your website. We already learned about header, body, and paragraph tags. But now we're gonna learn about tags which specifically help us to arrange content on our into different parts.

As you may know, every webpage has 3 distinct sections: Header, Body, and footer. Header is the element that we can see at the top of every webpage that normally carries some branding information or navigation bar. and the body tag is where we can store the main content of our article. And footer is where we normally use it for conclusions or maybe additional links.

HTML has the tags to define these sections, so inside the body tags, we can create a `header` tag. So any code we write inside these tags is going to act as the header of our webpage.

## Header Tag

``` HTML
<body>
    <header>
        Our article's header goes here.
    </header>
</body>
```

> Remember not to mix up \<head\>, \<h\> and \<header\>.

### Navigational Tag

Inside the header tag, we can define a navigation menu that mostly contains links to other pages of our website. So we put these navigational elements inside something called a navigation tag.

``` HTML
<body>
    <header>
        <nav>
            
        </nav>
    </header>
</body>
```

## Main Tag

The next tag is called `main`, where we write the main body for our webpage.

``` HTML
<body>
    <header>
        Our article's header goes here.
    </header>
    <main>
        The main body goes here.
    </main>
</body>
```

### Article Tag

The article tag is used as a subtle for main tag to specify that our main tag content is formatted as an article.

``` HTML
<body>
    <article>

    </article>
</body>
```

#### Section Tag

You can divide your article tag into different sections you you can specify them easily by using the `section` tag.

``` HTML
<body>
    <article>
        <section>
            First section goes here...
        </section>
        
        <section>
            Second section goes here...
        </section>
    </article>
</body>
```

##### Aside Tag

Aside tags are used for that kind of content that isn't directly related to the main topic of your webpage like ads or similar stuff.

``` HTML
<body>
    <article>
        <section>
            First section goes here...
        </section>
        
        <section>
            <aside>

            </aside>    
        </section>
    </article>
</body>
```

## Footer Tag

and finally, we have the `footer` tag.

``` HTML
<body>
    <header>
        Our article's header goes here.
    </header>
    <main>
        The main body goes here.
    </main>
    <footer>
        Footer goes here.
    </footer>    
</body>
```

Using page formatting tags is not necessary, but it's highly recommended to do because:

* It's useful for the SEO (Search Optimization System) for your site.
* It makes the code readable and clean so other developers can understand the code easily.
