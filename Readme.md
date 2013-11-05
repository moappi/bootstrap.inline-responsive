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
   display:inline-block !important;
```

Implmenents
--------------

+	visible-inline-xs
+	visible-inline-sm
+	visible-inline-lg
+	hidden-inline-xs
+	hidden-inline-sm
+	hidden-inline-lg

Test Cases
--------------
Test cases are included under test, copied and modified from the twitter bootstrap documentation <a href='http://getbootstrap.com/'>here</a>

