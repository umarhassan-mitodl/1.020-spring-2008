---
content_type: page
description: "This section provides guidelines on using MATLAB\xAE and links to helpful\
  \ resources."
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 2a3b4b56-1a0f-6d27-0195-939c76d43a28
video_files:
  video_thumbnail_file: null
video_metadata:
  youtube_id: null
---

Using MATLAB®
-------------

To run MATLAB from a Windows PC:

MATLAB may be started from a shortcut or from the Windows Start button. This will bring up the MATLAB **command/desktop window** with the MATLAB prompt >>.

You can specify the path name that MATLAB uses to search for program or data files in the **current directory** text box near the top of the command window. You can also save a set of path names that are routinely searched by selecting the Set Path... and then Add Folder... from the File pulldown menu.

Entering MATLAB commands:

**Interactive mode** - Run individual MATLAB commands directly from the command window.

**Batch mode** - Run a series of commands (a **program**) all at once. These commands are stored in a text file identified with a .m suffix.

To create or modify program files for batch mode use the MATLAB **editor**. To start the MATLAB **editor window** from the main MATLAB window select New and then M-file from the File pulldown menu in the desktop window or enter the command edit from the command line. To edit an existing file select open and select the appropriate file or enter edit followed by the file name.

A batch mode MATLAB program can take the form of a **script** or a **function**:

A **script** runs much as if you were typing the program statements in the command window. In particular, the values of all variables are retained in memory and are accessible even after the program has run.

A **function** is similar, except that only designated variables are available outside the function.

You can run a script or function by typing the name of its file (without the .m suffix) in the MATLAB command window. For example, if your program is stored in the file myprogram.m then you run it by entering:

\>> myprogram

Depending on the display options you chose the results of the computations will be shown in the main MATLAB window, plotted in a separate **plot window**, or written to another file.

MATLAB Resources
----------------

Help within MATLAB:

Typing **helpdesk** at the MATLAB prompt will bring up the MATLAB Helpdesk. This is a Web page based version of the MATLAB documentation/manuals.

Typing **help \[command\]** at the MATLAB prompt will give you a brief explanation of **\[command\]**.

If you **don't** know what command you are confused about, typing **help** at the MATLAB prompt will give you a list of categories. Then typing **help \[category\]** will produce a list of commands in **\[category\]**. For example, one of the categories is **graphics**. Typing **help graphics** produces a list of the MATLAB graphics commands.

{{% resource_link "844ad1cf-b0be-4f81-8dfb-a0453ba6a4c3" "MathWorks Homepage" %}}: The makers of MATLAB. Information on acquiring MathWorks products plus links to documentation, etc.

{{% resource_link "d7a8d754-9989-4d35-87d8-e36872a2e9d9" "MathWorks Support" %}}: This is a useful site that has technical information, Web version of Helpdesk, and a downloadable user-library of scripts. Everything you ever dreamed of knowing about MATLAB, plus you can always email MathWorks.