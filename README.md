# ScalerCaseStudy
 Clustering project

## Problem Statement

Scaler is an online tech-versity offering intensive computer science & Data Science courses through live classes delivered by tech leaders and subject matter experts. The meticulously structured program enhances the skills of software professionals by offering a modern curriculum with exposure to the latest technologies. It is a product by InterviewBit.

You are working as a data scientist with the analytics vertical of Scaler, focused on profiling the best companies and job positions to work for from the Scaler database. You are provided with the information for a segment of learners and tasked to cluster them on the basis of their job profile, company, and other features. Ideally, these clusters should have similar characteristics.


## Data Dictionary:

‘Unnamed 0’ - Index of the dataset

Email_hash - Anonymised Personal Identifiable Information (PII)

Company_hash - This represents an anonymized identifier for the company, which is the current employer of the learner.

orgyear - Employment start date

CTC - Current CTC

Job_position - Job profile in the company

CTC_updated_year - Year in which CTC got updated (Yearly increments, Promotions)


## Concept Used:

Manual Clustering
Unsupervised Clustering - K- means, Hierarchical Clustering
What does “good” look like?

## Task performed:

Import the dataset and do usual exploratory data analysis steps like checking the structure & characteristics of the dataset

Checking unique emails and frequency of occurrence of the same email hash in the data. Recording observation and inference, wherever necessary.

Checking for missing values and Prepare data for KNN/ Mean Imputation.

Checking for duplicates in the dataset and drop them

Making some new features like adding ‘Years of Experience’ column by subtracting orgyear from current year

Manual Clustering on the basis of learner’s company, job position and years of experience

Getting the 5 point summary of CTC (mean, median, max, min, count etc) on the basis of Company, Job Position, Years of Experience

Merging the same with original dataset carefully and creating some flags showing learners with CTC greater than the Average of their Company’s department having same Years of Experience - Call that flag designation with values [1,2,3]
Doing above analysis at Company & Job Position level. Name that flag Class with values [1,2,3]

Repeating the same analysis at the Company level. Name that flag Tier with values [1,2,3]

Data processing for Unsupervised clustering - Label encoding/ One- hot encoding, Standardization of data

Unsupervised Learning - Clustering

Checking clustering tendency

Elbow method

K-means clustering

Hierarchical clustering .
