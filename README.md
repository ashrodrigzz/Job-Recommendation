# Job-Recommendation<br><br>
I have developed a Job Recommendation Engine that recommends a list of jobs based on the job role we provide. This engine leverages advanced algorithms to analyze job descriptions and match them with user-provided job roles, generating a list of relevant job opportunities tailored to individual career goals. Its primary application is in job search platforms and career development tools, where it enhances user experience by offering personalized job suggestions and streamlining the job discovery process. By automating the recommendation process, the engine helps job seekers find suitable positions more efficiently and supports employers in reaching the right candidates for their job openings.<br><br>

Dataset: <br>
The dataset used for the Job Recommendation Engine includes 758 records and contains the following columns: Uniq ID, job title, company, job description, and advertiser URL. Dataset is given in **cleaned_recommendation.csv** file.<br><br>

Approach Used: <br>
The Job Recommendation Engine is developed using the **Flask Python framework** that takes a job role provided by the user as input and returns a list of available jobs that match the specified role. The engine combines the job title and job description columns from the dataset to create a comprehensive text feature for each job posting. It then applies **TF-IDF vectorization** to convert these textual features into numerical vectors, which are subsequently analyzed using **cosine similarity** to measure the relevance of each job to the provided job role. The **recommend()** function processes the user’s input, compares it with the job descriptions using these techniques, and generates a ranked list of job recommendations based on the similarity scores.<br><br>

Set-Up Instruction:<br>
•	Install and Open Visual Code Studio application for windows.<br>
o	https://code.visualstudio.com/download<br>
•	Python Version: Python 3.12.4<br>
•	Run python **app1.py**<br>
