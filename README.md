README for Assignment 1

Identify what aspects of the work have been correctly implemented and what have not.
Identify anyone with whom you have collaborated or discussed the assignment.
Say approximately how many hours you have spent completing the assignment.

For this assignment, I have created index.html, resume.html and bio.html and each with a css file according to the instructions. Each file has passed the W3C validation. My index.html under tufts cs account is able to redirect to my github personal page, however I have encountered several problems before successfully implementing the redirection. At first, I used my public_html on Halligan remote server as the origin repository for the master respository on Github, which led to the infinite redirections to my github page when my eecs page is opened. Then I figured everything except for the index.html that only contains the link to my github page should be kept under my tufts cs account, and therefore I have deleted the link to github page in my local index.html file and made my local assignment directory the origin repository. Instead of taking a shortcut, I have deleted the master repository I created at first and re-committed and re-pushed the files from my local directory to the new master repository. As most of the files I re-committed and re-pushed are in their final versions, there aren't many commit messages in my new master repository. 

I have asked a follow-up question on Piazza about the infinite redirection problem, and I solved it by changing the origin repository and removing the link to my webpage in the local index.html file. 

I have spent approximately 3 hours writing the html and css files, and the infinite redirection problem took me 1.5 hours in total to solve. Therefore, I have spent around 4.5 hours for the assignment.