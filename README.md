# css-tricks
css tricks give you useful snippets for your web projects.  Also, sample .sass and .less programs &amp; definitions.

# Changing website elements with CSS filters
CSS is not only a good alternative to Photoshop when it comes to shading; the style sheet language also comes with useful filter effects, similar to those of image editing programs. This is how graphics, backgrounds, texts, and videos can be creatively adapted by increasing the brightness, changing the contrast, or using grayscale. The filter options are available in nearly all modern browsers (except Internet Explorer). You can see the syntax of these CSS effects in the grayscale filter example:

```
.grayscale {
  -webkit-filter: grayscale(1);
  filter: grayscale(1);
}
```

The specified filter (grayscale in this case), is displayed in parenthesis and comes after the specific value, which determines the strength of the filter – in this example, the value (1) corresponds to 100%.
<image>

CSS enables you to customize graphic web elements with filter details such as 'grayscale'

| Filter | Description | Value |
| ----- | --------------- | --------- |
blur(VALUE) | Soft focus | Radius in Pixels |
brightness(VALUE) | Brightness | Standard: 1, brighten: >1, darken: <1 |
contrast(VALUE) | Contrast | Standard: 1, increase: >1, decrease: <1 |
invert(VALUE) | Invert colors | Value of 1: complete inversion |
opacity(VALUE) | Opacity | Maximum value: 1 (the element completely disappears) |
saturate(VALUE) | Sättigung | Standard: 1, increase: >1, decrease: <1 |
sepia(VALUE) | Sepia colors | Maximum value: 1 (corresponds to a Sepia tone of 100%) |

# Highlighting obligatory form fields
You can optimize forms embedded in your website by using :required and :optional. Both the pseudo classes allow color to indicate which form fields have to be filled out and which are optimal. The corresponding CSS snippet looks like this:

```
:required {
  border: 1px solid red;
}

:optional {
border: 1px solid black;
}
```

In this case, the required fields get a red border while the optional fields are displayed with a plain black frame:

Highlighted form fields
The two applied CSS pseudo classes highlight certain form fields depending on their importance
Lists with triangular bullet points
If you have unordered lists in your HTML document, you don’t always need to use the standard round bullet points. With the following CSS trick you can easily create triangular bullet points:
