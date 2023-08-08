# Resume-Short-lister---ML

Are you tired of manually going through countless resumes to find the best applicants? Look no further! Welcome to Resume Shortlister, a project that simplifies the process of filtering and sorting job applicants to help you discover the cream of the crop effortlessly.

<br>

<h3> What's the project all about? [ Problem Statement ]</h3>
<br>
Here our objective was to sort the best candidates for an internship role, The company got the applications from Internshala ( a leading intern hiring platform ). Here the applications were in a Excel ( CSV ) format which got the following columns: <br>

1) Name: This column represents the name of the individuals or participants in your dataset. <br>

2) Python (out of 3): This column indicates the proficiency level of each individual in Python programming, rated on a scale of 1 to 3. A rating of 3 suggests a high level of expertise in Python. <br>

3) Machine Learning (out of 3): This column represents the proficiency level of each individual in machine learning, rated on a scale of 1 to 3. A rating of 3 indicates a strong understanding and skills in machine learning. <br>

4) Natural Language Processing (NLP) (out of 3): This column represents the proficiency level of each individual in natural language processing (NLP), rated on a scale of 1 to 3. A rating of 3 suggests a high level of expertise in NLP. <br>

5) Deep Learning (out of 3): This column indicates the proficiency level of each individual in deep learning, rated on a scale of 1 to 3. A rating of 3 indicates a strong understanding and skills in deep learning. <br>

6) Other skills: This column contain additional skills or qualifications that are not specifically mentioned in the previous columns. <br>

7) Are you available for 3 months, starting immediately, for a full-time work from home internship? : This column determine if the individuals are available for a full-time work-from-home internship for a duration of 3 months, starting immediately. <br>

8) Degree: This column represents the degree obtained by each individual, such as Bachelor's, Master's, or Ph.D. <br>

9) Stream: This column might indicate the field or specialization of study for each individual, such as Computer Science, Engineering, or any other relevant discipline. <br>

10) Current Year Of Graduation: This column denotes the current year of graduation for each individual, indicating their progress in their respective academic programs. <br>

11) Performance_PG: This column represent the performance or grades obtained by each individual in their post-graduate (PG) studies. <br>

12) Performance_UG: This column represent the performance or grades obtained by each individual in their undergraduate (UG) studies. <br>

13) Performance_12: This column represent the performance or grades obtained by each individual in their 12th-grade examinations. <br>

14) Performance_10: This column represent the performance or grades obtained by each individual in their 10th-grade examinations. <br><br>


<h3> Sample Dataset 👇</h3><br>

![image](https://github.com/Hariikm/Resume-Short-lister---ML/assets/127305068/a22624b0-dea5-4d87-b9ac-9e1a41af5736)

<br><br>
<b>💥 Our objective is to develop an algorithm that can sort out the best individuals from all the applications. 💥</b> </font> <br>

<br>

To address this problem , we will:

🔸 Look at the data structures and find out what the data looks like. <br>

🔸 We sort the candidates based on the ranks that we are given as per their performance. <br>

🔸 After doing all the necessary procedures we finally move on to building the algo. <br>

🔸 We Create a function ( algo ) that will automatically evaluate candidates and give us the top n candidates from their resumes. <br>

🔸 The success of our project will be determined by the Algorithm's ability to sort out the best candidates from the resumes <br>

<br>

<h3> The code ideas summarised :</h3> <br>

Here we are creating a new column called overall_score to calculate the assigned score on basis of diffrent conditions as mentioned below: <br>

Overall score calculation matrix: <br>

-> For the value points in python, ML, NLP and DL will be given a higher preference and the scores of that is multiplied with 3 to make the overall_score. <br>

-> For each skills in others column which are in the skill_set will be getting an extra point in the overall_score.<br>

-> For avialability 'no' a point will be deducted and for 'yes' a point will be awarded in the overall_scores.<br>

-> If the tenth mark is not given 3 points will be deducted. ( as it either shows negligence or 10th failure )<br>

-> If the plus two mark is not given 2 points will be deducted. ( as it either shows negligence or 12th failure )<br>

-> If the UG mark is not given 1 point will be deducted.<br>

-> If someone got a PG mark 1 point will be awarded for the overall_score ( as it always an addition if someone got a PG degree )<br>

-> We are not considering the streams and thier respective degree because as we all know the real talents may not be reflected from those.<br>

​<h3> The final output </h3> <br>

We are now creating an algorithm ( function ) which takes the datset and return the top N candidates from the input <br>

Here the algorithm works with any similar datasets and it gives the best candidates from the given data. By default it gives the top 10 candidates, We can change this as per our wish by specifying the top argument.<br><br>

Sample Output 👇<br>

![image](https://github.com/Hariikm/Resume-Short-lister---ML/assets/127305068/35d80e61-e3de-4b02-97ef-a9d5a6714d63)

<br><br>

<h1> ThankYou </h1>
