
# Module 6: Configuring the WHO Data Quality Tool (2h 15 min)

## 6.0 - Overview of the module (5 min)

#### 6.0.1 - What’s In This Module? (5 min)

##### 6.0.1 - What’s In This Module?

### 6.0.1 - What’s In This Module?

Now that you’ve got a good understanding of data quality, as well as how some of the tools work in DHIS2, how do you set up your DHIS2 instance to facilitate good data quality?

In this Module, Bob Pond will walk you through **how to install and configure the WHO Data Quality Tool** (WHO DQ Tool). You’ll learn how to **configure the different types of numerators and parameters** you’ll need to set up to start analysing data quality in the WHO Data Quality Tool. You’ll also look at some of the **key considerations** you’ll need to make when configuring the app in relation to common challenges.

### Learning objectives

By the end of this Module, you will be able to:

- Install the WHO Data Quality Tool

- Map reference numerators

- Configure numerators

- Identify Numerator Relations

- Identify Numerator quality parameters

- Recognise key considerations for configuring the WHO Data Quality Tool

### How will you be evaluated?

After each video, you will find graded questions. In total, these questions contribute 10% of your grade for this course.

At the of the Module there is an ungraded activity-based exercise that will allow you to set up and configure the WHO Data Quality Tool in a DHIS2 training instance. Although this exercise is not graded, we recommend you complete it to improve your comprehension of the tool.

### How long will this module take?

This module will take about 2 hours and 15 minutes to complete.

##### 6.0.2 Account Creation - DQ App Configuration

### 6.0.2 Account Creation - DQ App Configuration

### Instructions - Account Creation on DQ App Configuration

In order to perform the exercises and assignments within Module 6, you will be accessing the **Data Quality App Config** training instance. The **DQ App Config** training instance has been set up to allow each person who logs in to configure the WHO data quality tool/app. The account you create will have limited access to the apps within DHIS2, only including the apps referenced in the screenshot below.

<img src="/static/image18.png" style="width:7.53125in;height:4.80208in" alt="DQ Config Apps">

Upon first accessing the WHO Data Quality Tool in this system, you will receive the following warning message

<img src="/static/image19.png" style="width:6.09375in;height:2.28125in" alt="DQ Config Apps">

Do not be alarmed by this message, as this system has been set up for each participant to have access to a clean configuration of the WHO Data Quality Tool. Dismiss it by selecting "OK" and proceed with your exercises.

Please create an account for the ***Data Quality App Config*** training instance by following the instructions below.

### Account Creation Walkthrough

In order to create your account on the DQ app config training instance, start the process by clicking on the “Request account” button in the Account Creation section below. **You only need to click the button once**, otherwise you will receive multiple account request emails.

<img src="/static/image3.png" style="width:5.33333in;height:1.52083in" alt="alternatetext">

After a few moments, you should receive the following notification in your browser window:

<img src="/static/image4.png" style="width:4.57292in;height:1.28125in" alt="alternatetext">

Click on OK to close the notification.

Login to your email. You should receive an email subject that looks like the following:

<img src="/static/image20.png" style="width:5.33333in;height:0.79167in">

You should see in the email subject that the DHIS2 system that has been identified is the Data Quality App Config training instance.

**For note:**this email may be in your junk folder. If you do not see it in one of your primary inboxes, please check your junk folder in case it was filtered out.

The email itself should look like the email below:

<img src="/static/image21.png" style="width:5.33333in;height:3in" alt="alternatetext">

In order to continue, click on the highlighted link or copy and paste it into a new tab in your browser. This link will take you to the following page:

<img src="/static/image7.png" style="width:5.33333in;height:4.32292in" alt="alternatetext">

Your email details will have already been filled in from your student account on the Online Academy platform. You will need to fill in the remaining fields.

Take note of the restrictions on the password, and follow **good password practice.** Your password must:

- Be at least 8 characters long

- Include an uppercase letter

- Include 1 number/digit

- Include a special character

After filling in all the fields, select “Create” to proceed.

<img src="/static/image8.png" style="width:5.33333in;height:4.03125in" alt="alternatetext">

This should log you in to the DHIS2 DQ App Config training instance where you can view the dashboard along with the relevant apps you have access to.

<img src="/static/image9.png" style="width:5.33333in;height:2.42708in" alt="alternatetext">

From here, please follow activity instructions for any activities or assignments that are referring you to the DHIS2 DQ App Config system.

### Account Creation

Click the "Request account" button below to request an account on the DHIS2 DQ App Configuration system.

You will receive an invitation by email with instructions on how to complete the registration in DHIS2.

*Note: the email address you use with the DHIS2 Online Academy will be sent to the DHIS2 database to create an account.*

## 6.1 - Configuring the WHO Data Quality Tool (1h 45 min)

#### 6.1.0 Resources (5 min)

##### 6.1.0 Resources

### 6.1.0 Resources

As you make your way through the following section, you may want to refer to the DHIS2 documentation. The full guide on how to configure the WHO Data Quality Tool is available here: [How to configure the WHO Data Quality Tool](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_configure_the_WHO_Data_Quality_Tool_11_June_2020.docx).

#### 6.1.1 Demo - WHO DQ Tool Installation (5 min)

##### 6.1.1 Demo - WHO DQ Tool Installation

### 6.1.1 Demo - WHO DQ Tool Installation

In this video, Bob Pond will walk you through how to install the WHO Data Quality Tool on your DHIS2 instance. This is also applicable to reinstalling the tool for software updates.

*Note: The DHIS2 training instances used in this course already have the WHO DQ Tool application installed. In Module 6.2, you will have the opportunity to practice configuring this tool in a training environment. Please check with your administrator before attempting to install this app on your own DHIS2 instance if you are not the administrator of your system.*

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Installing the WHO DQ Tool

### (Video) - Installing the WHO DQ Tool

[https://www.youtube.com/watch?v=njhXbuVuJX0](https://www.youtube.com/watch?v=njhXbuVuJX0)

##### Demo - WHO DQ Tool Installation - Video Download

### Demo - WHO DQ Tool Installation - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/6.1.1+-+Demo+-+WHO+DQ+App+Installation.mp4

You can download the guide on how this was presented here: [How to install the WHO DQ Tool](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_Configure_-_Part_1_-_Install_the_App.docx).

#### 6.1.2 Demo - Mapping Reference Numerators (20 min)

##### 6.1.2 Demo - Mapping Reference Numerators

### 6.1.2 Demo - Mapping Reference Numerators

In this video, Bob will show you how to configure the WHO Data Quality Tool. You’ll start by looking at how the base Numerators appear in the dashboard, and then how to configure them.

This demonstration will discuss how we can **map reference numerators** when we configure the WHO Data Quality Tool. This determines which the default numerators we are able to interact with when viewing dashboards and running the annual report.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Mapping Reference Numerators

### (Video) - Mapping Reference Numerators

[https://www.youtube.com/watch?v=O1anc58h4Qw](https://www.youtube.com/watch?v=O1anc58h4Qw)

##### 6.1.2 - Demo - Mapping Reference Numerators - Video Download

### 6.1.2 - Demo - Mapping Reference Numerators - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/6.1.2+-+Demo+-+Mapping+Reference+Numerators+.mp4

You can download the guide on how this was presented here: [Mapping reference numerators](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_Configure_-_Part_2_-_Mapping_Reference_Numerators.docx).

##### Graded question - Mapping Reference Numerators - Question 1

### Graded question - Mapping Reference Numerators - Question 1

1 point possible (graded)

To be able to edit the WHO Data Quality tool you need to have what authority associated with your user role in DHIS2?

Select the **one** correct answer: (2 attempts)

1. Only basic data entry

2. **Edit indicators**

3. Only data visualization

4. User management

Feedback: Edit Indicators is correct.

##### Graded question - Mapping Reference Numerators - Question 2

### Graded question - Mapping Reference Numerators - Question 2

By ticking the "core" check box when assigning a data element to a numerator you are doing what? Select the correct answer (1 attempt)

1. **Placing that data element into the "core" data group that can be selected for analysis.**

2. Marking the data element for follow-up by a system administrator

Feedback: Placing that data element into the "core" data group that can be selected for analysis is correct.

#### 6.1.3 - Demo - Configuring Numerator Groups (10 min)

##### 6.1.3 - Demo - Configuring Numerator Groups

### 6.1.3 - Demo - Configuring Numerator Groups

In this video, Bob Pond will continue the discussion on mapping reference numerators, this time focusing on how you can configure numerator groups. In addition, Bob looks at how you can add additional numerator groups that are not available by default.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Configuring Numerator Groups

### (Video) - Configuring Numerator Groups

[https://www.youtube.com/watch?v=xO4oVAMDGV8](https://www.youtube.com/watch?v=xO4oVAMDGV8)

##### 6.1.3 - Demo - Configuring Numerator Groups - Video Download

### 6.1.3 - Demo - Configuring Numerator Groups - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/6.1.3+-+Demo+-+Configuring+Numerator+Groups.mp4

You can download the guide on how this was presented here: [Mapping Reference Numerators and Configuring Numerator Groups.](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_Configure_-_Part_3_-_Reference_Numerators_Adding_Numerator_Groups.docx)

##### Graded question - Configuring Numerator Groups - Question 1

### Graded question - Configuring Numerator Groups - Question 1

1 point possible (graded)

Where is it possible to add a new indicator group for analysis?

Select the one correct answer: (2 attempts)

1. Nowhere. It is only used for meta-data administration

2. Only in the Annual Report

3. **In the WHO DQ tool dashboard where that group can be selected**

4. Both in the WHO DQ dashboard and the standard DHIS2 dashboard app

Feedback: In the WHO DQ tool dashboard where that group can be selected is the correct answer.

#### 6.1.4 - Demo - Considerations when Configuring the WHO DQ Tool (20 min)

##### 6.1.4 - Demo - Considerations when Configuring the WHO DQ Tool

### 6.1.4 - Demo - Considerations when Configuring the WHO DQ Tool

In this video, Bob and Shurajit look at some of the key considerations to take into account when configuring the WHO Data Quality Tool, focusing in particular on 7 different challenges that can occur when configuring the WHO DQ Tool.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

### Video Bookmarks

00:00 Introduction & Challenge #1 - Long lists of data elements and indicators

6:42 Challenge #2 - Numerator-only indicators

8:13 Challenge #3 - Incorrectly defined data elements and indicators

9:31 Challenges #4 - No data set for important numerators

12:26 Challenge #5 - Selecting between similar named data elements and indicators

14:15 Challenge #6 - The best available data element may be imperfect

16:15 Challenge #7 - DHIS2 may not be reliably reflect completeness of imported data sets

##### Video - Considerations when Configuring the WHO DQ Tool

### Video - Considerations when Configuring the WHO DQ Tool

[https://www.youtube.com/watch?v=pZiUc4Ivm90](https://www.youtube.com/watch?v=pZiUc4Ivm90)

##### 6.1.4 - Demo - Considerations when Configuring the WHO DQ Tool - Video Download

### 6.1.4 - Demo - Considerations when Configuring the WHO DQ Tool - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/6.1.4+-+Demo+-+Considerations+when+Configuring+the+WHO+DQ+Tool+.mp4

You can download the presentation for this session here: Considerations when configuring the [WHO Data Quality Tool](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_Configure_-_Part_4_-_Presentation.pptx).

##### Graded question - Considerations when Configuring the WHO DQ Tool - Question 1

### Graded question - Considerations when Configuring the WHO DQ Tool - Question 1

1 point possible (graded)

A data element must be in what for it to be able to be found when configuring the WHO DQ tool.

Select the one correct answer: (2 attempts)

1. Data set

2. **Data element group**

3. Indicator

4. Category combination

Feedback: Data Element Group is correct.

##### Graded question - Considerations when Configuring the WHO DQ Tool - Question 2

### Graded question - Considerations when Configuring the WHO DQ Tool - Question 2

1 point possible (graded)

True or False: It is important to use data elements with as high reporting rate/completeness as you can when configuring the WHO DQ tool.

Select the one correct answer: (1 attempt)

1. **True**

2. False

Feedback: True is correct

#### 6.1.5 - Demo - Numerator Relations (15 min)

##### 6.1.5 - Demo - Numerator Relations

### 6.1.5 - Demo - Numerator Relations

In this video, Bob will look at how to configure **numerator relations** within the WHO data quality tool.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Numerator Relations

### (Video) - Numerator Relations

[https://www.youtube.com/watch?v=SXly8-ThyYw](https://www.youtube.com/watch?v=SXly8-ThyYw)

##### 6.1.5 - Demo - Numerator Relations - Video Download

### 6.1.5 - Demo - Numerator Relations - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/6.1.5+-+Demo+-+Numerator+Relations.mp4

You can download the guide on how this session was presented here: [Configuring numerator relations](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_Configure_-_Part_5_-_Numerator_relations.docx).

##### Graded question - Numerator Relations - Question 1

### Graded question - Numerator Relations - Question 1

1 point possible (graded)

Numerator relations appear where on the WHO DQ tool dashboard?

Select the one correct answer: (2 attempts)

1. The Completeness tab

2. The Consistency - Time Tab

3. **The Consistency - Data Tab**

4. The Outliers Tab

Feedback: The Consistency - Data Tab is correct.

##### Graded question - Numerator Relations - Question 2

### Graded question - Numerator Relations - Question 2

1 point possible (graded)

If you already have some core numerators, the WHO DQ Tool will automatically do what?

Select the one correct answer: (2 attempts)

1. Run DQ analysis

2. **Configure some numerator relationships based upon WHO standards**

3. Complete all other configuration

4. Nothing

Feedback: Configure some numerator relationships based upon WHO standards is correct.

#### 6.1.6 - Demo - Numerator Quality Parameters (20 min)

##### 6.1.6 - Demo - Numerator Quality Parameters

### 6.1.6 - Demo - Numerator Quality Parameters

In this video, Bob will show you how to configure **numerator quality parameters** within the WHO data quality tool.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Numerator Quality Parameters

### (Video) - Numerator Quality Parameters

[https://www.youtube.com/watch?v=dzxKvWPLnts](https://www.youtube.com/watch?v=dzxKvWPLnts)

##### 6.1.6 - Demo - Numerator Quality Parameters - Video Download

### 6.1.6 - Demo - Numerator Quality Parameters - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/6.1.6+-+Demo+-+Numerator+Quality+Parameters_.mp4

You can download the guide on how this session was presented here: [Configuring numerator quality parameters](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@How_to_Configure_-_Part_6_-_Numerator_Quality_Parameters.docx).

For a bit more background on what some of the numerator quality parameters do when run using the analysis function, review the presentation here: [Numerator quality parameters and their relationship with the analysis function](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@Explanation_of_Analysis_-_Consistency_Functions_and_Options.pdf).

##### Graded question - Numerator Quality Parameters - Question 1

### Graded question - Numerator Quality Parameters - Question 1

1 point possible (graded)

How can you change the thresholds that are displayed on the WHO DQ tool dashboard Consistency - data tab?

Select the one correct answer: (2 attempts)

1. **Change the value in the numerator relations tab in the administration page**

2. It can not be changed

3. In the dashboard itself

4. In the maintenance app

Feedback: Change the value in the numerator relations tab in the administration page is correct.

##### Graded question - Numerator Quality Parameters - Question 2

### Graded question - Numerator Quality Parameters - Question 2

1 point possible (graded)

"A = B" means what in terms of the configuration of the WHO Data Quality Tool?

Select the one correct answer: (2 attempts)

1. You only want to see indicator from group A and group B

2. It means that indicator A is greater than indicator B

3. **It means that indicator A should be roughly equal to indicator B**

4. It does not mean anything.

Feedback: It means that indicator A should be roughly equal to indicator B is correct.

## 6.2 - Optional Exercise: Configuring the WHO Data Quality Tool - (30 min)

#### 6.2 - Configuring the WHO Data Quality Tool - Exercise (30 min)

##### 6.2 - Configuring the WHO Data Quality Tool - Exercise

### 6.2 - Configuring the WHO Data Quality Tool - Exercise

[DHIS2 Documentation](https://docs.dhis2.org/en/use/optional-apps/who-data-quality-tool/usage-and-interpretation.html)

Building on Module 6.1, where you learned about configuring the WHO Data Quality Tool, this exercise is meant to give you a chance to practice and help reinforce your understanding of how to configure the tool yourself.

This exercise is ungraded, so you do not have to complete it to pass the course. However, we highly recommend that you complete this exercise to improve your understanding of the material.

This activity will be completed in the [DHIS2 DQ App Config](https://academy.dq.dhis2.org/dqapp-config) training instance.

Good Luck!

##### Set Up - Configuring the WHO Data Quality Tool - Exercise

### Set Up - Configuring the WHO Data Quality Tool - Exercise

1. If you have not already created an account for the **Data Quality App Config** training instance, follow the instructions in Module 6.0.2 to create your account

2. When you have created your account, log in to the [Data Quality App Config](https://academy.dq.dhis2.org/dqapp-config) training instance

3. Open the WHO Data Quality Tool from the applications menu.

Work through the material in each of the numbered exercises below. At the end of each section, mark the completion field to indicate you have completed that part of the exercise.

*Note: When trying to configure the denominators in the WHO Data Quality Tool, you may receive a notification saying “the data quality tool has not been configured”. Please ignore this message, and click “OK” on the notification.*

##### Exercise 1 - Configuring the WHO Data Quality Tool - Indicators and Data Elements

### Exercise 1 - Configuring the WHO Data Quality Tool - Indicators and Data Elements

For this exercise, you will need to fill in the following table using the WHO metadata browser app.

|Numerator|(A) Possible data element (DE)/ Indicator (Ind) to map to|(B) Group for each data element or indocator|
|---------|---------------------------------------------------------|--------------------------------------------|
|DPT 1 (Penta)|||
|DPT 3 (Penta 3)|||
|ANC|||

The data elements you are looking for will be located in either the “Immunization” or “ANC” data element groups. This exercise is meant to allow you to map some of the default numerators that are within the Data Quality tool to the names within a specific configuration.

As an example, the default name for the number of Measles 1 doses given in the data quality tool is MCV 1.

<img src="/static/image22.png" style="width:9in;height:1.38889in">

If you explore the data elements available within the metadata browser we will not see any data element named “MCV 1”; however, you will see a data element called “Measles 1 vaccine given.”

<img src="/static/image23.png" style="width:9in;height:3.26389in">

This type of mapping is generally necessary between the default values of the data quality tool and the names either in the example system being used here, or your own system if the names are not the same as the default values within the DQ tool. The data element or indicator groups is also important, as the DQ tool has a limitation that does not allow it to map any metadata that is not part of a group.

An example of the table for MCV 1 has been filled for your reference.

|Numerator|(A) Possible data element (DE)/ Indicator (Ind) to map to|(B) Group for each data element or indocator|
|---------|---------------------------------------------------------|--------------------------------------------|
|MCV 1|Measles 1 vaccine given|Immunization|

Once you have completed the table, follow the instructions below:

1. Return to the Numerators page of the Tool (launch the Tool, then click on “More,” then click on “Administration”).

2. . For each of the first 3 numerators in your table from Exercise 1, click on “Edit,” complete the configuration and save.

##### Exercise 1 - Configuring the WHO Data Quality Tool - Completion

### Exercise 1 - Configuring the WHO Data Quality Tool - Completion

1 point possible (ungraded)

I have completed Exercise 1

1. **Yes**

2. No

##### Exercise 2 - Configuring the WHO Data Quality Tool - Configuring Numerator relations

### Exercise 2 - Configuring the WHO Data Quality Tool - Configuring Numerator relations

From the “Numerator relations” page, configure the following relations:

a. DPT 1 to DPT 3 dropout rate

b. ANC 1 – DPT 1 ratio; A = B; Threshold = 10%

c. If time permits, you should also configure one other relation of your choice. Remember that you will not be able to save a “Numerator relation” unless Numerator A and Numerator B have both already been mapped.

##### Exercise 2 - Configuring the WHO Data Quality Tool - Configuring Numerator relations - Completion

### Exercise 2 - Configuring the WHO Data Quality Tool - Configuring Numerator relations - Completion

1 point possible (ungraded)

I have completed Exercise 2

1. **Yes**

2. No

## 6.3 Feedback survey (2 min)

#### Feedback survey (2 min)

Once you are done with the module, please take 2 or 3 minutes to complete this feedback survey. Your careful response will have a real impact on how courses like this are run. Thank you!

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSd2gk1F6LLxY6xwKs5aWvYeXzuBEIk6kE8JoGDiH7twnv6ehg/viewform?embedded=true" width="100%" height="1623" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe
