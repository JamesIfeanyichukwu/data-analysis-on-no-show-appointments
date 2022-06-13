# Project: Medical Appointment No-Show Analysis

## Table of Contents
<ul>
<li>Introduction</li>
<li>Data Wrangling</li>
<li>Exploratory Data Analysis</li>
<li>Conclusions</li>
</ul>


## Introduction

### Dataset Description 

>This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
    <h4>Dataset Features:</h4>
    <li><b>PatientId</b> - Patient Identification Number.</li>
    <li><b>AppointmentID</b> - Identification of a patient's appointment</li>
    <li><b>Gender</b> - Male or Female.</li>
    <li><b>ScheduledDay</b> - The day the patient is due to see a doctor.</li>
    <li><b>AppointmentDay</b>- The day a patient's appointment is set.</li>
    <li><b>Age</b> - How old the patient is.</li>
    <li><b>Neighbourhood</b> - Where the hospital is located.</li>
    <li><b>Scholarship</b> - True of False - whether or not a patient is enrolled in a Brasilian welfare program, Bolsa Familia. </li>
    <li><b>Hipertension</b> - True or False</li>
    <li><b>Diabetes</b> - True or False. True if a patient is diabetic and false if a patient is not</li>
    <li><b>Alcoholism</b> - True or False</li>
    <li><b>Handcap</b> - True or False. True if a patient is handicapped and False if not.</li>
    <li><b>SMS_received</b> - True or False. True if a patient receives an sms and false if a patient does not.</li>
    <li><b>No-show</b> - Yes or No. Yes if a patient does not show up and No if a patient shows up</li>


### Question(s) for Analysis
<h4> We will be exploring the following questions in our analyses</h4>

>1. Which gender has the most scheduled appointments? 
>2. Which gender shows up more on their appointment days?
>3. Does age affect the chances of showing up?
>4. How does the gap in schedules (due_days) affect a patient's chance of showing up for their appointment?
>5. Do patients who receive sms show up more than those who do not?
>6. Do patients on scholarship show up for their appointments more than those who are not?
>7. Does a patient's handicap affect their chances of showing up?
>8. Do patients with a particular disease show up more than those without?
>9. Which months recorded the highest appointment, and what was the patients' turn-up for those months?
>10. What is the distribution of appointment schedules for each neighbourhood?


**Dataset used for the analyses** <a href="https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd2e9a_noshowappointments-kagglev2-may-2016/noshowappointments-kagglev2-may-2016.csv"> click here to download </a>
