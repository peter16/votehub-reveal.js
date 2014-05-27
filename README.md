votehub.js
==========

This is a JavaScript library for HTML framework reveal.js. It allow you easily insert your surveys from [Votehub](http://www.votehub.net/en) to the presentations.

**More reading:**

  * [Installation](https://github.com/peter16/votehub.js#installation): Step-by-step instructions for getting votehub.js running on your computer.
  * [Browser Support](https://github.com/peter16/votehub.js#browser-support): Explanation of browser support.

**What is reveal.js**

It's a framework for easily creating beautiful presentations using HTML. [More info here.](https://github.com/hakimel/reveal.js)

**Basic setup of reveal.js**

The core of reveal.js is very easy to install. You'll simply need to download a copy of this repository and open the index.html file directly in your browser.

1.  Download the latest version of reveal.js from https://github.com/hakimel/reveal.js/releases

2.  Unzip and replace the example contents in index.html with your own

3.  Open index.html in a browser to view it

Installation
-----------

1. Open index.html and add to the HEAD this code:

```html
<script src="http://code.jquery.com/jquery-2.1.1.min.js"></script>
<script src="http://www.votehub.net/static/contrib/reveal/votehub-reveal-1.0.0.min.js"></script>
<link rel="stylesheet" href="http://www.votehub.net/static/contrib/reveal/votehub-reveal-1.0.0.min.css">
<script>
$(function(){
votehub('YOUR_API_KEY');
});
</script>
```

2. Set your own API key which you find [in your profile.](http://www.votehub.net/en/accounts/api-keys/)

3. Open a 'My surveys' tab in Votehub. There are all your surveys. If you don´t have create one. Choose one survey and click on 'Share'. There is a URL address field: http://www.votehub.net/xxx/ (instead of xxx there is a ID of segment). Remember this ID.

4. Add a new section to your index.html:
 if you want to display a questions:
 ```
 <section id="question-xxx">
 </section>
 ```
 if you want to display a stats:
 ak chceme zobraziť štatistiky prieskumu:
 ```
 <section id="stats-xxx">
 </section>
 ```
 if you want to display a correct answers (if you create a quiz question):
 ak chceme zobraziť odpovede prieskumu:
 ```
 <section id="answer-xxx">
 </section>
 ```

Príklad, ak chceme zobraziť jednotlivé otázky zo segmentu 636, tak pridáme tento kód:
\begin{verbatim}
<section id="questions-636">
</section>
\end{verbatim}
%toto dať do prirucky

Installation
-----------
