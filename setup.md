---
title: Setup
---

## Pre-workshop setup steps

1. Install the following software (<a href="#install">all instructions are below</a>).
    - [R](https://www.r-project.org/)
    - [RStudio](https://rstudio.com/), an integrated development environment for R
    - `tidyverse` package, a collection of functions we'll use throughout the workshop
https://github.com/gus-pendleton/SLR_Summit_2026/raw/refs/heads/main/files/ontario-report.zip
1. After you have installed everything above, download [nerr_data.zip](https://github.com/gus-pendleton/SLR_Summit_2026/raw/refs/heads/main/files/nerr_data.zip). You'll need the files included during the workshop.
    1. Move `nerr_data.zip` to your Desktop and unzip it (double-clicking on Macs; right-click and "Extract All" on Windows).
        -  Note: In Windows, by default files will be unzipped into a folder called "nerr_data" within _another_ folder called "nerr_data". To prevent this, when asked where to extract, remove the "nerr_data" that shows up after Desktop, so that the file path looks something like "C\Users\your.username\Desktop". Alternatively, you can copy the files in the "inside" nerr_data folder to the "outside" nerr_data folder and then safely delete that empty folder.
    1. Start up **RStudio**. In the upper left menu, select `File` > `Open`. In the window that opens, go to the `nerr_data/` folder on your Desktop and select the file `check_setup.R` to open it in RStudio.
    1. Click the **`Source`** button to run the script. This script will make sure that everything is installed and setup correctly. You should see output printed to the console window (usually the lower left pane in RStudio).
    1. Take a screenshot of the console output (or copy & paste it) into an email and send it to the lead instructor.

If at any point you get stuck or run into problems, please don't hesitate to ask us for help!

<h2 id="install">Software Installation Instructions</h2>

{% include swc/setup.html %}
