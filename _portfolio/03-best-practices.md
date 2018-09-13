---
title: "Stop, collaborate, and listen: Best practices"
excerpt: A few resources and guidelines for best practices.
---
Even if you're the sole person working on a project that requires cleaning, analyzing, and presenting data, you're not. At a minimum you have your future self to consider:
![phd comics img]({{ site.url }}{{ site.baseurl}}/assets/images/phd052810s.png)

At some point everyone struggles with best practices. Particularly with where to start and finding good guidelines to help institute a best practices policy. [Wilson et al. (2017)](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510) presented a paper that provides "good enough practices" for the everyday researcher. They provide good guidelines on data management, software, collaboration, project organization, tracking changes, and manuscripts.

## Version control, version control, version control
The learning curve is like riding a bike with no granny gear up a 12% graded paved road: doable, seemingly difficult in the moment but well worth the effort in the end. There are several version control tools out there (e.g. Git, Mercurial, SVN) and you can spend your time figuring out (Google) what works best for you and what the differences are, but most R users use Git and it is an integrated feature with R Studio. There are a number of web-based hosting services for version control but GitHub and Bitbucket seem to be the most common but are slightly different in terms of pricing and user intent. These online services not only serve as a backup to your work but also provide tools for collaboration, project management, and host static websites like the one used for this workshop. (You'll notice a lot of packages that are developed for R are hosted in GitHub.)

Some resources:
- [git](https://git-scm.com/)
- Software Carpentry, [Version Control with Git](https://swcarpentry.github.io/git-novice/)
- Instructions for installing Git from [Software Carpentry](https://carpentries.github.io/workshop-template/#git)

## Style guide
Pick a common and logical style guide and stick to it. This applies to documentation, writing scripts, and organizing your projects and repositories.  

Some resources:
- Software Carpentry, [Programming with R: Best Practices for Writing R Code](https://swcarpentry.github.io/r-novice-inflammation/06-best-practices-R/)
- Wickham, H. [Advanced R: Style guide](http://adv-r.had.co.nz/Style.html)
