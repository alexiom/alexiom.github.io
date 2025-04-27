
added a pdf layout for linking to pdfs
- file location: _layouts/pdf.html

added page.image to be set as og_image if page.header.og_image is not supplied
- file location: _includes/seo.html


## Updating Default Images

To help with the explanation, suppose we want to use myheadshot.png as the default headshot for the website. 

1. Create a copy of myheadshot.png named default_headshot.png
2. Add original image to /files/images/ directory
3. Add the copy of the image to /assets/images/

Doing this ensures updating the imaged used as the headshot in the future only requires changing the /assets/images/default_headshot.png file rather than having to update the name of the new headshot file in multiple locations/pages.
