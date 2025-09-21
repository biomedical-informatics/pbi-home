---
layout: home
title: Home
nav_exclude: false
nav_order: 1
permalink: /:path/
seo:
  type: Course
  name: Programming for Biomedical Informatics (PBI) (INFR11260)
---

# Programming for Biomedical Informatics

## Informatics (INFR11260), Semester 1, 2025

---

{% raw %}
<div class="d-flex flex-justify-around flex-wrap">
  <figure class="shadow" style="width: 200px; text-align: center;">
    <img src="./assets/images/ian.png" alt="Prof. Ian Simpson" 
        style="width: 100px; height: 125px; object-fit: cover; border-radius: 50%;">
    <figcaption><b>Course Lecturer</b><br><a href='https://biomedicalinformaticsgroup.github.io/people/iansimpson.html'>Ian Simpson</a></figcaption>
  </figure>

  <figure class="shadow" style="width: 200px; text-align: center;">
    <img src="./assets/images/kendig.jpg" alt="Kendig Sham" 
        style="width: 100px; height: 125px; object-fit: cover; border-radius: 50%;">
    <figcaption><b>Teaching Assistant</b><br>Kendig Sham</figcaption>
  </figure>
</div>
{% endraw %}

---

{: .highlight}
{% assign announcements = site.announcements | reverse %}
{{ announcements.first }}

[List of Weekly Tasks](https://biomedical-informatics.github.io/pbi-home/announcements){: .btn .btn-outline}

In this course, you will learn how to use Python to retrieve and parse data from biological repositories through bulk download and application programming interfaces (APIs). You will learn about established data formats for different data modalities so that you can understand the structure and content of the data and how it was generated. Each week we will focus on analytical tasks in linked topics that span the main components of modern biomedical informatics research. Topics will change slightly each year, but will typically include tools, algorithms, and approaches for biological sequence, multi-omics (transcriptomics, proteomics, methylomics), biomedical network, and biomedical text analysis. Each topic will be explored using real-world examples.

On successful completion of this course, you should be able to:

1. select sources of biomedical data appropriate for a given research question.
2. determine the most suitable methods to use to analyse these data.
3. implement and critically evaluate advanced Python code for biomedical data projects using reproducible research practices.