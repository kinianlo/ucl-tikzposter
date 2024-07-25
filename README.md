## UCL tikzposter Poster Template
Welcome to the UCL tikzposter poster template repository! This template is designed for LaTeX users who want to create posters that adhere to the University College London (UCL) branding guidelines.

### Why another template?
UCL provides official poster templates in PowerPoint format (.pptx) through their [UCL Brand](https://www.ucl.ac.uk/brand/ucl-community/resource-and-templates/presentation-resources) resources. However, there is no official LaTeX template available. This repository fills that gap by offering a LaTeX poster template using the tikzposter package. The template closely follows UCL's official guidelines, including colour schemes, spacing, and font sizes.

### Usage
Simply download or clone this repo and start editing. 

#### Colour schemes
There are a few pre-defined colour schemes according to the [UCL Colour palette](https://www.ucl.ac.uk/brand/brand-essentials/colour-palette)
 - UCLVibrantPurple
 - UCLVibrantGreen
 - UCLVibrantBlue
 - UCLVibrantYellow
 - UCLVibrantPink
 - UCLDarkBlue
 - UCLBlack

Specify the colour scheme using the `\usecolorstyle` command. For instance, if you want to use `UCLVibrantPurple`, simply use `\usecolorstyle{UCLVibrantPurple}`.

#### Advanced tweaks
For finer controls usch as spacings, try to have a look at `ucltikzposter.sty` and identitfy the part you would like to modify. If you are unsure how to make it to your liking, please raise an issue.

### Contributing
Contributions and suggestions are more than welcomed from the UCL community and beyond.

### See Also
 - [ucl-beamer](https://github.com/UCL/ucl-beamer) - a UCL beamer theme for presentations
