# CMPG323-Project4-36787426
## Introduction:
In this project we're required to conduct a User Acceptance Test (UAT) by using RPA. An Excel sheet has been given us which contain various data that we can use to do RPA. If the record passed the test, then we need to update the excel sheet with the test result. TRUE if passed, and FALSE if failed.

## How to run the automation
Step 1: Download project from this github repo/

Step 2: Open the folder EcoPowerLogisitics folder and locate the Desktop folder.

Step 3: Click on the Main.xaml within the Desktop folder. This will open UiPath Studio on your computer

Step 4: Press the blue play "Debug File" at the ribbon. This will open MS Edge browser.

Step 5: Wait for the login process to complete.

Step 6: From there you'll be prompted to choose which tab you want to work on: Customers, Orders, Products, or Order Details

Step 7: After choosing a tab, you need choose if you want to add, edit, or delete.

> Note! You need to test the CRUD operations in this order: Add first, then Edit, then Delete. This is because the automation tool updates the Excel Test Result tab after deleting i.e it will Create, Read, Update, Delete then update the test result for that specific row to true. It does this for every item in the excel row, therefore if the number of rows in the webapp does not match the number of rows in the excel, you will encounter an error. It is important to follow this order of operations.

Therefore you need to 'Add' first, when done, the program will close, then you need to open it again but choose 'Edit' this time around. The program will close after editing, then you will open it again and select 'Delete' this time around. After the last operation is done the excel file will be updated.

## References
<ul>

<li><p><a href="https://academy.uipath.com/courses/introduction to-rpa-and-automation">Introduction to RPA and Automation</a></p></li>  
<li><p><a href="https://docs.uipath.com/studio/docs/ui-automation">UI Automation with UiPath</a></p></li>
<li><p><a href="https://www.uipath.com/learning/video-tutorials/excel datatables-automation">Excel Automation with UiPath</a></p></li>
<li><p><a href="https://academy.uipath.com/learning-plans/uipath-rpa-associate-certification-training">UiPath RPA Associate Certification Training</a></p></li>
<li><p><a href="https://academy.uipath.com/certification">UiPath Certified RPA Associate (UiRPA)</a></p></li>

<li><p><a href="https://youtu.be/wz0_2onmG4o">UiPath Orchestrator: securely manage your digital workforce, in-cloud or on-prem</a></p></li>  
<li><p><a href="https://youtu.be/z3p5hmPsGdU">UiPath Orchestrator Complete Tutorial 2021 | UiPath Tutorial | Simplilearn</a></p></li>
<li><p><a href="https://youtu.be/-KAjgwWF0hY">UiPath Automation Examples | Top 5 Automation Examples in UiPath | RPA UiPath Training | Edureka</a></p></li>
<li><p><a href="https://youtu.be/SP_JGuHr2VA">What is UiPath RPA</a></p></li>
<li><p><a href="https://youtu.be/OyQAhrcBr9U">UiPath Studio: Your First Process Automation</a></p></li>

<li><p><a href="https://youtu.be/774l72-fWN8">UiPath Web Automation | UiPath Web Automation Tutorial With Example | UiPath Tutorial | Simplilearn</a></p></li>  
<li><p><a href="https://youtu.be/sAQxxWFgWLY">UiPath- App/Web Recorder| How to use the recorder?|New recorder in the modern UiPath studio</a></p></li>
<li><p><a href="https://youtu.be/hUm5cgiaje4">UiPath - Different Ways of Reading Rows from a DataTable</a></p></li>
<li><p><a href="https://youtu.be/BAYmmUuB2Zo">Introduction to UiPath Portal, Orchestrator & Studio</a></p></li>
<li><p><a href="https://youtu.be/wpu4vjI36pM">How to Pass UiPath Arguments Example</a></p></li>

<li><p><a href="https://youtu.be/S8vyutaQgZ8">Meet the UiPath Automation Cloud</a></p></li>  
<li><p><a href="https://youtu.be/9XXHVFiR3wc">Using the Selection Screen for the first time</a></p></li>
<li><p><a href="https://youtu.be/0O2wiyZVm68">How to OPEN BROWSER in UiPath| UiPath Open Browser Example</a></p></li>
<li><p><a href="https://youtu.be/1JxC3_UTcYU">UiPath: How to delete files in a folder (with .net framework)</a></p></li>
<li><p><a href="https://youtu.be/NNm4dUZwjOU">Difference between data scraping and screen scraping in uipath</a></p></li>

<li><p><a href="https://datafinity.co.za/products/uipath-robotic-process-automation/">ROBOTIC PROCESS AUTOMATION</a></p></li>  
<li><p><a href="https://www.guru99.com/uipath-tutorial.html">UiPath Tutorial for Beginners: What is UiPath RPA? Features</a></p></li>
<li><p><a href="https://www.guru99.com/uipath-tutorial.html#5">Understanding UiPath Interface</a></p></li>
<li><p><a href="https://www.simplilearn.com/tutorials/rpa-tutorial/what-is-uipath">Understanding UiPath Interface</a></p></li>
<li><p><a href="https://www.youtube.com/user/uipath">UiPath YouTube Community</a></p></li>

<li><p><a href="https://forum.uipath.com/">UiPath Community forum</a></p></li>
<li><p><a href="https://docs.uipath.com/automation-hub/docs/the-user-interface">The User Interface</a></p></li>

</ul>
