---
title: Redesigning the website
author: "anpefi"
draft: false
date: '2017-12-20'
slug: redesigning-the-website
categories: []
tags: ["R","markdown","website","git"]
header:
  caption: 'New framework'
  image: 'headers/redesign.png'
---

I've changed the website design. 

For the last 2 years this site was relying on the [Jekyll framework](https://jekyllrb.com/) using the [Minimal Mistakes template](https://mmistakes.github.io/minimal-mistakes/). Recently, I started to dive deeper in [Rstudio](https://www.rstudio.com), [rmarkdown](http://rmarkdown.rstudio.com/) and the [tidyverse](https://www.tidyverse.org/) ecosystem. Few days ago I discovered in Twitter about the new Yihui Xie's package called [blogdown](https://bookdown.org/yihui/blogdown/) that allows to create static websites using Rmarkdown and [Hugo](https://gohugo.io/). After a quick read of the [Xie's book about this package](https://bookdown.org/yihui/blogdown/) I decided to change this website from Markdown+Jekyll to Rmarkdown+Blogdown+Hugo. Of course, the migration is quite easy as this website was almost empty and unchanged for these 2 years. In fact, this decision was boosted by the fact that I was trying to update Jekyll and found some troubles with ruby dependencies. Furthermore, the chapter 3.4 of the Xie's book gave me the idea to avoid relying on having everything installed on the computer: using [Travis CI](https://travis-ci.org/) to make the deployment to [github](https://github.com) (where the website was already hosted in the repo [anpefi/anpefi.github.io](https://github.com/anpefi/anpefi.github.io)). Although I already used Travis-CI for some of my programs, I did not use it to do the deployment. I was curious about how it would work and to pass this website to that system would allow me to practice. For this I had to create a new repository ([anpefi/anpefi-source](https://github.com/anpefi/anpefi.source)) for the sources of the page, which, with each commit in the master, will be built in Travis-CI and the static html deployed in anpefi.github.io. 

This is how the site looked in the last 2 years:

![old layout](/img/posts/old.website.png)

Now, I use the [Academic template](https://sourcethemes.com/academic/) for Hugo that I think it looks great for a site like this. What do you think? Leave me your comments below. 

My first impressions about the change from Jekyll to Hugo are very positive, and now it is easier to do everything from one place (Rstudio) and the pages are generated much faster and with a lighter load. The deployment via Travis also has an additional advantage, and that is that I do not depend on having the installation of R or Hugo on a computer. Now I can add content directly from the github website or from the mobile. It seems that the change has been a success. Now I just have to motivate myself to write some posts from time to time, but that's another bussiness.