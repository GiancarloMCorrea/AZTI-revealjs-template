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

## Get the Quarto code

This is the [main repository](https://github.com/GiancarloMCorrea/AZTI-revealjs-template). 
You can clone it to have it on your computer.

## Adapt it to your own case

Once you have the code on your computer, you may want to use it to make your own presentation. There are two ways to do this:

1. Start modifying the **template.qmd** file to make your own presentation. I suggest you change the name of the folder *AZTI-revealjs-template*.
If you want to make a different presentation, you will need to copy and paste the entire folder and rename it. Then, modify the **template.qmd** again.

    .
    ├── ...
    ├── test                    # Test files (alternatively `spec` or `tests`)
    │   ├── benchmarks          # Load and stress tests
    │   ├── integration         # End-to-end, integration tests (alternatively `e2e`)
    │   └── unit                # Unit tests
    └── ...