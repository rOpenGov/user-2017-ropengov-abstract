---
title: "Community-based learning and knowledge sharing"
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

R is increasingly used in learning to entry-level programming and quantitative analytics in universities, research institutes, public sector offices and private companies. Many researchers and data scientists are developing educational resources in R, such as open tutorial collections [@Kamvar2017 ; @Lahti2017] or domain specific training materials [@Afanador2017]. Initiatives such as Data Carpentry [REF?] and Software Carpentry [REF?] have already greatly facilitated such learning processes.

A particularly important but often overlooked feature of R is that in enables **interactive learning**, where learners can learn programming and data science skills by a problem-centered approach. Even programming-naive learners can, in our experience, rapidly adopt key programming concepts and practical skills by analyzing topical example data sets by adapting simple initial Rmarkdown templates, supported by dedicated tutorial collections. Whereas this approach has proven successful even with new R users, we have noticed that many learning aspects enabled by R can be better appreciated by advanced statisticians. Hence, R can be used as a teaching tools at various levels of data science expertise.

Moreover, the academia and public sector institutions, for example, have different needs. In public sector, such as statistical agencies, automation of existing manual data routines is a priority. New technology must comply with internal it-infrastructure and deliver sharp looking outputs. In academia, interest in novel methods and data sources, reproducibility and personal data management are shared across disciplines. However, successfull training scheme must allow great degree of **domain specificity** to adjust to, for instance, different of epistemological traditions of fields varying from history to quantum physics. This poses a great challenges for crafting common guidelines and materials.

The R community could further support teaching with R by documenting and archiving open course materials using modern sustainable techniques that facilitate collaboration and sharing.

By pooling the material and experience from personal and collective experiences, we aimed to facilitate the uptake of computational tools in various institutions. Based on our combined experience from universities, research institutes, and the public sector, we aimed to summarize key ingredients for successful teaching of modern data science, facilitated by the versatile toolkit that the R ecosystem and its active user communities can provide.

**Having fun** is important throughout the process. Gamification of assignments with real-time rankings or custom functions performing non-statistical operations like emailing gif images can raise awareness of how R as a full-fledged programming language differs from proprietary statistical packages. 







Simple, ready-made templates can be used as a starting point to expose the learners rapidly to the available tools and **best practices** in data science [@Wilson2016], **collaborative development** models, and the principles of **open science**.


This also helps to **get things done fast** Avoid the trap of many programs and get the feeling of success. Reproducible research / workflows. Potential of R packages (targeted tools, open science, reproducible research) easier to explain to experienced statisticians that have years of experience on repetitive tasks; compared to undergraduate students. korostaisin vielä kohdassa 3 sitä, että harjoittelun pitäisi nopeasti integroitua opiskelijan arkiseen datatyöhön (jos sellaista on). Se vaihe, jossa uuden kielen harjoittelu demomatskuilla kulkee rinnakkan varsinaisen työn/opinnäytteen tekemisen kanssa jossa käytössä vanhat tavat, pitäisi saada mahdollisimma lyhyeksi. nopeasti siirryttäisiin soveltamaan opittua käytännön töissä. Tää vaihe kriittinen ja vaatis paljon vieritukea kun aikataulupaineet ym.s **Domain specificity** Facilitating learning and knowledge sharing on grassroot level means, that the teaching experience can be very domain specific and hence very relevant for the learners. However, this also poses challenges for developing common processes and materials.

**Open collaboration model** If teaching is coupled with open collaboration model ie. straight from start using custom built R package, this can highlight the open development model and its dynamic potential. Not just a free replacement for commercial stats software but a collaborative platform for developing solutions and utilities, including ggplot themes, raport templates, rstudio-add-ins, shiny-modules, database functions etc. **Code review** Existing experience in the research/work community and knowledge sharing can be leveraged by using simple fork - pull request - code review model enabled by Github. **Show-and-tell culture** Actively promote sharing experiences of both how people learn R and how they have solved specific problems. Informal meetings, online communication channels (e.g. Slack, IRC, Facebook) and hackathons can all be leveraged to help sharing individual experiences.



# References

Pérez-Suárez (2015): Code Review - a Needed Habit in Science. https://software-carpentry.org/blog/2015/10/code-review-habit.html

Petre & Wilson (2013): PLOS/Mozilla Scientific Code Review Pilot: Summary of Findings. https://arxiv.org/abs/1311.2412

Petre & Wilson (2014): Code Review For and By Scientists. https://arxiv.org/abs/1407.5648

Wilson et al. (2014): Best Practices for Scientific Computing. http://dx.doi.org/10.1371/journal.pbio.1001745

Wilson et al. (2016): Good Enough Practices in Scientific Computing. https://arxiv.org/abs/1609.00037 (edited)
