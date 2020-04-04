---
layout: default
title: Add a new executable to project
nav_order: 3
---

# Add a new executable to project

In this procedure we will create a new executable file in your project. To be able to have more than one executable file in a project, it is necessary to complete this procedure. After completion, the new executable file should be able to be run by CLion.

## Pre-requisites

Before starting this procedure, you must have an existing project. If you do not, please [create a new project](https://amirashvins.github.io/how-to-use-CLion/docs/PROC1-Create-a-new-project/).

## Instructions

1. Open CLion.

    You should now be in the [starting window].

2. Click on your **project** to open it.

    ![starting-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image0.png?raw=true "Starting window")

    You should be now in the [main window].

3. Right-click the project's directory.

    ![right-click-on-project-directory](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image1.png?raw=true "Right click on project directory")

4. Hover across **New > C/C++ Source File**.

    ![right-click-on-project-directory](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image2.png?raw=true "Right click on project directory")

5. Enter the name of your new file in the **Name** box.

    ![new-source-file-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image3.png?raw=true "New source file window")

6. Click the desired type of file from the **Type** drop down menu, then click **Ok**.

    \* We will use a **.c** file (C source file) for demonstration purposes, but CLion also supports .cpp files (for C++ source files)
    {: .label .label-green}
    ![new-source-file-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image4.png?raw=true "New source file window")

7. Double-click **CMakeLists.txt** to open it.

    ![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image5.png?raw=true "Main window - Emphasis on project panel")

    The source code should now appear in the code pane of the [main window].

8. Type "add_executable()" in a new line.

    ![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image6.png?raw=true "Main window - Emphasis on code panel")

9. Inside the parenthesis, type:

    1. the name of your app followed by a space,
    2. the relative path to your executable file from the "CMakeList.txt".

    ![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image7.png?raw=true "Main window - Emphasis on code panel")

10. Click **Reload changes**.

    ![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image8.png?raw=true "Main window - Emphasis on code panel")

✓ Check for success: After this stage you should be able to find the new executable in the executables list.
{: .label .label-lime-green}

![main-window](https://github.com/AmirAshvins/how-to-use-CLion/blob/gh-pages/assets/images/proc2-image100.png?raw=true "Main window - Emphasis on executables list")
