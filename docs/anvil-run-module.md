
## Running a module on AnVIL 
<!-- change fig.align quotes from single to double -->
![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3709d9ac459_0_250.png){width=100%}

#### Purpose

In this section we will go over how to run C-MOOR modules on AnVIL. We will go over how to create an RStudio environment in that workspace to run the module and properly end a session on AnVIL to prevent runaway costs.

#### Learning Objectives

1. Launch a module through the cloned workspace
1. Close out a session on AnVIL properly to prevent runaway costs

### What is a workspace?

The workspace is the heart of AnVIL. Here are some key points about workspaces:

- Every workspace comes with its own Google Bucket (our cloud storage). Your bucket will be empty.
- Every workspace has its own billing project. Students who are not yet associated with a billing project will not be able to compute on their workspace.
- We can control access levels of users and set them either as owners, writers, or readers. Students will be writers with compute access.

### Running modules on AnVIL

#### Starting a module on AnVIL

When you open the workspace, you will be on the dashboard tab by default. The dashboard contains the instructions on how to use the workspace, links to C-MOOR websites, and the startup script. Let’s try running a module.

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3e8341b93fe_0_0.png){width=100%}

1.  Copy the URL of the startup script. Make sure there are no spaces before or after what you copy. This script is held in the original workspace everyone cloned. You will need to input this URL soon.

2. Click on the Environment Configuration button, the cloud with a thunderbolt.

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3e8341b93fe_0_13.png){width=100%}

3. In the RStudio section, click Settings

4. In the startup script field, paste the URL for the startup script. 

5. Select 4 CPUs and 15 gigabytes of memory.

6. Confirm that the cloud compute cost is 20 cents per hour. If it is not 20 cents per hour, reselect CPUs and memory allocation in step 5 This is a known bug in AnVIL at the writing of this guide.

7. Scroll to the bottom of the window and click “Create”. It will take about 2 minutes for the environment to be created.

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3709d9ac459_0_279.png){width=100%}

It will take some time for the RStudio Environment to be created. You can keep track of the status of the environment based on the colored dot next to the RStudio icon. The dot will turn green when the environment is ready. While it is loading (blue), you cannot interact with it.

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3e8341b93fe_0_29.png){width=100%}

8. When the environment is ready, use the Open RStudio button that will pop up. If you hold down Ctrl as you click, you can open RStudio in a new window.

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3e8341b93fe_0_33.png){width=100%}

9. Use the file explorer in RStudio to navigate to your module of choice. First, enter the folder of the curriculum you are using, either rnaseq (not cure-rnaseq) or 16s. Then enter the folder of the module you want to run. 

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3e8341b93fe_0_36.png){width=100%}

10. In the module’s directory, open the .Rmd file by double clicking its name.

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3e8341b93fe_0_39.png){width=100%}

11. Click Run Document in the open .Rmd file

<mark>**When you are finished, make sure you close out your session properly to prevent runaway costs!**</mark>. 

### Closing out a session on AnVIL

![](anvil-run-module_files/figure-docx//11wb3b7i9SwrDX_WO3mWNAycd2mbY4Moy8SuT0X3XvXo_g3709d9ac459_0_299.png){width=100%}

1. On the right side of the screen, click the Cloud Environment button. This is the Cloud with the lightning symbol.
1. Under the RStudio section, click settings.
1. Scroll to the bottom of the new window and click delete environment.
1. Check <mark>**Delete everything, including the persistent disk or your instructor's billing account will incur costs for storage**</mark>. 


