<h1>Investigating_Medical_Appointment_No_Show</h1>

<h2>Introduction</h2>

<h3>Dataset Description</h3>

This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row.
The dataset contains of 10,866 rows and 21 columns. The columns include;


|**Column Name**|**Description**|
|-----------------|-----------------|
|**PatientId**|Identification of a patient|
|**Appointment_ID**|Identification of each appointment|
|**Gender**|Male or Female|
|**Scheduled_Day**|The day of the actuall appointment, when they have to visit the doctor|
|**Appointment_Day**|The day someone called or registered the appointment, this is before appointment of course|
|**Age**|How old is the patient|
|**Neighbourhood**|Where the appointment takes place|
|**Scholarship**|True of False if the person had NHI| 
|**Hypertension**|True or False whether the person has the medical condition or not|
|**Diabetes**|True or False whether the person has the medical condition or not|
|**Alcoholism**|True or False whether the person has the medical condition or not|
|**Handicap**|Where the person is handicap or not|
|**SMS_Received**|True or False whether the person received the sms or not|
|**No_Show**|Yes or No whether the person showed up for the appointment or not|


<h3>Question(s) for Analysis</h3>

1) What medical condition on or not on scholarship mostly show up or does not show up for appointment?

> Examine the connection between the the medical condition of various patients, whether or not they are on scholarship, and whether or not they are showing up for appointments.

2) What rate does those received sms show up for appointment?

> Analyzing the difference in attendance between patients who receive a text message confirmation after scheduling an appointment and those who do not.

3) How many show up and does not show up for appointment on handicap?

> To examine patient attendance in order to understand the relationship between those who are handicaps and those who do not.

4) Which gender has the highest appointment attendance?

> Develop understanding of gender (males and females) differences in appointment attendance.


<h2>Conclusions</h2>

<h3>What medical condition on or not on scholarship mostly show up or does not show up for appointment?</h3>

__Observation__ This demonstrates that averagelly, patients with scholarships typically do not show for appointments, in contrast to patients without scholarships. This generally means that the majority of patients, whether on scholarship or not, tend to show up for appointments.

<h3>What rate does those received sms show up for appointment?</h3>

__Observation__ Most patients shows up for appointment after receiving sms. This indicate over 25,000 patients, while about 10,000 patients do not show up for appointment after receiving sms.

<h3>How many show up and does not show up for appointment on handicap?</h3>

__Observation__ Through the analysis, it was discovered that 80% shows up for appointment not handicap where the rest do. In total, this represented 80% not handicap and 20% people handicap.

<h3>Which gender has the highest appointment attendance?</h3>

__Observation__ Out of the total appointments scheduled, it was found that more than 79% Females and roughly 80% males actually showed up for their appointments. This demonstrates that, in contrast to Females, the majority of males prefer to make up for their appointment.

<h2>Limitation of the dataset</h2>

> This finding cannot be generalized because this dataset was based on a particular geographic area.
