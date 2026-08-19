# MEDIATION data catalog webpage

This repository is the source code for the [MEDIATION catalog webpage](https://mediation-ocean.github.io/mediation-catalog-webpage/). 
The website's architecture follows the same outline as the MEDIATION-catalog Github repository (simulation data / toolboxes & software / observations, topped by a short overview).


# How to add content

## Just a few prerequesites

Want to add a dataset, model configuration, or any product to this catalog all by yourself ? Before doing anything, there are 3 prerequisites to enrich this website with material of your own:

- You must have a [Github account](https://github.com/login),
- You must have been invited as a member of the website repository (the very one you are currently exploring). For this, please provide your github ID to [tino.bellayer@univ-grenoble-alpes.fr](mailto:tino.bellayer@univ-grenoble-alpes.fr).
- Make sure that you are not mistakenly altering other's work! 

# Procedure

Before getting to this github repository, please pre-write your content on your personal machine as a [markdown (.md) file]. 
Just provide a quick plain-text decription and fill in the following template:

for a model run or configuration:

    title
    people in charge and affiliation
    scientific context and background
    related publications
    number of simulations (+number of members if ensemble)
    configurations, parameters, resolution, timestep, domain, span
    target variables
    related processing tools
    calculation cost, volume, access
    other useful informations

for a software:

    title
    people in charge and affiliation
    description
    documentation, tutorials
    access
    other useful informations

Now, in order to add content to the website, you have to make a github commit. Here is ho to proceed: 

- After logging in to github, Simply go to the repository's [main page](https://github.com/MEDIATION-ocean/mediation-catalog-webpage/tree/main).
  ![main page](https://github.com/MEDIATION-ocean/mediation-catalog-webpage/blob/main/images/mainpage.png)

- The only thing you will have to look for is the **content** folder. Click on the folder to access it.
  ![content folder](https://github.com/MEDIATION-ocean/mediation-catalog-webpage/blob/main/images/contentsection.png)
  
- Once there, choose the subfolder that is adapted to your product (Litterature, simulations, software, etc...).
- Click on **add file --> upload file**.
  ![simulations subfolder](https://github.com/MEDIATION-ocean/mediation-catalog-webpage/blob/main/images/simsubsection.png)

- You are now able to drag & drop your file(s), and add a little description of your commit. As it is a community effort, you can simply upload your commit directly to the main branch.
  ![upload box](https://github.com/MEDIATION-ocean/mediation-catalog-webpage/blob/main/images/uploadbox.png)

And you are all good.

**NB:** If anything remains uncertain to you, please make your commit to a new branch, which will start a [pull request](https://docs.github.com/en/pull-requests/reference/pull-requests). This allows you to dicuss your modifications with the repository administrators, and eventually make your commit with their approval.
**NB:** The upload should take a few minutes to appear on the webpage itself, while the completion is going on.


## References & resources

### The Learn-Static Lesson template (adapted from evanwill, 2022)

This website was developed using the Learn-Static Lesson Template. It is a minimal [Jekyll](https://jekyllrb.com/) project to create a simple, light-weight websites, with a [Bootstrap](https://getbootstrap.com/)-based theme, designed for hosting on [GitHub Pages](https://pages.github.com/).
All content is written using basic Markdown. The template provides Liquid includes to simplify adding Bootstrap components to your pages.

Visit the [demo site](https://learn-static.github.io/lesson-template/) to view example output on GitHub Pages and basic documentation.
The [lesson-template repository](https://github.com/learn-static/lesson-template) is a template project. To get started quickly, make a copy and replace the demo with your own content and customizations. 
The content pages serve as documentation and examples to copy from. To use Lesson Template to create your own website, make a copy and replace the template content with your own.

### Git & GitHub

[GitHub](https://github.com/) is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and [free static web hosting](https://pages.github.com/) powered by [Jekyll](https://jekyllrb.com/).
Accounts are free.
To learn more check out Hello World on [GitHub Guides](https://guides.github.com/) or [GitHub Learning Lab](https://lab.github.com/).

### Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to simplify writing content for the web. 
Markdown can be used any where on GitHub and in Jekyll.

### Bootstrap 5

[Bootstrap](https://getbootstrap.com/) is a CSS framework designed to streamline developing user interfaces for your website.

[Bootstrap Icons](https://icons.getbootstrap.com/) are SVG-based icon set used to add graphics to your content.

### YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for configuration, site data, and front matter.
Jekyll projects are [configured](https://jekyllrb.com/docs/configuration/) using the "_config.yml" file.

### Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible template language.
[In Jekyll](https://jekyllrb.com/docs/liquid/) it allows you to layout pages built from modular components and data, using the "_includes", "_layouts", and "_data" directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

### Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programmatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the "_sass" directory, that will be combined and compiled into normal CSS files when the site is built.
