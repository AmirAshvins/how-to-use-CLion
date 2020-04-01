---
layout: default
title: Add a new executable to project
nav_order: 3
---

# Add a new executable to project
{: no-toc}


In this procedure we will create a new executbale file in your project so that the file could be ran by its own without the need for a "main.c" file.

## Prerequisites:

before proceeding with this procedure, make sure you do have an existing project in your CLion. If you do not, please create a new project or check out [create a new project guide](https://amirashvins.github.io/how-to-use-CLion/docs/PROC1-Create-a-new-project/).

★ RECOMMENDATION LABEL
{: .label .label-blue }

⚠ WARNING LABEL 
{: .label .label-yellow }


1. Open CLion application.
2. In the left pane in the starting window, open your project by clicking on it.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image0.png?raw=true "alt text here") 
  
3. In the right pane of the project's window, right-click on the project's directory.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image1.png?raw=true "alt text here") 
  
4. In contextual menu, hover over **New > C/C++ Source File**.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image2.png?raw=true "alt text here")
  
5. In the new source file window, enter the name of your new file in the **Name** box.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image3.png?raw=true "alt text here")
  
6. from the **Type** drop down menu, choose the type of the file and click **Ok**.

  \* Note: 
  {: .label .label-green}
    In this guide we will use a **.c** file (C source file) for demonstration purposes, but CLion also supports .cpp files (for c++ source files) 
  
  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image4.png?raw=true "alt text here") 
  
7. In the left pane in the project's window click on **CMakeLists.txt** file to open it.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image5.png?raw=true "alt text here")
  
8. In the right pane of the file, after the last **add_executable()**, type **add_executable()** in a new line.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image6.png?raw=true "alt text here") 
  
9. Inside the parenthesis, you need to add the two appropriate statements with a space inbetween them.

  ★ Recommendation:
  {: .label .label-blue} 
    The first statement that goes in the paranthesis is the name of the new file that will be used by the C compiler. It is best to simply use the name of the source file.
  
  ★ Recommendation:
  {: .label .label-blue}
    The second statemtn that goes in the paranthesis is the relative path of the source file that is created. if the file is created in the root level of the project (as demonstrated in the previous steps) simply use the file's name.
  
  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image7.png?raw=true "alt text here") 
  
10. To save the changes we have made, click **Reload changes**, located on the top right corner of the right pane.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image8.png?raw=true "alt text here")

Check for success: After this stage you should be able to run your code inside your newly created file.

