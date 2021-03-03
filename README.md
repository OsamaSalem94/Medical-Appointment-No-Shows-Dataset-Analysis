# Medical-Appointment-No-Shows-Dataset-Analysis
The analysis is focused on finding factors predicting whether or not the patient will show up to thier appointment.

## Introduction
"A person makes a doctor appointment, receives all the instructions and no-show. Who to blame?"
This dataset collects information from 100k medical appointments in Brazil and is focused on the question
of whether or not patients show up for their appointment.

The analysis is focused on finding factors predicting whether or not the patient will show up to thier appointment.

## Dataset & Wrangling Efforts
### Dataset
The dataset consists of 110,527 rows and 13 columns.
The columns are PatientId, AppointmentID,	Gender,	ScheduledDay,	AppointmentDay,	Age,	Neighbourhood,	Scholarship,	Hipertension,	Diabetes,	Alcoholism,	Handcap,	
SMS_received and	No-show.

### Wrangling Efforts
The dataset was pretty much clean except for mulitple quality issues such as:

    - Erroneous datatype for PatientID.
    
    - Erroneous datatype for Gender.
    
    - Erroneous datatype for ScheduledDay.
    
    - Erroneous datatype for AppointmentDay.
    
## Limitations:
While try to analyze the dataset trying to find a pattern to predict the likelihood of a patient showing up or not, I was met with some limitations.

  - It was important to analyze the relationship between the area of hospital and appointment attendance but the area data
    was lacking demographic information which can skew and mislead the analysis if it was done without that data.
    
  - There wasn't clear information on whether the patient chose the appointment date or hospital did and also the exact
    hour of the appointment was missing so analyzing humanbehavior based on lacked or vague information 
    seemed misleading
    
## Conclusion
What factors are important to predict if a patient will show up to thier appointment?
    - First factor analyzed was whether or not the patient was enrolled in the welfare program. 
        We found higher percentage of absence of patient enrolled in the program than others and the reason for that
        according to a study " people who aren't enrolled in any healthcare are careful with making appointment 
        resulting of lesser abscence.

    - Second factor analyzed was the Gender to see if it had any impact on the abscene percentage. 
        we found out that females makes almost twice the appointments than males but regarding the appointment abscence
        the percentage is almost the same.

    - Third Factor analyzed was receiving an SMS prior to the appointment.
        the analysis proved that pecentage of abscence in people receiving SMS is higher than other people who didn't
        receive SMS which means recieving SMS doesn't impact if a person will show or not since in most cases 
        the patient already decieded not to show up rather than forgetting about the appointment.

    -Fourth Factor was the Age
        as expected the percentage of abscence between the age of 20 to 40 is higher as people of that age have lesser
        regard to their health compared to the percentage of people older than 45 years old and even more than people 
        older than 60 years old as it's shown in previous studies that people starts to care more about their health 
        the older they grew.
        It is noteable that patients older than 17 years old have low abscence level that is probably 
        due to the partents making the appointments and accompanying the child.
