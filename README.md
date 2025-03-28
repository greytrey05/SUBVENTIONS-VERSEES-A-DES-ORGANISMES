
![Toulouse-metropole](https://wiki.resilience-territoire.ademe.fr/images/resilienceterritoire/3/33/Tlse-metropole-logo-couleur2.jpg)







# Toulouse Métropole subsidy 2022-2023


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

- Data Types and Completeness:
Utilised info() to check data types and identify any missing values. Notably, the "idBeneficiaire" column had some missing entries, but these were retained for data accuracy.

- Statistical Measures:
Calculated key statistical measures for the subsidy amounts in both datasets:

2022: Maximum subsidy of €15000000, minimum of €26.8, average of €224215.5, and median of €11517.5
2023: Maximum subsidy of €27132600, minimum of €184, average of €213647.3, and median of €6000

- Total Subsidy Distribution:

The total subsidies distributed were calculated as €88789356.48 for 2022 
and €11771667.87 for 2023, indicating a significant increase in funding.

- Sectoral Funding Patterns:

Identified the top 10 sectors receiving the most and least subsidies in each year. For instance, in 2022, the "Immobilier" sector received the highest funding, while "Agroalimentaire" received the least. In 2023, "Immobilier" again topped the list, with "Médias" receiving the least.

- Percentage Change Analysis:

A comparative analysis revealed a 32.58% increase in total subsidies from 2022 to 2023, highlighting a substantial rise in financial support.


# 5. Results


**Summary of Key Findings**

The analysis of subsidy allocations by the Metropole of Toulouse for the years 2022 and 2023 reveals several important insights:

In 2022, the total amount of subsidies distributed was €88789356.48, while in 2023, this amount increased to €117719667.87, representing a significant rise of 32.58%. This indicates a substantial increase in financial support provided by the Metropole.
The "Immobilier" sector consistently received the highest amount of subsidies in both years, highlighting its priority within the Metropole's funding strategy. Conversely, sectors such as "Agroalimentaire" in 2022 and "Médias" in 2023 received the least funding, suggesting potential areas for increased support.

The maximum subsidy amount increased from €15000000 in 2022 to €27132600 in 2023, reflecting a broader range of financial assistance. 
The median subsidy amount dropped from €11517.5 to €6000, indicating a shift towards smaller individual grants.
The analysis identified the top 10 sectors receiving the most and least subsidies, providing insights into the distribution patterns and highlighting sectors that may require additional attention or resources.

**Answers to Research Questions or Validation of Hypotheses**


In both 2022 and 2023, the "Immobilier" sector received the highest amount of subsidies, indicating its strategic importance to the Metropole. Conversely, the "Agroalimentaire" sector in 2022 and the "Médias" sector in 2023 received the least funding, suggesting these areas may be underrepresented in subsidy allocations.
The total subsidies distributed were €88789356.48 in 2022 and €117719667.87 in 2023, showing a substantial increase in financial support.
There was a 32.58% increase in total subsidies from 2022 to 2023, reflecting a significant rise in the Metropole's financial commitment.

The Association under the 1901 Law is the most represented, with 296 entities, followed by SAS (Sociétés par Actions Simplifiées) with 110 organisations, and public establishments with 42 organisations.

Between 2022 and 2023, subsidies were predominantly allocated to the real estate sector, accounting for 59.23% of the total amount distributed over these years. This is followed by the land development sector, which represents 14.78% of the share during the period studied, then culture with 7.63%, construction and public works (BTP) with 3.34%, and finally transport, which rounds out the top five with 2.2%.
December is the month with the highest number of registered organisations, with 232 entities, followed by November with 134 and July with 94.


Validation of Hypothesis:

There is a statistically significant increase in the total subsidy amount from 2022 to 2023.
This hypothesis is validated by the observed 32.58% increase in total subsidies, confirming a substantial rise in financial allocations by the Metropole.

# 6. Conclusion

To ensure a more equitable distribution of resources, it is recommended that the Metropole consider increasing support for underrepresented sectors such as "Agroalimentaire" and "Médias". This could help stimulate growth and innovation in areas that currently receive less funding.
It would be beneficial to assess the impact of these subsidies on the recipients. Understanding how these smaller grants contribute to organisational stability and growth can inform future allocation strategies.
Given the significant funding directed towards the real estate sector, it is important to regularly review and assess the outcomes of these investments. 
Ensuring that the funding aligns with broader economic and social goals will maximise the benefits for the community.
Implementing robust monitoring and evaluation mechanisms can help track the effectiveness of subsidies and identify areas for improvement. 
Engaging with stakeholders across various sectors can provide valuable insights into their needs and challenges. 
This collaborative approach can help tailor subsidy programmes to better meet the needs of the community and drive sustainable development.
