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
 
You can group selector by putting a "," comma in between

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

  note the different way to specificy color?
  You can specify color by using visual code auto just typing backgroundand colors
  you can also use color: rgb(0,0,12) (u can choose the numbers) also rgb is red,green,blue choosing the number will choose the color out of those three.
  or you can use color: rgba which is kinda the same thing just added a color 
  Another form is hex= color: #ff0000 which is something to learn in the future.
 
why it is important contrast?
 hsl mean Hues-Saturation-Lightness
  The color palettes can help you pick out color to put in your css. 
   It is important to contrast because if its to faded then your background it will be hard to see.
   If the colors are to bright and it will clash to were it will make your website hard to read.










h1w4/cssh1
rem=font size of the root element
Dont set font size for html root element let the browser auto set it

If using just em and not rem it will make the pixel larger. 
 use rem on font size the em doesnt look at parents it looks at the element
 ch helps define columns in late outs

 
 h2Boxmodelh2

You can find the boxmodel in devtools

Inside the box model is first the content, padding,boarder, and then margin

click styles and then computed to see the box model pixels to see exactly whats going on with your element 

Its good to use the default styles that are set and then go back and change what you need to change. 


h2font family/fallback/quotesh2

When choosing a font family if it cant find the first choose it will has suggested font that it will choose as a fall back.


h2hyperlinkh2

before visting the link it is blue 
after visitng the link its purple
you want your hyperlink to stand out 

h3psudeo class and specificityh3
 psuedeo represent the current state of the element like if its been visited or not
 
 the anchor element with a psudeo has more specificity than the element or others.
 also one can over ride the others have it in the right order 

 anchor tag  
visited class 
hover class
active class







