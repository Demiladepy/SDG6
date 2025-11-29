# 🌍 Integrated Project: Access to Drinking Water

## 🎯 Project Goal: UN SDG 6 Analysis

This integrated project investigates the global challenge of access to safe and affordable drinking water.  
The primary focus is to analyze inequalities in service levels across countries and regions, aligning with **United Nations Sustainable Development Goal 6 (SDG 6): Clean Water and Sanitation**.

> SDG 6 aims to "Ensure availability and sustainable management of water and sanitation for all."

Through this analysis, we seek to understand the progress made and the remaining gaps between **2000 and 2025**.

---

## 📊 Data Source

The analysis utilizes data from the **WHO/UNICEF Joint Monitoring Programme (JMP)** for water supply, sanitation, and hygiene.

The dataset provides estimates of household access to drinking water services between 2000 and 2020, enabling assessment of progress toward SDG 6.

### Key Data Fields

- **Country or area**: Specific geographical region  
- **Year**: Year of estimate  
- **Population**: Estimated population size (in thousands)  
- **% Urban**: Share of population living in urban areas  
- **Service levels**: National, rural, and urban access to drinking water service levels

---

## 💧 JMP Service Levels Definitions

The JMP defines five distinct service levels using a service ladder:

| Service Level   | Definition |
|-----------------|------------|
| **Safely managed** | Improved source accessible on premises, available when needed, and free from contamination |
| **Basic**          | Improved source with collection time ≤ 30 minutes round trip |
| **Limited**        | Improved source with collection time > 30 minutes round trip |
| **Unimproved**     | Unprotected dug well or spring |
| **Surface water**  | Direct use from river, lake, pond, stream, or canal |

---

## 🛠️ Methodology and Project Structure

The project is divided into two main parts, using **Google Sheets** for data import, cleaning, feature creation, visualization, and interpretation.

### Part 1: Understanding the Data

Focus: Foundational analysis and descriptive statistics

#### Key Questions

- How does the dataset population compare to world estimates?
- What is the urban vs rural population share?
- What are the tendencies and spreads of water access features?
- How do water access measures vary by area type (national, urban, rural)?
- What is the relationship between population size, urbanization, GNI, and water access?

### Part 2: Transforming the Data

Focus: Feature engineering and time-series analysis

#### Key Questions

- What are the differences between the dataset and 2020 estimates?
- What is the average year difference per country?
- What are the Annual Rates of Change (ARC) for national, rural, and urban areas?
- How does access to basic water change over time?
- How does ARC compare between rural and urban populations and across regions?
- How does national population size influence ARC?

---

## 🚀 Getting Started

To replicate this project:

1. **Obtain the JMP Dataset**  
   Download the *Estimates on the Use of Water (2000–2025)* from WHO/UNICEF JMP.

2. **Import & Clean**  
   Load the dataset into **Google Sheets** or **Microsoft Excel** and perform initial cleaning.

---

Feel free to fork, adapt, or expand this project to explore other SDG indicators or regional case studies.
