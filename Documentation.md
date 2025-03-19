# Toulouse Métropole subsidy 2022-2023

![Toulouse-metropole](https://wiki.resilience-territoire.ademe.fr/images/resilienceterritoire/3/33/Tlse-metropole-logo-couleur2.jpg)




## Table of Contents

**1. Introduction**

**2. Research questions**

**3. Methodology**

**4. Data Exploration**

**5. Results**

**6. Conclusion**




### 1. Introduction

**Project background**

The analysis of subsidies allocated by the Metropole of Toulouse was undertaken to gain a comprehensive understanding of the financial support distributed across various sectors. The primary aim of this study is to ascertain the total amount of subsidies allocated and to identify which sectors received the most and the least funding. This information is crucial for evaluating the effectiveness of current budget allocations.
The strategic goal of this analysis is to enhance the Metropole's impact on budget allocation, particularly in light of recent economic challenges that have led to the closure of several organisations. By identifying sectors and organisations in financial distress, the Metropole aims to provide targeted subsidies that can prevent closures and support continued operations, thereby having a significant positive impact on the local economy.
The expected outcome of this analysis is to offer a clearer understanding of spending patterns and to assess, over time and with additional data, whether these financial interventions have bolstered economic activity. By aligning subsidy allocations with the needs of the community, the Metropole of Toulouse seeks to optimise its budgetary impact and support sustainable economic growth.

**Objectives of the analysis**

This analysis examines the variation in subsidies allocated by the Metropole of Toulouse, located in the Occitanie region of southern France, between 2022 and 2023. The objective is to identify which sectors receive the highest and lowest amounts of funding, determine key statistical measures (minimum, average, median, and maximum subsidies allocated), and assess the total amount distributed over the years. Additionally, the study aims to analyse whether there has been an increase or decrease in the total subsidy amount between 2022 and 2023, expressed as a percentage.
Furthermore, the analysis seeks to identify which types of beneficiary structures receive the largest share of subsidies and which are underrepresented. Understanding these distribution patterns is essential for assessing the equity of funding allocations and optimising future budget planning. By highlighting where the majority of subsidies are directed, this study aims to provide valuable insights for decision-makers to ensure a more effective and balanced allocation of public resources.

**What is a subsidy ?**

A subsidy is a financial aid provided by an organisation, typically a government or public institution, to another entity, such as a business, association, or individual, to support a specific activity or project. Subsidies are often used to encourage initiatives deemed beneficial to society, such as economic development, education, research, culture, or the environment.
Unlike a loan, a subsidy does not need to be repaid, making it a valuable tool for promoting projects that might not be feasible without external financial support. Recipients of subsidies are usually required to meet certain conditions or objectives to receive and retain the funding.

**Different Use of subsidies**

**Operating Subsidy** (Subvention de Fonctionnement),
An operating subsidy is financial assistance provided to cover the day-to-day expenses of an organisation. This includes costs such as salaries, rent, utilities, and other general expenses necessary for the organisation's daily operations. The aim is to support the financial stability of the organisation so it can continue its regular activities.

**Capital Subsidy** (Subvention d'Équipement),
A capital subsidy, on the other hand, is financial assistance specifically allocated for the purchase or improvement of equipment or infrastructure. This can include buying machinery, computer equipment, or constructing new facilities. The purpose of this type of subsidy is to help the organisation expand or enhance its operational capabilities.


### 2. Research questions

1.	Sectoral Distribution: Which sectors received the highest and lowest amounts of subsidies in 2022 and 2023?
2.	Statistical Measures: What are the maximum, minimum, average, and median subsidy amounts received in 2022 and 2023?
3.	Least Funded Organisations: Which are the top 10 organisations that received the least amount of subsidies in 2022 and 2023?
4.	Most Funded Organisations: Which are the top 10 organisations that received the most amount of subsidies in 2022 and 2023?
5.	Annual Totals: What is the total amount of subsidies distributed in the year 2022 compared to 2023?
6.	Percentage Increase: What is the percentage increase in the total subsidies from 2022 to 2023?
7.	Beneficiary Analysis: What types of organisations are the primary beneficiaries of the subsidies, and which types are underrepresented?
8.	Yearly Change: Has there been a significant change in the total amount of subsidies distributed between 2022 and 2023?

Hypothesis
Increase in Subsidies Hypothesis: There is a statistically significant increase in the total subsidy amount from 2022 to 2023.

### 3. Methodology

**Data Description**

2023 Dataset:
- Dataset Identifier: "subventions-versees-a-des-organismes-ville-de-toulouse-2023"
- Downloads: 355
- Themes: Finance
- Keywords: Subsidy, 2023
- Licence: Open Licence v2.0 (Etalab)
- Language: French
- Last Modified: 18 October 2024, 18:50
- Data Producer: City of Toulouse
- Cities Covered: Toulouse
- Frequency: Annual
- Last Processed: 20 October 2024, 18:51 (both metadata and data)
- Access Link: [2023 Dataset](https://data.toulouse-metropole.fr/explore/dataset/subventions-versees-a-des-organismes-ville-de-toulouse-2023/information/)


2022 Dataset:
- Dataset Identifier: "subventions-versees-a-des-organismes-2022-ville-de-toulouse"
- Downloads: 1,454
- Themes: Finance
- Keywords: Subsidy, 2022
- Licence: Open Licence v2.0 (Etalab)
- Language: French
- Last Modified: 20 July 2023, 17:29
- Data Producer: Toulouse City Hall
- Territory: Toulouse Métropole
- Frequency: Annual
- Last Processed: 15 May 2024, 09:42 (metadata), 20 July 2023, 17:33 (data)
- Access Link: [2022 Dataset](https://data.toulouse-metropole.fr/explore/dataset/subventions-versees-a-des-organismes-2022-ville-de-toulouse/information/)


**Data Characteristics**

2023 Dataset:
- Time Period Covered: The dataset covers the entire calendar year of 2023.
- Update Frequency: Annually updated.
- Geographical Scope: City of Toulouse, within the Occitanie region of southern France.
- Data Format: The data is provided in CSV, JSON, Excel and parquet.

2022 Dataset:
- Time Period Covered: The dataset encompasses the full year of 2022.
- Update Frequency: Updated annually.
- Geographical Scope: City of Toulouse, within the Occitanie region of southern France.
- Data Format: The data is provided in CSV, JSON, Excel and parquet.

**Variables and Their Descriptions**

For both the 2022 and 2023 datasets, the following variables are included:

1. **nomAttribuant**: The name of the entity providing the subsidy.
2. **idAttribuant**: A unique identifier for the entity providing the subsidy.
3. **dateConvention**: The date on which the subsidy agreement was formalised.
4. **referenceDecision**: A reference number for the decision related to the subsidy.
5. **nomBeneficiaire**: The name of the beneficiary receiving the subsidy.
6. **idBeneficiaire**: A unique identifier for the beneficiary.
7. **objet**: The purpose or type of subsidy.
8. **montant**: The amount of money granted as a subsidy.
9. **nature**: The nature of the subsidy.
10. **conditionsVersement**: The conditions under which the subsidy is disbursed.
11. **datesPeriodeVersement**: The period over which the subsidy is paid.
12. **idRAE**: A unique identifier related to the subsidy agreement.
13. **notificationUE**: Indicates whether the subsidy is subject to EU notification requirements.
14. **secteur**: The sector in which the beneficiary operates.
15. **catégorie**: A category describing the beneficiary's specific area of activity.
16. **type**: The legal form or type of the beneficiary.


**Analytical Techniques Used**

- Descriptive Statistics:
Calculation of key statistical measures such as mean, median, minimum, and maximum to summarise the distribution of subsidies across different sectors and organisations.
- Comparative Analysis:
Year-over-year comparison to assess changes in subsidy allocations between 2022 and 2023, including percentage changes in total amounts distributed.
- Sectoral Analysis:
Identification of sectors receiving the highest and lowest subsidies to understand funding priorities and potential gaps.
- Beneficiary Analysis:
Examination of the types of organisations receiving subsidies to determine which are the primary beneficiaries and which are underrepresented.
- Data Visualisation:
Use of visualisation tools Power BI  to create charts and graphs that illustrate subsidy distribution patterns.
- Trend Analysis:
Analysis of trends over the two-year period to identify any significant shifts in funding patterns.
- Hypothesis Testing:
Statistical tests to evaluate the hypothesis regarding the increase in total subsidy amounts from 2022 to 2023, ensuring that observed changes are statistically significant.


**Tools and software utilised**

- Microsoft excel
- Pyhton
- Power BI

### 4. Data Exploration

**Descriptive Analysis**

- Initial Data Inspection:
The datasets for 2022 and 2023 were loaded using Pandas, and the first few rows were examined with head() to gain an initial understanding of the data structure and content.
2.	Data Types and Completeness:
•	Utilised info() to check data types and identify any missing values. Notably, the "idBeneficiaire" column had some missing entries, but these were retained for potential future analysis.
3.	Statistical Measures:
•	Calculated key statistical measures for the subsidy amounts in both datasets:
•	2022: Maximum subsidy of €15,000,000, minimum of €26.8, average of €224,215.5, and median of €11,517.5.
•	2023: Maximum subsidy of €27,132,600, minimum of €184, average of €213,647.3, and median of €6,000.
4.	Total Subsidy Distribution:
•	The total subsidies distributed were calculated as €88,789,356.48 for 2022 and €117,719,667.87 for 2023, indicating a significant increase in funding.
5.	Sectoral Funding Patterns:
•	Identified the top 10 sectors receiving the most and least subsidies in each year. For instance, in 2022, the "Immobilier" sector received the highest funding, while "Agroalimentaire" received the least. In 2023, "Immobilier" again topped the list, with "Médias" receiving the least.
6.	Percentage Change Analysis:
•	A comparative analysis revealed a 32.58% increase in total subsidies from 2022 to 2023, highlighting a substantial rise in financial support.
