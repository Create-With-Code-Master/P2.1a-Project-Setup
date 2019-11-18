---
layout: tabbed-assignment
---

# Instructions

{% include time-estimate.html %}

1. Start your notes. Make an entry in your notebook with:
    - Today's date
    - What you're working on, perhaps **Getting started on Prototype 2.**
    - Then as you work through this assignment make an outline of the steps for setting up a Unity project and creating a Git repository for it on GitHub.
1. In your browser, go to [Prototype 2: Lesson 1: Player Positioning][lesson].

   For this assignment, we'll be working through the first video to set up the project in Unity. We'll also create a new repostitory on GitHub to hold the code and track your changes. The instructions for creating the Git repository and pushing it to GitHub are in the [slides][].
   
1. Follow the instructions in the video to create a new Unity project for Prototype 2 - before importing the project assets, create a Git repository for your work. 
1. Work through the steps in the slides to create a Git repository for Prototype 2 and then push it to GitHub. There are a couple of critical things to keep in mind: <img src="assets/images/GitHub Desktop Create New Repository.png" align="right" width="40%">

    - **The project name you set in Unity Hub will also be the name of the repository in GitHub. GitHub does not allow spaces in repository names.** So, use dashes (-) in place of spaces when you give the project its name (i.e., call it Prototype-2 **not Prototype 2**.
    - GitHub Desktop will initialize a Git repository in an existing folder - even though the label on the button is "Create New Repository…" To make this work, you **must** make sure the **Local Path** given to GitHub Desktop points to the folder holding the project you created in Unity Hub.

1. After importing your assets you will see a set of changes (about 30 files) in GitHub Desktop. If that is the case, all is good. If not, you probably used a **Local Path** in GitHub Desktop that included the name of the project (Prototype-2). To fix it delete the repository in GitHub Desktop and recreate it with the correct path. Now commit the changes and publish your repository.
1. Finally, create and publish a new {{site.data.assignment.git-curr-branch}} branch.

Go to the submission tab and submit the assignment.    

<!-- Don't edit links here, change them in _data/assignment.yml instead. -->

{% if site.data.assignment.lesson   %}[lesson]: <{{site.data.assignment.lesson}}>     {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template]: <{{site.data.assignment.template}}> {% endif %}
