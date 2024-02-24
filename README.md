
<h1>Diabetes Analysis Project</h1>


<h2>Description</h2>
Project consists of a dataset containing health information of 250,000  patients. The dataset contained 21 Columns and 250,000 rows. The goal of the project is to discover findings and conclusions about the impact that certain health factors and lifestyle choices has on the overall health of people. Program showcases the fundamentals of data analysis including, data cleaning, manipulation, visualization etc. 

<h2>Language</h2>

- <b>Python</b> 


<h2>Program walk-through:</h2>

<p align="center">
Importing Pandas Library: <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/f73762d2-bf1b-4f26-92bb-db743a9fa783" height="80%" width="80%"/>
<br />
<br />
<br />
<br />
Data Cleaning: <br/>
   - Deleted the data that was not needed for the analysis. <br/>
   - Renamed columns to make them easier to understand and work with.   <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/2e1bfd96-b079-45e6-9ceb-b40453422fc7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Data Cleaning: <br/>
   - In the original dataset, numbers were used as values to describe a patients status. <br/>
   - For example, in the first line in this picture, 0 = No, 1 = Prediabetic, 2= Yes. <br/>
   - I chose to convert these into descriptive values so the data would be easy to look at and understand when working with it. <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/0dd41613-ce04-4ba2-85b1-feef011f8b25" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/49297be8-b30d-4ddc-9bba-707ddc5dbd4c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
Snippet of first 5 rows and columns of Dataset before cleaning:  <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/6a073f9c-e03d-4e34-a2c5-0fe9c45e538c" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After Cleaning:  <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/f0e25fa3-c686-47c8-82d9-0321c14da096" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
1. Analyzing and Visualizing:  <br/>
   - Now that the data was cleaned, I wanted to begin analyzing to find insights.  <br/>
   - The first piece of information I was interested in was to see how prevalent diabetes was amongst different age groups. <br/>
   - To get this, I grouped the "Age" and "Diabetes" Column, and created a "Count" column that had the total number of people with diabetes at each age group.  <br/>
   - I then found the percentage of people at each age group with diabetes.  <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/972cebbc-59ac-44b9-a34f-31b63cee797f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br/>
<br/>
1. Reasoning and Insights: <br/>
- The reason I chose to look at this is because I feel it can help the medical staff accurately assess the situation when a patient walks in. <br/>
   - If the patient is showing symptoms of diabetes, the healthcare worker can assess the liklihood that the patient has diabetes, based on this data and the knowledge gained from their examination. <br/>
   - From there they can use their expertise to move towards the right course of action. <br/>
   - Based on this data, you can see that diabetes is very rare among younger age groups, but the older a person is the more likely they are to have diabetes. With the age group of 70-74 being at 21.85%
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/abdfba1d-617d-4736-abc8-bacb06a7c5e7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
2. Analyzing and Visualizing: <br/>
   - Next, I wanted to see the correlation between drinking/smoking and having a heart attack/disease. <br/>
   - I first filtered the data set to only see the total count of patients who had a Heart Attack or Disease. <br/>
   - Then filtered even further to got a count of the patients who heavily consumed alcohol weekly and had a heart attack/disease.  <br/>
   - I turned this number into a percentage. <br/>
   - I followed the same process with finding out how many people with heart attack/disease are also smokers. <br/>
   - Lastly, I looked for the number of patients who drink and smoke. <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/6bc189b4-0a67-4317-98b1-c8293a5b1e21" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
2. Reasoning and Insights: <br/>
   - The reason I chose to look at this was to see which habit had a bigger impact on overall heart health; Smoking or Drinking. <br/>
   - The analysis shows that smoking is much more common amongst patients with heart issues. <br/>
   - These insights can help patients make better life style decisions if they choose to. Someone that deals with heart issues or has a family with a history of it can see this and choose not to smoke.<br/>
   - Medical professionals can also tell these people to stop smoking in order to help them. <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/6e1cb8fb-db28-49c2-80e3-0f6e14743127" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
3. Analyzing and Visualizing: <br/>
   - For this step, I wanted to look at the relationship between High Cholesterol and Diabetes. <br/>
   - I first filtered the dataset to only include the "Diabetes" Column and where the values was "Yes".<br/>
   - I further filtered to find where High_cholesterol was also "Yes". <br/>
   - I got a count of the amount of those patients and stored it in diabetes_high_cholesterol_count.<br/>
   - I then found the percentage of Diabetes patients who also have high cholesterol. <br/>
   - The same process was then followed, but  edited to contain rows where High_Cholesterol had "No" as the value, and further filtered to add the column "Chol_Check_5_Years" and only show the rows with a value of "Yes" <br/>
   
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/08e3d153-7155-42d5-b929-ca31df23da54" height="80%" width="80%" alt="Disk Sanitization Steps">
<br />
<br />
3. Reasoning and Insights: <br/>
 - I chose to look at the relationship between cholesterol and diabetes because I wanted to show that the food that we put in our body has an impact on our health. <br/>
 - Based on this data, you can see their is a positive relationship between high cholesterol and diabetes. 67% of diabetes patients also have high cholesterol.  <br/>
 - Therefore, people who are at risk of diabetes should place a bigger emphasis on what they eat and should avoid foods that will cause their cholesterol levels to increase. <br/>
 - I also wanted to see if this number could acually be higher.<br/>
 - Therefore, I looked at the diabetic patients who were stated to not have high cholesterol, and wanted to see if they had it checked in the past 5 years.<br/>
 - I found that a little less then half of them had it checked in the past 5 years (48.8%).<br/>
 - This shows that the 67% number should possibly be higher. <br/>
   
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/0ba7368a-cc83-43e2-b0b1-83b5dbede158" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />
4. Analyzing and Visualizing: <br/>
 - Next, I looked at the relationship between BMI and different health factors (Diabetes, Stroke, and Heart Attack/Disease). <br/>
 - I first got a count of the total amount of patients with Diabetes. <br/>
 - Then I filtered to find where a patient had diabetes and a BMI between 25 and 30 and turned this into a percentage. <br/>
 - I did the same thing again but where the BMI was 30 or over. <br/>
 - I followed the same steps but with Heart Attack/Disease and BMI. <br/>
 - Then again with Stroke. <br/>
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/78fc7ed3-9946-4f30-8808-0a4505eb815a" height="80%" width="80%" alt="Disk Sanitization Steps">
<br />
<br />
4. Reasoning and Insights: <br/>
 - The reason I looked at this was to see how much of a factor BMI plays in overall health.  <br/>
 - As the data shows, among patients that have dealth with issues such as diabetes, strokes, and heart attack/disease, having a high BMI is prevalent amongst them. Specifically, once they get into that obese range.  <br/>
 - This data can help medical staff assess patients who are dealing with these issues and inform them to make healtheir decisions to lower their BMI.  <br/>
 - It also gives people proof that they should watch their weight in order to remain healthy.  <br/>
   
<img src="https://github.com/MunrajSingh/Diabetes-Analysis/assets/74477225/72fe58c3-6cad-4ca4-9354-f8448dc29483" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<br />
<br />










</p>




<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
