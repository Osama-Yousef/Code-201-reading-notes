# Read:05 Summary 
## From the Duckett HTML book:
### Chapter 5: “Images” (pp.94-125)

* A picture can say a thousand words, and great images help make the difference between an average-looking site and a really engaging one
* If you are building a site from scratch, it is good practice to create a folder for all of the images the site uses.
* On a big site you might like to add subfolders inside the images folder. 
* For adding img to my html page we use this syntax : `( <img src="images/quokka.jpg" alt="A family of   quokka" title="The quokka is an Australian   marsupial that is similar in size to the   domestic cat." width="600"  height="450"  /> `
* `src` This tells the browser where it can find the image file
* ` alt` This provides a text description of the image which describes the image if you cannot see it.
* `title` : to provide additional information about the image
* height This specifies the height of the image in pixels
* width This specifies the width of the image in pixels.
* The size of images is increasingly being specified using CSS rather than HTML 
* we can put the `<img..><p>..` tag before the paragraph so The paragraph starts on a new line after the image
* `<p><img .../>` The first row of text aligns with the bottom of the image.
* ` <p><img..></p>` we can put the image  In the mIddle of a paragraph The image is placed between the words of the paragraph that it appears in.

* There are three rules for CreatIng Images :
   * saVe Images In the rIght format
   * You should save the image at the same width and height it will appear on the website
   * use the CorreCt resolutIon
* tools you can use to edit and save images to ensure that they are the right size, format, and resolution.such as : 
Adobe Photoshop ,Adobe Fireworks, Pixelmator, PaintShop Pro , Paint.net
* Image formats :
  * Jpeg : Whenever you have many different colors in a picture 
  * gIf and png : Use GIF or PNG format when saving images with few colors or large areas of the same color
  * When cropping images it is important not to lose valuable information. It is best to source images that are the correct shape if possible
* Images created for the web should be saved at a resolution of 72 ppi. The higher the resolution of the image, the larger the size of the file.
* Animated GIFs show several frames of an image in sequence and therefore can be used to create simple animations
* for CheCkIng the sIze of Images and doWnloadIng them : ( in the Chrome : to check Size: Open Image in New Tab then Size appears in new tab.for Download: Save Image As )
* `(<figure><img></figure> ) ` figure element : to contain images and their caption so that the two are associated.so to add a caption you can use the form : `( <figure><img src="images/otters.jpg"><figcaption>text..</figcaption> </figure> )`

------------------------------------------------------------------------------------------------------------------------------------

### Chapter 11: “Color” (pp.246-263)

* Color can really bring your pages to life.
* You can specify any color in CSS (Foreground & baCkground color) in one of three ways:
 * rgb values 
 * hex Codes 
 * Color names 
* Every color on a computer screen is created by mixing amounts of red, green, and blue (rgb)
* When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to 
be legible and easy to read especially a lot of texts
* opacity property which allows you to specify the opacity of an element and any of its child elements.
* CSS3 introduces an entirely new and intuitive way to specify colors using (hue, saturation, and lightness values)(hsl)
-----------------------------------------------------------------------------------------------------------------------------------

### Chapter 12: “Text” (pp.264-299)











