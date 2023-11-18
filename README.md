# css-tricks
css tricks give you useful snippets for your web projects.  Also, sample .sass and .less programs &amp; definitions.


# Highlighting obligatory form fields
You can optimize forms embedded in your website by using :required and :optional. Both the pseudo classes allow color to indicate which form fields have to be filled out and which are optimal. The corresponding CSS snippet looks like this:

:required {
  border: 1px solid red;
}

:optional {
border: 1px solid black;
}
In this case, the required fields get a red border while the optional fields are displayed with a plain black frame:

Highlighted form fields
The two applied CSS pseudo classes highlight certain form fields depending on their importance
Lists with triangular bullet points
If you have unordered lists in your HTML document, you don’t always need to use the standard round bullet points. With the following CSS trick you can easily create triangular bullet points:
