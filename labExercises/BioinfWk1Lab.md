#Bioinformatics Week 1 Lab: Jan 15, 2015
##Introduction to GitHub and Markdown

Slides for the introduction to today's lab, as well as a PDF of this document, can be found on [Blackboard](http://blackboard.uttyler.edu).

###Learning Objectives
1. Conceptualize version control and collaborative research using the GitHub web interface
2. Submit your homework electronically through a GitHub repository
3. Format text using a simple computer language (markdown)
4. Apply information from basic software documentation to perform bioinformatics tasks

###Activities
* Create a GitHub account 
	* Navigate to [GitHub](https://github.com) in a web browser (Firefox preferred) and sign up for GitHub using your university email address. You may eventually use this account as a professional resource, so I recommend using an appropriate username. ["How to pick the right username"](http://www.reputation.com/reputationwatch/articles/how-pick-right-username) provides a few guidelines if you are unsure about what is appropriate. Please note that your full name will be displayed as a part of this repository. If you are concerned about privacy, you are not required to use your legal name (but please note this when filling out the "GitHub survey" Blackboard, described below in "Assessment.").
	* You may want to apply for a GitHub Student Developer Pack. This collection of developer tools is available to students for free, and includes an upgraded GitHub account that allows private repositories. 
		* Go to [the application page](https://education.github.com/pack/join) and confirm you are a student. 
		* For "How do you plan to use GitHub?" please write a few sentences indicating you are a student in bioinformatics and will be using GitHub to develop a collection of example code.
		* It may take a day or so for the request for student developer tools to be approved, so watch your email for the confirmation notice.

* Go through GitHub's introductory material
	* Navigate in a web browser to [GitHub Guides](https://guides.github.com)
	* Work through the instructions on the following guides. Your assessment for today's lab will include confirmation of completion of the tasks listed below. Keep in mind that links are highlighted in blue and may contain additional information if you have questions:
		* **Hello World:** :pencil2: When you are finished with this guide, you will have created a repo called `hello-world`, opened an issue, created a branch, made a commit, opened a pull request, and merged a pull request.
		* **Forking Projects:** As a part of this guide, you will need to install the desktop client on your computer, log in locally (click on the gear in the upper right corner of the client), and then clone the repo (click on the + in the upper left corner). When instructed to modify a text file, use the text editor Notepad++ from your desktop. When you are finished with this guide, you will have forked `Spoon-Knife`, cloned the repo to the desktop, made/pushed a change, and made a pull request.  
		* **Be Social:** When you are finished with this guide, you will have followed another GitHub user (k8hertweck and/or a classmate) and watched [the GitHub repo for this class' materials](https://github.com/BioinformaticsSpring2015/BioinformaticsMaterials). You may also want to star the repo for this class.
		* **Mastering Markdown:** You will use the information in this lesson to format your assessment (see below).
	* Take a look at the [GitHub Glossary](https://help.github.com/articles/github-glossary/). This will help with today's assessment and next week's lab.

* Practice forking a repository on your own.
	* Fork the [`ForkMe` repo](https://github.com/k8hertweck/ForkMe)
	* Go to settings and add your instructor (k8hertweck) as a collaborator
	* Go to the [GitHub help page](https://help.github.com) and find the article that describes how to rename a repository. :pencil2: Save this link (e.g., copy to a text document) to report in your assignment (see questions below).
	* :pencil2: Use the information in that article to rename your new branch of `ForkMe` in the format `LastnameBioinf` (e.g., `HertweckBioinf`).

* Prepare your private repository for homework submission.
	* You should have received an email notification that you have been added to a repository with the name format `LastnameHomework` where Lastname is your last name.
	* :pencil2: Modify the `README.md` file in this private homework repository to remind yourself that this is where you submit homework. Please do not remove or modify the rubric table.
	* :pencil2: Edit and commit changes to `homeworkTemplate.md` to reflect your name and GitHub repo URL (this can just be your GitHub username).
	* :pencil2: Copy the text formatting from `homeworkTemplate.md` (click on Raw, select all, copy). Create a new file with the name `LastnameWkX.md`, where Lastname is your last name and X is 1 (for week 1). Use this file to answer the questions in the assessment section below and save in your private homework repo. 

###Assessment
* Due Wednesday, Jan 21 at 5 pm
* Assessment criteria:
	* Technical content (45 points): tasks in GitHub (above), questions 6-7 (below)
	* Critical thinking (40 points): answers to questions 1-5 (below) 
	* Documentation (5 points): README.md in your homework repository, survey on Blackboard (listed below), citations for resources used in questions embedded in answers 
	* Professional behavior (10 points): class participation, assignment formatting using homework template
* :pencil2: Complete the "GitHub survey" in [Blackboard](http://blackboard.uttyler.edu)
* :pencil2: Written assessment: Title is "GitHub and Markdown." Answer the following questions:

1. In today's lesson, you created a branch for `hello-world`. You also forked `Spoon-Knife`. Why would you want to fork or branch a repository, and what is the difference between these commands in GitHub?
2. Look at the details for the commit you made to `Spoon-Knife`. Why does GitHub record timestamps for collaborative projects like this? Why might you care about what has been changed in a file?
3. Look at the change history for this document (`BioinfWk1Lab.md`). When was the last change made? What was that change?
4. Why is your homework repository private, and why is your instructor a collaborator?
5. Why are README files recommended for inclusion in repositories?
6. Create a table using Markdown with eight rows (header and days of the week) and three columns (header, number of hours slept, number of hours spent in class). Label the rows and columns with appropriate headers, and make these labels bold. Fill in the table with your estimates from the first week of class. Hint: when you are editing a document in the online web interface, use the Preview changes tab at the top of the window to check whether your formatting is correct.
7. Write a sentence directing your instructor (k8hertweck, using an @ mention) to the help page you used to rename your repository, embedding the link in one of the words.
