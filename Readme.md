bootstrap.inline-responsive
=========

For Bootstrap 3.0
------------------
<a href='https://github.com/twbs/bootstrap'>Bootstrap 3.0</a> implements responsive design a little differently than in 2.3.x.  All visible and hidden responsive classes use 

```css
   display:block !important;
```

causing all elements which use these responsive classes to become block elements.  This css file extends the responsive classes to include the following inline variations which use

```css
   display:inline !important;
```

and

```css
   display:inline-block !important;
```

Implements (inline)
--------------

+	visible-inline-xs
+	visible-inline-sm
+	visible-inline-lg
+	hidden-inline-xs
+	hidden-inline-sm
+	hidden-inline-lg

Implements (inline-block)
--------------

+	visible-inline-block-xs
+	visible-inline-block-sm
+	visible-inline-block-lg
+	hidden-inline-block-xs
+	hidden-inline-block-sm
+	hidden-inline-block-lg


Test Cases
--------------
Test cases are included under test, copied and modified from the twitter bootstrap documentation <a href='http://getbootstrap.com/'>here</a>

License
--------------

Copyright (c) 2013 Crystalline Technologies
 Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the 'Software'), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense,  and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


