h1What is cascading?h1

In CSS, "cascading" s describes how styles are applied to HTML elements based on a set of rules. These rules are determined by the specificity of the selectors, the order in which they appear, and the origin of the stle.

h2CSS RULESETh2

The selector is the start of the ruleset for html. it defines the elements to be styled.
Declaration specifies elemnts properties that you want to style.
Properties are ways you can style an HTMl element. color is a property of the <P> element. 
Property value helps to choose one out of many possible appearances for a property you are using.]
Note that there are different types of selectors you can use.


notes on why using id in your css?????
 Id should only exist ONCE in a html they should be unique.
 Its not good practice id in your css.

 You should use classes and element selector.
 
You can group selector by putting a "," comma in between.

which ever {} element is used last css will be apllied.
Specificty can over ride it. t

The "." class overules other element Because it has more specifcity than an element selector. This class is not an inheritance class/element.

Inheritance is when another element inheritance the setting or the property from their parent element. 
body element is parent to all other element on css
Anything related to color inhernit size font is inheritance
 what is DRY?
 Inheritance keeps the code from getting dry which is Dont repeat yourself 
 ELEMENT SELECTOR.. is lest specfic and class selector is more  specific.
  dont use !important flag because it will overrides everything and it looks unorganize and sloppy.
  