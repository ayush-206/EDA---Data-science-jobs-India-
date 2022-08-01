# EDA-Data-science-jobs-India-
In this project, I have analyzed that how many data science jobs are there in India and more things. The dataset  used in my analysis is from the naukri.com website. It is an employment website where you can find jobs as per your preference. Also, according to Google Trends - This site is the most preferred job search destination in India.

<b>Overview </b> <li>I have downloaded this dataset from the Kaggle website. The data contains 12,000 rows and 5 columns.</li><li>Luckily, Our data is already cleaned. I can't get any null or missing values in our dataset.</li><li>To visually analyse the data, I also plot some graphs, tables and charts in the jupyter file by using python and its various libraries.</li><li>You will see top_jobs, Top skills required, Locations with maximum openings, average minimum job experience, and average maximum job experience</li>
<h1>Sample dataset</h1>
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/sample_dataset.PNG" alt="sample dataset" title="sample dataset">
</p>
This is a first few rows of the dataset in which you can see their are 5 columns.

<h1>Top Jobs</h1>
As i said earlier, there are 12000 rows in our dataset out of which there are 6563 rows has a unique job roles. In simple words, the data contains total 6563 different job roles.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/932c43603f283f27b2ab85e74241809fbccc21bb/total%20job%20roles.PNG" alt="total job roles" title="total job roles">
</p>
So, I have find top 5 jobs in accordance with the more number of job openings and here i got these 5 designations.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/Top%205%20jobs.PNG" alt="top jobs roles" title="top jobs roles">
</p>
<h1>Top jobs along with their required skills</h1>
So far, i have found the top jobs that has a huge demand in the market. Now i want to know that what skills are required to grab that job. Like - I want to become a data analyst. So, what skills do i learn to become fit for that job role.<br>
</br>
Therefore, I have made the sunburst chart whose inner circle is divided into job roles and outer circle is containing a skills required for specific job role. You can see the chart below:
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/Top_jobs.PNG" alt="top jobs roles with skills" title="top jobs roles with skills">
</p>
<h1>Job openings</h1>
Now, my next task was to find a number of job openings as per cities. For that, i have created a list of cities then counted the value as per job openings. Further, i removed the duplicate names that was present in our dataset. Lastly, I plotted the graph.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/job%20openings.PNG" alt="job openings" title="job openings">
</p>
Additionally, i made a graph that gives more transparent visuals of job openings in accordance with cities.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/jop%20openings%20graph.PNG" alt="job openings graph" title="job openings graph">
</p>
<h1>Top demanding skills in data science job</h1>
According to my analysis, I found that Python, Machine learning, IT skills, SQL, Big data and few more skills has a huge demand in market. Let's have a look below:
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/demanding%20skills.PNG" alt="Demanding skills" title="demanding skills">
</p>
<h1>Top companies</h1>
In our dataset, there are total 3507 different companies are offering jobs.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/total%20companies.PNG" alt="total companies" title="total companies">
</p>
But, I made the table in which you can see top 10 companies with a more number of openings. However, the multinational company accenture is right at the top. Have a look in table below:
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/top%20companies.PNG" alt="top companies" title="top companies">
</p>
Additionally, I plotted a sunburst chart again between top companies and job role. So that, viewer get's the easy idea that which company is hiring for which roles.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/main/Top_job_providers.PNG" alt="top job provider" title="top job provider">
</p>
<h1>Average Job Experience</h1>
During analyzing the data, I found that the company wants some experience in every job role. They are providing the range of experience(say 2-3 years). So, i found the average of the min. and max. experience for the different job roles and plotted a table.
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/2c79b35124a596b13ff68c61a4c53fe2f8c3b4dd/Average%20min.%20job%20experience.PNG" alt="Average minimum experience" title="Average minimum experience">
</p><br>

</br>
<p align="center">
  <img src="https://github.com/ayush-206/EDA-Data-science-jobs-India-/blob/2c79b35124a596b13ff68c61a4c53fe2f8c3b4dd/Average%20max.%20job%20experience.PNG" alt="Average maximum experience" title="Average maximum experience">
</p>
