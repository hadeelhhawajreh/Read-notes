# css 
CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.

# CSS Associates Style rules with HTML elements

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.
p {
 font-family: Arial;}
 P -> is a  Selectors indicate which element the rule applies to.  The same rule can apply to more than one element if you separate the element names
with commas.
font-family: Arial; -> Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value),
and are separated by a colon.
 -> CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify
 several properties in one declaration, each separated by a semi-colon.
  
  **Common  Type of selector**
  |Selector           | Meaning                                 |  Example  |
  |-------------------|:---------------------------------------:|----------:|
  |Universal Selector |  Applies to all elements in the documen | * {}      |
  |-------------------|:---------------------------------------:|----------:|
  |Type Selector      |  Matches element namesn                 |h1,h2...   |
  |-------------------|:---------------------------------------:|----------:|
  |Class Selector     |Matches an element whose class attribute |.className |
  |-------------------|:---------------------------------------:|----------:|
  |ID Selector        | Matches an element whose id attribute   |#id        |
  |-------------------|:---------------------------------------:|----------:|
  
  *another type selector:
  -Child Selector
  -Descendant Selector
  -Adjacent Sibling
  -Selector
  -General Sibling
  -Selector
  
  
# HOW APPLAYING CSS
1.INLINE
2.EXTERNAL
3.EXTERNAL


* CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.
* X Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).
* X Different types of selectors allow you to target your rules at different elements.
* X Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.
* X CSS rules usually appear in a separate document, although they may appear within an HTML page.
* Color not only brings your site to life, but also helps convey the mood and evokes reactions.
# There are three ways to specify colors in CSS:
 * RGB values
 * hex codes 
  * color names.
  


  
