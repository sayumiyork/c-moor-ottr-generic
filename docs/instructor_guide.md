
# (PART\*) Instructor guide {-}

# For first-time instructors

## Introduction

## To-dos
Set up on a cloud platform
Go through the modules
Make a post on our forum
Consider your schedule
Edit a rubric
Have students create an account on your chosen cloud platform and get them connected

## Setup your AnVIL account

#### Purpose

Students will create an AnVIL account and be added to a billing project by their instructor, which allows them to compute (run code) on AnVIL. They will then clone a workspace specific to their research project; **the steps in this section only need to be completed once.**

#### Learning Objectives

1. Create an account on AnVIL
1. Share your email address with your instructor
1. Clone the workspace for your specific research project

### Create an AnVIL account

1. Open [anvil.terra.bio](https://anvil.terra.bio/) in <mark> **Google Chrome** </mark>. Google Chrome is the only officially supported web browser for AnIVL.
    a. It is a good idea to bookmark this page so that you can easily access it throughout the course.
1. Click the hamburger icon (3 horizontal lines) in the top left corner of the screen 
1. Click "Sign in"
1. Click "Sign in with Google".
1. Sign in with a <mark>**Google associated email address**</mark> such as an institutional email that uses Gmail or a personal Gmail account. You must use a Google associated email address to gain access to Google Cloud computing resources. 
1. Follow all steps required to complete creating an account (ex. email verification of account)
1. Share the email you used to sign up for AnVIL with your instructor.

**Your instructor will add you to a billing project that will allow you to use computational resources on AnVIL. Until they do so, you will not be able to compute anything.** 

### Clone a workspace on AnVIL

1. While logged into AnVIL, using the hamburger icon in the top left corner of the screen, navigate to the workspaces page
1. Select the public tab
1. Search for the desired workspace. Your instructor will tell you which workspace to look for (miniCURE-RNA-seq or miniCURE-16S-Human_Gut).
1. Click on the more options icon on the right side of the desired workspace and click clone
1. Give the cloned workspace a unique name, such as by adding your initials or last name. All workspaces must have unique names; if someone has already taken the workspace name you initially wanted, please try a different name.
1. Confirm the billing project is the one your instructor has chosen.
1. The rest of the options should be left as is. Clone the workspace. It may take a few minutes to clone.

<mark>**You only have to clone the workspace once. From now on, use your cloned workspace.**</mark> After you clone the workspace you will automatically be directed to it. For all other times, your workspaces can be found using the hamburger icon in the top left.

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_18.png){width=100%}


## Running modules on AnVIL

#### Purpose

The purpose of this assignment is to learn how to access the modules for your course on AnVIL and properly close out your session when finished.

#### Learning Objectives

1. Start up a module on AnVIL using the RStudio environment
1. Delete your RStudio environment when finished

### Starting a module on AnVIL

When you open the workspace, you will be on the dashboard tab by default. The dashboard contains the instructions on how to use the workspace, links to C-MOOR websites, and the startup script.

1. <mark>**Copy the startup script**</mark>. Make sure there are no spaces before or after what you copy. This script is held in the original workspace everyone cloned. It does not have to be in your own workspace for it to work.
2. Click on the Environment Configuration button (cloud with thunderbolt)

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_87.png){width=100%}

3. In the RStudio section, click Settings
4. In application configuration, select Legacy RStudio (R 4.4.1, Bioconductor 3.19, Python 3.10.12). 
5. In the <mark>**startup script field, paste the startup script**</mark>
6. Scroll to the bottom of the window and click “Create”. 

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_91.png){width=100%}

It will take some time for the RStudio Environment to be created. You can keep track of the status of the environment based on the colored dot next to the RStudio icon. The dot will turn green when the environment is ready. While it is loading (blue), you cannot interact with it.

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_95.png){width=100%}

7. When the environment is ready, use the Open RStudio button that will pop up. You can also access RStudio through the Analyses tab. If you hold down Ctrl as you click, you can open RStudio in a new window.

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_99.png){width=100%}

8. Use the file explorer in RStudio to navigate to your module of choice. From the folder called cure-rnaseq, go to tutorials, and then the folder of the module you want.

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_103.png){width=100%}

9. In the module’s directory, open the .Rmd file by double clicking its name.

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_107.png){width=100%}

10. Click Run Document in the open .Rmd file

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_111.png){width=100%}

<mark>**When you are finished, make sure you close out your session properly to prevent runaway costs!**</mark>. 

### Closing out a session on AnVIL

1. On the right side of the screen, click the Cloud Environment button. This is the Cloud with the lighting symbol.
1. Under the RStudio section, click settings.
1. Scroll to the bottom of the new window and click delete environment.
1. Check <mark>**Delete everything, including the persistent disk or your instructor's billing account will incur costs for storage**</mark>. 

![](instructor_guide_files/figure-docx//1dI8-_iVqbkzNMf11M4dK85E8ZW3OyZECs_YwMKw5fhs_g3632cdae791_0_180.png){width=100%}

#### Footnotes

#### Contributions and Affiliations

- Sayumi York, Notre Dame University of Maryland

Last Revised: July 16, 2025
