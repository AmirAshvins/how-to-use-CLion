---
layout: default
title: Troubleshooting
nav_order: 8
---

# troubleshooting goes here
{: no-toc}

Use this section to solve any issues.

| Cannot Connect to git<br>                                | The login information may be<br>incorrect<br>                  | Check that the provided login information is accurate                                                                                                                                     |
|----------------------------------------------------------|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                          | Network issues                                                 | Run your OS network diagnostics tool                                                                                                                                                      |
| When I open CLion,<br>I cannot see the project I created | The project has been removed<br>from your active project list  | In the “Starting window” Click open, <br>the “Mac open dialog window” will appear. <br>Find the folder containing your project and click open.                                            |
|                                                          | The project has been deleted                                   | If the project was uploaded to Github, download it and<br>open the project folder with CLion <br>from the [starting window]                                                               |
|                                                          |                                                                | Try recovering the project from the Trash                                                                                                                                                 |
| Cannot see text after changing color                     | The background color may be<br>the same as the text color      | Redo the change color scheme procedure and<br>ensure the background color is not<br>the same as the text color                                                                            |
| Cannot run the new executable<br>I just added            | The path specified in the<br>CMakeList.txt is incorrect        | Assert that the entered file path is correct                                                                                                                                              |
|                                                          | The source file <br>has no main function                       | Create a main function in the<br>source file                                                                                                                                              |
|                                                          | CMakeList.txt was not reloaded                                 | Open the CMakeList.txt file and assert that<br>the "Reload changes" ribbon is not present<br>when CMakeFile.txt is open. <br>(See procedure “Add a new executable <br>to project” step 7) |
|                                                          | Text casing in the CMakeList.txt<br>may be incorrect           | Assert that the casing of the text in <br>the CMakeList.txt file is correct                                                                                                               |