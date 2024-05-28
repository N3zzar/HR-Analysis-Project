# HR-Analysis-Project
This is a documentation of the HR Analysis Project that I did.

## Table of contents
- INTRODUCTION
- PROJECT OBJECTIVE 
- TECH STACK
- DATA COLLECTION
- DATA TRANSFORMATION
- DATA MODELLING
- DATA VISUALIZATION
- DATA AND REPORT LIMITATION
- CONCLUSION



---
## INTRODUCTION
This is a personal project that i decided to work on to cap off everything I've learnt in PowerBI so far. It is a dataset in the HR Domain which i am passionate about because it helps bridge the gap between my two interests - Finding patterns and understanding humans. It will serve as a reference if I should be asked for projects that I've done that I'm passionate about.


---
## PROJECT OBJECTIVES
As this project didn't come with any objectives, my objective for the project was to represent the information that can't be easily understood at a glance in a visually appealing context.


---
## TECH STACK
The tech stack used for this was Microsoft PowerBI. It is a business intelligence tool that empowers users to turn raw data into meaningful insights through interactive visualization.

![image](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/1f11f395-027a-47ea-a965-ebcee0a3c0c6)


---
## DATA COLLECTION
The files were downloaded as a zip file from Kaggle.com. It contains datasets like the Engagement survey dataset showing the responses from the survey that was carried out, diversity dataset showing the diversity status of each employee, Job profile mapping showing the salary assigned to each role within the company.




---
## DATA TRANSFORMATION
````
- Every table, specifically the ones with the text format, was loaded and then transformed in PowerQuery.
- The engagement survey was duplicated and then the other columns aside from the survey ID were removed, and conditional formatting was applied to label each ID. This was all done to create a sort of dimension table
- In the diversity table, one notable transformation I made was adding a conditional column where if disability of a particular employee is 0, then I will replace it with "No" and "Yes" if it is equal to 1.
- The company data table was where I did the most transformation. I merged the first name and last name of each employee, splitting and merging it back to convert "MM-DD-YYY" to "DD-MM-YYYY" so that data manipulation functions can be possible on it.
- Other transformations that I didn't mention are general ones, including: Promoting headers, sorting rows, reordering and renaming columns, and changing data types. 
- I ended up with the following tables that were then loaded into PowerBI Desktop.
````
![image](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/3e656055-7c7c-4234-b5c5-a9a1fa59ddd9)

![image](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/c0d86a6f-2d9c-4c60-adf9-21a05ad6d9c4)




---

## DATA MODELLING
I worked with a star schema for this project. The company data was the fact table, while the others were the dimension tables.

![Git](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/259c5ef4-0c76-467d-a729-36c965fddd74)

----

## DATA VISUALIZATION
![image](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/f0aa3ed9-048f-461f-8c3a-c2d945bdc18c)
![image](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/293f2094-6d37-44aa-ba37-5a69cd71f49a)
![image](https://github.com/N3zzar/HR-Analysis-Project/assets/85373417/162f148b-ba9a-4c59-92ae-f1c52361a7b4)

You can interact with here 
A more wordy explanation of the analysis can be found on the medium documentation.


---
## DATA AND REPORT LIMITATION
- It was a fictitious data as it didnt really reflect some real-life data that i needed.
- My design skills isn't that great yet so i just kept it simple.
- I couldn't think of any other insights to generate on the survey data.


---
## CONCLUSION
In conclusion, this PowerBI Project "HR Analysis of Nezzar Inc." aimed to provide a visual informational analysis of the company to assist in making informed decisions. I was able to implement all that I had learnt and also improved on the ones that I implemented on the last project that I did with PowerBI.

---
## FURTHER DOCUMENTATION
**You can read the non-technical documentation on medium here**


