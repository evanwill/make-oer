---
title: Resources
nav: true
---

# OER Resources

- Student PIRGs, [Make Textbooks Affortable](https://www.studentpirgs.org/textbooks) campaign.
- The William and Flora Hewlett Foundation, [Open Education Resources](https://hewlett.org/strategy/open-educational-resources/) grant making and leadership.
- Top Hat, [The Average Cost of Textbooks is Increasing](https://tophat.com/blog/average-cost-of-textbooks-infographic/) infographic.
- University of Idaho Library, [Think Open Fellowships](https://libguides.uidaho.edu/THINKOPEN).


## Static Web Glossary

----------

#### Git 

[Git](https://git-scm.com/){:target="_blank"} is a [free](https://www.gnu.org/philosophy/free-sw.en.html){:target="_blank"}, [distributed version control](https://en.wikipedia.org/wiki/Distributed_version_control){:target="_blank"} system originally developed for coordinating huge software development projects (specifically the [Linux kernel](https://www.kernel.org/){:target="_blank"}). 
However, it is fast and flexible enough to be used on any scale project, from your personal notes to your research lab's code--and offers many benefits beyond "track changes".

- Software Carpentry [Unix Shell](http://swcarpentry.github.io/shell-novice/01-intro/){:target="_blank"} and [Git lesson](http://swcarpentry.github.io/git-novice/){:target="_blank"}
- Bitbucket [Git Tutorials](https://www.atlassian.com/git/tutorials){:target="_blank"}
- [Get Git](https://evanwill.github.io/get-git/) workshop

----------

#### GitHub

[GitHub](https://github.com/){:target="_blank"} is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and static web hosting ([GitHub Pages](https://pages.github.com/){:target="_blank"}).
You can even [create DOIs for your repositories](https://guides.github.com/activities/citable-code/)!
Accounts are free for public repositories--private repositories are available on a subscription pricing model.

- [GitHub Guides](https://guides.github.com/){:target="_blank"} (check out Hello World)
- [GitHub Training](https://services.github.com/on-demand/){:target="_blank"}

Alternatives: 

- [Gitlab](https://about.gitlab.com/gitlab-com/){:target="_blank"} (Free public and private repos with unlimited collaborators, [gitlab pages](https://pages.gitlab.io/){:target="_blank"}, and focus on DevOps / CI pipelines)
- [Bitbucket](https://bitbucket.org/){:target="_blank"} (Free private repos with limited collaborators, Git or Mercurial, [SourceTree](https://www.atlassian.com/software/sourcetree){:target="_blank"} GUI app, [Education discount](https://bitbucket.org/product/education){:target="_blank"})

----------

#### Jekyll

[Jekyll](https://jekyllrb.com/){:target="_blank"} is the most popular static site generator, a commandline application that bundles together a stack of web development tools to simplify creating web sites.
Static site generators typically feature a command line interface, a builtin development server, simplified markup based content, a web templating language, a CSS preprocessor, and file-based data options.
Jekyll is integrated into GitHub Pages, so if you are using a template or theme, you can use Jekyll without installing anything.

- [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/)

----------

#### Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is an open standard to simplify writing content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub and in Jekyll.

- [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html)
- GitHub Guide [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

----------

#### YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for [configuration](https://jekyllrb.com/docs/configuration/), [site data](https://jekyllrb.com/docs/datafiles/), and [front matter](https://jekyllrb.com/docs/frontmatter/).
Jekyll projects are configured using the `_config.yml` file.

----------

#### Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible templating language.
[In Jekyll](https://jekyllrb.com/docs/templates/) it allows you to layout pages built from modular components and data, using the `_includes`, `_layouts`, and `_data` directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

----------

#### Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the `_sass` directory, that will be combined and compiled into normal CSS files when the site is built.
