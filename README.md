# USYD-Beamer-Theme

This repo contains an unofficial University of Sydney LaTeX Beamer theme for the School of Mathematics and Statistics.

**Created by**: Samantha Clarke

**Current Version**: 0.1

**Updated**: 9 May 2017

**Complied with**: pdflatex

**Based on**: BerlinFU theme (http://www.mi.fu-berlin.de/w/Mi/BeamerTemplateCorporateDesign) and Seth Brown's bunsen theme (http://www.drbunsen.org/home/2011/11/2/designing-a-custom-beamer-template-theme-for-presentations.html). 

Please see the beamerusyd_example.pdf and beamerusyd_example.tex to get an idea of what the theme looks like.

*This template is still under development. Any comments, feedback, additions, or suggestions are welcome.* 

### Getting started:
- Download the files from the GitHub link as a zip file. 
    - GitHub users are welcome to clone or fork. 
- You can now use the beamerusyd_example.tex as you would like any other LaTeX file.
    - If you use R Studio, there is an R Studio project file included if you wish to use that. You will need to set that up the usual wasy you set up R Studio projects (which is not covered here). 

### A few pointers:
- Download the most current version of the **PowerPoint presentation** (standard) from the USYD Staff Intranet - [Basic Design Templates](https://intranet.sydney.edu.au/services/marketing-communications/brand-tools/basic-design-templates.html). 
    - Open in PowerPoint and save as new PowerPoint
- Creating a **Title Slide with USYD Background** from the USYD brand-compliant PowerPoint presentation:
    - Check you have the most recent version of the USYD brand-compliant PowerPoint presentation
    - Open template in PowerPoint 
    - Add a new title slide from the options
    - Leave the slide blank (i.e. do not add any text on the slide)
    - Exception: if you selected a “add your own picture” title slide, insert your picture
    - Save the PowerPoint 
    - Export PowerPoint as a PDF
    - Extract the title page as a single page from PDF
    - Save the single page with a sensible name (e.g. titlebgstdjun16_myimage.pdf)
    - Place this file in the same folder as the Beamer .tex file
    - In .tex file, change the line: \usebackgroundtemplate{\includegraphics[width=\paperwidth,height=\paperheight]{titlebgstd2jun16.pdf}} to the name of your single page background title page PDF file. 
- Creating a **Section Divider Slide with USYD Background** from the USYD brand-compliant PowerPoint presentation:
    - Follow the same as for Title Slide, using a Section Divider slide within the USYD brand-compliant PowerPoint presentation.


