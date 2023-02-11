## Font Properties
#### Font-Family
Changes the font family of certain words, sentences, paragraphs, etc.
```
P { font-family: "New Century Schoolbook", Times, serif; }
```
#### Font-Style
Changes text: normal, oblique, and italics. H1 { font-style: oblique; }
```
P { font-style: normal; }
```
#### Font-Variant
Used to display font in normal or small-caps. 
```
SPAN { font-variant: small-caps; }
```
### Font-Weight
Used to specify the weight of the font.
```
H1 { font-weight: 800; } or P { font-weight: normal; }
```
#### Font-Size
Used to modify the size of the displayed font.
``` 
H1 { font-size: large; } or P { font-size: 12pt; }
LI { font-size: 90%; }
STRONG { font-size: larger; }
```
####Font
Used to combine all properties of fonts. 
```
P { font: italic bold 12pt/14pt Times, serif; }
```

## Color and Background Properties
#### Color
Changes the color of text.
```
H1 { color: blue; }  
H2 { color: #000080; }
```
#### Background-Color
Sets the background color of an element. 
```
BODY { background-color: white; }
H1 { background-color: #000080; }
```
#### Background-Image
Sets the background image of an element.
```
BODY { background-image: url(/images/foo.gif); }
P { background-image: url(http://www.htmlhelp.com/bg.png); }
```
#### Background-Repeat
Determines how a specified background image is repeated. The repeat-x value will repeat the image horizontally while the repeat-y value will repeat the image vertically.
```
BODY { background: white url(candybar.gif);
background-repeat: repeat-x; }
```
#### Background-Attachment
Determines if a specified background image will scroll with the content or be fixed with regard to the canvas.
```
BODY { 
	background: white url(candybar.gif); 
	background-attachment: fixed; 
}
```
#### Background
Used to combine all properties of background.
```
BODY { background: white url(http://www.htmlhelp.com/foo.gif); } 
BLOCKQUOTE { background: #7fffd4; }

P { background: url(../backgrounds/pawn.png) #f0f8ff fixed; } 
TABLE { background: red url(leaves.jpg) no-repeat bottom right; }
```

## Text Properties
#### Word-Spacing
Defines an additional amount of space between words.
``` 
P EM { word-spacing: 0.4em; }
P.note { word-spacing: -0.2em; }
```
#### Letter-Spacing
Defines an additional amount of space between characters.
```
H1 { letter-spacing: 0.1em; }
P.note { letter-spacing: -0.1em; }
```
#### Text-Decoration
Allows text to be decorated through one of five properties: underline, overline, line-through, blink, none.
```
A:link, A:visited, A:active { text-decoration: none; }
```
#### Vertical-Align
Used to alter the vertical positioning of an inline element, relative to its parent element or to the element's line. 
```
IMG.middle { vertical-align: middle; }
IMG { vertical-align: 50%; }
.exponent { vertical-align: super; }
```
#### Text-Transform
Allows for capitalizing the first letter of each word (capitalize), capitalizing all letters of a word (uppercase), using all small letters in each word(lowercase), and the inital value(none). 
```
H1 { text-transform: uppercase; }
H2 { text-transform: capitalize; }
```
#### Text-Align
Used to justify text left, center, right, and justify. 
```
H1 { text-align: center; }
P.newspaper { text-align: justify; }
```
#### Text-Indent
Used to specify the amount of indentation prior to the first line of text.
```
P { text-indent: 5em; }
```
#### Line-Height
Used to control the spacing between baselines of text. 
```
P { line-height: 200%; }
```
## Classification Properties
#### List-Style-Type
Specifies the type of list-item marker, and is used if list-style- image is none or if image loading is turned off.
```
LI.square { list-style-type: square; }
UL.plain { list-style-type: none; }
OL { list-style-type: upper-alpha; } /* A B C D E etc. */
OL OL { list-style-type: decimal; } /* 1 2 3 4 5 etc. */
OL OL OL { list-style-type: lower-roman; } /* i ii iii iv v etc. */
```
#### List-Style-Image
Specifies the image that will be used as list-item marker when image loading is turned on, replacing the marker specified in the list-style-type property.
```
UL.check { list-style-image: url(/LI-markers/checkmark.gif); }
UL LI.x { list-style-image: url(x.png); }
```
#### List-Style-Position
Determines where the marker is placed in regard to the list item. If the value inside is used, the lines will wrap under the marker instead of being indented. outside is default.
```
UL { list-style-position: inside; }
```

References:

[x] - https://web.stanford.edu/group/csp/cs21/csscheatsheet.pdf