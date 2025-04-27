
added a pdf layout for linking to pdfs
- file location: _layouts/pdf.html

added page.image to be set as og_image if page.header.og_image is not supplied
- file location: _includes/seo.html

## Organization of files directory
I added subdirectories in the files directory to better organize the "raw" files needed for my website.

```
files/
├── CV.pdf
├── images
│   ├── image1.png
│   └── image2.png
├── presentations
│   ├── slides1.pdf
│   └── slides2.pdf
├── research
│   ├── code
│   |   ├── script1.R
│   |   └── script2.py
│   └── papers
│       ├── paper1.pdf
│       └── paper2.pdf
├── statements
│   ├── statement1.pdf
│   └── statement2.pdf
└── teaching
    ├── evaluations
    │   ├── evals1.pdf
    │   └── evals2.pdf
    └── syllabi
        ├── syllabus1.pdf
        └── syllabus2.pdf
```

## Where to add images that are to be included as part of the page layout and how to name them

To help with the explanation, suppose we want to use myheadshot.png as the default headshot for the website. 

1. Create a copy of myheadshot.png named default_headshot.png
2. Add original image to /files/images/ directory
3. Add the copy of the image to /assets/images/

Doing this ensures updating the imaged used as the headshot in the future only requires changing the /assets/images/default_headshot.png file rather than having to update the name of the new headshot file in multiple locations/pages.
