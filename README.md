Template (AZTI presentations)
============================

This is a template for presentations inspired by the format in PPTX in AZTI. 
You can see an example [here](https://giancarlomcorrea.netlify.app/slides/azti-template/template#/title-slide).

Below, I provide some instructions on how to use this template and how to adapt it to your own presentation. 
I assume that the user has already some experience making presentations using [Quarto](https://quarto.org/).

> **Important**
> The default output format of this template is [Revealjs](https://quarto.org/docs/presentations/revealjs/). 
> There are some another [output formats](https://quarto.org/docs/presentations/) available,
> but the design of this template may change. I suggest you use PowerPoint if you want to use
> PPTX as your main format. 

## First step: Get the Quarto code

This is the [main repository](https://github.com/GiancarloMCorrea/AZTI-revealjs-template). 
You can clone it to have it on your computer.

## Second step: Adapt it to your own case

Once you have the code on your computer, you may want to use it to make your own presentation. There are two ways to do this:

1. Copy the entire folder (*AZTI-revealjs-template*) to a desired location on your computer and rename it (e.g., *MyFirstPresentation*).
Start modifying the **template.qmd** file to make your own presentation. If you want to make a second presentation, you will need to follow the same steps.

2. Copy the entire folder (*AZTI-revealjs-template*) to a desired location on your computer. Rename the folder if you want. 
To make your first presentation, copy and paste the **template.qmd** file in the same folder, and then rename it (e.g., **MyFirstPresentation.qmd**). Start making your changes.
To make a second presentation, follow the same steps (e.g., you may now have **MySecondPresentation.qmd**). Your folder would look like:

```bash
    ├── ...
    ├── AZTI-revealjs-template                    
    │   ├── _extensions   
    │   ├── images 
    │   ├── azti.svg
    │   ├── images
    │   ├── README.md
    │   ├── template.qmd		
    │   ├── MyFirstPresentation.qmd	
    │   └── MySecondPresentation.qmd          
    └── ...
```

I personally prefer the second option, but it is up to you. 

## Instructions

### Images

**All** your images should be located in the *images* folder. 

### Title slide

The default option is to include a background image (*images/main_image.jpg*). Replace this image with some cool figure related to your presentation. 
You can also change the opacity (`data-background-opacity` in the header in **template.qmd**). 
If you want to have a white background, just remove these lines from the header in **template.qmd**:

```
title-slide-attributes:
    data-background-image: "images/main_image.jpg"
    data-background-size: cover
    data-background-opacity: "0.3"
```

- Remember that the subtitle is optional, you can remove it from the header in **template.qmd**.
- If you want to change the font color and size, you will need to do it in the **_extensions/azti/azti.scss** (see `#title-slide` section).

### Last slide

There is no format for this slide. You can make your own design here using your Quarto skills. I personally like the black background and the white AZTI logo.

## Suggestions

Please, [contact me](mailto:gmoron@azti.es) if you have any suggestions or questions. My experience using Quarto and HTML is limited, but I will do my best to incorporate your comments. 