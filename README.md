[![Screenshot of the Website](https://raw.githubusercontent.com/mikepierce/conference-website-template/master/screenshot.png)](https://mikepierce.github.io/conference-website-template/)

---

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Buy Me a Coffee](https://img.shields.io/badge/Buy%20Me%20a-Coffee-orange)](https://www.buymeacoffee.com/mpierce)

An HTML/CSS website template perfect for a small academic conference or seminar.
It's quick and straightforward to customize.
You can [explore it live here](https://mikepierce.github.io/conference-website-template/),
and see some folks' use of the template
[here](https://math.ucr.edu/~mathconn/) 
and [here](https://data-science-conference.github.io) 
and [here](https://aquaticdatasciopensci.github.io) 
and [here](https://comp-expe.github.io) 
and [here](https://enba-phd-call.github.io).
Let me know if you create a nice site from my template so I can feature you here ☺

## Installation

If you have access to server for web hosting, 
perhaps through your university or academic department, 
then using this template is as easy as cloning this repository 
directly into your public HTML directory.
If not you can pretty easily host a website using this template with [GitHub Pages](https://pages.github.com/).
See that link for more details, but the basic procedure is this:

 1. Create a GitHub repository named `username.github.io`, 
 where *username* is your username on GitHub.

 2. Click the *Use this template* button above, 
 being sure to give your copy of this repository a more apt name,
 like *awesome-conference*.

 3. In your copy go to *Settings* and scroll down to *GitHub Pages*.
 Under *Source* choose the master branch of your forked copy.
 Then your copy of the website will be hosted at `username.github.io/awesome-conference`.

## Beautiful Math with MathJax

It may be helpful to include mathematical notation on this website,
especially in the abstracts of talks. 
This can be done using [MathJax](https://github.com/mathjax/MathJax).
For an example see the [*programs* page](https://mikepierce.github.io/conference-website-template/program/) of the template site.
To include math in a page of this website, include the line

````HTML
<script type="text/javascript" async 
    src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=default"> 
</script>
````

in the `<head>` of that page. Then math can by typeset by using LaTeX's math notation enclosed in `\(...\)` delimiters.

## Sitemap (optional)

The `sitemap.xml` helps search engines understand the structure of the site.
In this file, each instance of "WEBSITE" should be replaced
with the actual address where this website is being hosted.
See the [sitemaps protocol page](https://www.sitemaps.org/protocol.html) for more details.

## Alternatives

The simplicity of the HTML/CSS source for this template is its strongest feature.
For something more slick/modern/sophisticated/complicated:

 - [Hoverboard](https://github.com/gdg-x/hoverboard) is beautiful but requires some tech know-how.

 - You can build something from scratch based on a 
 [GitHub Pages site with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll) 
 or a template from [Pixelarity](https://pixelarity.com).

