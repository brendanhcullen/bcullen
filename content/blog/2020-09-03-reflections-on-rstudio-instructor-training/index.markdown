---
title: Reflections on RStudio Instructor Training
layout: single-sidebar
author: Brendan Cullen
date: '2020-09-03'
slug: []
categories: []
tags:
  - data science
  - education
  - R
subtitle: 'tl;dr You should definitely look into it.'
summary: "The 'what' and 'why' of RStudio Instructor Training and resources for those interested in pursuing it."
authors: []
lastmod: '2020-09-03T21:28:31-07:00'
featured: no
image:
  caption: '<span>Photo by <a href="https://www.istockphoto.com/portfolio/oatawa?assettype=image&mediatype=photography&sort=mostpopular">oatawa</a> on <a href="https://www.istockphoto.com/">iStock</a></span>'
  focal_point: ''
  preview_only: no
projects: []
output: 
  blogdown::html_page:
    toc: TRUE
    toc_depth: 4
---
<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>

A while back I wrote about how we [need more data science training](https://bcullen.rbind.io/post/2020-03-08-data-science-training-needs-in-grad-school/) as grad students in psychology and that one of the best ways for us to get this training is to [learn from each other](https://twitter.com/_bcullen/status/1237414725081653249). This is just one of many reasons why I'm so humbled and excited to have recently become an [RStudio Certified Instructor](https://education.rstudio.com/trainers/people/cullen+brendan/) in the tidyverse.

I'm looking forward to start implementing and sharing what I learned with my fellow grad students, especially at the end of this month when I will be leading an introductory R workshop for the new cohort of first year PhD and master's students in my department.

As a small way of paying it forward, I wanted to offer a reflection on what I think makes this training so unique and worthwhile along with a summary of what's involved and some resources for those who might be interested in knowing more.

------------------------------------------------------------------------

# The *what*

<div class="note">
The best place the start is to read about the RStudio Instructor Training and Certification Program [here](https://education.rstudio.com/trainers/#info). The [RStudio Education Blog](https://education.rstudio.com/categories/certify/) also has lots of helpful posts about the program.
</div>

The process boils down to three steps.

## Training Course <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M208 352c-2.39 0-4.78.35-7.06 1.09C187.98 357.3 174.35 360 160 360c-14.35 0-27.98-2.7-40.95-6.91-2.28-.74-4.66-1.09-7.05-1.09C49.94 352-.33 402.48 0 464.62.14 490.88 21.73 512 48 512h224c26.27 0 47.86-21.12 48-47.38.33-62.14-49.94-112.62-112-112.62zm-48-32c53.02 0 96-42.98 96-96s-42.98-96-96-96-96 42.98-96 96 42.98 96 96 96zM592 0H208c-26.47 0-48 22.25-48 49.59V96c23.42 0 45.1 6.78 64 17.8V64h352v288h-64v-64H384v64h-76.24c19.1 16.69 33.12 38.73 39.69 64H592c26.47 0 48-22.25 48-49.59V49.59C640 22.25 618.47 0 592 0z"/></svg>

The first step is to sign up for the training course, which will likely be held over Zoom and chunked into 3-4 hour segments across 2-3 days. You can access the training materials [here](https://drive.google.com/drive/folders/13ohFt3D0EJ5PDbMaWTxnHH-hwA7G0IvY).

The training course is an interactive introduction to applying evidence-based teaching methods to data science education, such as [learner personas](https://docs.google.com/presentation/d/1aOnX-B9XlAzkrlIeZa5db3_X2Dk8cS27k3klvPn1SQI/edit), [concept maps](https://docs.google.com/presentation/d/1k45SqyM-w4DtK7dmedeX7pk_r8B9Aq0FKKCxC04pTRM/edit), and [formative assessment](https://docs.google.com/presentation/d/1PBxBFpkB4w-C3_l2rWdGMtjxaxDeu8gVP0K0CHJfbdQ/edit) (i.e. short, diagnostic questions or exercises to figure out if learners are forming accurate mental models). The course also covers how to design teaching materials with [reverse instructional design](https://docs.google.com/presentation/d/1PBxBFpkB4w-C3_l2rWdGMtjxaxDeu8gVP0K0CHJfbdQ/edit#slide=id.g5501944768_0_197) that takes into account [cognitive load](https://docs.google.com/presentation/d/1t9QTkRfGP9WYQjiXoaVAuceFe3ySVe_wLT7j2MYC8bE/edit#slide=id.g39e398e252_0_14), [multiple learning strategies](https://docs.google.com/presentation/d/1bq599QkDdaWXmw-B8JM5jwdl5In9O-NTxLPT2iES0vY/edit#slide=id.g5479673425_0_87), and issues of [inclusivity and student motivation](https://docs.google.com/presentation/d/1uYQCbs88aao7Ho4d4mUfYi6hOXhgHWV6noR_-jOaE50/edit) in the classroom.

<br>

## Technical Exam <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M255.03 261.65c6.25 6.25 16.38 6.25 22.63 0l11.31-11.31c6.25-6.25 6.25-16.38 0-22.63L253.25 192l35.71-35.72c6.25-6.25 6.25-16.38 0-22.63l-11.31-11.31c-6.25-6.25-16.38-6.25-22.63 0l-58.34 58.34c-6.25 6.25-6.25 16.38 0 22.63l58.35 58.34zm96.01-11.3l11.31 11.31c6.25 6.25 16.38 6.25 22.63 0l58.34-58.34c6.25-6.25 6.25-16.38 0-22.63l-58.34-58.34c-6.25-6.25-16.38-6.25-22.63 0l-11.31 11.31c-6.25 6.25-6.25 16.38 0 22.63L386.75 192l-35.71 35.72c-6.25 6.25-6.25 16.38 0 22.63zM624 416H381.54c-.74 19.81-14.71 32-32.74 32H288c-18.69 0-33.02-17.47-32.77-32H16c-8.8 0-16 7.2-16 16v16c0 35.2 28.8 64 64 64h512c35.2 0 64-28.8 64-64v-16c0-8.8-7.2-16-16-16zM576 48c0-26.4-21.6-48-48-48H112C85.6 0 64 21.6 64 48v336h512V48zm-64 272H128V64h384v256z"/></svg>

The technical exam assesses your proficiency in whatever topic for which you are attempting to become a certified instructor. Currently there are options to become a certified instructor in [tidyverse](https://www.tidyverse.org/) and [shiny](https://shiny.rstudio.com/), and each has its own accompanying technical exam.

I took the tidyverse exam, which, broadly speaking, consists of a series of live coding challenges related to using core tidyverse packages for data cleaning and wrangling, data visualization, string manipulation, functional programming, basic statistical modeling, and creating reproducible documents with R Markdown.

As many others have suggested, a great way to prepare for this exam is to work through the exercises [R for Data Science](https://r4ds.had.co.nz/), particularly for topics that feel rusty to you, and review the community-contributed [solutions](https://jrnold.github.io/r4ds-exercise-solutions/).

<div class="note">
I highly recommend going through these sample exams from the RStudio Education Blog start to finish to get a sense of what you might need to review.

-   [Sample Tidyverse Exam 1](https://education.rstudio.com/blog/2020/02/instructor-certification-exams/#tidyverse-certification-exam) \| [solutions](https://marlycormar.github.io/tidyverse_sample_exam/sample_exam_sols/sols.html)
-   [Sample Tidyverse Exam 2](https://education.rstudio.com/blog/2020/08/more-example-exams/#tidyverse-exam) \| [solutions](https://tidyverse-exam-v2-solutions.netlify.app/)
</div>

<br>

## Teaching Exam <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 448 512"><path d="M319.4 320.6L224 416l-95.4-95.4C57.1 323.7 0 382.2 0 454.4v9.6c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48v-9.6c0-72.2-57.1-130.7-128.6-133.8zM13.6 79.8l6.4 1.5v58.4c-7 4.2-12 11.5-12 20.3 0 8.4 4.6 15.4 11.1 19.7L3.5 242c-1.7 6.9 2.1 14 7.6 14h41.8c5.5 0 9.3-7.1 7.6-14l-15.6-62.3C51.4 175.4 56 168.4 56 160c0-8.8-5-16.1-12-20.3V87.1l66 15.9c-8.6 17.2-14 36.4-14 57 0 70.7 57.3 128 128 128s128-57.3 128-128c0-20.6-5.3-39.8-14-57l96.3-23.2c18.2-4.4 18.2-27.1 0-31.5l-190.4-46c-13-3.1-26.7-3.1-39.7 0L13.6 48.2c-18.1 4.4-18.1 27.2 0 31.6z"/></svg>

The first certification exam assesses pedagogical skills related to teaching data science with R and requires giving a 15-minute demonstration lesson on a topic of your choice followed by a series of applied questions, which will likely involve creating formative assessments on unseen material (e.g. multiple choice questions and fill-in-the-blank coding exercises), developing concept maps on data science topics and giving feedback on example teaching based on pedagogical theory.

<div class="note">
There are also sample teaching exams available.

-   [Sample Teaching Exam 1](https://education.rstudio.com/blog/2020/02/instructor-certification-exams/#teaching-exam)
-   [Sample Teaching Exam 2](https://education.rstudio.com/blog/2020/08/more-example-exams/#teaching-exam)
</div>

### Demonstration Lesson: Example

*Column-wise operations with `dplyr`: Old and New*

If you'd like to see an example of a demonstration lesson, below are the materials I created for this portion of the teaching exam. I used `penguins` from the [`{palmerpenguins}`](https://allisonhorst.github.io/palmerpenguins/) package as an example data set.

<div class="github">
You can find all of the materials for this lesson and the accompanying code on [Github](https://github.com/brendanhcullen/rstudio-instructor-certification). Feel free to share, adapt and re-use for your own teaching.
</div>

#### Slides <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 512 512"><path d="M488 64h-8v20c0 6.6-5.4 12-12 12h-40c-6.6 0-12-5.4-12-12V64H96v20c0 6.6-5.4 12-12 12H44c-6.6 0-12-5.4-12-12V64h-8C10.7 64 0 74.7 0 88v336c0 13.3 10.7 24 24 24h8v-20c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v20h320v-20c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v20h8c13.3 0 24-10.7 24-24V88c0-13.3-10.7-24-24-24zM96 372c0 6.6-5.4 12-12 12H44c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v40zm0-96c0 6.6-5.4 12-12 12H44c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v40zm0-96c0 6.6-5.4 12-12 12H44c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v40zm272 208c0 6.6-5.4 12-12 12H156c-6.6 0-12-5.4-12-12v-96c0-6.6 5.4-12 12-12h200c6.6 0 12 5.4 12 12v96zm0-168c0 6.6-5.4 12-12 12H156c-6.6 0-12-5.4-12-12v-96c0-6.6 5.4-12 12-12h200c6.6 0 12 5.4 12 12v96zm112 152c0 6.6-5.4 12-12 12h-40c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v40zm0-96c0 6.6-5.4 12-12 12h-40c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v40zm0-96c0 6.6-5.4 12-12 12h-40c-6.6 0-12-5.4-12-12v-40c0-6.6 5.4-12 12-12h40c6.6 0 12 5.4 12 12v40z"/></svg>

I made heavy use of [Yihui Xie](https://yihui.org/en/about/)'s [`{xaringan}`](https://slides.yihui.org/xaringan/) 📦, [Garrick Aden-Buie](https://www.garrickadenbuie.com/)'s [`{xaringanExtra}`](https://pkg.garrickadenbuie.com/xaringanExtra/#/) 📦, and [Kelly Bodwin](https://www.kelly-bodwin.com/)'s [`{flair}`](https://kbodwin.github.io/flair/index.html) 📦, along with [Allison Horst](https://www.allisonhorst.com/)'s unbeatable [artwork](https://github.com/allisonhorst/stats-illustrations). For an excellent `{xaringan}` tutorial, I recommend you check out [these slides](https://arm.rbind.io/slides/xaringan.html#1), from the R Markdown whisperer herself, [Alison Hill](https://alison.rbind.io/). Note: you absolutely do not have to use `{xaringan}` to make your slides, and if your lesson includes more images than code, another method for delivering your slides might be better.

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="https://columnwise-operations-dplyr.netlify.app/" width="1600" height="900" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>

Full slides available [here](https://columnwise-operations-dplyr.netlify.app/).

<center>

<br>❖ ❖ ❖<br>

</center>

#### Concept Map <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M128 352H32c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h96c17.67 0 32-14.33 32-32v-96c0-17.67-14.33-32-32-32zm-24-80h192v48h48v-48h192v48h48v-57.59c0-21.17-17.23-38.41-38.41-38.41H344v-64h40c17.67 0 32-14.33 32-32V32c0-17.67-14.33-32-32-32H256c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h40v64H94.41C73.23 224 56 241.23 56 262.41V320h48v-48zm264 80h-96c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h96c17.67 0 32-14.33 32-32v-96c0-17.67-14.33-32-32-32zm240 0h-96c-17.67 0-32 14.33-32 32v96c0 17.67 14.33 32 32 32h96c17.67 0 32-14.33 32-32v-96c0-17.67-14.33-32-32-32z"/></svg>

<img src="columnwise-operations.png" width="150%" />

For other community-contributed data science concept maps you can use in your teaching and/or lesson prep, see [here](https://github.com/rstudio/concept-maps).

<center>

<br>❖ ❖ ❖<br>

</center>

#### Learner Persona <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 448 512"><path d="M224 256c70.7 0 128-57.3 128-128S294.7 0 224 0 96 57.3 96 128s57.3 128 128 128zm89.6 32h-16.7c-22.2 10.2-46.9 16-72.9 16s-50.6-5.8-72.9-16h-16.7C60.2 288 0 348.2 0 422.4V464c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48v-41.6c0-74.2-60.2-134.4-134.4-134.4z"/></svg>

<img src="learner_persona.png" width="865" />

For a list of other example learner personas, see [here](https://rstudio-education.github.io/learner-personas/).

<center>

<br>❖ ❖ ❖<br>

</center>

#### Formative Assessment <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M224 256c70.7 0 128-57.3 128-128S294.7 0 224 0 96 57.3 96 128s57.3 128 128 128zm89.6 32h-16.7c-22.2 10.2-46.9 16-72.9 16s-50.6-5.8-72.9-16h-16.7C60.2 288 0 348.2 0 422.4V464c0 26.5 21.5 48 48 48h274.9c-2.4-6.8-3.4-14-2.6-21.3l6.8-60.9 1.2-11.1 7.9-7.9 77.3-77.3c-24.5-27.7-60-45.5-99.9-45.5zm45.3 145.3l-6.8 61c-1.1 10.2 7.5 18.8 17.6 17.6l60.9-6.8 137.9-137.9-71.7-71.7-137.9 137.8zM633 268.9L595.1 231c-9.3-9.3-24.5-9.3-33.8 0l-37.8 37.8-4.1 4.1 71.8 71.7 41.8-41.8c9.3-9.4 9.3-24.5 0-33.9z"/></svg>

I created [these interactive exercises](https://brendancullen.shinyapps.io/columnwise_operations_formative_assessment/) using the [`learnr`](https://rstudio.github.io/learnr/) package, which I highly recommend you check out. It's quite powerful and versatile.

Here's a quick look.

<iframe src="https://brendancullen.shinyapps.io/columnwise_operations_formative_assessment/?showcase=0" width="672" height="500px"></iframe>

------------------------------------------------------------------------

# The *why*

Ok, this might all seem like quite a bit of time and effort. Why go to the trouble of doing this training? In a word, [Greg Wilson](https://third-bit.com/about/).

Greg, who co-founded the [Software Carpentry](https://software-carpentry.org/), has over 35 years of experience in education in data science and software engineering, and it shows. He is now part of the [RStudio Education](https://education.rstudio.com/) team, where he runs the the instructor training and certification program. One of the reasons this program stands out is that it benefits from Greg's unique expertise and careful curation of decades of research on evidence-based teaching methods that he has translated into clear and actionable advice. I can guarantee that you will learn a LOT from him.

Greg's most important [advice for teaching](https://third-bit.com/10rules/#teaching), in my opinion:

> "Be kind: all else is details."

**Now, here are some other reasons why you should do this training...**

## Surge in online teaching <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M537.6 226.6c4.1-10.7 6.4-22.4 6.4-34.6 0-53-43-96-96-96-19.7 0-38.1 6-53.3 16.2C367 64.2 315.3 32 256 32c-88.4 0-160 71.6-160 160 0 2.7.1 5.4.2 8.1C40.2 219.8 0 273.2 0 336c0 79.5 64.5 144 144 144h368c70.7 0 128-57.3 128-128 0-61.9-44-113.6-102.4-125.4z"/></svg>

Interest in data science education seems to be ever-increasing. The fact that COVID-19 has forced most education to go online might actually present an opportunity to meet this demand in a more scalable and (hopefully more accessible way that doesn't incur the traditional limitations of travel costs or room capacity. Of course, online education comes with a host of inherent challenges. The training course includes a [whole section](https://docs.google.com/presentation/d/1kbYaHv47Vt59JxqXF7U7pQl5XOwsctzpP740iVM7Bc8/edit#slide=id.g55ddde1eae_0_2) on this. I also recommend you check out this [RStudio webinar](https://rstudio.com/resources/webinars/teaching-online-at-short-notice/) and accompanying [blog post](https://education.rstudio.com/blog/2020/03/teaching-online-on-short-notice/) along with answers to some [frequently asked questions](https://education.rstudio.com/blog/2020/03/online-teaching-qa/) about teaching online.

As online data science education is becoming increasingly the norm, it seems natural to assume that there will be a need for more certified instructors to meet the growing demand.

<center>

<br>❖ ❖ ❖<br>

</center>

## Teaching resources galore <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 576 512"><path d="M485.5 0L576 160H474.9L405.7 0h79.8zm-128 0l69.2 160H149.3L218.5 0h139zm-267 0h79.8l-69.2 160H0L90.5 0zM0 192h100.7l123 251.7c1.5 3.1-2.7 5.9-5 3.3L0 192zm148.2 0h279.6l-137 318.2c-1 2.4-4.5 2.4-5.5 0L148.2 192zm204.1 251.7l123-251.7H576L357.3 446.9c-2.3 2.7-6.5-.1-5-3.2z"/></svg>

Another great reason to become a certified instructor is that, as a data science educator, you have a huge and ever-increasing bank of resources at your disposal. What's more, as a certified instructor, you are eligible for free licenses to [RStudio Pro products](https://rstudio.com/products/) and a significant discount for [RStudio Cloud](https://rstudio.cloud/). Here are just some of the great teaching tools from RStudio and the \#rstats community.

<div class="bookmark">
The [RStudio Education Blog](https://education.rstudio.com/blog/) is a 💎 treasure trove 💎 of resources. Add it to your bookmarks immediately.
</div>

**Teaching with RStudio Cloud**

-   [webinar](https://rstudio.com/resources/webinars/teaching-r-online-with-rstudio-cloud/) and accompanying [blog post](https://education.rstudio.com/blog/2020/04/teaching-with-rstudio-cloud-q-a/), courtesy of [Mine Çetinkaya-Rundel](https://www2.stat.duke.edu/~mc301/)

**Interactive lessons with `learnr`**

-   [tutorial and demonstration](https://education.rstudio.com/blog/2020/05/learnr-for-remote/), courtesy of [Allison Horst](https://www.allisonhorst.com/)

-   [lessons learned](https://education.rstudio.com/blog/2020/06/summer-camp-hs/) from using `learnr` to teach high schoolers, courtesy of [Ezgi Karaesmen](https://www.ezgikaraesmen.com/)

-   [a deep dive](https://education.rstudio.com/blog/2020/07/learning-learnr/) into `learnr`, courtesy of [Nischal Shrestha](http://nischalshrestha.me/)

-   [{gradethis} package](https://rstudio-education.github.io/gradethis/) for easily grading `learnr` exercises

**Openly licensed teaching materials**

-   [a thorough summary](https://education.rstudio.com/blog/2020/05/remote-roundup/) of recent online courses/workshops, courtesy of [Alison Hill](https://alison.rbind.io/)

-   [Data Science in a Box](https://datasciencebox.org/), courtesy of [Mine Çetinkaya-Rundel](https://www2.stat.duke.edu/~mc301/)

-   [STAT 545](https://stat545.com/), courtesy of [Jenny Bryan](https://jennybryan.org/about/)

-   [Many others](https://education.rstudio.com/teach/materials/#workshops), courtesy of the RStudio Education Team

**rstudio4edu**

-   a [book-in-progress](https://rstudio4edu.github.io/rstudio4edu-book/), courtesy of [Desirée De Leon](https://desiree.rbind.io/) and [Alison Hill](https://alison.rbind.io/). This is in a category of its own because it's an absolute gold mine.

<center>

<br>❖ ❖ ❖<br>

</center>

## Tried and tested <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 576 512"><path d="M416 192c0-88.4-93.1-160-208-160S0 103.6 0 192c0 34.3 14.1 65.9 38 92-13.4 30.2-35.5 54.2-35.8 54.5-2.2 2.3-2.8 5.7-1.5 8.7S4.8 352 8 352c36.6 0 66.9-12.3 88.7-25 32.2 15.7 70.3 25 111.3 25 114.9 0 208-71.6 208-160zm122 220c23.9-26 38-57.7 38-92 0-66.9-53.5-124.2-129.3-148.1.9 6.6 1.3 13.3 1.3 20.1 0 105.9-107.7 192-240 192-10.8 0-21.3-.8-31.7-1.9C207.8 439.6 281.8 480 368 480c41 0 79.1-9.2 111.3-25 21.8 12.7 52.1 25 88.7 25 3.2 0 6.1-1.9 7.3-4.8 1.3-2.9.7-6.3-1.5-8.7-.3-.3-22.4-24.2-35.8-54.5z"/></svg>

The instructor training program started back in February 2019 and [as of August 2020](https://education.rstudio.com/blog/2020/08/august-2020-instructors/) there are almost 150 certified tidyverse instructors and 20 shiny instructors. This means that the program has gone through multiple iterations and has made data-driven improvements based on [feedback from participants](https://education.rstudio.com/blog/2020/07/instructor-certification-findings/) -- especially in the realm of supporting online teaching in the aftermath of COVID-19. So you can rest assured that, while it is still a relatively new program, all the kinks have been worked out.

Plus, I'm sure that the content and structure of the training will continue to adapt to the needs and priorities of the community, and you might even be lucky enough to catch a special guest presentation. For example...

<center>

<blockquote class="twitter-tweet">

<p lang="en" dir="ltr">

Enjoyed sharing some tips today on "Teaching in Production" for our <a href="https://twitter.com/RStudioEDU?ref_src=twsrc%5Etfw">[@RStudioEDU]</a> certified-instructors-to-be (another <a href="https://twitter.com/thomas_mock?ref_src=twsrc%5Etfw">[@thomas_mock]</a> distill success story!) <br><br>Thx to <a href="https://twitter.com/gvwilson?ref_src=twsrc%5Etfw">[@gvwilson]</a> for the invite, <a href="https://twitter.com/allison_horst?ref_src=twsrc%5Etfw">[@allison_horst]</a> for <a href="https://twitter.com/hashtag/rmarkdown?src=hash&amp;ref_src=twsrc%5Etfw">\#rmarkdown</a> 🦔(❣️), and <a href="https://twitter.com/dcossyle?ref_src=twsrc%5Etfw">[@dcossyle]</a> for all her 🎨.<a href="https://t.co/sngAwlcSqN">https://t.co/sngAwlcSqN</a>

</p>

--- Alison Presmanes Hill ([@apreshill]) <a href="https://twitter.com/apreshill/status/1296553009522962432?ref_src=twsrc%5Etfw">August 20, 2020</a>

</blockquote>

```{=html}
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
```
</center>

<center>

<br>❖ ❖ ❖<br>

</center>

## A focus on inclusivity <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M488 192H336v56c0 39.7-32.3 72-72 72s-72-32.3-72-72V126.4l-64.9 39C107.8 176.9 96 197.8 96 220.2v47.3l-80 46.2C.7 322.5-4.6 342.1 4.3 357.4l80 138.6c8.8 15.3 28.4 20.5 43.7 11.7L231.4 448H368c35.3 0 64-28.7 64-64h16c17.7 0 32-14.3 32-32v-64h8c13.3 0 24-10.7 24-24v-48c0-13.3-10.7-24-24-24zm147.7-37.4L555.7 16C546.9.7 527.3-4.5 512 4.3L408.6 64H306.4c-12 0-23.7 3.4-33.9 9.7L239 94.6c-9.4 5.8-15 16.1-15 27.1V248c0 22.1 17.9 40 40 40s40-17.9 40-40v-88h184c30.9 0 56 25.1 56 56v28.5l80-46.2c15.3-8.9 20.5-28.4 11.7-43.7z"/></svg>

The focus of this training is not technical competency -- it's how be an effective teacher. One of the most critical components of teaching effectively is to be inclusive of all learners, regardless of race, religion, sexual orientation, gender identity, disability, etc.

The [\#rstats learning community](https://twitter.com/R4DScommunity) is known for being welcoming and inclusive, so it's no surprise that the training course emphasizes these values as well. What I appreciate most about this aspect of the training is that it will challenge you to think about questions and hypothetical scenarios to which there are no easy answers.

However, it is extremely important to be pushed out of your comfort zone to consciously and proactively reflect on how you will confront issues such as systemic racism and institutionalized violence against BIPOC communities, sexism and a deeply ingrained culture of sexual harassment. These issues will inevitably arise in one form or another in your classroom or teaching setting, and it's absolutely necessary that we confront these challenges now more than ever. Check out [this slide](https://docs.google.com/presentation/d/1uYQCbs88aao7Ho4d4mUfYi6hOXhgHWV6noR_-jOaE50/edit#slide=id.g56df7927dc_0_1) and [this talk](https://www.youtube.com/watch?v=EhNisFJPfrs) on effective allyship when you get a chance.

<div class="book">
For further reading on inclusivity and social justice in data science education, I recommend you read [this post](https://education.rstudio.com/blog/2020/06/native-classroom/) by [Nicole Thompson Gonzalez](http://www.nicolethompsongonzalez.com/) and [this one](https://medium.com/@yimregister/10-ways-to-integrate-social-justice-into-teaching-data-science-f48d13f2337c) by [Yim Register](http://students.washington.edu/yreg/). Also check out the amazing work that [JooYoung Seo](https://jooyoungseo.com/), the first blind RStudio Certified Instructor, has been doing to make data science tools [more accessible](https://education.rstudio.com/blog/2020/07/a11y-midterm/).
</div>

Another exciting feature is that the training materials are now [available in Spanish](https://drive.google.com/drive/folders/1qwTEMqoqphF9qu7f0lSCSTmikIf5chBi), courtesy of [Laura Acion](https://lacion.rbind.io/), and hopefully other languages soon, as interest in the training seems to be growing around the world. A similar ongoing project to check out is [`glosario`](https://carpentries.github.io/glosario/), an open source glossary of data science terms translated in multiple languages that can be used for teaching (read more [here](https://education.rstudio.com/blog/2020/07/announcing-glosario/)).

<center>

<br>❖ ❖ ❖<br>

</center>

## Community of practice <svg style="height:0.8em;top:.04em;position:relative;" viewBox="0 0 640 512"><path d="M96 224c35.3 0 64-28.7 64-64s-28.7-64-64-64-64 28.7-64 64 28.7 64 64 64zm448 0c35.3 0 64-28.7 64-64s-28.7-64-64-64-64 28.7-64 64 28.7 64 64 64zm32 32h-64c-17.6 0-33.5 7.1-45.1 18.6 40.3 22.1 68.9 62 75.1 109.4h66c17.7 0 32-14.3 32-32v-32c0-35.3-28.7-64-64-64zm-256 0c61.9 0 112-50.1 112-112S381.9 32 320 32 208 82.1 208 144s50.1 112 112 112zm76.8 32h-8.3c-20.8 10-43.9 16-68.5 16s-47.6-6-68.5-16h-8.3C179.6 288 128 339.6 128 403.2V432c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48v-28.8c0-63.6-51.6-115.2-115.2-115.2zm-223.7-13.4C161.5 263.1 145.6 256 128 256H64c-35.3 0-64 28.7-64 64v32c0 17.7 14.3 32 32 32h65.9c6.3-47.4 34.9-87.3 75.2-109.4z"/></svg>

To extend the idea of including *everyone* who wants to learn data science, we must be active in building teaching communities that extend beyond just the walls of academic institutions.

RStudio's [mission](https://education.rstudio.com/teach/#:~:text=RStudio's%20mission%20is%20to%20equip,economy%20that%20rewards%20data%20literacy.&text=All%20of%20RStudio's%20resources%20are,materials%20in%20their%20own%20ways.) is to

> "equip everyone, regardless of means, to participate in a global economy that rewards data literacy."

A more concrete goal, put forth by [Carl Howe](https://education.rstudio.com/trainers/people/howe+carl/), Director of Education at RStudio, is to train the [next million R users](https://rstudio.com/resources/rstudioconf-2019/the-next-million-r-users/). In becoming an RStudio certified instructor, you can better position yourself to actively participate in reaching this goal. But it's worth reflecting on the fact that teaching and learning doesn't happen in a vacuum -- this is where the idea of community comes in. In my opinion, the fact that R users around the world already have a strong sense of community will make it that much easier to welcome new learners into the fold and make it more likely that they themselves will start to train others one day.

<div class="book">
<br> Read more about building a community of practice [here](https://teachtogether.tech/en/index.html#s:community).
</div>

------------------------------------------------------------------------

*P.S.* If you need yet another reason to do this training, you get a fancy certificate at the end. ✨

![](certificate.png)

------------------------------------------------------------------------

# Get in touch

Please feel free to [reach out](https://twitter.com/_bcullen) if you are thinking of participating in the training yourself and want to hear more from someone who's gone through it recently. I would be glad to chat any time!

![](https://media.giphy.com/media/3o7btQsLqXMJAPu6Na/giphy.gif)
