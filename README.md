# Marketing Data Analysis

## 📌 Project Overview
This project analyzes **marketing spend, reservations, and revenue performance** to determine the **most important cities, countries, and marketing campaigns** for the company. The goal is to optimize marketing budget allocation and improve business strategy.

## 📂 Project Structure
- **`marketing_mapping.csv`** → A new mapping file that links **marketing subchannels** (Google, Bing, Facebook, Impact) to their **corresponding marketing channels** (SEM, Paid Social, Affiliate).
- **`Q1.ipynb`** → Jupyter Notebook containing the **SQL-based analysis** for the first task.
    - The mapping file **`marketing_mapping.csv`** follows the assumption:
    - ROAS calculations are based on **marketing costs aggregated at the channel level**.
    - Reservations data does not contain subchannels, so the ROAS analysis in Q1 assumes that SEM includes both Google & Bing.

- **Tableau Visualization** → Available at **[https://public.tableau.com/views/report-marketing/Report?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]()**, which contains:
