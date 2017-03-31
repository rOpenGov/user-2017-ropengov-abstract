---
title: "Group learning and knowledge sharing in R"
author:
  Lahti L^1^, Lehtomäki J^2^, and Kainu M^3
  $^1$Department of Mathematics and Statistics, University of Turku, Finland
  $^2$Department of Earth Sciences, VU Amsterdam
  $^3$The Social Insurance Institution of Finland
output:
  pdf_document
bibliography:
  - bibliography.bib
---

**Keywords**: Teaching, Open Science, Best Practices

**Webpages**: [https://ropengov.github.io](https://ropengov.github.io)

R is increasingly used in learning to entry-level programming and quantitative analytics in universities, research institutes, public sector offices and private companies. Many researchers and data scientists are developing educational resources in R, such as open tutorial collections [@Kamvar2017 ; @Lahti2017] or domain specific training materials [@Afanador2017]. Initiatives such as Data Carpentry [REF?] and Software Carpentry [REF?] have already greatly facilitated the learning process. By pooling the material and experience from personal and collective experiences, we can further facilitate the uptake of computational tools in various institutions. Simple, ready-made templates can be used as a starting point to expose the learners rapidly to the available tools and best practices in programming, collaborative development models, and the principles of open science. Based on our combined experience from universities, research institutes, and the public sector, we have collected a set of best practices, aiming to summarize key ingredients for successful teaching of modern computational science, facilitated by the versatile toolkit that the R ecosystem and its active user communities can provide. 

The **level of learning** is one of the first things to consider. Many aspects enabled by R can be better appreciated by advanced statisticians than those who are still learning the basics of programming and data analysis. Moreover, the academia and public sector institutions, for example, have different needs. In public sector, such as statistical agencies, automation of existing manual data routines is a priority. New technology must comply with internal it-infrastructure and deliver sharp looking outputs. In academia, interest in novel methods and data sources, reproducibility and personal data management are shared across disciplines. However, successfull training scheme must allow great degree of **domain specificity** to adjust to, for instance, different of epistemological traditions of fields varying from history to quantum physics. This poses a great challenges for crafting common guidelines and materials.

**Open science** and **Best practices** Good Enough Practices for Scientific Computing [@Wilson2016] / Tidy data principles

R enables **interactive learning**, where students can start from a simple Rmarkdown workflow and expand from it. When coupled with good software development practises this can quickly bridge the gap between new set of skills and ones own analytical problems. The time between being introduced to new tools until being able apply them in real world tasks should be minised with good scheduling and personal consultations. Avoiding being trapped with multiple statistical packages simultaneously is very important. Potential of internal R packages (targeted tools, open science, reproducible research) is easier to explain to experienced statisticians with years of experience on repetitive tasks, compared to undergraduate students. 

Reproducible research / workflows.

**Open collaboration model** If teaching is coupled with open collaboration model ie. straight from start using custom built R package, this can highlight the open development model and its dynamic potential. Not just a free replacement for commercial stats software but a collaborative platform for developing solutions and utilities, including ggplot themes, raport templates, rstudio-add-ins, shiny-modules, database functions etc. **Code review** Existing experience in the research/work community and knowledge sharing can be leveraged by using simple fork - pull request - code review model enabled by Github. **Show-and-tell culture** Actively promote sharing experiences of both how people learn R and how they have solved specific problems. Informal meetings, online communication channels (e.g. Slack, IRC, Facebook) and hackathons can all be leveraged to help sharing individual experiences.

**Educational resources** Document and archive course materials on Github and Canvas using modern sustainable techniques that facilitate collaboration and sharing. 

In summary, R community could better support teaching with R by.. collections of open teaching materials, sharing best practices etc..


# References

Pérez-Suárez (2015): Code Review - a Needed Habit in Science. https://software-carpentry.org/blog/2015/10/code-review-habit.html

Petre & Wilson (2013): PLOS/Mozilla Scientific Code Review Pilot: Summary of Findings. https://arxiv.org/abs/1311.2412

Petre & Wilson (2014): Code Review For and By Scientists. https://arxiv.org/abs/1407.5648

Wilson et al. (2014): Best Practices for Scientific Computing. http://dx.doi.org/10.1371/journal.pbio.1001745

Wilson et al. (2016): Good Enough Practices in Scientific Computing. https://arxiv.org/abs/1609.00037 (edited)
