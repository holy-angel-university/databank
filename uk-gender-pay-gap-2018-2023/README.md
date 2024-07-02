# UK Gender Pay Gap Data 2018 - 2023

[![Dataset Link Badge](https://img.shields.io/badge/datasets-uk_gender_pay_gap-%23FFF8C9?style=for-the-badge)](https://github.com/cogxen/datasets/blob/main/market-size-of-evs/datasets/)

## Dataset Contents

This dataset currently contains data collected by the Gender Pay Gap Service for the 2018 to 2023 reporting years. More data will be added as it becomes available.

- `EmployerName`: The name of the employer at the time of reporting
- `EmployerID`: Unique ID assigned to each employer that is consistent across every reporting year
- `Address`: The current registered address of the employer
- `PostCode`: The postal code of the current registered address of the employer
- `CompanyNumber`: The Company Number of the employer as listed on Companies House (null for public sector)
- `SicCodes`: List of comma-separated SIC codes used to describe the employer's purpose and sectors of work
- `DiffMeanHourlyPercent`: Mean % difference between male and female hourly pay (negative = women's mean hourly pay is higher)
- `DiffMedianHourlyPercent`: Median % difference between male and female hourly pay (negative = women's median hourly pay is higher)
- `DiffMeanBonusPercent`: Mean % difference between male and female bonus pay (negative = women's mean bonus pay is higher)
- `DiffMedianBonusPercent`: Median % difference between male and female bonus pay (negative = women's median bonus pay is higher)
- `MaleBonusPercent`: Percentage of male employees paid a bonus
- `FemaleBonusPercent`: Percentage of female employees paid a bonus
- `MaleLowerQuartile`: Percentage of males in the lower hourly pay quarter
- `FemaleLowerQuartile`: Percentage of females in the lower hourly pay quarter
- `MaleLowerMiddleQuartile`: Percentage of males in the lower middle hourly pay quarter
- `FemaleLowerMiddleQuartile`: Percentage of females in the lower middle hourly pay quarter
- `MaleUpperMiddleQuartile`: Percentage of males in the upper middle hourly pay quarter
- `FemaleUpperMiddleQuartile`: Percentage of females in the upper middle hourly pay quarter
- `MaleTopQuartile`: Percentage of males in the top hourly pay quarter
- `FemaleTopQuartile`: Percentage of females in the top hourly pay quarter
- `CompanyLinkToGPGInfo`: Voluntary link to additional GPG data published by the reporting employer
- `ResponsiblePerson`: The name of the responsible person who confirms that the published information is accurate - Employers covered by the private sector regulations only
- `EmployerSize`: The number of employees in the employer's workforce
- `CurrentName`: The name of the employer at the time of reporting
- `SubmittedAfterTheDeadline`: TRUE/FALSE value showing whether the employee submitted their GPG data after the relevant reporting deadline. If a report is updated after the initial submission, it is marked as late only if the figures are changed
- `DueDate`: The date that the GPG data should have been submitted by. Format: **dd/MM/yyyy HH:mm:ss**
- `DateSubmitted`: Date that GPG data was submitted (if this was updated after the initial submission, this date also changes). Format: **dd/MM/yyyy HH:mm:ss**
