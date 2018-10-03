---
title: Resources
nav: true
---

# Glossary

### Git 

[Git](https://git-scm.com/){:target="_blank"} is a [free](https://www.gnu.org/philosophy/free-sw.en.html){:target="_blank"}, [distributed version control](https://en.wikipedia.org/wiki/Distributed_version_control){:target="_blank"} system originally developed for coordinating huge software development projects (specifically the [Linux kernel](https://www.kernel.org/){:target="_blank"}). 
However, it is fast and flexible enough to be used on any scale project, from your personal notes to your research lab's code--and offers many benefits beyond "track changes".

### GitHub

[GitHub](https://github.com/){:target="_blank"} is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and static web hosting.
You can even [create DOIs for your repositories](https://guides.github.com/activities/citable-code/)!
Accounts are free for public repositories--private repositories are available on a subscription pricing model.
To learn more check out Hello World on [GitHub Guides](https://guides.github.com/){:target="_blank"} or [GitHub Training](https://services.github.com/on-demand/){:target="_blank"}.

### Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to [simplify writing](https://evanwill.github.io/_drafts/notes/writing-markdown.html) content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub and in Jekyll.

### YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for configuration, site data, and front matter.
Jekyll projects are [configured](https://jekyllrb.com/docs/configuration/) using the `_config.yml` file.

### Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible template language.
[In Jekyll](https://jekyllrb.com/docs/templates/) it allows you to layout pages built from modular components and data, using the `_includes`, `_layouts`, and `_data` directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

### Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the `_sass` directory, that will be combined and compiled into normal CSS files when the site is built.
