# Los Angeles Crime Data Analysis

![Los Angeles skyline](la_skyline.jpg)

This project, proposed by DataCamp, focuses on analyzing crime data in Los Angeles, California. Known for its warm weather, palm trees, and Hollywood, Los Angeles is also a city with significant crime activity due to its large population. The Los Angeles Police Department (LAPD) seeks to understand crime patterns across the city to allocate resources more effectively and address criminal activity in different areas.

Using the crime data provided by DataCamp, this project explores and identifies trends in criminal behavior, providing insights into the distribution of various types of crime. By analyzing the data, we aim to help the LAPD optimize their efforts and create strategies to improve safety and reduce crime in Los Angeles.

___

## 1. Dataset Overview

They have provided you with a single dataset to use. A summary and preview are provided below.

It is a modified version of the original data, which is publicly available from Los Angeles Open Data.

### crimes.csv

| Column     | Description              |
|------------|--------------------------|
| `'DR_NO'` | Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits. |
| `'Date Rptd'` | Date reported - MM/DD/YYYY. |
| `'DATE OCC'` | Date of occurrence - MM/DD/YYYY. |
| `'TIME OCC'` | In 24-hour military time. |
| `'AREA NAME'` | The 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. For example, the 77th Street Division is located at the intersection of South Broadway and 77th Street, serving neighborhoods in South Los Angeles. |
| `'Crm Cd Desc'` | Indicates the crime committed. |
| `'Vict Age'` | Victim's age in years. |
| `'Vict Sex'` | Victim's sex: `F`: Female, `M`: Male, `X`: Unknown. |
| `'Vict Descent'` | Victim's descent:<ul><li>`A` - Other Asian</li><li>`B` - Black</li><li>`C` - Chinese</li><li>`D` - Cambodian</li><li>`F` - Filipino</li><li>`G` - Guamanian</li><li>`H` - Hispanic/Latin/Mexican</li><li>`I` - American Indian/Alaskan Native</li><li>`J` - Japanese</li><li>`K` - Korean</li><li>`L` - Laotian</li><li>`O` - Other</li><li>`P` - Pacific Islander</li><li>`S` - Samoan</li><li>`U` - Hawaiian</li><li>`V` - Vietnamese</li><li>`W` - White</li><li>`X` - Unknown</li><li>`Z` - Asian Indian</li> |
| `'Weapon Desc'` | Description of the weapon used (if applicable). |
| `'Status Desc'` | Crime status. |
| `'LOCATION'` | Street address of the crime. |

___

## 2. Analysis Objectives:

- Identify key crime trends based on temporal patterns, geographic locations, victim demographics, and crime types.

- Generate insights that can assist the LAPD in resource allocation and crime prevention strategies.

- Highlight areas requiring focused law enforcement interventions.

___

## 3. Key Analytical Steps and Findings:
### 3.1. Temporal Analysis:
Crimes **peak at 12:00 PM**, with a recorded **13,663 incidents**, which could be attributed to high public activity, business operations, and increased movement of people during lunch hours. Many commercial and social activities take place around this time, creating more opportunities for theft and assault. Additionally, some businesses have shift changes, leading to moments of distraction and reduced vigilance, while students and workers are commuting, making them more vulnerable to crimes. **Fridays** record the **highest crime frequency**, with **28,625 reported cases**, possibly due to the start of the weekend, increased nightlife, alcohol consumption, and larger financial transactions, as people receive paychecks and businesses handle high volumes of cash. The month of **June** sees the **highest number of reported crimes**, totaling **26,997 incidents**, which could be linked to warmer summer temperatures encouraging more outdoor activities, school holidays leading to more unsupervised youth, and an increase in public events and festivals that provide more opportunities for criminal activities.

### 3.3 Geographic Analysis:

The highest number of night time crimes, occurring between **10 PM and 3:59 AM**, is reported in **Central** Los Angeles, with **3,011 incidents**. This can be attributed to the presence of nightlife, entertainment venues, and lower police visibility during late hours. Additionally, crime type concentration reveals that the most commonly reported offenses include **Identity Theft and Battery**, both of which can occur in various settings, including residential areas, commercial districts, and nightlife hotspots. Property-related crimes such as **burglary and theft** remain prevalent in both residential and commercial zones, especially during late hours when businesses are closed and homes are left unattended.

### 3.4 Demographic Analysis:

Hispanic individuals are the most frequently victimized demographic group, which may reflect the city's population distribution and socioeconomic factors that make certain communities more vulnerable to crime. Among gender and age trends, Hispanic **females aged 26-34** report the highest number of victimization cases, totaling **10,719 incidents**, while Hispanic **males in the same age** bracket follow closely with **9,161 reported cases**. These numbers suggest a need for community-based interventions that focus on crime prevention and victim support programs tailored to these groups.

### 3.5 Crime Case Status:

A significant proportion of cases, **153,790 incidents**, remain under the status of Investigation Continued, highlighting potential challenges in resolving crimes efficiently. The number of cases resulting in arrests is disproportionately low, raising concerns about case backlog, investigative effectiveness, and the ability to bring perpetrators to justice in a timely manner.

___

## 4. Conclusion:
To enhance crime prevention and public safety, it is recommended to increase law enforcement presence on **Fridays and during June**, when crime rates are at their peak. Community safety initiatives should focus on outreach programs and protective measures specifically targeting **Hispanic individuals aged 26-44**, who are the most frequently victimized demographic. Strengthening policing efforts in Central Los Angeles, particularly between **10 PM and 3:59** AM, can help address the spike in nighttime criminal activities. Additionally, law enforcement agencies should prioritize streamlining investigative processes to reduce the backlog of unresolved cases and improve crime resolution rates. By leveraging these insights, LAPD can adopt data-driven strategies to enhance public safety and crime prevention across Los Angeles.


