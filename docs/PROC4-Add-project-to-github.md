---
layout: default
title: Share project to github
nav_order: 5
---

# Share project to github
{: no-toc}

In this procedure, we will share a project ,in CLion, on GitHub cloud. It is imperative for software developers and programmers to know how to do this since it enables collaborators to import our code into thier machines and to work on it on the project. After this procedure, you have shared your project on github, and you would be able to see it on your github reposetory.

## Prerequisites: 

Before proceeding with this procedure, make sure you have done the following:

* you have created a project on CLion. If you have not, please create one or check out [how to create a projet guide](https://amirashvins.github.io/how-to-use-CLion/docs/PROC1-Create-a-new-project/).
* you have linked your GitHub account to CLiom. if your have not, please go ahead and do it or check out [how to set up github account guide](https://amirashvins.github.io/how-to-use-CLion/docs/PROC3-Setup-github/).

## Instructions:

1. Open CLion application.
2. Click on your desired project in the right pane of starting window.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image1.png?raw=true "alt text here")
2. In the \[Mac Menue Bar] on the top, click **VSC**.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image2.png?raw=true "alt text here" )
3. In the appeared menu, hover over **Import into Version Control > Create Git Repository…**. 

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image3.png?raw=true)
4. Choose your intended directory path to create the Git repository in \[Open Dialog Window] and click **OK**.
  
  ★ We recommend accepting the path already chosen for you by CLion, as most of the time it picks the most appropriate path
  {.label, .label-blue}
  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image5.png?raw=true "alt text here")
  \* After this step, your files' color will turn into red to show that it git reposetory has been created on your machine.
  {.label, .label-green}
5. Click **VSC > Import into Version Control > Share Project on GitHub**.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image6.png?raw=true "alt text here")
6. Type your new online reposetory name in **Reposetory name** box and add an optioanl description in **Description** box.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image7.png?raw=true "alt text here")
Optional: to make your project private, check the **private** check-box and click **Share**.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image8.png?raw=true "alt text here")
7. In the \[Add files for initial commit window], check the files that you want to add to your online reposetory and click **Add**.

  ★ We recommend not checking the **.idea** folder and **.gitignore** file to make your project cross-platform.
  {.label, .label-blue}
  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image9.png?raw=true "alt text here")

Check success: After last step, you should see a message from CLion indicating that the project has been successfully shared on GitHub and the color of files changed from red to white.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc4-image10.png?raw=true "alt text here")
