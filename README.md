jsonerator
==========


Overview
--------

Minimal web interface to create a personal JSON for [Smart Spaces](http://smartspac.es) (and the greater Internet of Things).  Simply enter any or all of the fields at left and the JSON will automatically be populated.  Try it live via GitHub pages: [reelyactive.github.io/jsonerator/](http://reelyactive.github.io/jsonerator/)

![jsonerator Screenshot](http://reelyactive.com/images/jsonerator-barnowl.png)

Yes, by _minimal_ we mean __minimal__.  We've intentionally kept it this way so that you can easily understand the code and quickly style the page as you wish with CSS.  In most cases, we expect this code to be embedded in an existing page.


Installation
------------

Simply clone the repository and open the index.html file in your favourite web browser.


JSON-LD and schema.org
----------------------

All data is represented in [JSON-LD](http://json-ld.org/) using [schema.org](http://schema.org/) as a context.  We selected this combination after much reading, research and debate.  Interested in the history of how we came to this decision?  Check out:
- [JSON-LD and Why I Hate the Semantic Web](http://manu.sporny.org/2014/json-ld-origins-2/) by Manu Sporny
- The [Linked Data](http://www.manning.com/dwood/) book by David Wood
- [The Semantic Web, Linked Data & JSON-LD](http://univership.org/projects/qDM2dZP5F5MZ5zgMA/blog), a tale of "Great Ideas & A Lot of Problems" by George Koulouris


Notes
-----

There is absolutely no validation of fields at this time.  Whatever the user enters in the form comes out in the JSON.


License
-------

MIT License

Copyright (c) 2014-2015 reelyActive

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN 
THE SOFTWARE.

