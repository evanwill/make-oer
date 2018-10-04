---
title: Examples
nav: true
---

# Examples of OER on GitHub

Some projects and organizations I have been involved in to demonstrate the broad range of possibilities for OER on GitHub.

--------

### Integrated Musicianship

Sean Butterfield of University of Idaho, with support of the [Think Open Fellowship](https://libguides.uidaho.edu/c.php?g=772392&p=5540605) and Evan Williamson, created an interactive music textbook:

- [Integrated Musicianship: Theory](https://intmus.github.io/inttheory18-19/){:target="_blank"} 
- [IntMus Theory source code](https://github.com/intmus/inttheory18-19){:target="_blank"} on GitHub
- Interactive features:
    - Live note taking during class discussion (e.g. [Labeling Pitches](https://intmus.github.io/inttheory18-19/01-pitches-clefs/b2-labelingpitches.html)). Student learning becomes part of the textbook!
    - [abcjs](https://github.com/paulrosen/abcjs){:target="_blank"} enables live editable music examples in the text (e.g. [Happy Birthday in G major](https://intmus.github.io/inttheory18-19/02-int-scales-keys/b1-scales.html){:target="_blank"}).
    - [Disqus](https://disqus.com/){:target="_blank"} (discussion around assignments, e.g. [Unit 4 assignment](https://intmus.github.io/inttheory18-19/assignments/Fall-semester/2018-09-17.html){:target="_blank"})

Freed from many of the limitations of a conventionally published text, we were able to add innovative features to enrich the learning experience and flexibly adapt to the needs of the course and students.
Importantly, these interactive features and responsive workflow in creating the textbook compliment the philosophy of inquiry-based learning, a "flipped-classroom" driven by students' exploration and examination of the subject.
In this case, GitHub provides an ideal platform not only for project management, collaboration, and sharing source code, but also for implementing an actively evolving textbook informed by an inquiry-based pedagogical method.

Other OER music textbooks:

- [Eyes and Ears](http://www.lightandmatter.com/sight/sight.html) by Ben Crowell, 2004 (LaTex / LilyPond [source code](https://github.com/bcrowell/eyes_and_ears))
- [Open Music Theory](http://openmusictheory.com/){:target="_blank"}, by Kris Shaffer, Bryn Hughes, and Brian Moseley, 2014+ ([OMT source on GitHub](https://github.com/openmusictheory/openmusictheory.github.io){:target="_blank"})

--------

### Software Carpentry

An international organization that teaches basic tech skills for researchers. 
Content is collaboratively developed on GitHub by hundreds of contributors.
When running a workshop, organizers create a custom website by copying ("importing") the SWC templates.

- [Software Carpentry](https://software-carpentry.org/)
- [Data Carpentry](http://www.datacarpentry.org/)
- [Library Carpentry](https://librarycarpentry.org/)

--------

### The Programming Historian

A web journal of peer reviewed tutorials about digital humanities tools, techniques, and research workflows.
Articles are proposed, moved through editing and open peer review using GitHub project management features.
All content is written in Markdown and is eventually pushed to their Jekyll-based website.

- [Programming Historian](https://programminghistorian.org/)
- [PH submissions](https://github.com/programminghistorian/ph-submissions) (repository where articles are proposed, developed, and open peer reviewed)

--------

### Workshops

[workshop-template](https://github.com/evanwill/workshop-template/) (minimal theme) and [workshop-template-b](https://github.com/evanwill/workshop-template-b/) (Bootstrap theme) are Jekyll templates for a simple workshop website, designed for hosting on GitHub Pages.
As an alternative to making slides or a handout, why not create an open website?
Since it only requires editing a few Markdown files, it is easier to write, access, share, and reuse. 
I have used it for many workshops:

- [get-git](https://evanwill.github.io/get-git/)
- [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/)
- [hello-arduino](https://evanwill.github.io/hello-arduino/)
- [clean-your-data](https://evanwill.github.io/clean-your-data/)
- [Make @ the MILL](https://uidaholib.github.io/make-at-the-mill/)
- This site ([get source](https://github.com/evanwill/make-oer))!

--------

### Digital Exhibits

[CollectionBuilder-gh](https://github.com/CollectionBuilder/collectionbuilder-gh/) is a project to create a simple template for hands-on teaching about digital libraries, taking participants through digitization, metadata creation, to having a live collection site hosted on GitHub Pages.

Similar learning experiences use [Omeka](https://omeka.org/) or other DAMS/[CMS](https://en.wikipedia.org/wiki/Content_management_system) platforms that are overkill for one off projects.
Although CMS feature familiar GUI administration interfaces, they are not simple to learn and customize.
These experiences must focus on teaching the specific tool rather than general web skills and the heavy infrastructure is a barrier to adoption and further development.

`collectionbuilder-gh` aims to be well documented and easy to configure by following the example, with the potential to scaffold learning a multitude of transferable digital and data skills.
A project in "minimal computing", it provides a depth of learning opportunities, allowing users to take complete ownership over the project and make their work open to the world.
