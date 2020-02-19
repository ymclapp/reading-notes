## Reading for O5

### From the Duckett HTML book:

#### Chapter 5: “Images” (pp.94-125)
- The -img- element is used to add images to a web page
    - Some stock photo sites: www.istockphoto.com www.gettyimages.com www.veer.com www.sxc.hu www.fotolia.com
- You must always specify a src attribute to indicate the source of an image and an alt attribute to describe the content of an image
    - This can be either an outside link or a file within your repo
    - Inside = imag/quokka.jpg
    - Outside = you will use the url for the image.  It is best to save it to your img file and not have to rely on it loading from an outside site.
    - Also add alt to give the image a title for when the image can't be seen.  Ex. alt = "A family of quokka"
- You should save images at the size you will be using them on the web page and in the appropriate format
    - example of how to size:  -img src="images/quokka.jpg" alt="A family of quokka" width="600" height="450" /-
- Photographs are best saved as JPEGs; illustrations or logos that use ﬂat colors are better saved as GIFs

#### Chapter 11: “Color” (pp.246-263)
- Color not only brings your site to life, but also helps convey the mood and evokes reactions.
    - There are foreground and background colora
- There are three ways to specify colors in CSS: RGB values, hex codes, and color names.
    - RGB values - Values for red, green, and blueare expressed as numbers between 0 and 255
    - hex codes - Hex values represent valuesfor red, green, and blue inhexadecimal code
    - color names - Colors are represented bypredened names. However,they are very limited in number
- Color pickers can help you ﬁnd the color you want.
- It is important to ensure that there is enough contrast between any text and the background color (otherwise people will not be able to read your content).
- CSS3 has introduced an extra value for RGB colors to indicate opacity. It is known as RGBA.
    - Opacity is how solid the item is
- CSS3 also allows you to specify colors as HSL values, with an optional opacity value. It is known as HSLA.

#### Chapter 12: “Text” (pp.264-299)
- There are properties to control the choice of font, size, weight, style, and spacing.
    - font - font-family: Georgia, Times, serif;
    - size - font-size: 12px;
    - weight - font-weight: bold;
    - style - font-style: italic;
        - Only three choices:  normal, italic, oblique
    - spacing - letter-spacing: 0.2em; word-spacing: 1em;
- There is a limited choice of fonts that you can assume most people will have installed.
- If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.
    - Ex. www.fontsquirrel.com www.fontex.org www.openfontlibrary.org
- You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justiﬁed. 
- It can also beindented.You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, orwhen they have visited a link.