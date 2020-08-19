# HTML is all you need!

> Text written to accompany a presentation about HTML on an online
> [meetup](https://www.meetup.com/opensanca/events/272507261/)

[This repository](https://github.com/marcel0ll/presentation-html) contains a
[live editor](https://marcel0ll.github.io/presentation-html) that you can see
some HTML examples or experiment on your own. Remember that learning is an
active process and not passive!

Nowadays is easy to get lost on the plethora of javascript frameworks, trying to
create your website and forgetting that to create a website you don't need no
javascript. Plain old HTML is more than enough and although I do belive that
adding javascript might benefit your website, it's always for the best to know
the basics very well.

So today I am going to walk you through the very basics of html, how your
browser reads and renders it, a little bit of what is an HTTP request and point
out where CSS comes in play, but I won't get into much details about CSS.

## What is HTML?

HTML stands for hyper text markup language and it is a [declarative programming
language that is not turing
complete](https://www.youtube.com/watch?v=4A2mWqLUpzw).

It was invented in the beginning of the internet to easily exchange written
documents across the world wide web (WWW) using http, one of it's most
innovative features was that a document could be linked to as many other
documents as someone wanted.  This is the base of what you today use on your
browser.

## What is HTTP?

HTTP stands for hyper text transfer protocol, and as the name implies it has
strong relations with HTML, at least for when and why it was invented.

HTTP is a transfer protocol built on top of the Transmission Control
Protocol(TCP) to reliable transfer files across the WWW enabling hypermedia
information systems. In other words, it allows you to click a link and open
another page or a cat picture. 

> Note: HTTP can be adapted to use User Datagram Protocol(UDP)

## How the browser interacts with all this?

A Browser is basically a an HTTP client that requests files across the web, in
other words it fetchs a file from a server, an HTTP server.

So when you open google.com you request the server responsible for this domain
(google.com) the address "/" and as a response google sends you an HTML file
that your browser will render!

> Note: Right click on browser and look at the page's source code, what you will
> see is a big HTML file.

> Note: Some parts of a page are actually rendered by your operating system(OS)
> and not by the browser. One example is dropdown menus (`<select>`) that will
> look in one way on your computer and a totally different way on your mobile
> phone.


## What can I write in HTML?

Basically text, a lot of it. 

You can also point to other files and your browser will do its best to render
it. For example you might want to show an image alongside your beatiful text, so
what you do is you write some markup that points to another file (an image) that
your browser will make a second request on the background, will get its response
and renders it in your page view.

Note that although most of the common browsers will embed the image file into
the document, not all browsers are like that or may be configured to not do
that. This is the case for browsers like [Lynx](https://lynx.browser.org/), a
terminal based browser that as far as I know only displays texts.

Some people might configure a browser not to load images to test accessibility,
simulate a text browser or they might just not like images.

## HTML syntax

HTML is written using tags that are written like `<tag></tag>`, each tag has its
purpose: add content inside the document, add information about the document or
add semantic structure to the document.

Inside each tag you can declare multiple attributes using the syntax `key="key"`
or just `key`. Like, `<div class="button" disabled>New post</div>`.

Most of HTML tags needs an opening (`<>`) and ending (`</>`), but some can be
opened and closed at once: `<input type="text" />`.

Here is a nice picture of an "html periodic table" by Castus that I've found on
[Smashing
Magazine](https://www.smashingmagazine.com/2015/05/desktop-wallpaper-calendars-june-2015/#periodic-table-of-html5-elements)

![HTML periodic table](./html-periodic-table.jpg)

Those are all HTML tags that existed when this table was designed in 2015,
nowadays there might be some small differences.

I created some HTML examples that you can find in [this
editor](https://marcel0ll.github.io/presentation-html)

Hope you enjoyed, keep coding!

marcel0ll

