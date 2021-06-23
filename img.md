# Images, Color, Text 

> ## Images : 
- There are many reasons why you might 
want to add an image to a web page: you 
might want to include a logo, photograph, 
illustration, diagram, or chart.
- There are several things to consider when selecting and 
preparing images for your site, but taking time to get them 
right will make it look more attractive and professional.

### storing images on your site : 
- As a website grows, keeping 
images in a separate folder 
helps you understand how the 
site is organized. Here you can 
see an example of the files for 
a website; all of the images are 
stored in a folder called images 
### Adding images : 
- `<img>` : 
To add an image into the page 
you need to use an <img> 
element. This is an empty 
element (which means there is 
no closing tag). It must carry the 
following two attributes

- `<src>` : 
This tells the browser where 
it can find the image file. This 
will usually be a relative URL 
pointing to an image on your 
own site. (Here you can see that 
the images are in a child folder 
called images — relative URLs 
were covered on pages 83-84). 
- `<alt>` : 
This provides a text description 
of the image which describes the 
image if you cannot see it.
- `<title>` : 
You can also use the title 
attribute with the <img> element 
to provide additional information 
about the image. Most browsers 
will display the content of this 
attribute in a tootip when the 
user hovers over the image

### Three rules for Creating Images :
- **Save  Images In 
the right format**
Websites mainly use images in 
jpeg, gif, or png format. If you 
choose the wrong image 
format then your image might 
not look as sharp as it should 
and can make the web page 
slower to load

- SAVE IMAGES AT THE RIGHT SIZE 
You should save the image at 
the same width and height it will 
appear on the website. If 
the image is smaller than the 
width or height that you have 
specified, the image can be 
distorted and stretched. If the 
image is larger than the width 
and height if you have specified, 
the image will take longer to 
display on the page

- **Use the Correct
resolution**
Computer screens are made up 
of dots known as pixels. Images 
used on the web are also made 
up of tiny dots. Resolution refers 
to the number of dots per inch, 
and most computer screens only 
show web pages at 72 pixels 
per inch. So saving images at 
a higher resolution results in 
images that are larger than 
necessary and take longer to 
download

- The  `<img>` element is used to add images to a         
web page.
- You must always specify a `src` attribute to indicate the 
source of an image and an `alt` attribute to describe the 
content of an image.
- You should save images at the size you will be using  
them on the web page and in the appropriate format.
- Photographs are best saved as JPEGs; illustrations or  
logos that use flat colors are better saved as GIFs.

> ## Color : 
- The color property allows you 
to specify the color of text inside 
an element. You can specify any 
color in CSS in one of three ways:

- **rgb values** These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)
 - **hex Codes**
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80
- **Color names**
There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan
We look at these three different 
ways of specifying colors on the 
next double-page spread.
CSS3 has also introduced 
another way to specify colors 
called HSL

### Background color : 
- CSS treats each HTML element 
as if it appears in a box, and the 
background-color property 
sets the color of the background 
for that box.<br> 
You can specify your choice of 
background color in the same 
three ways you can specify 
foreground colors: RGB values, 
hex codes, and color names 
(covered on the next page).<br>
If you do not specify a 
background color, then the 
background is transparent. <br>
By default, most browser 
windows have a white 
background, but browser users 
can set a background color for 
their windows, so if you want 
to be sure that the background 
is white  you can use the 
background-color property on 
the `<body>` element.<br>

> ## TEXT : 
- Typeface Terminology : 

**Serif** : 
Serif fonts have extra details on 
the ends of the main strokes of 
the letters. These details are 
known as serifs.

**SanS-Serif**  : 
Sans-serif fonts have straight 
ends to letters, and therefore 
have a much cleaner design.

**MonoSpace**  : 
Every letter in a monospace (or 
fixed-width) font is the same 
width. (Non-monospace fonts 
have different widths.)