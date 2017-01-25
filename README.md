# learn-typography
Learning typography

## LINKS
- http://www.dafont.com/
- https://fonts.google.com/
- http://www.font2web.com/
- https://www.web-font-generator.com/
- https://transfonter.org/
- http://www.cssfontstack.com/
- http://www.typegenius.com/ (combine fonts)
- http://www.as8.it/handouts/mixing-typefaces_U&lc1992.pdf
- http://www.fastprint.co.uk/Assets/User/650-google-fonts-infographic-new.jpg

## TYPES
- **Serif**
> The serifs are small ornaments located at the ends of each letter and are intended to provide greater fluidity in reading. These details make one letter practically connect to another.
![Image of font SERIF](http://i.imgur.com/yEPEymU.png)
- **Sans-serif**
> Fonts without the serif usually look more streamlined. They do not have the ornament that provides fluidity, in contrast can make the text lighter.
![Image of font SANS-SERIF](http://i.imgur.com/s6aHFfJ.png)
- **Monospace**
> As the name says, fonts of fixed spacing, or monospace, always have the same measure between the characters, that is, they do not have kerning. Kerning is an automatic adjustment that approximates characters that would be visually distanced by their shapes.
![Image of font MONOSPACE](http://i.imgur.com/9pyjjnp.png)
- **Coursive**
> They are fountains that simulate a handmade text, with calligraphic letters. Reading this type of font may vary and is usually not the easiest - it is not recommended for paragraph texts.
![Image of font COURSIVE](http://i.imgur.com/RDATtBY.png)
- **FANTASY**
> They are the sources that do not fit the other rules and can have different aspects. When used, they usually stylize titles or decorative elements.
![Image of font FANTASY](http://i.imgur.com/D8OZtgX.png)


## EXTENSIONS
- **TrueType** | Are _highly scalable_ and _lightweight_ fonts in character set. They are the most common sources to enter, their extension is .**ttf**
- **OpenType** | Support a greater number of characters and other languages. Its extension is .**otf**
- **PostScript** | _Focused mainly on printing_, because it has _high definition_ and _great compatibility with printers_. It is found in groups of files. On Windows and Mac, the following extensions make up the source: **.afm**, **.pfb**, and **.pfm**. In Linux, the extensions are: **.pfa** and **.afm**

## COMPOSITONS
### HIERARCHY
- TITLE **>** P
  - The layout of each element of a layout is the importance we want to give to them. It is the way in which the user's look will be conducted to facilitate the location of the information that he wants to find. HTML should be well-developed with the weights and styles compatible with the elements they represent, including to work well on screen readers.
### CONSISTENCY
- If the brand has a visual identity manual, we must use the recommended typography. When there is no manual, we must choose the sources and define the combinations that refer to the characteristics of the brand. Proper distribution of information will also provide more consistent layouts. There should be a pattern of alignment in each section of information.
### CONTRAST
- The relationship of text color to background color or image, font thickness, line height, and margins define the contrast that the text block will produce. Poor contrast makes it difficult to read and too much contrast can make reading tiring. It is important to define a standard that allows for a pleasant reading and also relates to the identity.
### RHYTHM
- **letters, words**
- The spacing between one element and another, the established hierarchy itself, as well as letter spacing or word-spacing determine the pace of the user's reading. A page with a good rhythm is more pleasant and demonstrates that the elements and the content are well distributed in the layout.
### SPACE
- **border, elements**
- Text blocks should be placed in appropriate spaces. In the case of a responsive page, such as this, the breaks should consider a good distribution of the words by the blocks so that they do not form very short lines. If necessary, the blocks should be 100% wide to better allocate the text on devices with screens of smaller width.
### PROPORTION
- It is interesting that the elements are in the layout so that they distribute the weight evenly. With the use of proportion, the layout acquires greater consistency and occupies possible empty spaces. The size of the text elements is directly linked to the content, so in order for there to be a proportion, it is interesting to stipulate a minimum and maximum number of characters.


## COMBINE
- Title with **serif**
- Paragraph with **sans-serif**

## PROPERTIES
### HEIGHTS
![Image of font FANTASY](http://i.imgur.com/7jPK1HB.png)


- **X** | **Height** of the _lower case_ **letter** of the font.
![Image of font FANTASY](http://i.imgur.com/mmChenB.png)

- **VERSAL** | **Distance** from the _baseline_ to the _top_ of the **capital letter**.
![Image of font FANTASY](http://i.imgur.com/ArJEqrs.png)

- **ASCENDANT** | **Height** that some _lowercase_ **letters** reach, being able to _equal_ the height of **versal**.
![Image of font FANTASY](http://i.imgur.com/qBb82xD.png)

- **DESCENDANT** | _Length_ that some letters reach for the _bottom of the baseline_.
![Image of font FANTASY](http://i.imgur.com/zbVSBkM.png)

- **Baseline** | **Axis** that _aligns all characters_.
![Image of font FANTASY](http://i.imgur.com/7BRfJoq.png)

- **Saliênca** | **Curves** at _the base_ of letters that extend beyond the _baseline_, used to _balance the text_. If the types were not positioned like this, they would appear to be wobbling along a text.
![Image of font FANTASY](http://i.imgur.com/HCjLlaA.png)

## UNIT OF MEASURES
- CSS offers a large number of options for units of measure: **in, px, pt, cm, in**, among others. Some units have to do with the physical world and serve well for printing, such as **cm** (inches) and **in** (inches - inches), but they are not functional for web page developments. Others have a fixed size, such as **px** (pixels), work well for web, _but may present problems for responsive sites if the user has specific settings about the size of the browser's font_.

## CSS
- _Set_ font and _get_ especify _type_()
```css
element{
  font-family: 'font1', 'font2', serif | sans-serif | monospace | coursive;
}
```
- **IMPORT** new _fonts_
  - **font-weight: bold** | _Weights_ Variations font
  - **font-style: italic** | Variations font
```css
@font-face{
  font-family: 'name font';
  src: url(path) format(name);
}
```
- **Capitulate** | _Get_ **first-letter**
```css
target:first-letter{
  font-size: value;
}
```
- **QUOTE** | _Change_ caracter **<q></q>**
```css
element{
  quotes: value;
  content: open-quote | close-quote;
}
```
- **Hyphens** | _Best_ **justify** content
```css
target{
  hyphens: auto;
}
```
## HTML
- **&­shy;** | test-e
```html
Test&­shy;e
```

## OBSERVATIONS
- **KERNING** | Automatic _adjustment_ in _letters_
- _CASE_ **font-face** **don't** _work_ check **compatibility** with _browser_ and _font format_
  - **DECLARE** the _format_ using **format(name)**;
- **CONTRAST**
  - **auto** | Text gets _heavy_
  - **low** | _Lower_ readability
- **serif**
  - _classic_
- **sans-serif**
  - _modern_
  - _clean_
- **text uppercase** use *letter-spacing** is _good_ idea, _more readability_
