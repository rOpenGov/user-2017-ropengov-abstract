---
title: "Grassroot level learning and knowledge sharing in R"
author:
  Lahti L^1^, Lehtomäki J^2^, and Kainu M^3
  $^1$Department of Mathematics and Statistics, University of Turku, Finland
  $^2$Department of Earth Sciences, VU Amsterdam
output:
  pdf_document
bibliography:
  - bibliography.bib
---

**Keywords**: Teaching, Open Science, Workflows, Tutorials, Best Practices

**Webpages**: [https://ropengov.github.io](https://ropengov.github.io)

R is increasingly used in learning to entry-level programming in universities, research institutes, public sector offices and private companies. In addition, many researchers and data scientists are developing educational resources in R, such as open tutorial collections [@Kamvar2017 ; @Lahti2017], exercise materials [REF?] or presentation slides [REF?]. In addition, initiatives such as Data Carpentry [REF?] and Software Carpentry [REF?] have already facilitated the learning process greatly. By pooling the material and experience from these personal and collective experiences, we can further facilitate the uptake of computational tools in various institutions. Simple, ready-made templates can be used as a starting point to expose the learners rapidly to the available tools and best practices in programming, collaborative development models, and the principles of open science. Based on our combined experience from universities, research institues, and the public sector, we have collected a set of ten simple rules, aiming to summarize key ingredients for successful teaching of modern computational science, facilitated by the versatile toolkit that the R ecosystem and its active user communities can provide. 

1. **Levels of teaching** As in all teaching, it is essential to identify the learners’ prior knowledge and the overall learning goals. Many aspects enabled by R can be better appreciated by advanced statisticians than those who are still learning the basics of programming. Moreover, the academia and public sector institutions, for example, have different needs.

2. **Interactive learning** Students can start from a simple Rmarkdown workflow and expand that. 

3. **Getting things done fast** Avoid the trap of many programs and get the feeling of success. Reproducible research / workflows. Potential of R packages (targeted tools, open science, reproducible research) easier to explain to experienced statisticians that have years of experience on repetitive tasks; compared to undergraduate students. 

4. **Open science**

5. **Best practices** Good Enough Practices for Scientific Computing [@Wilson2016] / Tidy data principles

6. **Code review** Existing experience in the research/work community and knowledge sharing can be leveraged by using simple fork - pull request - code review model enabled by Github.

7. **Open collaboration model** If teaching is coupled with open collaboration model ie. straight from start using custom built R package, this can highlight the open development model and its dynamic potential. Not just a free replacement for commercial stats software but a collaborative platform for developing solutions and utilities, including ggplot themes, raport templates, rstudio-add-ins, shiny-modules, database functions etc.

8. **Educational resources** Document and archive course materials on Github and Canvas using modern sustainable techniques that facilitate collaboration and sharing. 

9. **Domain specificity** Facilitating learning and knowledge sharing on grassroot level means, that the teaching experience can be very domain specific and hence very relevant for the learners. However, this also poses challenges for developing common processes and materials.

10. **Show-and-tell culture** Actively promote sharing experiences of both how people learn R and how they have solved specific problems. Informal meetings, online communication channels (e.g. Slack, IRC, Facebook) and hackathons can all be leveraged to help sharing individual experiences.

In summary, R community could better support teaching with R by.. collections of open teaching materials, sharing best practices etc..



# References

Pérez-Suárez (2015): Code Review - a Needed Habit in Science. https://software-carpentry.org/blog/2015/10/code-review-habit.html

Petre & Wilson (2013): PLOS/Mozilla Scientific Code Review Pilot: Summary of Findings. https://arxiv.org/abs/1311.2412

Petre & Wilson (2014): Code Review For and By Scientists. https://arxiv.org/abs/1407.5648

Wilson et al. (2014): Best Practices for Scientific Computing. http://dx.doi.org/10.1371/journal.pbio.1001745

Wilson et al. (2016): Good Enough Practices in Scientific Computing. https://arxiv.org/abs/1609.00037 (edited)
