# StatTheoryLabs   
learnr tutorials and labs for a mathematical statistics course
These labs were originally adapted from labs by [Dr. Sara Stoudt](https://sastoudt.github.io/). 
This repo was forked from her [original one](https://github.com/sastoudt/StatTheoryLabs). Minor implementation edits for Spring 2023 by Sanogo.

### To install this package:

1. One time only (may need to reinstall for updates throughout the semester):

`remove.packages("learnr") ## might not need this if you do not have learnr pre-installed`

`install.packages("remotes")`

`remotes::install_github("rstudio/learnr")`

`remotes::install_github("rstudio-education/gradethis")`

`remotes::install_github("rundel/learnrhash")`

`remotes::install_github("fatsanogo/StatTheoryLabs", build_vignettes = T)`


2. Thanks to Marney for this one: after install is complete (I know this seems weird, but go with it):

```remove.packages("htmltools")```

```install.packages("htmltools")```

Exit RStudio and then open it again.

#### Troubleshooting

- These packages have more recent versions available. Which would you like to update? --> If the list only includes `htmltools` say No.

- Do you want to install from sources the package which needs compilation? (in reference to `dplyr 1.0.3` instead of `dplyr 1.0.4`) --> No 

### Launch a lesson:

1. In the console (bottom left) type: `learnr::run_tutorial("ct-1", "StatTheoryLabs")`

### Stop a lesson 

1. Click stop sign on the left.

![](stop-tutorial.png)

#### Troubleshooting

- If you get some kind of error having to do with "parse" when you try to run a tutorial:
![](restartR.png) 

Click "Session" --> "Restart R" and try to run the tutorial again. 

![](restartR2.png) 

- The tutorial will often pop up in a new browser tab automatically. If you have a popup blocker, you might need to turn it off or update the settings.

![](popups.png) 

## Available Vignettes

- "code-training-1": intro to RStudio

## Available Tutorials

- "first-day": first day activity to guess the color
- "ct-1": code training 1 - intro to interactive tutorials
- "ct-2": code training 2 - structures and subsetting
- "ct-3": code training 3 - loops
- "ct-4": code training 4 - plots and probability distributions
- "ct-9": code training 9 - plot expectation sketching
- "lab1": Estimation (capture-recapture)
- "sampling-practice": extra sampling, bootstrap, and permutation distribution practice

## Available Templates

- "lab0": reproducibility and documentation
- "lab1": estimation (capture-recapture)
- "lab2": sampling distributions
- "lab3": bootstrap
- "lab4": confidence intervals
- "lab5": hypothesis testing
- "code-training-5": Functions and Simulating Data
- "code-training-6": Functions and Simulating Power
- "code-training-7": Simulation Scenarios and Preliminary Plots
- "code-training-8": Tidy Data and Better Plots
- "intro-np": introduction to nonparametrics
- "intro-project": introduction to final project
- "hw7": optimization for bivariate MLE

(under development and updating for Spring 2022)

## How to Submit Google Form portion of Lab

Note: your Google form might look a little different, but the instructions stay the same.

![](submit-tutorial.png)

#### Troubleshooting

I can't see the Google Form at the end. 

Open in the browser (this should happen automatically if you use `run_tutorial` ), use Google Chrome, and make sure you are logged in to your Bucknell e-mail in the same browser (only Bucknell authenticated accounts can access the form to avoid any spam).

**Run into any problems not listed above? Let me know and when we figure it out we'll add to the list.**

