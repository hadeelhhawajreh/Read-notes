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


  
