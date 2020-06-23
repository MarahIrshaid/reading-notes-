# Chapter 10 Introducing CSS Summary:
CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon

There are 3 ways to link CSS to HTML file:
**1. Using External CSS**
link tag : it contains these :
href : path to CSS
type: This attribute specifies the type
of document being linked to. The
value should be text/css.
rel :  The value
should be stylesheet when
linking to a CSS file.


**2. Using style tag:**
**3. inside the element itself**

#### Types of selectors:

Universal Selector : "star" {} </br>
Type Selector : h1 {} </br>
Class Selector : .{} </br>
ID Selector hashtag {} </br>
Child Selector : li>a {} </br>
Descendant Selector : p a {} </br>
Adjacent Sibling Selector : h1+p {} </br>
General Sibling Selector : h1~p {} </br>

In CSS, inheritance controls what happens when no value is specified for a property on an element. ... inherited properties, which by default are set to the computed value of the parent element. non-inherited properties, which by default are set to initial value  </br>





# Chapter 11 : Color , summary:



**You can specify any color in CSS in one of three ways:**

*Foreground Color:*

1. rgb values:  Values for red, green, and blue
are expressed as numbers
between 0 and 255. </br>

2. hex codes: Hex values represent values
for red, green, and blue in
hexadecimal code </br>

3. names of colors:  Colors are represented by
predefined names. However,
they are very limited in number.</br>

*Background color:* </br>

CSS treats each HTML element
as if it appears in a box, and the
background-color property
sets the color of the background
for that box. </br>

#### Contrast :
1. Low Contrast : harder to read</br>
2. High contrast : Text is easier to read when
there is higher contrast between
background and foreground
colors.
If you want people to read a lot
of text on your page, however,
then too much contrast can
make it harder to read, too.  </br>
3. Medium Contrast : good for reading long texts </br>

#### Opacity:

 you can specify a color
as a hex code, color name or
RGB value, followed by the rule
that specifies an RGBA value. If
the browser understands RGBA
colors it will use that rule. If it
doesn't, it will use the RGB value.

#### CSS3: HSL Colors:
Hue -saturation -lightness

#### CSS3 : HSL & HSLA:
hue
This is expressed as an angle
(between 0 and 360 degrees).
saturation
This is expressed as a
percentage.
lightness
This is expressed as a
percentage with 0% being white,
50% being normal, and 100%
being black

alpha
This is expressed as a
number between 0 and 1.0.
For example, 0.5 represents
50% transparency, and 0.75
represents 75% transparency.




