---
layout: tabbed-assignment
---

# Instructions

{% include time-estimate.html %}

1. Start your notes. Make an entry in your notebook with:
    - Today's date
    - What you're working on, perhaps **Getting started on Prototype 2.**
1. In your browser, go to [Prototype 2: Lesson 1: Player Positioning][lesson].

   For this assignment, we'll be working through the first video to set up the project in Unity. We'll also create a new repostitory on GitHub to hold the code and track your changes. The instructions for creating the Git repository and pushing it to GitHub are in the [slides][].
   
1. Follow the instructions in the video to create a new Unity project for Prototype 2 - before importing the project assets, create a Git repository for your work and publish it on GitHub. 
1. Work through the steps in the slides to create a Git repository for Prototype 2 and then push it to GitHub. There are a couple of critical things to keep in mind: <img src="assets/images/GitHub Desktop Create New Repository.png" align="right" width="40%">

    - **The project name you set in Unity Hub will also be the name of the repository in GitHub. GitHub does not allow spaces in repository names.** So, use dashes (-) in place of spaces when you give the project its name (i.e., call it Prototype-2 **not Prototype 2**.
    - GitHub Desktop will initialize a Git repository in an existing folder - even though the label on the button is "Create New Repository…" To make this work, you **must** make sure the path given to GitHub Desktop points to the folder you created in Unity Hub. In GitHub Desktop the path is built from two parts:
        
        - The *repository name* in the **Name** field - e.g., **Prototype-2**.
        - The path to the folder holding your Prototype-2 project in the **Local Path** field. One way to get the path is to use the **Choose** button and navigate to the folder holding your **Prototype-2** folder.

<p>
<details>
<summary>Launch GitHub Desktop and make sure that your local copy of the {{site.data.assignment.starter-code-repo}} repository is up to date.</summary>

- Make sure that your **{{site.data.assignment.starter-code-repo}}** repository is selected.
- Do a **fetch** to make sure your local copy of the code is up to date, if you have done work on the GitHub site or at home between classes you will be prompted to do a **pull** to incorporate your changes.
- Make sure that you are on the **{{site.data.assignment.get-prev-branch}}** branch.

</details>

<p><details><summary>Create and publish a {{site.data.assignment.git-curr-branch}} branch.</summary>

</details>

<p><details><summary>Go to the <a href="{{site.data.assignment.lesson}}">lesson</a> and get ready to take notes.</summary>

- Get headphones if you need them.
- Start a page for this lesson in your notebook with a title and date.
- Review the learning targets to see what you should be focusing on.

</details></p>

<p><details><summary>Watch each video, taking notes on the new material.</summary>

- Vocabulary
- The Unity user interface
- Implementing game mechanics.
    
</details>

<p><details><summary>After watching each video, do the steps in Unity.</summary>

If necessary refer to your notes (update them if you find yourself stuck). You can use the abreviated steps below each video for cues on what to do.

</details>

<p><details><summary>Submit your work.</summary>

When you're done for the day, go to the submission tab, check the instructions, and submit.

</details>

<!-- Don't edit links here, change them in _data/assignment.yml instead. -->

{% if site.data.assignment.lesson   %}[lesson]: <{{site.data.assignment.lesson}}>     {% endif %}
{% if site.data.assignment.slides   %}[slides]:   <{{site.data.assignment.slides}}>   {% endif %}
{% if site.data.assignment.template %}[template]: <{{site.data.assignment.template}}> {% endif %}
