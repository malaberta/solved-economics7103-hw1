Download Link: https://assignmentchef.com/product/solved-economics7103-hw1
<br>
The goal of this homework is to get you to install and integrate Anaconda, Overleaf, and GitHub. Please follow these initial installation instructions that you will need to complete all of the homework assignments: 1. Register for free accounts with GitHub and Overleaf as specified in the homework guidelines.

<ol start="2">

 <li>Download Python via the Anaconda distribution and GitHub desktop as specified in the homeworkguidelines.</li>

 <li>Complete the GitHub “hello world” exercise: <a href="https://guides.github.com/activities/hello-world/">https://guides.github.com/activities/hello-world/</a></li>

 <li>Complete the Overleaf “hello world” exercise: <a href="https://www.overleaf.com/learn/latex/Questions/How_to_create_a_very_basic_hello_world_document_using_LaTeX">https://www.overleaf.com/learn/latex/Questions/ </a><a href="https://www.overleaf.com/learn/latex/Questions/How_to_create_a_very_basic_hello_world_document_using_LaTeX">How_to_create_a_very_basic_hello_world_document_using_LaTeX</a></li>

 <li>Explore the Spyder introduction videos: <a href="http://docs.spyder-ide.org/develop/current/first-steps-with-spyder.html">http://docs.spyder-ide.org/develop/current/first-ste</a>ps-with-spyde <a href="http://docs.spyder-ide.org/develop/current/first-steps-with-spyder.html">html</a></li>

 <li>On Overleaf, link your account with GitHub.</li>

</ol>

<h1>Setting up your homework repository</h1>

For this homework, you will create a homework repository in which you will save all of your homework code and output to turn in to me. To do this, you will exactly replicate the files in the sample_code folder in the repository I shared with you. This exercise will help you to integrate all of these tools into one automated workflow that is reproducible and able to be shared. To do this, follow these steps (there are other, arguably better ways to do these things, but I am just sharing what I have found most convenient so far—next year these processes will be updated as I learn more!): Set up a repository using GitHub desktop.

<ol>

 <li>In GitHub desktop, create a new repository using File, New repository. Name it phdee-2021-XX where you replace XX with your own initials. You can create this anywhere on your local system that you would like. Check the box to initialize the repository with a readme. This will create a folder called phdee-2021-XX on your computer.</li>

 <li>In your repository, create a subfolder called homework1. Within that subfolder, create two subfolders: one for code called code and one for TeX output called tex. In each subfolder, I like to copy and paste a readme file to get it started. For an example of the repository setup, refer to the sample_code</li>

</ol>

Now, copy my sample.py Python script from the phdee-2021-homework/sample_code/code folder, run it, and push the script and output to GitHub:

<ol>

 <li>Open up Spyder in Anaconda. Create a new Python script copying the sample code contained inpy in the repository I shared with you.</li>

 <li>Edit the directory path outputpath so that they match the path to the subfolders you created.</li>

</ol>

1

<ol start="3">

 <li>Save your .py script in your code subfolder.</li>

 <li>Run the .py code (and fix any errors if necessary). In your output folder, you should have two .texfiles and two .eps files.</li>

 <li>In GitHub desktop, commit these changes to the main branch. Then publish your repository to GitHub.</li>

</ol>

You now have saved a record of your code and your output to GitHub. Next, you will replicate the main.tex and Homework_sample.pdf file using Overleaf:

<ol>

 <li>From the Overleaf main page, click new project and use the option to import from GitHub. Youshould be able to import your homework repository phdee-2021-XX. Pull any changes from GitHub to Overleaf if necessary.</li>

 <li>In Overleaf, create a new .tex file and copy and paste the text from my phdee-homework/sample_code/tex/main.tex file in the sample_code/tex Click the green button to compile it.</li>

 <li>You will notice some errors or warnings in the paper icon next to the compile button. One of the errors isthat you need to include a bibliography file to use with natbib. Create in your output folder a file called bib and copy and paste the content from phdee-2021-homework/sample_code/output/sampleref.bib to create the file.</li>

 <li>Recompile your main file and fix any errors or warnings until you have an error-free pdf. In Overleaf, usethe menu button, click GitHub, and push your changes to your GitHub repository. This synchronizes your Overleaf with the GitHub repository.</li>

 <li>Finally, from Overleaf, download the .pdf file you have created, save it in your homework 1 folder, andpush this change to GitHub.</li>

</ol>

Your homework1 folder in your phdee-XX repository should now look exactly like my sample_code folder. If not, figure out where you went wrong and troubleshoot it.