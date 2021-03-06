---
title: How?
nav: true
---

# OER on GitHub <span class="fab fa-github"></span>

[GitHub](https://github.com/) is a cloud [Git](https://git-scm.com/) repository hosting service, with benefits!
It provides a handy web interface for managing, editing, and collaborating on remote Git repositories.
Originally designed to manage large open-source software projects, its use has expanded to many other types of organizations and individuals, with over 20 million users.
Accounts are free for public repositories--private repositories are available on a subscription pricing model.

Features: 

- Version control (permanently stores the history of your project)
- Friendly web platform (lowers barriers to contributors)
- Project management features (organize collaboration!)
- Large open source community (increases visibility and leverage outside contributors)

Hosting your source code on GitHub makes it easier to write, access, share, and reuse OER, ensuring the content is provided in a truly [open](https://opendefinition.org/) manner.

However, one amazingly useful GitHub feature is [GitHub Pages](https://guides.github.com/features/pages/), a free service that provides static web hosting from any repository.
Using GH-Pages removes infrastructure and cost barriers, making it a great option for teaching and learning because your web presentation and source code will be openly available from the same platform.

{% capture text %}Note:
GH-pages is intended to host relatively simple sites for your GitHub portfolio, project, or documentation.
There are *soft* limits and guidelines for gh-pages usage: sites should be < 1GB, use < 100GB bandwidth per month, and make < 10 builds per hour.
If your site exceeds these quotas, GitHub will send you a notice asking you to modify the repository.
All content must follow the [community guidelines](https://help.github.com/articles/github-community-guidelines/), e.g. no violence, obscene sex, or illegal stuff.{% endcapture %}
{% include alert.md text=text color=secondary %}

## Static Web

Unlike [WordPress](https://wordpress.com/) or [Drupal](https://www.drupal.org/), gh-pages is not a content management system or dynamic web application.
There is no database, server side language / processing, or admin interface.
This is known as a [static web](https://en.wikipedia.org/wiki/Static_web_page) host. 
HTML, CSS, and JS stored in the repository are served to the user without dynamic changes.

In the olden days static web was the norm, but database driven dynamic web sites have dominated the last decade.
Dynamic web applications enable features such as live comments, user authentication, and personalized streams. 
However, this functionality requires complex server-side infrastructure and processing.

Despite their limitations static sites are experiencing a [new boom](https://www.smashingmagazine.com/2015/11/modern-static-website-generators-next-big-thing/), because they offer some significant advantages:

- much faster performance (caching, low bandwidth, no processing time).
- low hosting requirements (simple web servers, no dependencies, minimal infrastructure).
- no security vulnerabilities.
- easy version control.

To make development easier, hundreds of static site generators have sprung onto the scene.
Static generators are commandline applications that bundle together a stack of web development tools which are used to transform a directory of source code into a web site.
Static site generators typically feature a command line interface, a builtin development server, simplified markup based content, a web templating language, a CSS preprocessor, and file-based data options.

## Jekyll

[Jekyll](https://jekyllrb.com/){:target="_blank"} is the most popular static site generator, largely because it is integrated into GitHub Pages.
This means that with a template or theme you can use Jekyll without installing anything on your local machine.

Jekyll enables the separation of the content and data from the look and feel of the website.
The creation of content is simplified by using [Markdown](https://daringfireball.net/projects/markdown/){:target="_blank"}.
This ensures that your OER is easily editable and sustainable, with self-contained and portable content.
It lowers the barrier to contributions, since content creators can just learn about Markdown (which takes about a [minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html)) to meaningfully engage with the website.

To make a website like this one (or like many of the [examples]({{ '/content/3-examples.html' | relative_url }})), the basic steps are:

{% capture text %}
1. Have a [GitHub](https://github.com) account.
2. *Optional:* have [Git](https://git-scm.com/), [Jekyll](https://jekyllrb.com/), and a nice [text editor](https://code.visualstudio.com/) installed.
3. [Import](https://help.github.com/articles/importing-a-repository-with-github-importer/) or Fork a Jekyll theme or template (such as [workshop-template](https://github.com/evanwill/workshop-template)) on GitHub.
4. Work on the GitHub web interface to edit files, or `clone` to your local machine.
5. Edit the site configuration `_config.yml` with your info.
6. Edit the content pages in markdown.
7. Add images to the "images" folder.
8. Push to GitHub (or commit on the web interface).
9. In your repo's settings, activate gh-pages, using master branch.{% endcapture %}
{% include card.md header="GH-Pages Overview" text=text %}

For a full introduction to the basics, check my [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/) workshop.

{% include alert.md text="GitHub is not the only option! There are alternative hosts that offer the similar services, such as [Gitlab](https://about.gitlab.com/gitlab-com/), or you could manage your own simple static web hosting. This workshop focuses on GitHub because it is the largest community and features the easiest to use web interface." color="success" %}
