---
layout: default
title: Add a new executable to project
nav_order: 3
---

# Add a new executable to project
{: no-toc}

In this procedure we will create a new executable file in your project. After completion, the new executable file should be able to be run by CLion.

## Prerequisites

Before starting with this procedure, you must have an existing project. If you do not, please [create a new project](https://amirashvins.github.io/how-to-use-CLion/docs/PROC1-Create-a-new-project/).

1. Open CLion.
2. Open your project by clicking on it in the projects pane in the [starting window].
   You should be now in the [main window].

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image0.png?raw=true "alt text here")
  
3. Right-click on the project's directory.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image1.png?raw=true "alt text here")
  
4. Hover over **New > C/C++ Source File** in contextual menu.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image2.png?raw=true "alt text here")
  
5. Enter the name of your new file in the **Name** box in the [new source file window].

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image3.png?raw=true "alt text here")
  
6. Choose the desired type of file and click **Ok** from the **Type** drop down menu.

  \* In this guide we will use a **.c** file (C source file) for demonstration purposes, but CLion also supports .cpp files (for C++ source files)
  {: .label .label-green}

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image4.png?raw=true "alt text here")
  
7. In the project pane in the [main window] double-click **CMakeLists.txt** to open it. The source code should now appear in the code pane of the [main window].

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image5.png?raw=true "alt text here")
  
8. In the code pane of the [main window], after the last **add_executable()**, type **add_executable()** in a new line.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image6.png?raw=true "alt text")

9. Inside the parenthesis, you need to add
    1. the name of your app followed by a space,
    2. the relative path to your executable file from the "CMakeList.txt".
  
  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image7.png?raw=true "alt text here")
10. To save the changes we have made, click **Reload changes**, located on the top right corner of the right pane.

  ![image-name](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image8.png?raw=true "alt text here")

Check for success: After this stage you should be able to run your code inside your newly created file.
