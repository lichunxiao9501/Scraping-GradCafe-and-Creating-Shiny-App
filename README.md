# LetMeIn App

### What is LetMeIn?
LetMeIn is a ShinyApp that allows prospective students who want to apply to statistics graduate programs make better and faster decisions about where to apply based on their GPA, GRE scores and citizenship status. Students first select a school they are interested in, and LetMeIn calculates the average scores for accepted, rejected and waitlisted students and compares them to the student's scores. By seeing how their scores stack up, students can quickly determine whether they should apply to their selected school. All estimates are based on entries from thegradcafe.com, a public forum where graduate school applicants share their admissions information and whether they got accepted, rejected or waitlisted. 


### How was LetMeIn constructed?
This repository explains the step-by-step process of creating LetMeIn. 

The process included the following steps: 
* Scraping the appropriate data on statistics graduate programs from thegradcafe.com to put into a dataframe
* Cleaning GRE scores in the dataframe
* Cleaning the institution names to standarize them in the dataframe
* Scraping Wikipedia for college descriptions and pictures for logos and seals
* Generating the ShinyApp using the finalized dataframe from Step 3. 

### LetMeIn Demos
The two screenshots below give an overview of the LetMeIn App.

![screenshot 1](https://github.com/lichunxiao9501/Scraping-GradCafe-and-Creating-Shiny-App/blob/master/pics/screenshot1.png)

![screenshot 2](https://github.com/lichunxiao9501/Scraping-GradCafe-and-Creating-Shiny-App/blob/master/pics/screenshot2.png)
