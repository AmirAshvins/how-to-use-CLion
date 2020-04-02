---
layout: default
title: Share project to github
nav_order: 5
---

# Share project to github

In this procedure, we will share a project from CLion to GitHub. To be able to collaborate with other developers, projects must be shared on a version control platform such as Github. After completion, the project will be accessible from Github.

## Pre-requisites

Before starting this procedure you need the following requirements:

* You have an existing project. If you do not, please [create a new project](https://amirashvins.github.io/how-to-use-CLion/docs/PROC1-Create-a-new-project/).
* Your Github account has been set up in CLion. If your have not, [set up github account](https://amirashvins.github.io/how-to-use-CLion/docs/PROC3-Setup-github/).

## Instructions

1. Open CLion application.

    You should now be in the [starting window].

2. Click on your desired project in the right pane of starting window.

    ![starting-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image1.png?raw=true "Starting window")

    You should be now in the [main window].

3. Click **VSC**.

    ![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image2.png?raw=true "Main window" )

4. Hover over **Import into Version Control > Create Git Repository…**.

    ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image3.png?raw=true)

5. Choose the intended directory path for the Git repository and click **OK**.
  
    ★ It is recommended to accept the default path.
    {.label, .label-blue}

    ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image5.png?raw=true "Starting window")

    After this step, your files' color will turn into red to show that it git repository has been created on your machine.

6. Click **VSC > Import into Version Control > Share Project on GitHub**.

    ![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image6.png?raw=true "Main window")

7. Enter the repository name and click **Share**.

    Optional: You may also type a description for the repository.

    ![share-project-dialogue](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image7.png?raw=true "Share project dialogue")

    ★ Make your project private by checking the **private** check-box.
    {.label, .label-blue}

    ![share-project-dialogue](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image8.png?raw=true "Share project dialogue")

    You should now be in the [Add Files For Initial Commit window].

8. Check the files that you want to add and click **Add**.

    ★ We recommend not checking the **.idea** folder and the **.gitignore** file as these are only useful to yourself.
    {: .label .label-blue}

    ![add-files-for-initial-commit-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image9.png?raw=true "Add Files For Initial Commit window")

✓ After last step, you should see a message from CLion indicating that the project has been successfully shared on GitHub and the color of files changed from red to white.
{: .label .label-lime-green}

![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image10.png?raw=true "Main window")
