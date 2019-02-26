---
layout: lesson
root: .  # Is the only page that don't follow the partner /:path/index.html
permalink: index.html  # Is the only page that don't follow the partner /:path/index.html
---

**Synopsis:** This series of lessons get running your computing Learn about the University of Sydney’s High Performance Computer (HPC) ‘Artemis’, including directory structure, software, and how to submit and monitor compute jobs using the PBS Pro scheduling software. Artemis is available at no cost to University of Sydney staff and students.

**Target audience:** Students and staff who would like to learn how to run compute jobs on Artemis HPC. Participants must have a valid USyd unikey.

> ## Prerequisites
> Competency on the Unix/Linux command line:
>
> * If you are interested in learning HPC but have no Unix/Linux command-line skills, you MUST first take an [Introduction to Unix/Linux](https://intersect.org.au/training/course/unix) course.
>
> **OWN LAPTOP REQUIRED**.
{: .prereq}

# Workshop Overview

| Lesson    | Overview |
| ------- | ---------- |
| [Introduction to Artemis HPC]({{ site.sih_pages }}/training.artemis.introhpc/) | Introduces USyd's High Performance Computer (HPC), ‘Artemis’. We cover connecting and navigating Artemis, available software, and how to submit and monitor jobs using the PBS Pro scheduler.|
| [Introduction to the Research Data Store and Data Transfer]({{ site.sih_pages }}/training.artemis.rds) |  Learn how to transfer data between your local computer, external sources, the University's Research Data Store (RDS) and Artemis HPC. |
|[Intermediate Artemis HPC (Automation)]({{ site.sih_pages }}/training.artemis.interhpc) | Learn how to automate multiple-run analyses with job arrays and do simple bash scripting on Artemis. The live training consists of two hours of instruction and practical exercises. |
|[Matlab on Artemis: The MDCS]({{ site.sih_pages }}/training.artemis.mdcs) | Artemis HPC hosts a Matlab Distributed Computing Server (MDCS) - this allows users to submit MATLAB jobs directly to Artemis from within their local Matlab instance on their machines. Come and learn how to use this service. |
|[Introduction to GPU computing with HPC]({{ site.sih_pages }}/training.artemis.gpu) | Introduces GPU computing, and running GPU jobs on Artemis and other HPC systmes. |

{% include links.md %}
