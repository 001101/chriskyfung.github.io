---
layout: post
title: "Working MATLAB with MS Excel"
author: Chris KY Fung
date: 2015-03-10
category: Data-Science
tags: [MATLAB, MS Excel]
header:
  teaser: /images/posts/matlab/excel_addin_menu.png
permalink: /blog/matlab/Working-MATLAB-with-MS-Excel
redirect_from:
 - /blog/2015/03/10/Working-MATLAB-with-MS-Excel
---

This is a tutorial to show the installation of **Spreadsheet Link EX for use with MATLAB and Excel**.

<!--more-->

### Procedures

1. First, make sure you can find the `excllink.xlam` file under your MATLAB program directory `\matlabroot\toolbox\exlink\`.

2. Click Open. In the Add-Ins dialog box, the Spreadsheet Link EX for use with MATLAB and Excel checkbox is selected.

![image: MS Excel Add-in Dialog](/images/posts/matlab/excel_addins_available.png)
 

The **Spreadsheet Link EX Add-In** loads now and with each subsequent Excel session. The MATLAB group appears on the top right of the Home tab in your Excel worksheet. Open the Menu and click **Start MATLAB**.

![image: Menu of MATLAB Spreadsheet Link EX Add-In in Excel Toolbar](/images/posts/matlab/excel_addin_menu.png)


The **MATLAB Command Window** button appears on the Microsoft Windows taskbar. Spreadsheet Link EX is ready for use.

![image: Windows taskbar with MS Excel and MATLAB](/images/posts/matlab/ml_cmd_window_taskbar.excel2010.png)
 

Now, you can see a list of the MATLAB options in the context menu when you right-click a cell in Excel.

![image: context menu of MATLAB Spreadsheet Link EX Add-In](/images/posts/matlab/excel_addin_menu_right_click.png)

**Related post:**
- [Matrix Conversion between MATLAB and Microsoft Equation Editor](/blog/matlab/Convert-MATLAB-Matrix-to-MS-Office-Equation)