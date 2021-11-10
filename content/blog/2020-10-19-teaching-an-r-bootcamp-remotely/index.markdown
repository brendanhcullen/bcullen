---
# title: "Flattening the leaRning curve: Teaching R online during COVID-19"
# author: Brendan Cullen
# date: '2020-10-19'
# tags:
#   - data science
#   - education
#   - R
# subtitle: ''
# summary: 'Lessons learned from my first experience teaching an R bootcamp remotely & a collection of tools and resources I found useful'
# lastmod: '2020-10-19'
# featured: no
# image:
#   caption: '<span>Photo by <a href="https://unsplash.com/@martinadams?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Martin Adams</a> on <a href="https://unsplash.com/s/photos/sky?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText">Unsplash</a></span>'
#   focal_point: ''
#   preview_only: no
# projects: []
# disable_codefolding: false
# codefolding_show: "hide"
# codefolding_nobutton: false
title: "Flattening the leaRning curve: Teaching R online during COVID-19"
subtitle: ""
summary: "Lessons learned from my first experience teaching an R bootcamp remotely & a collection of tools and resources I found useful"
date: 2020-10-19
author: "Brendan Cullen"
draft: false
images:
series:
tags:
  - R
  - tidyverse
  - education
categories:
layout: single-sidebar
---
<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>
<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>
<script src="{{< blogdown/postref >}}index_files/fitvids/fitvids.min.js"></script>



At this point, you’re probably familiar with the phrase “flatten the curve” —  remember back in March when we were all talking about that? It was part of a critical public health messaging campaign aimed at slowing the spread of COVID-19 to prevent hospitals from becoming overwhelmed beyond their capacity. Based on how things are going, we really should *still* be talking about that. So allow me to unabashedly steal this catchphrase as a flawed metaphor for teaching and learning R during the era of this pandemic... 

It’s no secret that R has a significant leaRning curve — and, while it seems that more people than ever are now wanting to learn R, almost everyone is having to do it in an online format of some kind. For those who are used to a traditional in-person classroom environment, having a first introduction to R in an online format might make the leaRning curve even steeper (as I said, a flawed metaphor -- the concept of a "steep learning curve" is actually the [opposite](https://www.valamis.com/hub/learning-curve#steep-learning-curve) of what most people think, but we’ll run with it anyway). After recently teaching an introductory [R Bootcamp](https://uopsych-r-bootcamp-2020.netlify.app/) online, I've spent a lot of time thinking about strategies to lower the learning threshold and make it easier to conquer any potential fear of learning R -- to "flatten the leaRning curve", as it were.

<div class="reader">
For anyone who might be new to teaching R, teaching online, or both, the goal of this post is to share some valuable lessons I learned and resources I used during this online teaching experience. I hope it may be of some benefit for your own teaching.
</div>

# Background

Back in Fall 2018, the Department of Psychology at the University of Oregon started to offer a grad-student-led introductory R Bootcamp the week before the start of the new academic year. The bootcamp consists of three 3-4 hour sessions that take place over the course of a week. The idea behind the bootcamp is to give a first exposure to R to incoming students who have little to no background in it before being launched headfirst into using R to analyze data for their first year project and to complete labs and homework assignments for [PSY611](https://uopsych.github.io/psy611/), the first in a series of graduate statistics courses taught entirely in R.

In addition, as I've [written about previously](/post/2020-03-08-data-science-training-needs-in-grad-school/index.html), current grad students, along with other members of the psychology department, have expressed a keen interest in developing a stronger foundation in skills such as basic programming, data wrangling, and data visualization. So the bootcamp also serves as an opportunity for existing R users to get a refresher and deeper dive into those topics for those who want it.

After spending lot of time thinking about how to improve the data science learning experience for my fellow grad students and having [recently become](https://bcullen.rbind.io/post/2020-09-03-reflections-on-rstudio-instructor-training/) an [RStudio Certified Instructor](https://education.rstudio.com/trainers/people/cullen+brendan/) in the tidyverse, it was my great privilege to be able to put all of this into action by leading the 3rd Annual UO Psych Bootcamp this year.

## The challenge

However, I found myself facing a rather significant challenge. The R Bootcamp, like many intro R workshops, usually occurs in-person in a large room with a giant projector screen, coffee and snacks, and, most importantly, the ability to run over and look over someone's shoulder at their computer screen when they need help. Because of COVID-19, I needed to design and deliver a bootcamp for a large group of beginners (many using R for the very first time) entirely over a webcam. 

Moreover, I assumed that student motivation would be at an all-time low and feelings of anxiety and uncertainty would be at an all-time high -- especially for those about to start their graduate school journey entirely online, very much contrary to plan. There were a lot of horrible things going on in the world in September 2020, which marked 6 months into the COVID-19 pandemic in the U.S. -- people's loved ones were getting sick, the killing of innocent Black lives continued, a bitter presidential race reached full swing -- not to mention devastating wildfires that raged all along the west coast. (Of course, while I wish I could actually write about these events in the past tense, all of these problems continue). 

So, how do you get people excited about learning R amidst all of *that*? Needless to say, this felt a little daunting. Fortunately, though, there are people out there who are experts in this sort of thing who have graciously shared their resources and advice, and this helped me immensely to run a successful bootcamp. 

## Who attended?

52 people registered for the bootcamp. While the majority of those who attended were incoming first-year psychology grad students, we also had a mix of more advanced grad students, undergrads, research assistants, lab managers, staff data analysts, and faculty members from a variety of departments/centers across the University, including the Departments of Psychology, Linguistics, Economics and the Center for Translational Neuroscience.

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-2-1.png" width="672" />

<br><br>

<img src="{{< blogdown/postref >}}index_files/figure-html/unnamed-chunk-3-1.png" width="672" />

## Logistics

### Zoom + Slack = 👌

We ran synchronous sessions live over Zoom. However, rather than use the Zoom chat for communicating with each other and asking questions, we used Slack. A few reasons for this: 

1) this way people could continue to ask questions outside of the live sessions and a permanent and searchable record of questions and answers would be available for posterity

2) The Zoom chat can get easily cluttered and doesn't easily allow you to make threads, which keep things more organized

3) Slack has better emojis 🤓. 

I was fortunate to have the very knowledgeable and talented [Cameron Kay](http://cameronstuartkay.com/) and [Cianna Bedford-Petersen](https://ciannabp.com/) as teaching assistants. Cam and Cianna remained on deck throughout the sessions to answer questions on Slack while we went through the material. We also decided that if a student ran into technical issues or felt completely lost, then one of the TA's would pull them into a breakout room on Zoom to offer one-on-one help. 

### RStudio Cloud 

For "Your Turn" exercises, an idea I stole from Alison Hill's excellent rstudio::conf(2020) [workshop](https://conf20-intro-ml.netlify.app/), we used [RStudio Cloud](https://rstudio.com/products/cloud/), a hosted version of the RStudio IDE available in the web browser. We did this to avoid issues with students installing RStudio on their local machines, as troubleshooting technical issues over Zoom in a large group is not something we felt prepared for. Using RStudio Cloud also allowed me to configure specific IDE settings and pre-load specific packages to allow students to initially avoid technical issues. Lastly, sharing a workspace on RStudio Cloud allowed each student to save their own copy of the projects containing the Your Turn exercises, which in turn made it possible for myself or the TA's to "peek" into a student's exercises and help them figure out where their errors were coming from. Overall it went really smoothly, and everyone who filled out the feedback survey said they had no issues using it. I highly recommend using this for your teaching, even if it's in-person.

### Blogdown site

To make the bootcamp materials more accessible and shareable, I decided to package them into a website, which I created using the [blogdown](https://github.com/rstudio/blogdown) package (see more on this [below](#ssn)). Organizing your teaching materials into a website has three clear advantages in my mind: 

1) A website makes your materials easier to access and more shareable -- you send someone a single link they can access on their phone or computer, no need to download anything

2) A website is highly sustainable in the sense that it's easy for students to bookmark and refer back to over and over, and if you push changes to Github with continuous deployment (e.g. via [Netlify](https://www.netlify.com/)), students will always have access to the most updated materials. This avoids having to introduce Github and version control, which is a whole other beast to teach to beginners.

3) Websites are pretty and highly customizble

🔗 [uopsych-r-bootcamp-2020.netlify.app](https://uopsych-r-bootcamp-2020.netlify.app/)

<iframe src="https://uopsych-r-bootcamp-2020.netlify.app/" width="672" height="500px"></iframe>


## Tools I learned {#tools}

{{< panelset class="tools" >}}
{{< panel name="`xaringanExtra`" >}}

📦 [pkg.garrickadenbuie.com/xaringanExtra](https://pkg.garrickadenbuie.com/xaringanExtra/)

<i class="fas fa-user"></i> [Garrick Aden-Buie](https://www.garrickadenbuie.com/)

`{xaringanExtra}` extends the functionality of the already amazing `{xaringan}` package by [Yihuie Xie](https://yihui.org/en/about/), and it has become one of my all-time favorite packages. Here are the features I use most often and *highly* recommend.

📖 [Share again](https://pkg.garrickadenbuie.com/xaringanExtra/#/share-again)

<video width="700" height="533" controls>
  <source src="share_again.mov" type="video/mp4">
</video>

📖 [Panelset](https://pkg.garrickadenbuie.com/xaringanExtra/#/panelset)

<video width="700" height="533" controls>
  <source src="panelset.mov" type="video/mp4">
</video>

📖 [Tile view](https://pkg.garrickadenbuie.com/xaringanExtra/#/tile-view)

<video width="700" height="533" controls>
  <source src="tile_view.mov" type="video/mp4">
</video>

📖 [Extra styles](https://pkg.garrickadenbuie.com/xaringanExtra/#/extra-styles)

<video width="700" height="533" controls>
  <source src="extra_style.mov" type="video/mp4">
</video>

In case it still isn't obvious enough how much I love this package...

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Ok, {xaringanExtra} continues to blow my freakin&#39; mind 🤯 Here&#39;s a quick demo that shows tile view and `embed_xaringan()` in the context of a <a href="https://twitter.com/hashtag/ggplot2?src=hash&amp;ref_src=twsrc%5Etfw">#ggplot2</a> flipbook (h/t <a href="https://twitter.com/EvaMaeRey?ref_src=twsrc%5Etfw">@EvaMaeRey</a>). <a href="https://twitter.com/grrrck?ref_src=twsrc%5Etfw">@grrrck</a>, I owe you an absurd amount of beers 🍻 Thank you for all you do for the <a href="https://twitter.com/hashtag/rstats?src=hash&amp;ref_src=twsrc%5Etfw">#rstats</a> community 🙌 <a href="https://t.co/ucMCbOvopW">pic.twitter.com/ucMCbOvopW</a></p>&mdash; Brendan Cullen (@_bcullen) <a href="https://twitter.com/_bcullen/status/1310696423239819264?ref_src=twsrc%5Etfw">September 28, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Jump back up to see more tools](#tools) ⤴️

{{< /panel >}}

{{< panel name="`flair`" >}}

📦 [r-for-educators.github.io/flair](https://r-for-educators.github.io/flair/index.html)

<i class="fas fa-user"></i> [Kelly Bodwin](https://www.kelly-bodwin.com/)

`{flair}` allows you to spice up your code with color-coding and dynamic syntax highlighting. One of the most useful applications is to match colors to concepts -- e.g. giving each argument of a function a unique color. I feel like I've only scratched the surface with `{flair}` and can't wait to use it more in my teaching going forward.

Below is a demonstration of color-coding with `flair` to introduce `dplyr::filter()` and its arguments.

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="https://uopsych-r-bootcamp-2020.netlify.app/slides/07-slides.html?panelset=arguments&amp;panelset9=arguments6&amp;panelset10=arguments7&amp;panelset11=q14&amp;panelset12=arguments8&amp;panelset13=arguments9&amp;panelset14=q15&amp;panelset15=arguments10&amp;panelset16=example-110&amp;panelset17=q16#22" width="1600" height="900" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>

You can read more about other educational use cases for `flair` in this great [post](https://education.rstudio.com/blog/2020/05/flair/) on the RStudio Education Blog.

[Jump back up to see more tools](#tools) ⤴️

{{< /panel >}}

{{< panel name="`flipbookr`" >}}

📦 [evamaerey.github.io/flipbooks/about](https://evamaerey.github.io/flipbooks/about)

<i class="fas fa-user"></i> [Gina Reynolds](https://evangelinereynolds.netlify.app/)

`{flipbookr}` is an amazing teaching tool -- it allows you to incrementally build up a plot line by line, which capitalizes on the "blink comparator" method. This means that students are able to easily map a specific change in code to a specific visual change in the corresponding plot output. Flipbooks are also great for demonstrating incremental changes in a data wrangling pipeline, and they're relatively easy to make!

<video width="700" height="533" controls>
  <source src="flipbook.mov" type="video/mp4">
</video>

[Jump back up to see more tools](#tools) ⤴️

{{< /panel >}}

{{< panel name="`countdown`" >}}

📦 [pkg.garrickadenbuie.com/countdown](https://pkg.garrickadenbuie.com/countdown/)

<i class="fas fa-user"></i> [Garrick Aden-Buie](https://www.garrickadenbuie.com/)

`{countdown}` is another great gem from Garrick and allows you to put timers directly on your slides. This is really useful for timed "Your Turn" exercises or to make sure you stay on track with Q & A sessions or breaks.

<video width="700" height="533" controls>
  <source src="countdown.mov" type="video/mp4">
</video>

[Jump back up to see more tools](#tools) ⤴️

{{< /panel >}}
{{< /panelset >}}

## Resources I recommend 

### Sharing on short notice {#ssn}

<i class="fas fa-user"></i> [Alison Hill](https://alison.rbind.io/), [Desirée De Leon](https://desiree.rbind.io/)

A super helpful webinar on how best to share your teaching materials online.

- <i class="fas fa-video"></i> [webinar](https://rstudio.com/resources/webinars/sharing-on-short-notice-how-to-get-your-materials-online-with-r-markdown/)
- <i class="fas fa-images"></i> [slides](https://rstudio-education.github.io/sharing-short-notice/)
- <i class="fab fa-github"></i> [share-blogdown template](https://github.com/apreshill/share-blogdown)
- <i class="fas fa-book"></i> [blog post](https://education.rstudio.com/blog/2020/04/sharing-on-short-notice/)

### Teaching online on short notice

<i class="fas fa-user"></i> [Greg Wilson](https://third-bit.com/)

Concrete tips and advice on making the most of teaching via a webcam. There's a ton of great stuff in here you wouldn't necessarily think of, including important advice on making your teaching accessible and inclusive in an online format.

- <i class="fas fa-video"></i> [webinar](https://rstudio.com/resources/webinars/teaching-online-at-short-notice/)
- <i class="fas fa-images"></i> [slides](https://docs.google.com/presentation/d/1rE5e2kSFNICNkBJ4iIIgd9eqACi62gxahknKLtw9Hzs/edit#slide=id.g55ddde1eae_0_2)
- <i class="fas fa-book"></i> [blog post](https://education.rstudio.com/blog/2020/03/teaching-online-on-short-notice/)

### Teaching R online with RStudio Cloud

<i class="fas fa-user"></i> [Mine Çetinkaya-Rundel](https://www2.stat.duke.edu/~mc301/)

A very thorough and easy to follow walk-through of using RStudio Cloud for teaching, highlighting its most useful features. 

- <i class="fas fa-video"></i> [webinar](https://rstudio.com/resources/webinars/teaching-r-online-with-rstudio-cloud/)
- <i class="fas fa-images"></i> [slides](https://mine-cetinkaya-rundel.github.io/rstudio-cloud-webinar/rstudio-cloud.html#1)
- <i class="fas fa-book"></i> [blog post](https://education.rstudio.com/blog/2020/04/teaching-with-rstudio-cloud-q-a/)

### Teaching the tidyverse in 2020

<i class="fas fa-user"></i> [Mine Çetinkaya-Rundel](https://www2.stat.duke.edu/~mc301/)

A series of blog posts describing a recommended order in which to teach tidyverse topics to beginners, including very recent tidyverse features that are useful for R users at all levels to learn

- <i class="fas fa-book"></i> [Part 1: Getting started](https://education.rstudio.com/blog/2020/07/teaching-the-tidyverse-in-2020-part-1-getting-started/)
- <i class="fas fa-book"></i> [Part 2: Data visualization](https://education.rstudio.com/blog/2020/07/teaching-the-tidyverse-in-2020-part-2-data-visualisation/)
- <i class="fas fa-book"></i> [Part 3: Data wrangling and tidying](https://education.rstudio.com/blog/2020/07/teaching-the-tidyverse-in-2020-part-3-data-wrangling-and-tidying/)
- <i class="fas fa-book"></i> [Part4: Part 4: When to purrr?](https://education.rstudio.com/blog/2020/07/teaching-the-tidyverse-in-2020-part-4-when-to-purrr/)

### Data science concept maps

A growing list of concept maps related to data science topics in R. Great for planning your lessons and/or sharing in your slides to summarize topics, no matter how seemingly simple or complex.

<i class="fas fa-users"></i> Community contributors, curated by [Greg Wilson](https://third-bit.com/)

- <i class="fab fa-github"></i> [github repo](https://github.com/rstudio/concept-maps)
- <i class="fab fa-google-drive"></i> [google drive folder](https://docs.google.com/presentation/d/1ForBjP0pVhljBLuqOyYfyHw_1rrwJzpWW1ZHzCqAJpU/edit#slide=id.p)
- <i class="fas fa-book"></i> [blog post](https://education.rstudio.com/blog/2020/09/concept-maps/)

### rstats artwork {#artwork}

<i class="fas fa-user"></i> [Allison Horst](https://www.allisonhorst.com/)

A collection of mind-blowing art that makes it 1000% more fun to learn R. 

- <i class="fab fa-github"></i> [github repo](https://github.com/allisonhorst/stats-illustrations)
- <i class="fas fa-comments"></i> [interview with Allison Horst](https://www.dataquest.io/blog/making-learning-to-code-friendlier-with-art-allison-horst-interview/)

## The importance of encouragement & positivity

The leaRning curve is no secret. I hadn't touched R before starting grad school in 2017, but I had heard whispers here and there that learning R is really difficult. But I think there's an element of self-fulfilling prophecy here. If you expect it to be impossible, then it will feel impossible. I more or less started my journey with that expectation. 

Things changed for me when I took my first course with [Daniel Anderson](https://twitter.com/datalorax_). Daniel has developed a fantastic 5-course [Data Science Specialization in Educational Leadership](https://education.uoregon.edu/data-science-specialization-educational-leadership) in the [College of Education](https://education.uoregon.edu/) at the University of Oregon, taught entirely in R, which ranges from the very basics of R to advanced machine learning with [tidymodels](https://www.tidymodels.org/) (see more info [here](data_sci_specialization.jpg)). Daniel's teaching completely changed the way I approached using and learning R, and it was largely on his recommendation that I joined #rstats Twitter (which was a game-changer). More importantly, Daniel modeled the kind of teacher I wanted to be -- clear, thorough, thoughtful, and above all else, kind and inclusive of everyone.

It was very much with Daniel's model in mind that I found inspiration for making learning R feel more inviting and less daunting. Here are a few things that came to mind that can be abstracted to some general advice...

### Anticipate the challenge 

Recognize the fact that learning R is *hard*. Don't pretend it's a walk in the park -- it isn't. But at the same time, emphasize that the investment of time it takes is worth it!

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="https://uopsych-r-bootcamp-2020.netlify.app/slides/00-slides.html#10" width="1600" height="900" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>

### Normalize errors & mistakes

The first time someone uses R, error messages are one of the first things that they'll see. As we all know, this feels frustrating, especially as a beginner. So it makes sense to acknowledge that up front and discuss what error messages are and why they occur. As error messages go hand-in-hand with debugging, it's also a good idea to at least introduce that concept as well, without necessarily going into great depth since that's a whole other topic of it's own. As debugging is commonly considered part of ["what they forgot to teach you about R"](https://rstats.wtf/debugging-r-code.html), I'm sure I'm not alone in wishing that I had been introduced to debugging much earlier on in my R learning experience. 

While learning a systematic approach to debugging is important down the line, it's more important at first for beginners to understand that seeing lots of error messages at first is not a bad thing. It's worth spending some effort to convince your students that error messages should not be cause for discouragement or giving up. Simply put, error messages are part and parcel of programming. Sometimes they take a matter of seconds to fix, sometimes a matter of weeks, but everyone who uses R will regularly encounter error messages, no matter your level of experience. And when it really comes down to it, every error message is an opportunity to learn something!

<div class="shareagain" style="min-width:300px;margin:1em auto;">
<iframe src="https://uopsych-r-bootcamp-2020.netlify.app/slides/03-slides.html?panelset4=q14&amp;panelset5=nrow2&amp;panelset6=q15&amp;panelset7=q16#60" width="1600" height="900" style="border:2px solid currentColor;" loading="lazy" allowfullscreen></iframe>
<script>fitvids('.shareagain', {players: 'iframe'});</script>
</div>

<br> 

Taking this one step further, it's a good idea to deliberately incorporate making mistakes into your own teaching and use error messages as a teachable moment. You can even use unintentional mistakes as teachable moments -- demonstrate for your students how you fix the mistake and invite them to give their thoughts and feedback. This not only makes your presentation less rehearsed, but it provides a really valuable "real-world" context for learning. 

<div class="note">
This idea is referred to as "positive error framing" -- and if you want to learn more about this topic in depth I recommend you check out <a href="https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008090#sec011">this section</a> from the recent article <a href = "https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1008090">"Ten quick tips for teaching with participatory live coding"</a>.
</div>


## Make your materials friendly and inviting! 

If your slides read like one long piece of dense help documentation, people are not going to feel inclined to engage with it. How do you make your materials more inviting and approachable? 

One of the most powerful tools out there, in my opinion, is the incredible artwork by Allison Horst, RStudio's first [artist-in-residence](https://blog.rstudio.com/2019/11/18/artist-in-residence/) (see more [above](#artwork)). The bigger picture behind the artwork, in Allison's words: 

>"All of it is towards a goal of trying to make R, and data science in general, more approachable, welcoming, and engaging to diverse learners".

<img src="monster_support.jpg" width="3802" />

## A final thought

No matter how long someone has been using R, it never hurts to remind them (yourself included) that a little time and effort can go a long way.

<center>

<img src="time_effort.gif"  width = 417/>

</center>

## Acknowledgements 

I owe a huge debt of gratitude to all the people who were instrumental in my initial experience of learning R: [Daniel Anderson](https://twitter.com/datalorax_), [Dani Cosme](https://twitter.com/danicosme), [Krista DeStasio](https://twitter.com/PsychNeurd), [Cory Costello](https://twitter.com/CostelloCK), [Jessica Kosie](https://twitter.com/JessKosie), and [Sara Weston](https://twitter.com/saraweston09), to name only a few. 

Thanks again to [Cameron Kay](https://twitter.com/cameronskay) and [Cianna Bedford-Petersen](https://twitter.com/ciannabp) for being such awesome TA's for the R Bootcamp. 

I also wouldn't know half of what I know about learning and teaching R if it weren't for the RStudio Education team -- in particular, [Alison Hill](https://twitter.com/apreshill), [Greg Wilson](https://twitter.com/gvwilson), [Desirée De Leon](https://twitter.com/dcossyle), [Mine Çetinkaya-Rundel](https://twitter.com/minebocek), and [Garrett Grolemund](https://twitter.com/StatGarrett). 

Artwork included in this post is by [Allison Horst](https://twitter.com/allison_horst).

<details><summary>Session Info</summary>

```
## ─ Session info ───────────────────────────────────────────────────────────────
##  setting  value                       
##  version  R version 4.0.3 (2020-10-10)
##  os       macOS Catalina 10.15.7      
##  system   x86_64, darwin17.0          
##  ui       X11                         
##  language (EN)                        
##  collate  en_US.UTF-8                 
##  ctype    en_US.UTF-8                 
##  tz       America/Los_Angeles         
##  date     2021-11-09                  
## 
## ─ Packages ───────────────────────────────────────────────────────────────────
##  package       * version    date       lib
##  assertthat      0.2.1      2019-03-21 [1]
##  backports       1.1.10     2020-09-15 [1]
##  blob            1.2.1      2020-01-20 [1]
##  blogdown        1.0.1      2021-01-11 [1]
##  bookdown        0.21       2020-10-13 [1]
##  broom           0.7.1      2020-10-02 [1]
##  cellranger      1.1.0      2016-07-27 [1]
##  cli             2.2.0      2020-11-20 [1]
##  colorspace      2.0-0      2020-11-11 [1]
##  crayon          1.3.4      2017-09-16 [1]
##  DBI             1.1.0      2019-12-15 [1]
##  dbplyr          1.4.4      2020-05-27 [1]
##  digest          0.6.27     2020-10-24 [1]
##  dplyr         * 1.0.3      2021-01-15 [1]
##  ellipsis        0.3.1      2020-05-15 [1]
##  emo             0.0.0.9000 2020-11-04 [1]
##  evaluate        0.14       2019-05-28 [1]
##  fansi           0.4.2      2021-01-15 [1]
##  farver          2.0.3      2020-01-16 [1]
##  forcats       * 0.5.0      2020-03-01 [1]
##  fs              1.5.0      2020-07-31 [1]
##  generics        0.1.0      2020-10-31 [1]
##  ggplot2       * 3.3.3      2020-12-30 [1]
##  glue            1.4.2      2020-08-27 [1]
##  gtable          0.3.0      2019-03-25 [1]
##  haven           2.3.1      2020-06-01 [1]
##  highr           0.8        2019-03-20 [1]
##  hms             0.5.3      2020-01-08 [1]
##  htmltools       0.5.0      2020-06-16 [1]
##  httr            1.4.2      2020-07-20 [1]
##  janitor         2.0.1      2020-04-12 [1]
##  jpeg            0.1-8.1    2019-10-24 [1]
##  jsonlite        1.7.2      2020-12-09 [1]
##  knitr           1.30       2020-09-22 [1]
##  labeling        0.4.2      2020-10-20 [1]
##  lifecycle       0.2.0      2020-03-06 [1]
##  lubridate       1.7.9.2    2020-11-13 [1]
##  magrittr        2.0.1      2020-11-17 [1]
##  Manu          * 0.0.1      2020-11-04 [1]
##  modelr          0.1.8      2020-05-19 [1]
##  munsell         0.5.0      2018-06-12 [1]
##  pillar          1.4.7      2020-11-20 [1]
##  pkgconfig       2.0.3      2019-09-22 [1]
##  purrr         * 0.3.4      2020-04-17 [1]
##  R6              2.5.0      2020-10-28 [1]
##  Rcpp            1.0.5      2020-07-06 [1]
##  readr         * 1.4.0      2020-10-05 [1]
##  readxl          1.3.1      2019-03-13 [1]
##  reprex          0.3.0      2019-05-16 [1]
##  rlang           0.4.10     2020-12-30 [1]
##  rmarkdown       2.6        2020-12-14 [1]
##  rstudioapi      0.13       2020-11-12 [1]
##  rvest           0.3.6      2020-07-25 [1]
##  scales          1.1.1      2020-05-11 [1]
##  sessioninfo     1.1.1      2018-11-05 [1]
##  snakecase       0.11.0     2019-05-25 [1]
##  stringi         1.5.3      2020-09-09 [1]
##  stringr       * 1.4.0      2019-02-10 [1]
##  tibble        * 3.0.5      2021-01-15 [1]
##  tidyr         * 1.1.2      2020-08-27 [1]
##  tidyselect      1.1.0      2020-05-11 [1]
##  tidyverse     * 1.3.0      2019-11-21 [1]
##  vctrs           0.3.6      2020-12-17 [1]
##  withr           2.4.0      2021-01-16 [1]
##  xaringanExtra * 0.2.4      2020-11-04 [1]
##  xfun            0.20       2021-01-06 [1]
##  xml2            1.3.2      2020-04-23 [1]
##  yaml            2.2.1      2020-02-01 [1]
##  source                                  
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  Github (rstudio/blogdown@0f7f73f)       
##  CRAN (R 4.0.3)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.3)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  Github (hadley/emo@3f03b11)             
##  CRAN (R 4.0.1)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.3)                          
##  Github (G-Thomson/Manu@a12062f)         
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
##  Github (gadenbuie/xaringanExtra@aebe20a)
##  CRAN (R 4.0.3)                          
##  CRAN (R 4.0.2)                          
##  CRAN (R 4.0.2)                          
## 
## [1] /Library/Frameworks/R.framework/Versions/4.0/Resources/library
```
</details>

