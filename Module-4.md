
# Module 4: Data Quality Checks During Data Capture (1h 20 min)

## 4.0 - Overview of the module (5 min)

#### 4.0.1 - What's In This Module? (5 min)

### 4.0.1 What’s In This Module?

Data Quality issues can often be caused during the data capture process. How can you avoid these issues? What DHIS2 tools and methods can you use to prevent these issues before they occur?

In this module, you will learn useful tips for working with individual-level (Tracker) data in DHIS2 to support better data quality in capturing Tracker data. First, Yury Rogachev, a specialist on Tracker implementation, will show you **how to move Tracker data to aggregate data sets**, and you will present scripts that you can use to **map useful data from the imported data**.

Then, Scott will show you how you can implement good data quality in Tracker Programs by learning how to **create and use program rules and indicators to ensure good data quality in the data capture process**.

### Learning objectives

By the end of the module you will be able to:

- Import Tracker data to aggregate data sets

- Turn the tracker data into aggregate data using an aggregate script

- Create a program rule for good data quality

- Identify how program indicators work to ensure good Data Quality

### How will you be evaluated?

There is a short graded quiz to test your understanding of Program Rules and Data quality issues in Tracker. You’ll need to pass this quiz in order to gain your certificate of completion for the course. This graded quiz contributes 10% to your final grade.

### How long will this module take?

This module should take about **1 hours 20 min** to complete.

## 4.1 - From Tracker to Aggregate (30 min)

#### 4.1.1 - From Tracker to Aggregate (30 min)

##### 4.1.1 - From Tracker to Aggregate

### 4.1.1 - From Tracker to Aggregate

In this video, Yury will show you how you can turn Tracker data into aggregate data. You’ll start by looking at the Data Import tool in DHIS2 that you can use to import the Tracker data, then work through an example of the data being imported with it. You’ll then look at how to use the Tracker to Aggregate script to map the Tracker data into useful aggregate data.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

### Key Concepts & Video bookmarks

00:00 Introduction

05:00 Importing Tracker Data example

12:23 Tracker to aggregate script

19:00 Questions

##### (Video) - From Tracker to Aggregate

### (Video) - From Tracker to Aggregate

[https://www.youtube.com/watch?v=nSg8Vn0wtV8](https://www.youtube.com/watch?v=nSg8Vn0wtV8)

##### Tracker to Aggregate - Video Download

### Tracker to Aggregate - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/4.1.1+-+Tracker+to+Aggregate.mp4

You can find the PDF of the presentation here: [https://drive.google.com/file/d/1lFM8rKM9qVctgJtHoBAbK6nR9TRnbrUN/view?usp=sharing](https://drive.google.com/file/d/1lFM8rKM9qVctgJtHoBAbK6nR9TRnbrUN/view?usp=sharing)

##### Exercise - Tracker to Aggregate - Graded Exercise

### Exercise - Tracker to Aggregate - Graded Exercise

This exercise is a **graded exercise** and contains two questions. You have **two** attempts at each question. Once you have selected your answers, select the submit button to confirm that you are ready to submit your response. You can return to this page later on if you want to refresh yourself on the material.

### Question 1

0.0/1.0 point (graded)

Which of the following scenarios are where automated transfer of tracker data to aggregate data set could be a considered solution?

Select all answers that apply.

1. **Phased scale up of tracker: certain facilities/districts start implementing individual data entry (Tracker), the other facilities retain paper-based data entry forms.**

2. **Tracker system contains sensitive personal data that needs to be well protected.**

3. **Tracker reports need to be closed for a given reporting period, where no further edits or new events can be made.**

4. **Pivoting analysis data by age and sex dimensions in analytics apps is required.**

Feedback: All are correct. Data obtained from individual data records (tracker) improves the quality of reporting. Aggregate data is easier to dimensionalize in analytics apps. System performance is less affected when processing aggregate data. When it comes to protecting personal data, it is possible to restrict access to such data in tracker on user level, however transferring data to aggregate data sets adds another level of protection. Closing reporting periods is only supported for aggregate reporting.

### Question 2

0.0/1.0 point (graded)

How do you need to map tracker and aggregate metadata for correct data transfer:

Select all answers that apply.

1. Make sure that the program indicator code in the tracker system matches the aggregate data element code in the aggregate data set.

2. **Make sure that the program indicator in the tracker system references data element id and category option combination id.**

3. **Make sure that the program indicator in the tracker system references aggregate data element code and category option combination code.**

Feedback: B and C are correct. A is insufficient. As data elements are often dimensionalized by categories/category combinations, Matching 1 program indicator with 1 data element will only work if the data element does not have any other dimensions than “default”. In other cases, both the data element and the category option combination have to be matched in order to enable correct data transfer.

### Question 3

0.0/1.0 point (graded)

A user has a quarterly data set assigned to a regional level and would like to import aggregated facility level tracker data into this dataset for the past 3 years. Choose correct statements:

Select all answers that apply.

1. Data transfer is not possible in this case, because Tracker data and Aggregate data are entered at different levels. (Facility for tracker, region for aggregate)

2. Data transfer is only possible for daily data sets because tracker data is based on enrollment and event dates.

3. **Data transfer is possible if the organisation unit hierarchy in Tracker and Aggregate instances is the same and the user specifies OU level dimension that corresponds to “Region” when fetching tracker data.**

4. **The transfer is possible if data entry for the data set is not closed for past periods (expiry periods and data input periods are set up).**

Feedback: C and D are correct. It is possible to aggregate tracker data to the desired level and relative period using the ou and pe dimensions. In order to transfer data for past periods, it is important to make sure that the data set is open for data entry for those specific periods.

## 4.2 - Data Quality in Tracker Programs (45 min)

#### 4.2.1 - Data Quality in Tracker Programs (45 min)

##### 4.2.1 - Data Quality in Tracker Programs

### 4.2.1 - Data Quality in Tracker Programs

In this video, Scott Russpatrick will show you how to implement Data Quality in Tracker Programs. You’ll start by looking at what exactly a Program Rule is, and then an example of it in DHIS2. You’ll then look at how to set up Program Rules for good Data Quality. Finally, you’ll look at how program indicators can be used to ensure good Data Quality.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

### Video Bookmarks & Key Concepts

00:00 Introduction

10:10 Program Rule Variables

16:40 Program Indicators

23:30 Questions

##### (Video) Data Quality in Tracker Programs

### (Video) Data Quality in Tracker Programs

[https://www.youtube.com/watch?v=oO4OkCSkyuA](https://www.youtube.com/watch?v=oO4OkCSkyuA)

##### Data Quality in Tracker Programs - Video Download

### Data Quality in Tracker Programs - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/4.2.1+Data+Quality+in+Tracker+Programs_.mp4

You can find the PDF of the presentation here: <https://drive.google.com/file/d/1yqU8FqKgSAo4QD0fR_UNW7Rg2qpuW1AB/view?usp=sharing

##### Exercise - Data Quality in Tracker Programs - Graded Exercise

### Exercise - Data Quality in Tracker Programs - Graded Exercise

This exercise is a **graded exercise** and contains two questions. You have **two** attempts at each question. Once you have selected your answers, select the submit button to confirm that you are ready to submit your response. You can return to this page later on if you want to refresh yourself on the material.

### Question 1

0.0/1.0 point (graded)

Which is a common issue with data quality checks in Tracker?

Select all that apply. (2 attempts)

1. **Complex data entry with little or no workflow support**

2. **Calculating coverage based upon only tracker data**

3. **Calculating completeness from individual patient data**

Feedback: **All options are correct.**

### Question 2

0.0/1.0 point (graded)

Which statement(s) below are correct about program rules?

Select all that apply. (2 attempts)

Program rules:

1. **Allow the interaction with the user based on input.**

2. **Allow you to create and control dynamic behavior of the user interface in the Tracker Capture and Capture apps.**

3. **Expressions are evaluated each time the user interface is displayed and each time a data element is changed.**

Feedback: **All options are correct.**

## 4.3 Feedback survey (2 min)

#### Feedback survey (2 min)

Once you are done with the module, please take 2 or 3 minutes to complete this feedback survey. Your careful response will have a real impact on how courses like this are run. Thank you!

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSeDJAVT9jHNEd9cURMu5v94okAbjIniTJq35Y0Iwtqyuzhd2w/viewform?embedded=true" width="100%" height="1239" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe
