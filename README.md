### [Click here - vasugargdev.me](https://vasugargdev.me/)




## Basic structure of the website

● Most of the content of the site comes from the ```_data``` folder.

● The website is designed to have 4 sections if you want to change what they are, modify the ```sections.yml``` file inside ```_data``` folder. If you do change the sections, make sure not to change the class property, as css file rely on them being called a cetain way.

● To update projects modify the ```projects.yml```, you can add your own tags and later reference them in ```_includes/project_box``` by putting 
```{{project.your_tag}}``` in the html.

● To use the form in the contact page, create an account with https://formspree.io/. Then simply update the email in the _config.yml to whatever you used to register.

For more info on how to use jekyll see documentation https://jekyllrb.com/docs/home/




## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/VasuGargDev/VasuGargDev.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/VasuGargDev/VasuGargDev.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
