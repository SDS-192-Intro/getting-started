# Getting Started

> I'm going to start off by saying that I dread this day every time I teach R in a course. Students have different computers, sometimes have older versions of software installed on them, and different levels of experience setting up coding environments. I'll also admit that as a former CS undergrad, for me, the absolute hugest barrier to getting started on any project was getting my coding environment set up. We **are** going to run into frustrations today; it's inevitable. I'm going to do whatever I can to support you through them, which is why I'm carving out class time to do it. I don't expect to get every issue we run into to be sorted out by the end of class or even by class on Monday. I'm telling you this because I don't want you to worry if you run into roadblocks in setting up in your environment. *We will get through them.*

> On the other hand, some of you might breeze through this, having certain components already set up or having previous experience configuring GitHub. While not required, if you finish early and would be willing to help me troubleshoot other issues that come up, it would certainly be appreciated. Feel free to meet me back in the main meeting room when you're done if so. 

Below are instructions for setting up our course environment. It's important that you follow them in order and do exactly as is described in the videos. Today, you will be in break-out rooms, but feel free to work independently. If you have any questions, first ask the other students in your breakout room. I ask that you take this step as I will be managing about 20 different rooms at once. If you can't answer the question this way, call me into the breakout room. 

**Don't worry if you don't know what certain terms mean at this point. We will be going over things like the difference between R and RStudio, what a package is, what it means to commit code, and what a markdown file is a little later in the semester.** I just believe it will be easier to follow along with me in learning those things if you can follow along on your own computers. That's why we're taking this step to get things up and running so earlier in the semester. 

1. Follow the instructions in [chapter 4](https://happygitwithr.com/github-acct.html) of Happy Git and GitHub for the useR to create a GitHub account. 
2. Follow [these instructions](https://rstudio-education.github.io/hopr/starting.html) to download and install R and RStudio. Be sure to install R first and RStudio second. 
3. Open RStudio.
4. Follow instructions in this video to ensure git is installed: 

<p><a href="https://vimeo.com/511798611">Verify Git Installation</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

5. If git is not installed, leave your break-out room and come talk to me. 
6. Edit your git config by following these instructions: 

<p><a href="https://vimeo.com/511798861">Edit gitconfig file</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

7. Create a personal access token by following these instructions: 

<p><a href="https://vimeo.com/511801645">Create a Personal Access Token (PAT) on GitHub</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

8. Store your personal access token by following these instructions: 

<p><a href="https://vimeo.com/511803103">Store Personal Access Token to Connect RStudio and GitHub</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

9. Open the [Getting Started Assignment URL]() listed in Moodle. This will copy a GitHub repo into your GitHub account. 
10. Copy the link to the GitHub Repo that was just created to your clipboard. It should look something like https://github.com/SDS-192-Intro/getting-started/YOUR-USER-NAME
11. Create a project in RStudio from this GitHub repo by following the instructions starting at 26 seconds of this video:

<p><a href="https://vimeo.com/511804881">How to Connect RStudio Projects with GitHub Repositories: GitHub First</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

12. Install the rmarkdown package in RStudio by entering the following lines of code in the Console Pane of RStudio (lower left hand corner on initial install).  

```
install.packages("rmarkdown")
library(rmarkdown)
```

![RStudio Panels](images/rstudio_panels.png)

13. On the initial install, the Files tab will be in the lower right hand corner of RStudio. Open the getting-started.Rmd file. Follow instructions in the file. 
14. When the file tells you to commit your code, follow the instructions in this video starting at 14 seconds: 

<p><a href="https://vimeo.com/511800674">Make a Commit and View More History</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

15. Push your code to GitHub.com by following the instructions in this video starting at 27 seconds:

<p><a href="https://vimeo.com/511805399">General Workflow: Push</a> from <a href="https://vimeo.com/user95475944">David Keyes</a> on <a href="https://vimeo.com">Vimeo</a>.</p>

