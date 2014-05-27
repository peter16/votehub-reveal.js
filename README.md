votehub.js
==========

This is a JavaScript library for HTML framework reveal.js. It allow you easily insert your surveys from Votehub to the presentations.

**More reading:**

  * [Installation](http://example.com): Step-by-step instructions for getting votehub.js running on your computer.
  * [Changelog](http://example.com): Up-to-date version history.
  * [Browser Support](http://example.com): Explanation of browser support.
  * [Examples](http://example.com): Some presentations created with surveys.

**What is reveal.js**

It's a framework for easily creating beautiful presentations using HTML. https://github.com/hakimel/reveal.js

**Basic setup of reveal.js**

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1.  Download the latest version of reveal.js from https://github.com/hakimel/reveal.js/releases

2.  Unzip and replace the example contents in index.html with your own

3.  Open index.html in a browser to view it

Installation
-----------

<script src="http://code.jquery.com/jquery-2.0.3.js"></script>
<script src="http://www.votehub.net/votehub.js"></script>
<link rel="stylesheet" href="http://www.votehub.net/votehub.css">
<script>
$(function(){
votehub('<API_key>');
});
</script>
