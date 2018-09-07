# About
- We have the earl project website spread across two repositories. 
- https://github.com/earl-project/earl-project.github.io is the public facing website. 
- https://github.research.its.qmul.ac.uk/eecsearl/website is the hugo version of the website.
- Make changes in the hugo version and publish the output html into the github.com version to update the website. 
- We have the public facing website on github.com instead of qmul's github because we wanted to use github.io. 

# Instructions to make changes to the website
- This repo has the Hugo code https://github.research.its.qmul.ac.uk/eecsearl/website
- Make your changes in the qmul repo, for example if you want to update the dissemination webpage, change https://github.research.its.qmul.ac.uk/eecsearl/website/blob/master/content/dissemination.md
- Then generate the new website with the command `hugo` in the root directory of the qmul github repo. Install [https://gohugo.io/getting-started/installing/] `hugo` first if you don't have it.
- Copy the appropriate index.html file from within the desired folder such as `public/dissemination/index.html` and replace the `dissemination.html in` https://github.com/earl-project/earl-project.github.io
- Once you push the changes to github.com, the website should be update within 15 minutes. 
