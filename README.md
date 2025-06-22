                          
 
![Thumbnail Picture](https://github.com/fangkiigopramana/Fangki_CP_DATA_SCI_2025/raw/main/Gemini_Generated_Image_sxobs2sxobs2sxob.png)
 
# Data Classification And Summarization of US Presidential Debates

[![GitHub last commit](https://img.shields.io/github/last-commit/fangkiigopramana/Fangki_CP_DATA_SCI_2025)](https://img.shields.io/github/last-commit/fangkiigopramana/Fangki_CP_DATA_SCI_2025)

# Table of Contents

This is a table of contents for your project. It helps the reader navigate through the README quickly.
- [Project Title](#data-classification-and-summarization-of-us-presidential-debates)
- [Project Overview](#project-overview)
- [Raw Dataset Link](#raw-dataset-link)
- [Insight and Findings](#insight-and-findings)
- [AI Support Explanation](#ai-support-explanation)
- [Contribute](#contribute)


# Project Overview

![Demo Preview](https://i.ytimg.com/vi/0s4HTZUI2QU/maxresdefault.jpg)

This project focuses on the classification and summarization of data from US Presidential Debates. By leveraging data science techniques, the project aims to analyze debate transcripts, categorize key topics, and generate concise summaries. The goal is to provide insights into debate content, highlight major discussion points, and support further research in political discourse analysis.

## Goals
To get insights from the transcripts of the 2016 US presidential debates between Donald Trump and Hillary Clinton to understand the communication dynamics, issue focus, and rhetorical strategies of each candidate

## Objective
Identify the most frequently discussed topics and issues.
Uncover specific debate strategies
Calculate the talk frequency of each contestant

## Benefit
Provides an in-depth understanding of how presidential candidates communicate and interact in a debate setting.
Identifies rhetorical trends and key issues that shaped the political narrative of that time.

# Raw Dataset Link
[(Back to top)](#table-of-contents)

![Thumbnail Picture](https://github.com/fangkiigopramana/Fangki_CP_DATA_SCI_2025/raw/main/dataset.png)
Source Link:  https://www.kaggle.com/datasets/mrisdal/2016-us-presidential-debates


# Insight and Findings
[(Back to top)](#table-of-contents)

A.  Supreme Court and Rights:

**Hillary Clinton**

**-- Insight:**

> Strong emphasis on upholding existing civil rights, including women's rights (Roe v. Wade), LGBT rights, and affordable healthcare. Advocates for stricter gun control and overturning Citizens United (which deals with campaign finance).

**-- Funding:**
> 1. Healthcare: Potential for increased federal funding for healthcare programs, expansion of affordable care initiatives, and possibly funding for reproductive health services. Companies in the healthcare sector, particularly those focused on accessibility and preventative care, might see increased government contracts or grants.
> 2. Civil Rights/LGBTQ+ Rights: Funding for legal aid organizations, advocacy groups, and programs promoting equality and anti-discrimination initiatives.
> 3. Gun Control Research/Programs: Increased funding for research into gun violence prevention, community programs aimed at reducing gun violence, and potentially for technology related to gun safety. 
> 4. Campaign Finance Reform: Organizations advocating for campaign finance reform or those developing alternative funding models for political campaigns might find support.


**Donald Trump**

**-- Insight:**

> Focus on appointing conservative justices who interpret the Constitution "as the Founding Fathers intended," with a strong emphasis on protecting the Second Amendment (gun rights) and appointing pro-life judges. Also highlights strong border security.

**-- Funding:**
> 1. Second Amendment Advocacy: Groups supporting gun rights and manufacturers in the firearms industry might see a more favorable regulatory environment and potentially increased sales.
> 2. Pro-Life Initiatives: Funding for organizations providing alternatives to abortion, crisis pregnancy centers, and programs supporting adoption.
> 3. Border Security: Significant federal funding for border infrastructure (e.g., wall construction), increased personnel for border patrol, and surveillance technology. Companies in the construction, security, and defense sectors could benefit.

---

B. Character, Unity, and Governance:

**Hillary Clinton**

**-- Insight:**

> Emphasis on unity, respect, economic growth, education reform, and celebrating diversity. Critical of divisive rhetoric and perceived lack of fitness for office.

**-- Funding:**
> 1. Education Reform: Increased funding for public education, early childhood education, and programs aimed at reducing achievement gaps. Opportunities for educational technology companies, curriculum developers, and teacher training programs.
> 2. Diversity & Inclusion: Funding for initiatives promoting diversity, equity, and inclusion across various sectors, including workplace programs, community development, and cultural institutions.
> 3. Community Development: Grants for urban and rural development projects, social programs, and initiatives fostering community engagement.

**Donald Trump**

**-- Insight:**

> Focus on "Make America Great Again" through economic recovery, strong borders, law and order, and improving inner cities. Defends controversial statements and attacks opponent's record. Emphasis on energy independence.

**-- Funding:**
> 1. Economic Recovery Programs: Potential for tax cuts (especially corporate), deregulation, and incentives for businesses to keep jobs within the country. Industries like manufacturing and traditional energy (e.g., oil, gas, coal) could see favorable policies and investments.
> 2. Law and Order Initiatives: Increased funding for law enforcement, correctional facilities, and programs aimed at crime reduction. Companies providing security services, surveillance technology, and prison management could see increased demand.
> 3. Inner City Development: While focused on "improving inner cities," the approach might lean towards private sector investment and reduced regulation rather than large-scale federal programs.
> 4. Energy Independence: Significant investment and deregulation in fossil fuel industries, potentially including new drilling projects, pipeline construction, and export infrastructure.

---

C. Economy and Jobs:

**Hillary Clinton**

**-- Insight:**

> Advocates for an economy that benefits everyone, with a focus on job creation through infrastructure, manufacturing, innovation, and clean energy. Emphasizes fairness through minimum wage increases, equal pay, profit-sharing, and family support (paid leave, childcare, debt-free college). Plans to fund these by taxing the wealthy and closing corporate loopholes.

**-- Funding:**
> 1. Infrastructure: Massive federal investment in infrastructure projects (roads, bridges, public transit, broadband). This represents a huge funding opportunity for construction companies, engineering firms, and materials suppliers.
> 2. Clean Energy: Significant funding and incentives for renewable energy projects (solar, wind), energy efficiency initiatives, and green technology development. Opportunities for companies in the renewable energy sector, research institutions, and sustainable development.
> 3. Manufacturing Innovation: Funding for advanced manufacturing research, workforce training for high-tech manufacturing, and incentives for reshoring manufacturing jobs.
> 4. Social Programs/Worker Benefits: Increased funding for social safety nets, family leave programs, affordable childcare, and student loan relief initiatives. This could indirectly stimulate consumer spending and create jobs in related service sectors.
> 5. Taxation on Wealthy/Corporations: Potential for increased tax revenue for federal programs, but could also disincentivize some private sector investment.

**Donald Trump**

**-- Insight:**

> Focus on jobs leaving the country due to unfair trade, proposing renegotiation of trade deals, tariffs on imports, and reduced corporate taxes. Critical of past trade policies and regulations.

**-- Funding:**
> 1. Trade Policy Changes: Industries impacted by tariffs (both positively and negatively) would need to adjust. Domestic industries protected by tariffs might see growth.
> 2. Corporate Tax Reduction: A lower corporate tax rate aims to encourage businesses to invest and expand within the U.S., potentially leading to job creation. This could benefit large corporations and stimulate private sector investment.
> 3. Deregulation: Industries heavily regulated (e.g., environmental, financial) might see reduced compliance costs, potentially leading to increased investment and job creation in those sectors.
 
# AI Support Explanation
[(Back to top)](#table-of-contents)

## Model Used: IBM Granite 3.3-8B Instruct

This project leverages the [ibm-granite/granite-3.3-8b-instruct](https://huggingface.co/ibm-granite/granite-3.3-8b-instruct) large language model for AI-powered classification and summarization tasks. IBM Granite 3.3-8B Instruct is a state-of-the-art open-source model designed for instruction following and natural language understanding.

**Key Features:**
- Fine-tuned for following instructions and generating high-quality summaries.
- Supports multi-turn dialogue and contextual understanding.
- Efficient for text classification, topic extraction, and summarization.

**Usage in This Project:**
- Automatically classifies debate transcript segments into relevant topics.
- Generates concise summaries of lengthy debate exchanges.
- Assists in extracting key insights and rhetorical strategies from the data.

By integrating IBM Granite 3.3-8B Instruct, the project ensures robust, scalable, and accurate AI support for analyzing complex political discourse.
 
# Contribute
[(Back to top)](#table-of-contents)

We welcome contributions! To contribute, please follow these steps:

- Fork this repository and create your branch from `main`.
- Submit a pull request with a clear description of your changes.
- For bug reports or feature requests, please open an issue [here](https://github.com/fangkiigopramana/Fangki_CP_DATA_SCI_2025/issues).
- If you would like to sponsor this project, please contact the repository owner or use GitHub Sponsors if available.
