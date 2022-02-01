
# Module 7 - Final Assessment

## 7.1 - Graded Final Assessment (1 h)

#### 7.1 - Final Assessment - Graded (1 h)

##### 7.1 - Final Assessment - Graded

### 7.1 - Final Assessment - Graded

[DHIS2 Data Quality](https://academy.dq.dhis2.org/dq) training instance

[DHIS2 Documentation](https://docs.dhis2.org/en/use/optional-apps/who-data-quality-tool/usage-and-interpretation.html)

Now that you have completed all of the modules, you are now able to take the Final Assessment for this course. The final assessment consists of 12 questions and the assessment comprises 45% of your total grade. Each question is worth one point for a total of 12 points. You have 1 or 2 attempts on each question. This assessment is not timed, so feel free to take your time with it. If you get stuck, you can simply pause, and come back to the question later.

This assessment will test you on what you have learned about Data Quality within DHIS2 throughout this course. You’ll be tested on how to operate the WHO Data Quality Tool, as well as how to spot Data Quality issues.

### Set up - final assessment

You'll be required to use the [DHIS2 Data Quality](https://academy.dq.dhis2.org/dq) training instance to complete the assessment.

Use the dashboard of the WHO Data Quality Tool to identify suspicious values and important missing data.

Configure the dashboard as follows: Data = District; Period = March 2021; Boundary = National; Disaggregation = District.

##### Question 1

### Question 1

0.0/1.0 point (graded)

Review the Completeness dashboard. Which district had the lowest reporting rate for the maternity dataset in March 2021?

Select the one correct answer: (2 attempts)

1. A-2

2. B-2

3. **A-5**

4. D-1

Feedback: The correct answer is A-5

##### Question 2

### Question 2

0.0/1.0 point (graded)

Review the Consistency - Time dashboard. Which district had a suspiciously high value for ANC 1 in January 2021?

Select the one correct answer: (2 attempts)

1. A-2

2. **B-2**

3. C-2

4. D-2

Feedback: The correct answer is B-2

##### Question 3

### Question 3

0.0/1.0 point (graded)

Continue to review the Consistency - Time dashboard. Which district had a suspiciously high value for ANC 1 in May of 2020?

Select the one correct answer: (2 attempts)

1. A-1

2. B-1

3. C-1

4. **D-1**

Feedback: The correct answer is D-1

##### Question 4

### Question 4

0.0/1.0 point (graded)

Review the Consistency - Data dashboard. Reset the Period to September, 2020. Which district had the most suspicious Penta 1 to Penta 3 dropout rate for the last 12 months?

Select the one correct answer: (2 attempts)

1. A-4

2. B-4

3. C-4

4. **D-4**

Feedback: The correct answer is D-4.

##### Question 5

### Question 5

0.0/1.0 point (graded)

Continue to review the Consistency-Data dashboard. Set Data = District; Period = March 2021; Boundary = Other, then District A-3; Disaggregation = Facility;

Is the following statement True or False:

During the last 12 months, most health facilities of District A-3 reported a higher number of 1st doses of Penta vaccine than 3rd doses of Penta vaccine.

Select the one correct answer: (1 attempt)

1. True

2. **False**

We cannot determine this from the Consistency-Data dashboard

Feedback: The correct answer is False.

##### Question 6

### Question 6

0.0/1.0 point (graded)

Review the Outliers dashboard. Reset the dashboard configuration: Data = District; Period = last month; Boundary = National; Disaggregation = District. Set the Options as follows: first under “Display Columns'' select Outliers, then select the Include Z-Score. Next, under the Outlier Filter, select the Modified Z-Score and set to Extreme.

Which of the following districts had an extreme outlier value for ANC 1 visits in January 2021?

Select the one correct answer: (2 attempts)

1. C-5

2. B-4

3. **C-6**

4. C-1

Feedback: The correct answer is B-2.

##### Question 7

### Question 7

0.0/1.0 point (graded)

From the previous question, drill down into the district with the highest deviation from the non-supicious values for BCG given less then 1.

Which health facility reported the most extreme outlier for BCG given less then 1?

Select the one correct answer: (2 attempts)

1. **Facility 579**

2. Facility 12

3. Facility 608

4. Facility 14

Feedback: the correct answer is Facility 579.

##### Question 8

### Question 8

0.0/1.0 point (graded)

Now select the Outliers dashboard. Configure the dashboard as follows: Data = District; Period = July 2020; Boundary = - Other, then select Region C, and then District C-1; Disaggregation = Facility.

An extreme outlier value of Penta 3 given < 1 was reported for July 2020. Further investigation shows that this value is due to a data entry error and that this error resulted in over reporting of Penta 3 doses administered. Estimate the amount of over-reporting compared to an average month.

Select the one correct answer: (2 attempts)

1. 1638

2. **1072**

3. 546

4. 23.9

Feedback: The correct answer is 1072.

##### Question 9

### Question 9

0.0/1.0 point (graded)

Stay on the Outliers dashboard. Do not change the settings except for the Options. Set Options as follows: Under “display columns” select Missing data, and select the Outlier filter to Off. Click twice in the Column header “Missing” to sort the rows by smallest to largest.

For which health facility is the largest amount of ANC 1 data missing?

Select the one correct answer: (2 attempts)

1. Facility 346

2. Facility 543

3. Facility 559

4. **Facility 378**

Feedback: The correct answer is Facility 378.

#####

##### Question 10

### Question 10

0.0/1.0 point (graded)

Stay on the outliers dashboard. Do not change the settings except for the Options. Set the options as follows: under Display columns, select Outliers. Set outlier filter to Modified Z-Score. Keep the Dimensions as before. In the table, sort by Outlier column from high to low.

Which facility has the highest outlier in the resulting table?

Select the one correct answer: (2 attempts)

1. Facility 543

2. Facility 565

3. **Facility 553**

4. Facility 478

Feedback: The correct answer is Facility 553, with an outlier of 18088 for OPD total attendance.

##### <sQuestion 11</s

### <sQuestion 11</s

<s0.0/1.0 point (graded)</s

<sOpen Data entry form for Region D/District D4/Facility 281/ANC dataset/March 2021. Double click on Albendazole dose at ANC.</s

<sHow many values are below the minimum for the time period March 2020 to March 2021?</s

<sSelect the one correct answer: (2 attempts)</s

1. <s0</s

2. **<s1</s**

3. <s6</s

4. <s10</s

<sFeedback: 1 is correct. March 2021 (11) is below the minimum. No data was entered for September 2020</s

##### Question 11

### Question 11

### 0.0/1.0 point (graded)

A validation rule compares the following 2 data elements:

-Malaria RDT done OPD < 5 years

-Malaria RDT confirmed OPD < 5 years

Using best practice, select the correct option for creating this rule:

Select the one correct answer:

1. Malaria RDT done OPD < 5 years == Malaria RDT confirmed OPD < 5 years

2. Malaria RDT done OPD < 5 years = Malaria RDT confirmed OPD < 5 years

3. Malaria RDT done OPD < 5 years <= Malaria RDT confirmed OPD < 5 years

4. **Malaria RDT confirmed OPD < 5 years <= Malaria RDT done OPD < 5 years**

Feedback: Malaria RDT confirmed OPD < 5 years <= Malaria RDT done OPD <5 years is correct.

## 7.2 Feedback survey (2 min)

#### Feedback survey (2 min)

Once you are done with the module, please take 2 or 3 minutes to complete this feedback survey. Your careful response will have a real impact on how courses like this are run. Thank you!

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf388vvGIxL4etxwk_DihWSS2PoOJcGuXzaoiG9MraFklCV9Q/viewform?embedded=true" width="100%" height="1023" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe
