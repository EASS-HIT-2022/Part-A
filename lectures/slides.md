---
header-includes:
  - \usepackage{upgreek}
  - \usepackage{txfonts}
  - \usepackage{mathtools}
  - \usepackage{braket}
  - \usepackage{amsmath}
  - \usepackage{multicol}
  - \usepackage{xcolor}
  - \usepackage{gensymb}
  - \usepackage[utf8]{inputenc}

fontsize: 8pt
interlinespace: 4ex
whitespace: small
title: Engineering of Advanced Software Solutions (EASS)
author: Yossi Eliaz
subtitle: HIT, Israel
date: "2022"
---


# EASS 2022 - Lecture 1
:::::::::::::: {.columns}
::: {.column width="50%"}
- Admin
- Technical debt
- Business logic
- Bash and commandline (based on MIT's missing semester)
- Git, GitHub
- Interactive class

:::
::: {.column width="50%"}
<!-- ![](static\\review.png){ height=400px } -->
![](static\eass_logo.PNG){ width=50px }
:::
::::::::::::::

# Admin stuff
:::::::::::::: {.columns}
::: {.column width="50%"}
- Discord
- Github account
- HW on Github
- Creating a Canvas account (https://canvas.instructure.com/)
- AWS on Cavnvas
- LinkedIn
- Commandline (WSL)
- Docker
- Moodle (minimal interaction over there)
- Volunteer to summarize the lectures
- Stackoverflow
- Engagment on Discord
- Hackernews

:::
::: {.column width="50%"}

:::
::::::::::::::

###### References:
*Missing Semester MIT*

*AWS cloud certificate*


# What is Technical Debt?
- "In software development, there is always a constant need to balance speed and quality. Some quality will always have to be sacrificed to release features within a reasonable timeframe, so any of these shortcuts will often be tasked as future projects. Those unattended tasks become what is called technical debt."

- "There are several reasons why technical debt happens. Product owners may focus more on the need to implement and release new features and less on fixing past problems or create a generic enough infrastructure to support future developments. In some severe cases, product owners completely underestimate the outcomes of dealing with poor infrastructure, bugs and poorly designed software."

- "Ultimately, technical debt can sometimes lead to software users having bad experiences and thereby increasing user churn rates. Together, a lack of developer awareness and task ownership can lead to more technical debt."


###### References:
https://logz.io/blog/technical-debt/



# Business logic

:::::::::::::: {.columns}
::: {.column width="40%"}

- "**Business rules** are what your non-software developers tell you what your software needs to do."


- "**Business logic** is the part of your code that specifically implements business rules."

:::
::: {.column width="60%"}
![](http://www.ritholtz.com/blog/wp-content/uploads/2013/07/2011.06.27_organizational_charts.png){ height=200px }
:::
::::::::::::::



###### References:
https://softwareengineering.stackexchange.com/questions/234251/what-really-is-the-business-logic

http://www.ritholtz.com



# Intro to commandline and tools (interactive)
:::::::::::::: {.columns}
::: {.column width="50%"}
- Vim
- Bash
- Git
- Docker

:::
::: {.column width="50%"}

:::
::::::::::::::

# Bash
- `echo`, `while`, `find`, `vars`, `printenv`, `htop`, shebang, wild cards
- `cp`, `touch`, `mkdir`, `ls`, `uniq`, `awk`, `rm`
- `man man`
- brew
- `wget`
- `curl`

###### References:
https://missing.csail.mit.edu/2020/shell-tools/


# Sneak peek to docker
- `docker run`
- `docker ps`
- `docker run -ti`


# Stackoverflow good questions usually have
1. Problem statement
2. Sample code and data
3. Spelling, grammar and formatting

Example:

https://stackoverflow.com/questions/11227809/why-is-processing-a-sorted-array-faster-than-processing-an-unsorted-array

###### References:
https://codeblog.jonskeet.uk/2010/08/29/writing-the-perfect-question/

https://stackoverflow.com/help/how-to-ask


# First task

- Checkout github classroom and the first task about git and github
https://classroom.github.com/classrooms/99552739-eass-hit-2022-part-a



# Good luck to all of us

:::::::::::::: {.columns}
::: {.column width="50%"}
![](static\eass_logo.PNG){ width=150px }

:::
::: {.column width="50%"}
Be active on EASS discord and try to learn and help each other as much as you can.
:::
::::::::::::::

