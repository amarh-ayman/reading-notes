# CSS (Cascading Style Sheets)

CSS is the language for describing the presentation of Web pages (the style), including colors, layout, and fonts. It allows one to adapt the presentation to different types of devices, such as large screens, small screens, or printers. CSS is independent of HTML and can be used with any XML-based markup language. The separation of HTML from CSS makes it easier to maintain sites, share style sheets across pages, and tailor pages to different environments. This is referred to as the separation of structure (or: content) from presentation.

- The following very simple example of a portion of an HTML document illustrates how to create a link within a paragraph.

\<p class="moreinfo">For more information see the
\<a href="http://www.example.com/report">final report\</a>.\</p>

- The class attribute on the paragraph's start tag (“\<p>”) can be used, among other thing, to add style. For instance, to italicize the text of all paragraphs with a class of “moreinfo,” one could write, in CSS:

  p.moreinfo { font-style: italic }

> By placing that rule in a separate file, the style may be shared by any number of HTML documents.
