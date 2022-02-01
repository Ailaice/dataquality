
# Module 5: DHIS2 Design for Data Quality (4h)

## 5.0 - Overview of the module (5 min)

#### 5.0.1 - What’s In This Module? (5 min)

##### 5.0.1 - What’s In This Module?

### 5.0.1 - What’s In This Module?

Small design decisions can drastically impact how we interact with different systems. So, how does the design of DHIS2 impact how you capture data? How does it impact the quality of your data?

In this module, Shurajit Dutta will look at **how DHIS2 System Design impacts Data Quality.** He’ll walk you through how to design and customize DHIS2 to facilitate Data Quality. Through a series of videos, Shurajit will teach you **how to set up your DHIS2 system to avoid bad data capture**, which can significantly impact data quality. You’ll learn some **best practices for managing different data dimensions**, and be able to identify **how manual review processes can contribute to DHIS2 system design review.**

### Learning objectives

By the end of this module you will be able to:

- Review data capture forms design to avoid duplicate variables

- Identify procedural challenges associated with managing metadata

- Distinguish data element value types

- Identify best practices for managing data dimensions and duplicate data elements, and data set design

- Describe General Maintenance Challenges and Organisation Unit Management's Effect on Data Quality

- Describe the link between user management and data access, and challenges with sharing

- Identify how manual review processes can contribute to DHIS2 system design review

- Identify the key principles used for naming indicators and data elements and apply them.

- Identify how SQL scripts can be used to support assessments of DHIS2 system design

### How will you be evaluated?

You will find 1-3 graded questions after each video. You will have 1 or 2 attempts to submit each question. Overall, all the assessments in this module contribute 15% to your final grade.

### How long will this module take?

This module will take about 4 hours to complete.

## 5.1 - Form Design Issues (25 min)

#### 5.1.1 - Poor Form Source Design (10 min)

##### 5.1.1 - Poor Form Source Design

### 5.1.1 - Poor Form Source Design

In this video, Shurajit will look at some of the inputs of DHIS2, and how it can affect Data Quality. You’ll look at form design, and some of the irrelevant criteria that shouldn’t be collected in a source form.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Poor Form Source Design

### (Video) - Poor Form Source Design

[https://www.youtube.com/watch?v=KDwxOa2ILns](https://www.youtube.com/watch?v=KDwxOa2ILns)

##### Poor Form Source Design - Video Download

### Poor Form Source Design - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.1.1+-+Intro+_+Poor+Form+Source+Design.mp4

##### Graded question - Poor Form Source Design

### Graded question - Poor Form Source Design

<img src="/static/image15.png" style="width:9in;height:3.76389in">

1 point possible (graded)

What is the main issue identified in the above form? (2 attempts)

1. There are too many age disaggregations.

2. **There should not be any sex disaggregations.**

3. The data elements are sequenced poorly.

Feedback: The main issue in this form is B, because **You do not need to collect any information on males related to these services.** We cannot say that there are too many age disaggregations because this is subjective and they may need this information to accurately measure adolescent pregnancy. Although data elements might be sequenced poorly, that is not the main problem with this form.

#### 5.1.2 - Incorrect Disaggregations & Duplication of Variables (15 min)

##### 5.1.2 - Incorrect Disaggregations & Duplication of Variables

### 5.1.2 - Incorrect Disaggregations & Duplication of Variables

In this video, you will continue to look at form design. Shurajit will start by showing you incorrect disaggregations. Then, you’ll look at Duplicate variables within the same form, and then both duplicate variables across different forms between different programs, as well as duplicate variables across different forms in the same program.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Incorrect Disaggregations & Duplication of Variables

### (Video) - Incorrect Disaggregations & Duplication of Variables

[https://www.youtube.com/watch?v=lC9NiQ6WSyo](https://www.youtube.com/watch?v=lC9NiQ6WSyo)

##### 5.1.2 - Incorrect Disaggregations & Duplication of variables - Video Download

### 5.1.2 - Incorrect Disaggregations & Duplication of variables- Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.1.2+-+Disaggregations+_+Duplication.mp4

##### Graded question - Incorrect Disaggregations & Duplication of variables - Question 1

### Graded question- Incorrect Disaggregations & Duplication of variables - Question 1

<img src="/static/image16.png" style="width:9in;height:3.51389in">

1 point possible (graded)

What is the main issue that has the highest impact on data quality with the above form? (2 attempts)

1. Clinical cases should not be grouped with testing and results.

2. The disaggregations are using a mix of months and years.

3. **Pregnant Women is a subset of 15 years+.**

**Feedback: Option C has the largest impact on data quality because totals will be incorrect for each data element.** Regarding disaggregations using a mix of months and years, as well as Clinical cases should not be grouped with testing and results, both may be a formatting issue, but is less likely to have a direct impact on data quality.

##### Graded question - Incorrect Disaggregations & Duplication of variables - Question 2

### Graded question- Incorrect Disaggregations & Duplication of variables - Question 2

<img src="/static/image17.png" style="width:9in;height:4.05556in">

1 point possible (graded)

The above results have been tallied from two different datasets within the HIV program. What is the main issue that has the highest impact on data quality that has been highlighted by these tallies? (2 attempts)

1. There have been no disaggregations applied to these tallies to identify source values

2. **The data elements being collected within the program are the same across different data sets. There are now different values being reported.**

3. Comparing these tallies is not possible

Feedback: The data quality issue is that the data elements collected within the program are the same across different data sets which makes that different values are being reported. Disaggregations can be applied a la later time when issues with the total are first verified. Regarding option C, there is no reason tallies can’t be compared.

## 5.2 - Customization Challenges (1h 30 min)

#### 5.2.1 - Procedural Challenges (15 min)

##### 5.2.1 - Procedural Challenges

### 5.2.1 - Procedural Challenges

In this video, Shurajit will introduce you to some of the design decisions made with DHIS2 and the impact they have had on Data Quality, focusing on procedural challenges associated with DHIS2 systems design.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Procedural Challenges

### (Video) - Procedural Challenges

[https://www.youtube.com/watch?v=zKnWS-MRE0g](https://www.youtube.com/watch?v=zKnWS-MRE0g)

##### Procedural Challenges - Video Download

### Procedural Challenges - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.2.1+-+Intro+and+Procedural+Challenges.mp4

##### Additional Resources

### Download additional resources

You can get more information about procedural challenges in the following links:

- [Download the example SOP](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@New_Metadata_SOP_Data_Elements__Category_Options_Category_CoCs.docx)

- [Download an extended version of the SOP](https://studio.academy.dhis2.org/assets/courseware/v1/f19f5d53bb0dfbfb55a499765febf707/asset-v1:DHIS2+DHIS2_DQL2O+2021_Q1-4+type@asset+block/New_Metadata_SOP_Data_Elements__Category_Options_Category_CoCs_Extended.docx)

- Reference : [The correct way to create category combos](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@The_correct_way_to_create_category_combos___jason-p-pickering_zambiahmis_Wiki.pdf) <https://drive.google.com/file/d/13LF70BkUC2XK9v4-vmFiHfisbhVbKeZN/view?usp=sharing

##### Graded question - Procedural Challenges - Question 1

### Graded question - Procedural Challenges - Question 1

1 point possible (graded)

What is a potential challenge with configuration of a WHO metadata package? (2 attempts)

1. **It may result in the creation of duplicate metadata**.

2. It can cause a number of saved outputs to display incorrectly.

3. It will result in data sets being modified directly.

Feedback: Configuring a WHO metadata package may result in the creation of duplicate metadata. In this case, you have to also factor in how you handle updates to the packages. Management of this legacy metadata along with the new metadata becomes a key consideration. It would not cause an incorrect display of saved outputs, but it may result in the creation of duplicate analytical outputs. Data sets can be modified only if specified.

##### Graded question - Procedural Challenges - Question 2

### Graded question - Procedural Challenges - Question 2

1 point possible (graded)

Should we ever make large-scale untested metadata changes on a live production server? (1 attempt)

1. Yes

2. **No**

Feedback: No. This is highly unrecommended practice.

#### 5.2.2 - Numerical Value Types (15 min)

##### 5.2.2 - Numerical Value Types

### 5.2.2 - Numerical Value Types

In this video, Shurajit will walk you through the different numerical data element value types that exist in DHIS2. You’ll also be shown how to identify the most appropriate data element value type that can be used in most cases.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Numerical Value Types

### (Video) - Numerical Value Types

[https://www.youtube.com/watch?v=Ox6PVhlR-XE](https://www.youtube.com/watch?v=Ox6PVhlR-XE)

##### Numerical Value Types - Video Download

### Numerical Value Types - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.2.2+-+Numerical+Value+Types.mp4

##### Knowledge Check - Numerical Value Types

### Knowledge Check - Numerical Value Types

[DHIS2 DQ Metadata](https://academy.dq.dhis2.org/metadata)

Now that you have watched the Numerical Value Types video, you will now need to work through a short exercise to test your knowledge. You will need to complete this exercise in the DHIS2 DQ Metadata training instance, using the username and password shown on the login screen.

Good Luck!

##### Set Up - Numerical Value Types ungraded exercise

### Set Up - Numerical Value Types ungraded exercise

1. Log in to the [DHIS2 DQ Metadata](https://academy.dq.dhis2.org/metadata) training instance.

2. Navigate to **Maintenance**, and then select **Data Element**s.

3. Place a filter on the data elements for the data element and value type.

4. Change the data element type to "Aggregate" and the value type to "Number."

Review the data elements that appear after you filter them. Are they appropriate based on what needs to be collected?

(Poll tool)

- Yes

- No

[Survey](https://docs.google.com/forms/d/e/1FAIpQLSfGZ507H2uXsugN8zj_X9SEkvpe9LRcCn09JdfiZjkZggLwzw/viewform?usp=sf_link): <https://docs.google.com/forms/d/e/1FAIpQLSfGZ507H2uXsugN8zj_X9SEkvpe9LRcCn09JdfiZjkZggLwzw/viewform?usp=sf_link

After you have reviewed "Number" change the filter to "Positive or Zero Integer." What do you notice when you perform this filter?

text field

Based on your brief assessment, what would you think needs to be changed?

text field

#### 5.2.3 - Historical Data (15 min)

##### 5.2.3 - Historical Data

### 5.2.3 - Historical Data

In this video, Shurajit will show you how to approach, identify and manage historical data, including dealing with changes to disaggregations and managing completeness.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Historical Data

### (Video) - Historical Data

[https://www.youtube.com/watch?v=k3xMlAxHRno](https://www.youtube.com/watch?v=k3xMlAxHRno)

##### 5.2.3 - Historical Data - Video Download

### 5.2.3 - Historical Data - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.2.3+-+Historical+Data.mp4

##### Graded question - Historical Data

### Graded question - Historical Data

1 point possible (graded)

We can use the category combo override function to… (2 attempts)

1. Delete category combinations.

2. **Re-use data elements that have disaggregations changed due to form updates.**

3. Move data from one category combination to another.

Feedback: We can use the category combo override function to reuse data elements that have disaggregations changed due to form updates. This allows us to see historical data trends as far back as there is data for a data element. Unfortunately, there is no easy way to move data from one category combination to another, and we cannot delete category combinations with this function.

#### 5.2.4 - Managing Duplicate Category Options (10 min)

##### 5.2.4 - Managing Duplicate Category Options

### 5.2.4 - Managing Duplicate Category Options

In this video, Shurajit will walk you through category options within DHIS2 and how they can impact Data Quality. First, you’ll look at the impact of duplicate category options. Then, you’ll learn how category option groups and group sets can be used to hide duplicate category options from users.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Managing Duplicate Category Options

### (Video) - Managing Duplicate Category Options

[https://www.youtube.com/watch?v=sx0W5fo5Js0](https://www.youtube.com/watch?v=sx0W5fo5Js0)

##### Managing Duplicate Category Options - Video Download

### Managing Duplicate Category Options - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.2.4+-+Managing+Duplicate+Category+Options.mp4

##### Graded question - Managing Duplicate Category Options

### Graded question - Managing Duplicate Category Options

1 point possible (graded)

Category option groups and group sets allow us to… (2 attempts)

1. Entirely collapse duplicate category options and fix the underlying problem by merging data from these two items

2. Deal with repeated category option combinations resulting from the same category option

3. **Hide the problem of 2 or more category options from the user by creating a shared dimension for them in analytics apps**

**Feedback:** Category option groups and group set allows us to hide the problem of 2 or more category options from the user by creating a shared dimension for them in analytics apps. We can at least hide the problem from the user to increase the quality of data outputs. The underlying problem may need to be fixed over time depending on its severity. Option A “**Entirely collapse duplicate category options and fix the underlying problem by merging data from these two items”** is incorrect because you will still have two separate category options in your system. Option B “**Deal with repeated category option combinations resulting from the same category option”** is ok in some cases, as the same category option may be used in multiple category combinations.

#### 5.2.5 - Data Dimensions & Duplicate Data Elements (10 min)

##### 5.2.5 - Data Dimensions & Duplicate Data Elements

### 5.2.5 - Data Dimensions & Duplicate Data Elements

In this video, Shurajit will look at Data Dimensions in DHIS2. You’ll look at how to identify duplicate data elements, as well as taking a look at some of the best practices for managing data dimensions.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Data Dimensions & Duplicate Data Elements

### (Video) - Data Dimensions & Duplicate Data Elements

[https://www.youtube.com/watch?v=kAobkYOjcwM](https://www.youtube.com/watch?v=kAobkYOjcwM)

##### Data Dimensions & Duplicate Data Elements - Video Download

### Data Dimensions & Duplicate Data Elements - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.2.5+-+Data+Dimensions+_+Duplicate+Data+Elements.mp4

##### Graded question - Data Dimensions & Duplicate Data Elements

### Graded question - Data Dimensions & Duplicate Data Elements

1 point possible (graded)

What is the problem with having too many data dimensions? (2 attempts)

1. **It will be very challenging for users to find the dimensions they need to perform analysis on their data**

2. It will result in disaggregations behaving incorrectly when summing data

3. You will be unable to keep track of managing these data dimensions over time

Feedback: The problem with having too many data dimensions is “It will be very challenging for users to find the dimensions they need to perform analysis on their data”, therefore option A is correct. In order to control this, create some procedures and training on this limitation! Option B “It will result in disaggregations behaving incorrectly when summing data” is incorrect because this should not be the case if the system is functioning well. Option C “You will be unable to keep track of managing these data dimensions over time, is also incorrect because this is possible, but remember to create a good data dictionary!

#### 5.2.6 - Data Set Design (15 min)

##### 5.2.6 - Data Set Design

### 5.2.6 - Data Set Design

In this video, Shurajit looks at Data Set Design, and how you can control the data set inputs for Data Quality. You’ll start by looking at the functionality you can use to control what can be entered into a data set. You’ll then look at the best practices for data set design.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Data Set Design

### (Video) - Data Set Design

[https://www.youtube.com/watch?v=F8TlY2BcCSo](https://www.youtube.com/watch?v=F8TlY2BcCSo)

##### Data Set Design - Video Download

### Data Set Design - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.2.6+-+Data+Set+Design.mp4

##### Graded question - Data Set Design - Question 1

### Graded question- Data Set Design - Question 1

1 point possible (graded)

What is one method we can use to control which data elements can have data entered in them that is not available on a paper/source form? (2 attempts)

1. Validation Rules

2. Section Form

3. **Grey Cells**

**Feedback: Grey cells can be used to easily block data elements or disaggregations from being entered.** Validation rules can be used to check data, but can not be used to block a single data element from being entered. Section forms are a type of form we can make, they do not control what can be entered

##### Graded question - Data Set Design - Question 1

### Graded question- Data Set Design - Question 2

1 point possible (graded)

We must always follow a forms source design without making recommendations on how it will affect data quality, use and the DHIS2 data model? (1 attempt)

1. True

2. **False**

Feedback: We can be more careful with how we implement tools into DHIS2 to make sure it does not result in poor usability and data quality. This can often be done without changes being made to the source form design.

## 5.3 - Maintenance App Challenges (30 min)

#### 5.3.1 - General Challenges & Organisation Unit Management (15 min)

##### 5.3.1 - General Challenges & Organisation Unit Management

### 5.3.1 - General Challenges & Organisation Unit Management

In this video, Shurajit looks at some of the General Maintenance Challenges that exist in DHIS2 and how they can impact Data Quality, beginning with the impact of Organisation Unit management.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - General Challenges & Organisation Unit Management

### (Video) - General Challenges & Organisation Unit Management

[https://www.youtube.com/watch?v=ej05pG4l54k](https://www.youtube.com/watch?v=ej05pG4l54k)

##### 5.3.1 - General Challenges & Organisation Unit Management - Video Download

### 5.3.1 - General Challenges & Organisation Unit Management - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.3.1+-+General+Challenges+_+Organisation+Unit+Management.mp4

##### Graded question - General Challenges & Organisation Unit Management - Question 1

### Graded question - General Challenges & Organisation Unit Management - Question 1

1 point possible (graded)

What are some general maintenance challenges that are limitations within DHIS2? (2 attempts)

Select all that apply

1. Hiding duplicate category options

2. **Deleting metadata due to dependencies**

3. **Making batch changes**

4. **Nested searches for specific items**

**Feedback:** Correct options are B, C, and D. Deleting metadata is difficult and there is often little feedback on what is happening. The maintenance app is currently not well suited to make large batch changes. Nested searches for specific items is correct because we can not find all data elements within a tracker program easily for example. Option A is incorrect because we can use category option groups and group sets to hide this, even if we can't solve the underlying problem immediately.

##### Graded question- General Challenges & Organisation Unit Management - Question 2

### Graded question - General Challenges & Organisation Unit Management - Question 2

1 point possible (graded)

Organisation unit management has a direct effect on data quality and use? (1 attempt)

1. **True**

2. False

Feedback: This is a critical function as it directly impacts completeness and what types of organisation unit group sets are available to disaggregate data.

#### 5.3.2 - User Management & Sharing (15 min)

##### 5.3.2 - User Management & Sharing

### 5.3.2 - User Management & Sharing

In this video, Shurajit will continue looking at general maintenance challenges, focussing on User Management issues. You’ll look at the link between user management and data access, as well as challenges with sharing.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

### Additional materials

- [Download an example procedure on user creation](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@Users_SOP_V2.docx)

- [Download a second example procedure on user creation with more detail](https://studio.academy.dhis2.org/assets/courseware/v1/cb540fc90d8fe37109de1f4fe0cacdae/asset-v1:DHIS2+DHIS2_DQL2O+2021_Q1-4+type@asset+block/Users_SOP_Extended.docx)

##### (Video) - User Management & Sharing

### (Video) - User Management & Sharing

[https://www.youtube.com/watch?v=XXlpH7_d6d0](https://www.youtube.com/watch?v=XXlpH7_d6d0)

##### User Management & Sharing - Video Download

### User Management & Sharing - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.3.2+-+User+Management+_+Sharing.mp4

## 5.4 - Functions to Assess Database Design (1h)

#### 5.4.1 - Manual Metadata Review (10 min)

##### 5.4.1 - Manual Metadata Review

### 5.4.1 - Manual Metadata Review

In this video, Shurajit will present an overview of how manual review processes can contribute to a DHIS2 system design review to improve Data Quality.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Manual Metadata Review

### (Video) - Manual Metadata Review

[https://www.youtube.com/watch?v=xQvAdmcm_DA](https://www.youtube.com/watch?v=xQvAdmcm_DA)

##### 5.4.1 - Manual Metadata Review - Video Download

### 5.4.1 - Manual Metadata Review - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.4.1+-+Manual+Metadata+Review.mp4

##### Graded question - Manual Metadata Review

### Graded question - Manual Metadata Review

1 point possible (graded)

Fill in the remainder of the statement. "Manual Metadata Review… (2 attempts)

1. Is not necessary as metadata review can be fully automated

2. **Can be time consuming but often can result in significant usability improvements**

3. Can have a negative effect on data quality

Feedback: Option B is correct. Manual Metadata Review c**an be time consuming but often can result in significant usability improvements.** This requires detailed knowledge of DHIS2 data models along with inputs from programs etc. regarding metadata that is no longer valid but can be very useful for long term maintenance, data use and data quality. Option A is incorrect because a number of tasks can be automated; however usually some manual review is also required. Option C is incorrect because reviewing the metadata from time to time is always a good practice and should be encouraged.

#### 5.4.2 - Naming Conventions (10 min)

##### 5.4.2 - Naming Conventions

### 5.4.2 - Naming Conventions

In this video, Shurajit will show you how naming conventions can impact Data Quality. You’ll look at some key principles used for naming indicators and data elements, as well as how to apply these naming principles when naming indicators and data elements.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

### Additional materials

- [Download an example on defining naming conventions](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@naming_convention.pdf)

##### (Video) - Naming Conventions

### (Video) - Naming Conventions

[https://www.youtube.com/watch?v=D_r32XEeRtU](https://www.youtube.com/watch?v=D_r32XEeRtU)

##### 5.4.2 - Naming Conventions - Video Download

### 5.4.2 - Naming Conventions - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.4.2+-+Naming+Conventions.mp4

#####

##### Graded question - Naming Conventions - Question 1

### Graded question - Naming Conventions - Question 1

1 point possible (graded)

The text 'Number of' is appropriate at the beginning of a data element name. (1 attempt)

1. True

2. **False**

Feedback: It can be used in the form or in the description, but it is not required in the actual name

##### Graded question - Naming Conventions - Question 2

### Graded question - Naming Conventions - Question 2

1 point possible (graded)

Adding 'Percentage' or '%' at the beginning of an indicator name is best practice. (1 attempt)

1. True

2. **False**

Feedback: This will make sorting in analytics tools challenging. You can add it to the end of the name, for example, Indicator name (%)

#### 5.4.3 - (Meta) Data Integrity Checks (20 min)

##### 5.4.3 - (Meta) Data Integrity Checks

### 5.4.3 - (Meta) Data Integrity Checks

In this video, Shurajit will discuss data integrity checks and how they impact Data Quality. He’ll then show you how to perform a data integrity check in DHIS2.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - (Meta) Data Integrity Checks

### (Video) - (Meta) Data Integrity Checks

[https://www.youtube.com/watch?v=SDwDRhc5ARQ](https://www.youtube.com/watch?v=SDwDRhc5ARQ)

##### 5.4.3 - (Meta) Data Integrity Checks - Video Download

### 5.4.3 - (Meta) Data Integrity Checks - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.4.3+-+(Meta)+Data+Integrity+Checks.mp4

##### Graded Exercise - (Meta) Data Integrity Checks

### Graded Exercise - (Meta) Data Integrity Checks

In this graded exercise, you’ll need to run a data integrity check in DHIS2. You will need to complete this exercise in the [DHIS2 DQ Metadata](https://academy.dq.dhis2.org/metadata) training instance, using the username and password shown on the login screen.

Good Luck!

##### Set-up - Graded Exercise - (Meta) Data Integrity Checks

### Set-up - Graded Exercise - (Meta) Data Integrity Checks

Log in to the [DHIS2 DQ Metadata](https://academy.dq.dhis2.org/metadata) training instance.

To run the data integrity check, open the Data Administration application. Then, select the Data Integrity button and select "Run Integrity Checks."

This may take some time to run. Review the outputs. There are items that can be fixed technically and items that are more process based and need wider inputs from program and system experts.

Survey <https://docs.google.com/forms/d/e/1FAIpQLSc0lC7h6ITr__L930T3FiSbqnGhLYnOvG-9QMiJG2kHDk7peg/viewform?usp=sf_link

Based on what you have found, what might be your next course of action for some of the violations that have been identified?

### Exercise Completion

1 point possible (graded)

I have attempted to run the data integrity check in DHIS2 (1 attempt)

1. **Yes**

2. No

#### 5.4.4 - SQL Scripts (15 min)

##### 5.4.4 - SQL Scripts

### 5.4.4 - SQL Scripts

In this video, Shurajit describes the extended SQL scripts that can be used to support assessments of DHIS2 system design.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

### Additional Materials

[Download the metadata assessment SQL reference file](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@metadataAssessment.sql)

##### (Video) SQL Scripts

### (Video) SQL Scripts

[https://www.youtube.com/watch?v=BsvaFEn6GYQ](https://www.youtube.com/watch?v=BsvaFEn6GYQ)

##### 5.4.4 - SQL Scripts - Video Download

### 5.4.4 - SQL Scripts - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.4.4+-+SQL+Scripts.mp4

##### Optional Exercise - SQL Scripts

### Optional Exercise - SQL Scripts

[Download the metadata assessment SQL reference file](https://studio.academy.dhis2.org/asset-v1:HISP+D2DQ300+2020_Q2+type@asset+block@metadataAssessment.sql)

If you are familiar with running SQL, give some of the scripts a try on databases you have access to and see what kind of results you are getting. You can do this exercise in the [DHIS2 DQ Metadata](https://academy.dq.dhis2.org/metadata) training instance, using the username and password shown on the login screen.

If you are not, do not worry. Just know that these tools are available to support additional assessment.

## 5.5 - Summary (10 min)

#### 5.5.1 - Summary (10 min)

##### 5.5.1 - Summary

### 5.5.1 - Summary

In this video, Shurajit does a brief summary of what you have covered in this module.

*This video was recorded for a live academy in October 2020. Any references to dates in relation to this academy can be ignored.*

##### (Video) - Summary

### (Video) - Summary

[https://www.youtube.com/watch?v=yRLKui4-8s8](https://www.youtube.com/watch?v=yRLKui4-8s8)

##### 5.5.1 - Summary - Video Download

### 5.5.1 - Summary - Video Download

You can download the video here. <https://academy.downloads.dhis2.org/Data+Quality/5.5.1+-+Summary.mp4

## 5.6 Feedback survey (2 min)

#### Feedback survey (2 min)

Once you are done with the module, please take 2 or 3 minutes to complete this feedback survey. Your careful response will have a real impact on how courses like this are run. Thank you!

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSc8AhkfqWheFM2ofmN0AhS0rbRjEBBbsYi6Px3z1suGSsIN8Q/viewform?embedded=true" width="100%" height="1999" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe
