# 📊 Python, Excel & Power BI – Distributor Data Matching & Workflow Optimization

### *Python, Pandas, Jupyter Notebook, Excel PivotTables, Power Pivot, DAX & Power BI Business Analytics Project*

> **Transforming months of manual customer-matching data into a data-driven strategy for prioritizing monthly workloads, improving team efficiency, identifying automation opportunities, reducing backlog growth, and delivering Power BI reporting to support operational decision-making.**

---

# 🚀 Project Summary

This project began with a real operational challenge: **manual customer-mapping review was consuming a significant amount of employee time while new distributor records continued arriving every month and an existing historical backlog still needed to be addressed.**

Leadership wanted to understand whether historical matching results could be used to determine **which records deserved immediate attention, where manual research was producing meaningful results, where the process was becoming low-yield, and how much of the monthly workload could be completed efficiently by starting with the strongest potential matches first.**

After manually reviewing and classifying customer records across multiple distributor workbooks, I developed a **Python/Pandas workflow in Jupyter Notebook** to consolidate the completed results, clean and organize the data, group match scores into meaningful ranges, and summarize mapping outcomes at scale.

I then brought the Python-generated results into **Microsoft Excel**, where I built:

- 📊 **PivotTables**
- 🧮 **Power Pivot / DAX measures**
- 🎯 **Score-range performance analysis**
- 📈 **Cumulative match-performance analysis**
- 📦 **Distributor performance analysis**
- 📑 **Worksheet performance analysis**
- 🤖 **Automation / cumulative sweet-spot analysis**

I then developed a **Microsoft Power BI dashboard** to transform the underlying analysis into an interactive business-intelligence and reporting layer focused on:

- 📈 **Executive KPIs**
- 📦 **Distributor performance**
- 📑 **Worksheet performance**
- 🎯 **Score-range performance**
- 📊 **Workload prioritization**
- 📉 **Cumulative workload vs. matching-performance tradeoffs**

Together, the analysis and dashboard created a framework for determining **what type of work the team should expect each month, what should be worked first, where manual research adds the most value, how workload can be distributed more efficiently, and how far down the score distribution it makes sense to work based on available employee capacity.**

Ultimately, the project connected technical analysis to a larger operational objective:

> ### **Process monthly data more efficiently → save employee research time → prevent additional backlog → create capacity to resolve historical records → improve customer/account data → provide better information to Sales → support revenue-generating activity.**

---

# ⭐ Project Highlights

- 🐍 Developed a **Python/Pandas workflow in Jupyter Notebook** to consolidate and analyze completed customer-matching results across multiple distributor workbooks.
- 📊 Built **Excel PivotTables** to analyze performance across distributors, worksheets, score ranges, record volumes, and mapping outcomes.
- 🧮 Created **Power Pivot / DAX measures** for Quick Match %, Manual Match %, Create New %, Not Mapped %, Total Match %, and cumulative performance.
- 📈 Developed a **cumulative score-range analysis** to quantify the tradeoff between workload coverage and matching performance.
- 📊 Developed a **Power BI dashboard** to translate the analytical framework into executive KPIs, distributor analysis, worksheet analysis, score-range performance, and workload-prioritization reporting.
- 📋 Analyzed **877 June 2026 records**, with **648 successfully matched — a 73.9% Total Match Rate**.
- ⚡ Identified **302 Quick Matches (34.4%)** and **346 Manual Matches (39.5%)**.
- 🎯 Found that scores from **50–80 covered only 38.1% of the workload while producing 309 successful matches at a 92.5% Total Match Rate**.
- 📈 Expanding through **40–80 covered 53.6% of the workload while producing 398 successful matches at an 84.7% Total Match Rate**.
- 📦 Found that the **five highest-volume distributors represented 720 of 877 records — approximately 82.1% of the analyzed workload**.
- 📑 Identified meaningful differences between **Default D365, Historic, and In D365** record groups.
- ⏱️ Created a framework for concentrating employee time on **higher-value work rather than treating every incoming record equally**.
- 👥 Provided a method for **prioritizing and distributing work across team members** based on expected workload and historical results.
- 🤖 Identified areas that could support **future automation or reduced manual intervention**.
- 🗃️ Connected monthly efficiency directly to **preventing new backlog and creating capacity to resolve existing historical records**.
- 💰 Connected improved customer/account information to downstream **Sales targeting and revenue-generating activity**.

---

# 🌎 Project Background

Solmetex receives recurring customer data from dental distributors that must be **matched to existing customer accounts, manually researched, created as new accounts, or classified as unmapped when sufficient evidence cannot be established**.

Over several months, I worked directly with distributor workbooks and manually researched customer records to determine their appropriate mapping outcomes.

This created a valuable historical dataset containing actual completed matching decisions.

At the same time, the organization was managing a **historical customer-mapping backlog**.

The challenge was that the two problems were directly connected.

If incoming monthly distributor records could not be processed efficiently, unfinished records would eventually become **additional backlog**.

The project therefore began with an important question:

> ### **Can historical matching results tell us where employee time should be spent so that recurring monthly work can be completed more efficiently?**

---

# ❓ Business Questions From Leadership

The project originated from a request from leadership to determine how the role and process could become **more focused on data and business analysis while preventing manual mapping review from consuming all available time**.

Data mapping remained foundational work and still needed to be completed.

However, leadership wanted to identify opportunities to **speed up or remove stages that were consuming time without providing enough additional value**.

The initial analysis needed to answer several specific business questions.

---

## 1️⃣ How Much of the Monthly Workload Can Be Completed Efficiently?

The first question focused on **medium-to-high-quality potential matches below the existing 80 Match Score threshold**.

Leadership wanted to understand:

> **What percentage of the monthly workload consists of medium-to-high-quality records with one potential match but a Match Score below 80?**

More practically:

> **If the team starts with the highest scores and works downward, quickly completing records where additional research is unnecessary, what percentage of the total monthly workload can be covered?**

This required measuring both:

### **Workload Coverage**

and

### **Matching Success**

---

## 2️⃣ What Is the Yield From Lower-Quality Manual Review?

The opposite side of the problem involved lower-quality potential matches where customer names were significantly different.

The question was:

> **When employees manually research lower-scoring records, what percentage are ultimately successfully mapped?**

In practical terms:

> **If the team works through X accounts within a lower score range, how many are successfully mapped and how much employee effort is required to achieve those additional matches?**

This was essential because a large population of lower-scoring records could consume substantial employee time.

Leadership needed evidence showing whether that additional effort was producing enough value to justify continuing deeper into the workload.

---

## 3️⃣ Which Portions of the Process Are Low-Yield?

After the initial analysis, leadership expanded the requested metrics.

The analysis needed to include:

- 📊 **Records Processed**
- ✅ **Records Matched**
- 📈 **% Processed**
- 🎯 **% Mapped**

These metrics were intended to identify:

> ### **Which portions of the matching process consume substantial effort while producing comparatively little successful output?**

This shifted the project from simply measuring match rates to analyzing **process efficiency**.

---

## 4️⃣ Do Recent Records Behave Differently?

Leadership also requested that the analysis be repeated specifically for **recent records**.

**Earliest Invoice Date** was used as a proxy for separating the relevant recent/monthly population from older records.

This was important because the goal was not simply to understand historical performance.

The findings needed to help determine **how the team should approach the recurring distributor data arriving each month**.

---

# 🎯 Core Analytical Question

Together, the leadership questions became a larger analytical problem:

> ### **How far down the matching-score distribution should the team work before the additional employee time required begins producing diminishing returns?**

Answering that required analyzing more than Match Score alone.

The analysis needed to combine:

**Match Score**  
+
**Records Processed**  
+
**Records Matched**  
+
**Quick Match Yield**  
+
**Manual Match Yield**  
+
**Record Volume**  
+
**Distributor**  
+
**Worksheet Type**  
+
**Final Mapping Outcome**

The goal was to identify a practical balance between:

> ### **Coverage + Successful Matching + Employee Time**

---

# 🎯 Project Objective

The broader objective became determining:

> ### **What types of customer records should the team expect each month, and how should those records be prioritized and distributed to complete the greatest amount of valuable work with the available employee time?**

The project therefore focused on answering:

- Which distributors generate the greatest monthly volume?
- Which score ranges generate the strongest results?
- Which records are most likely to Quick Match?
- Where does manual research provide substantial additional value?
- Which worksheet types behave differently?
- Where does additional review begin producing diminishing returns?
- What percentage of the workload can be completed at different score thresholds?
- How should work be distributed across the team?
- Which groups may support future automation?
- How can the recurring workload be controlled before additional backlog accumulates?
- How can the findings be presented through **Power BI** for clearer operational decision support?

The objective was not simply to analyze what had already happened.

> ### **It was to use historical work to improve how future work should be performed.**

---

# ❓ Business Challenge

Solmetex was working through a **historical customer-mapping backlog** while continuing to receive new distributor data every month.

This created two interconnected problems.

---

## 📥 Recurring Monthly Workload

New distributor records continuously needed to be:

- ⚡ **Quick Matched**
- 🔍 **Manually researched and matched**
- ➕ **Created as new customer accounts**
- ❌ **Classified as Not Mapped** when sufficient evidence could not be established

Every record requires some level of processing.

If the team cannot efficiently complete the recurring monthly workload:

**Monthly Records Arrive**  
⬇️  
**Records Require Review**  
⬇️  
**Employee Capacity Is Consumed**  
⬇️  
**Some Records Remain Unfinished**  
⬇️  
**Unfinished Records Become Additional Backlog**

---

# 🗃️ Historical Customer-Mapping Backlog

Historical records can be considerably more difficult to resolve than current records.

Over time, dental practices may have:

- 🏢 Changed ownership
- 📍 Relocated
- 🚪 Closed
- 🦷 Transitioned to successor dentists or practices
- 🔄 Changed business names
- 🤝 Merged with another organization
- 🏥 Shared an address with another dental practice
- 📑 Accumulated duplicate or outdated customer information

A distributor record that may be relatively straightforward to research today can become substantially more complicated years later.

This created the central operational challenge:

> ### **The historical backlog could not be efficiently reduced if unfinished monthly records continually created additional backlog.**

The recurring workload therefore needed to be controlled before meaningful additional capacity could be dedicated to historical research.

---

# 🔍 Step 1: Manual Customer Matching & Classification

I spent several months working directly through distributor workbooks and researching individual customer records.

Each record had to be evaluated to determine whether the distributor customer corresponded to an existing Solmetex customer/account.

The workflow tracked fields including:

- ⚡ **Quick Match (Y/N)**
- 🔍 **Manual Review Required (Y/N)**
- ✅ **Manual Match (Y/N)**
- 📋 **Final Mapping Status**
- 🎯 **Match Score**
- 📅 **Earliest Invoice Date**
- 📦 **Distributor**
- 📑 **Worksheet / record type**

Final outcomes included:

- ⚡ **Quick Match**
- 🔍 **Manual Match**
- ➕ **Create New**
- ❌ **Not Mapped**

This manual work established the **ground truth for the analysis**.

Instead of analyzing theoretical matching behavior, the project analyzed **actual outcomes from records that had already been reviewed and classified**.

---

# 🐍 Step 2: Python & Jupyter Notebook Data Pipeline

After completing the manual review process, I developed a **Python workflow in Jupyter Notebook using Pandas**.

The purpose was to transform completed workbook results into a consolidated analytical dataset.

### Python/Pandas was used to:

- 📂 Read data across multiple distributor workbooks
- 🔗 Consolidate completed records into a unified dataset
- 🧹 Clean and standardize fields
- 🏷️ Interpret final mapping outcomes
- 🎯 Convert individual Match Scores into defined score ranges
- ⚡ Count Quick Matches
- 🔍 Count Manual Matches
- ➕ Count Create New outcomes
- ❌ Count Not Mapped outcomes
- 📦 Group results by distributor
- 📑 Group results by worksheet type
- 📅 Support analysis of recent records
- 📊 Generate structured summary data for further analysis

Instead of manually counting results across numerous worksheets, Python converted **months of individual matching decisions into structured data that could be analyzed at scale**.

---

# 🎯 Step 3: Match-Score Segmentation

Individual customer records contained calculated Match Scores.

Rather than analyzing hundreds of individual score values independently, I grouped those scores into defined ranges:

- **80–70**
- **69–60**
- **59–50**
- **49–40**
- **39–30**
- **29–20**
- **19–0**

Each range could then be compared across:

- 📊 Total Records
- ⚡ Quick Matches
- 🔍 Manual Matches
- ➕ Create New
- ❌ Not Mapped
- 📈 Quick Match %
- 📈 Manual Match %
- 📈 Total Match %

This segmentation allowed the analysis to measure **how both matching performance and the type of employee effort required changed as Match Scores decreased**.

---

# 📊 Step 4: Excel PivotTable Analysis

After Python generated the consolidated dataset, I brought the results into **Microsoft Excel**.

I created separate analytical views for:

- 📦 **Distributor Summary**
- 📑 **Worksheet Summary**
- 🎯 **Score-Range Summary**
- 📈 **Cumulative Match Performance**
- 🤖 **Automation / Cumulative Sweet Spots**
- 📋 **Underlying Raw Data**

Using **PivotTables**, I could analyze the same underlying dataset from several operational perspectives.

This allowed the project to move beyond individual customer records and evaluate **how the overall matching process was performing**.

---

# 🧮 Step 5: Power Pivot & DAX Measures

I created custom analytical measures using **Power Pivot / DAX**.

Measures included:

- ⚡ **Quick Match %**
- 🔍 **Manual Match %**
- ➕ **Create New %**
- ❌ **Not Mapped %**
- ✅ **Total Match %**
- 📊 **Cumulative Total Records**
- 🎯 **Cumulative Total Matches**
- 📈 **Cumulative Total Match %**

The cumulative measures were especially important because they allowed me to compare:

> **How much of the workload the team reviews**

against

> **How much successful matching value that workload produces**

This transformed the analysis from a descriptive report into a **workload-prioritization tool**.

---

# 📊 Step 6: Power BI Dashboard Development

After completing the underlying analysis in **Python, Excel, Power Pivot, and DAX**, I extended the project into **Microsoft Power BI** to create an interactive business-intelligence and decision-support dashboard.

The purpose of the dashboard was not simply to recreate the Excel analysis visually.

It was designed to make the project's major findings easier to interpret by bringing together:

- 📊 **Key performance indicators**
- 🎯 **Match-score performance**
- 📦 **Distributor workload**
- 📑 **Worksheet performance**
- ⚡ **Quick Match behavior**
- 🔍 **Manual Match behavior**
- 📈 **Cumulative workload coverage**
- ⏱️ **Workload-prioritization tradeoffs**

The dashboard organized the analysis into focused reporting views so the same underlying customer-matching data could be evaluated from both an **operational** and **management-reporting** perspective.

---

## 📈 Executive Overview

The **Executive Overview** provides a high-level view of the customer-matching process.

Key performance indicators include:

- 📋 **Total Records**
- ✅ **Total Matches**
- 📈 **Total Match Rate**
- ⚡ **Quick Match Rate**
- 🔍 **Manual Match Rate**

These KPIs summarize the overall workload and immediately show how much of the analyzed data was successfully resolved.

The page also visualizes **performance across Match Score ranges**, making it easier to see how matching behavior changes as scores decrease.

One of the strongest patterns was:

> ### **Higher score ranges were heavily concentrated in Quick Matches, while lower score ranges became increasingly dependent on manual research.**

This distinction is important because Match Score was not simply predicting whether a record could eventually be matched.

It was also helping identify **what type of employee effort the record was likely to require**.

---

## 📦 Distributor Analysis

The **Distributor Analysis** view examines both **record volume and matching performance across distributor sources**.

The dashboard allows distributor groups to be compared using measures such as:

- 📊 **Total Records**
- ✅ **Total Matches**
- 📈 **Total Match Rate**
- ⚡ **Quick Match Rate**
- 🔍 **Manual Match Rate**

This is important because distributor workload was not evenly distributed.

The five highest-volume distributors accounted for:

> ### **720 of 877 records — approximately 82.1% of the entire analyzed workload.**

That concentration means workload planning can focus on the sources that historically generate the largest share of incoming records.

The distributor view also makes it easier to identify where matching behavior differs by source.

Rather than assuming every distributor should be handled identically, the analysis supports evaluating:

> ### **Distributor + Score Range + Record Volume + Historical Outcome**

---

## 📑 Worksheet Analysis

The **Worksheet Analysis** view compares performance across the major worksheet / record groups:

- 📋 **Default D365**
- 🗃️ **Historic**
- 🔗 **In D365**

The dashboard compares these groups across:

- 📊 **Total Records**
- ⚡ **Quick Match Rate**
- 🔍 **Manual Match Rate**
- ✅ **Total Match Rate**

The underlying analysis showed meaningful differences between these populations.

For example:

- 🏆 **In D365:** highest Total Match Rate at **78.9%**
- ⚡ **Historic:** highest Quick Match Rate at **40.6%**
- 📦 **Default D365:** represented **48.7% of the analyzed workload**

Worksheet type therefore provided another indicator of **what kind of work employees should expect before beginning individual record research**.

---

## 🎯 Workload Prioritization

The **Workload Prioritization** view connects the Power BI dashboard directly to the project's central business question:

> ### **How much of the workload should the team process before additional employee effort begins producing diminishing returns?**

The dashboard visualizes the relationship between:

### **Cumulative Workload Coverage**

and

### **Cumulative Matching Performance**

This allows the underlying workload tradeoff to be viewed visually rather than only through static tables.

The purpose is to help answer:

> **How much additional work are we taking on, how many additional matches are we gaining, and what happens to overall matching performance as we expand the workload?**

---

# 🔥 Key Findings

The June 2026 analysis contained:

## **877 Total Records**

Of those records:

- ✅ **648 were successfully matched**
- 📈 **73.9% Total Match Rate**
- ⚡ **302 were Quick Matches**
- 📈 **34.4% Quick Match Rate**
- 🔍 **346 were Manual Matches**
- 📈 **39.5% Manual Match Rate**
- ➕ **19.2% resulted in Create New**
- ❌ **7.0% remained Not Mapped**

One of the most important findings was the contribution of manual research.

Quick Match successfully resolved **34.4% of the total dataset**, while manual research contributed another **39.5% of all records as successful Manual Matches**.

This demonstrated that manual review was not simply additional administrative effort.

> ### **Manual research was responsible for a substantial portion of successful customer mapping.**

The business question therefore became:

> ### **Where should that valuable but time-intensive manual research be concentrated?**

---

# 🎯 Score-Range Performance

Matching behavior changed substantially as scores decreased.

| Score Range | Records | Quick Match % | Manual Match % | Total Match % | Create New % | Not Mapped % |
|---|---:|---:|---:|---:|---:|---:|
| **80–70** | 141 | **87.2%** | 10.6% | **97.9%** | 1.4% | 0.7% |
| **69–60** | 98 | **77.6%** | 12.2% | **89.8%** | 4.1% | 6.1% |
| **59–50** | 95 | **58.9%** | 28.4% | **87.4%** | 7.4% | 5.3% |
| **49–40** | 136 | 22.1% | **43.4%** | 65.4% | 27.9% | 6.6% |
| **39–30** | 261 | 5.4% | **54.8%** | 60.2% | 29.9% | 10.0% |
| **29–20** | 132 | 1.5% | **61.4%** | 62.9% | 26.5% | 10.6% |
| **19–0** | 14 | 7.1% | **64.3%** | 71.4% | 28.6% | 0.0% |

---

# 🔎 What the Score Ranges Revealed

The score ranges did more than indicate whether a record might eventually be matched.

They helped indicate **what type of work the record was likely to require**.

---

## ⚡ Higher Scores → Quick-Match Heavy

### 80–70

- ⚡ Quick Match: **87.2%**
- 🔍 Manual Match: **10.6%**
- ✅ Total Match: **97.9%**

### 69–60

- ⚡ Quick Match: **77.6%**
- 🔍 Manual Match: **12.2%**
- ✅ Total Match: **89.8%**

These records represented strong opportunities for efficiently completing substantial amounts of successful matching work.

---

## 🔄 Middle Scores → Transition Toward Manual Research

### 59–50

- ⚡ Quick Match: **58.9%**
- 🔍 Manual Match: **28.4%**
- ✅ Total Match: **87.4%**

### 49–40

- ⚡ Quick Match: **22.1%**
- 🔍 Manual Match: **43.4%**
- ✅ Total Match: **65.4%**

The nature of the work changed substantially around these ranges.

Quick Matches became less common while manual research became increasingly important.

---

## 🔍 Lower Scores → Manual-Research Heavy

### 39–30

- ⚡ Quick Match: only **5.4%**
- 🔍 Manual Match: **54.8%**
- ✅ Total Match: **60.2%**

### 29–20

- ⚡ Quick Match: only **1.5%**
- 🔍 Manual Match: **61.4%**
- ✅ Total Match: **62.9%**

This answered an important part of leadership's original question.

Lower scores produced **very few Quick Matches**, but manual research continued to recover a meaningful number of successful mappings.

The finding was therefore more nuanced than:

> **"Low scores are not worth reviewing."**

Instead:

> ### **Lower scores represent a different, substantially more research-intensive type of work.**

That distinction is important when deciding how employee time should be allocated.

---

# 📈 Cumulative "Sweet Spot" Analysis

I used DAX measures to evaluate cumulative performance as progressively lower score ranges were included.

| Scores Included | % of Records Covered | Total Matches | Total Match Rate |
|---|---:|---:|---:|
| **80–70** | 16.1% | 138 | **97.9%** |
| **80–60** | 27.3% | 226 | **94.6%** |
| **80–50** | 38.1% | 309 | **92.5%** |
| **80–40** | 53.6% | 398 | **84.7%** |
| **80–30** | 83.4% | 555 | **75.9%** |
| **80–20** | 98.4% | 638 | **73.9%** |
| **80–0** | 100.0% | 648 | **73.9%** |

---

# ⭐ Major Efficiency Finding

One of the strongest findings was the relationship between **workload coverage and matching success**.

> ### **Scores from 50–80 represented only 38.1% of the total workload while producing 309 successful matches at a 92.5% Total Match Rate.**

If additional coverage was desired:

> ### **Expanding through scores 40–80 covered 53.6% of all records while producing 398 successful matches at an 84.7% Total Match Rate.**

This provided leadership with measurable options.

### Prioritize 50–80

**38.1% of workload**  
→ **309 matches**  
→ **92.5% Total Match Rate**

### Expand Through 40

**53.6% of workload**  
→ **398 matches**  
→ **84.7% Total Match Rate**

### Expand Through 30

**83.4% of workload**  
→ **555 matches**  
→ **75.9% Total Match Rate**

Instead of simply saying:

> **"Higher scores perform better."**

the analysis could answer:

> ### **"If we increase the amount of work reviewed, how much additional coverage and matching output do we gain, and what happens to overall efficiency?"**

This became the basis of the project's **cumulative sweet-spot analysis** and the **Power BI workload-prioritization view**.

---

# ✅ Answering Leadership Question #1

Leadership initially asked what percentage of the monthly workload could be handled by **starting with the strongest matches and working downward**.

The analysis provided a quantitative answer.

A team could address:

> **38.1% of the workload by reviewing scores from 50–80 while maintaining a 92.5% Total Match Rate.**

Or, if additional capacity was available:

> **53.6% of the workload could be covered by expanding through scores 40–80 while maintaining an 84.7% Total Match Rate.**

Rather than choosing an arbitrary threshold, leadership could evaluate the tradeoff between **coverage and expected matching performance**.

---

# ✅ Answering Leadership Question #2

Leadership also asked about the yield from lower-quality records.

The analysis showed that Quick Match performance dropped sharply:

- **80–70:** 87.2%
- **69–60:** 77.6%
- **59–50:** 58.9%
- **49–40:** 22.1%
- **39–30:** 5.4%
- **29–20:** 1.5%

However, Manual Match performance moved in the opposite direction:

- **80–70:** 10.6%
- **69–60:** 12.2%
- **59–50:** 28.4%
- **49–40:** 43.4%
- **39–30:** 54.8%
- **29–20:** 61.4%

This showed that lower-score records were not necessarily worthless.

They were **more expensive in employee research time because successful outcomes increasingly depended on manual investigation rather than Quick Match**.

That distinction gave leadership better information for deciding **when and where deeper research should be performed**.

---

# 📦 Distributor Performance

The analysis also revealed substantial differences in both **record volume and matching behavior across distributors**.

| Distributor | Records | Total Matches | Quick Match % | Manual Match % | Total Match % |
|---|---:|---:|---:|---:|---:|
| **Frontier Dental - USA** | 220 | 165 | 27.7% | 47.3% | 75.0% |
| **Henry Schein Dental** | 190 | 136 | 31.6% | 40.0% | 71.6% |
| **Benco Dental Company** | 123 | 92 | 39.8% | 35.0% | 74.8% |
| **Patterson Dental Supply - USA** | 121 | 84 | 40.5% | 28.9% | 69.4% |
| **Dental City** | 66 | 50 | 42.4% | 33.3% | 75.8% |
| **DC Dental** | 40 | 32 | 27.5% | 52.5% | 80.0% |
| **Safco Dental** | 31 | 25 | 35.5% | 45.2% | 80.6% |
| **Dental Health Products** | 30 | 25 | 43.3% | 40.0% | **83.3%** |

---

# 📦 Top 5 Monthly Workload Sources

The five largest distributors were:

1. **Frontier Dental - USA — 220 records**
2. **Henry Schein Dental — 190 records**
3. **Benco Dental Company — 123 records**
4. **Patterson Dental Supply - USA — 121 records**
5. **Dental City — 66 records**

Together:

> ### **720 of 877 records — approximately 82.1% of the entire analyzed workload — came from only five distributors.**

Frontier Dental - USA alone represented:

> **25.1% of all analyzed records.**

This finding has important workload-planning implications.

The monthly process did not consist of evenly distributed work across every distributor.

Instead, a relatively small number of distributors generated the overwhelming majority of the volume.

That means team capacity can be planned around the sources that historically create most of the work.

---

# 🏆 Distributor Matching Findings

Among distributors with at least 30 records:

- 🥇 **Dental Health Products:** 83.3% Total Match Rate
- **Safco Dental:** 80.6%
- **DC Dental:** 80.0%
- **Dental City:** 75.8%
- **Frontier Dental - USA:** 75.0%
- **Benco Dental Company:** 74.8%
- **Henry Schein Dental:** 71.6%
- **Patterson Dental Supply - USA:** 69.4%

Manual Match contribution also varied substantially:

- 🔍 **DC Dental:** 52.5%
- 🔍 **Frontier Dental - USA:** 47.3%
- 🔍 **Safco Dental:** 45.2%
- 🔍 **Henry Schein Dental:** 40.0%

This demonstrated why **one universal rule should not necessarily be applied to every distributor**.

The optimal workflow needed to consider:

> **Distributor + Score Range + Record Volume + Historical Outcome**

---

# 📑 Worksheet Performance

The 877 records were also segmented by worksheet type.

| Worksheet | Records | Quick Match % | Manual Match % | Total Match % | Create New % | Not Mapped % |
|---|---:|---:|---:|---:|---:|---:|
| **Default D365** | 427 | 34.0% | 35.8% | 69.8% | 24.4% | 5.9% |
| **Historic** | 180 | **40.6%** | 35.6% | 76.1% | 13.3% | 10.6% |
| **In D365** | 270 | 31.1% | **47.8%** | **78.9%** | 14.8% | 6.3% |

### Key Findings

- 🏆 **In D365 achieved the highest Total Match Rate at 78.9%** — 213 of 270 records successfully matched.
- 🔍 **In D365 had the highest Manual Match Rate at 47.8%**, showing the significant contribution of manual research within this group.
- ⚡ **Historic achieved the highest Quick Match Rate at 40.6%** — 73 of 180 records.
- 📦 **Default D365 represented 427 records — 48.7% of the entire workload**.
- ➕ **Default D365 had the highest Create New rate at 24.4%**.

Worksheet type therefore provided another indicator of **what kind of work employees should expect before beginning individual record research**.

---

# 🏆 Creating a Monthly Prioritization Strategy

Combining all dimensions created a stronger framework than using Match Score alone.

The analysis could consider:

### **Distributor**
+
### **Worksheet Type**
+
### **Score Range**
+
### **Record Volume**
+
### **Historical Match Performance**

Instead of:

> **Receive File → Start at the Top → Review Everything Equally**

the process could become:

> **Receive File → Identify Distributor → Identify Worksheet → Evaluate Score Range → Prioritize Historically Productive Segments → Assign Appropriate Work → Distribute Across Team**

This gives the team a better understanding of:

- 🎯 **What should be worked first**
- 📦 **Where most of the volume is coming from**
- ⚡ **Where Quick Matches are concentrated**
- 🔍 **Where manual research contributes the most**
- ➕ **Where Create New outcomes are more common**
- 👥 **How work can be distributed across employees**
- ⏱️ **Where limited employee time is likely to produce the greatest return**

---

# ⚙️ Automation Opportunities

The project also helped identify areas where the matching workflow could potentially support greater automation.

Instead of assuming one score threshold should work everywhere, potential automation opportunities could be evaluated using:

**Distributor**  
+
**Worksheet Type**  
+
**Score Range**  
+
**Record Volume**  
+
**Historical Match Performance**

Groups with consistently strong historical performance and sufficient record volume could be investigated as stronger candidates for automated handling or reduced manual intervention.

Minimum-record safeguards were also considered so that very small sample sizes would not incorrectly appear to represent reliable automation opportunities.

This created a framework for distinguishing between:

- 🤖 **Potential automation candidates**
- ⚡ **High-confidence Quick Match groups**
- 👤 **Records where human review adds substantial value**
- 🔍 **Research-heavy record groups**
- ⏱️ **Areas where additional manual effort may produce diminishing returns**

---

# ⏱️ Time & Efficiency Impact

The central business resource being optimized was **employee time**.

Customer matching requires research, judgment, and manual effort.

Every hour spent on one portion of the dataset is an hour that cannot simultaneously be spent on:

- High-probability matches
- Productive manual-review groups
- Current monthly records
- Historical backlog research
- Other data-quality responsibilities

The analysis made those tradeoffs visible.

---

## ❌ Traditional Approach

**Incoming Distributor Data**  
⬇️  
**Large Volume of Records**  
⬇️  
**Work Through Records With Limited Prioritization**  
⬇️  
**Significant Employee Research Time**  
⬇️  
**Incomplete Monthly Work**  
⬇️  
**Additional Backlog**

---

## ✅ Data-Driven Approach

**Incoming Distributor Data**  
⬇️  
**Identify High-Volume Distributors**  
⬇️  
**Identify Worksheet Type**  
⬇️  
**Apply Score-Range Performance**  
⬇️  
**Prioritize Highest-Value Segments**  
⬇️  
**Assign Work Based on Expected Research Requirements**  
⬇️  
**Distribute Work More Efficiently Across Team Members**  
⬇️  
**Monitor Performance Through Power BI**  
⬇️  
**Complete More Meaningful Work in Available Time**  
⬇️  
**Prevent Additional Backlog**

---

# 💡 Time Is a Business Resource

The goal was not simply to make an Excel report or Power BI dashboard.

The goal was to make the **people performing the actual work more efficient**.

The cumulative analysis quantified the tradeoff.

For example:

> ### **38.1% of the workload produced 309 matches at a 92.5% Total Match Rate.**

Expanding through the next score range:

> ### **53.6% of the workload produced 398 matches at an 84.7% Total Match Rate.**

That information allows the business to make a more informed decision about **how much employee time should be committed to progressively more research-intensive portions of the workload**.

Power BI provides a visual layer for communicating that relationship between **workload coverage and matching performance**.

In practical terms:

> ### **Better prioritization + less unnecessary research + smarter workload distribution = more completed work from the same available employee hours.**

---

# 🗃️ Backlog Reduction Strategy

Monthly workload efficiency and historical backlog reduction were directly connected.

Every month that incoming distributor records remained unresolved created **additional records that could eventually require historical research**.

Those records can become increasingly difficult over time because:

- 🏢 Ownership changes
- 🔄 Practice names change
- 🦷 Dentists retire
- 👨‍⚕️ New dentists take over practices
- 📍 Businesses relocate
- 🚪 Practices close
- 🏥 Multiple practices occupy the same address
- 📑 Customer information becomes outdated
- 🔁 Duplicate accounts accumulate

Therefore, improving the monthly process accomplishes two goals.

## 1️⃣ Prevent New Backlog

Process a greater portion of current distributor data while the information is still relatively current.

## 2️⃣ Reduce Existing Backlog

Use capacity created through better prioritization and efficiency to investigate older, more complicated records.

The monthly process therefore acts as the **front line of backlog prevention**.

---

# 🔮 Next Analytical Phase

The efficiency analysis was also intended to create capacity for a larger data-quality initiative involving the existing mapped-record population.

Leadership outlined a future process for evaluating the quality and continued relevance of a much larger population of **140,000+ previously mapped records**.

The proposed analytical workflow included:

1. 📥 Reading the **customer matrix from the ERP (F&O)**
2. 🔗 Joining it with the **Retail dataset** to identify addresses and customer names associated with distributor customer numbers
3. 🔗 Joining with the **Customer table** to retrieve the most recent customer name and address
4. 🧩 Segmenting customers into quality groups such as:
   - Single customer name / single address
   - Multiple customer names
   - Multiple addresses
   - Other potentially inconsistent relationships
5. 🎯 Using those groups to evaluate the quality and continued relevance of historical mappings

The immediate project therefore had a larger strategic purpose:

> ### **Reduce the amount of employee time consumed by recurring manual mapping so additional analytical capacity can be redirected toward larger-scale customer-data quality and backlog initiatives.**

---

# 🔄 Operational Impact

The complete analytical process created the following chain:

**Leadership Identifies Manual-Mapping Efficiency Problem**  
⬇️  
**Define Business Questions**  
⬇️  
**Months of Manual Matching Results**  
⬇️  
**Python/Pandas Consolidation**  
⬇️  
**Jupyter Notebook Data Processing**  
⬇️  
**Structured Analytical Dataset**  
⬇️  
**Excel PivotTables**  
⬇️  
**Power Pivot / DAX Measures**  
⬇️  
**Score-Range Performance Analysis**  
⬇️  
**Cumulative Sweet-Spot Analysis**  
⬇️  
**Distributor + Worksheet + Score-Range Findings**  
⬇️  
**Power BI Dashboard Development**  
⬇️  
**Executive KPI Reporting**  
⬇️  
**Distributor + Worksheet + Workload-Prioritization Views**  
⬇️  
**Visual Decision Support**  
⬇️  
**Identify Highest-Value Monthly Work**  
⬇️  
**Prioritize & Distribute Work Across the Team**  
⬇️  
**Reduce Low-Yield / Unnecessary Research**  
⬇️  
**Complete More Incoming Records**  
⬇️  
**Prevent Additional Backlog**  
⬇️  
**Create Employee Capacity**  
⬇️  
**Address More Difficult Historical Data Problems**

---

# 💰 Downstream Business Impact

Customer matching is not simply a data-cleaning exercise.

The process helps establish **which customer, dental practice, dentist, or organization is associated with distributor activity**.

Improving that information creates value beyond the immediate data team.

**More Accurate Customer Matching**  
⬇️  
**Cleaner Customer / Account Data**  
⬇️  
**Better Understanding of Customer Activity**  
⬇️  
**More Reliable Information for Downstream Teams**  
⬇️  
**Sales Can Better Identify Appropriate Customers to Contact**  
⬇️  
**More Focused Revenue-Generating Outreach**

Saving employee research time therefore has a compounding effect.

> **The same team can process more meaningful records, reduce unnecessary research, prevent additional backlog, create capacity for historical research, improve customer information, and support the teams that use that information for business activity.**

In essence:

> ### **Time saved in the data process creates capacity and value elsewhere in the organization.**

---

# 🛠️ Key Skills Demonstrated

- 🐍 **Python**
- 🐼 **Pandas**
- 📓 **Jupyter Notebook**
- 📊 **Advanced Microsoft Excel**
- 📈 **PivotTables**
- 🧮 **Power Pivot**
- 📐 **DAX Measures**
- 📊 **Microsoft Power BI**
- 📈 **Dashboard Development**
- 🎯 **Executive KPI Reporting**
- 📊 **Data Visualization**
- 📈 **Cumulative Performance Analysis**
- 📂 **Multi-Workbook Data Consolidation**
- 🧹 **Data Cleaning & Transformation**
- 🔗 **Entity Resolution / Customer Matching**
- 🎯 **Score-Range Segmentation**
- 📊 **KPI & Performance Analysis**
- ⚙️ **Workflow Optimization**
- 🤖 **Automation Opportunity Analysis**
- 🔍 **Manual Data Validation**
- ⏱️ **Operational Efficiency Analysis**
- 🧠 **Root-Cause Analysis**
- 💡 **Business Process Analysis**
- 📋 **Requirements Translation**
- 🎯 **Data-Driven Decision Support**
- 📊 **Business Intelligence Reporting**

---

# 💻 Tools Used

| Tool | Application |
|---|---|
| **Python** | Automated data processing and analysis |
| **Pandas** | Workbook consolidation, cleaning, grouping, and aggregation |
| **Jupyter Notebook** | Python development and analytical workflow |
| **Microsoft Excel** | Analysis, reporting, and presentation |
| **PivotTables** | Distributor, worksheet, score-range, and outcome analysis |
| **Power Pivot** | Data-model calculations and analytical measures |
| **DAX** | Match-rate and cumulative-performance measures |
| **Power BI** | Interactive dashboards, KPI reporting, performance visualization, and workload-prioritization reporting |
| **Excel Formulas** | Classification, calculations, and supporting workflow metrics |

---

# 📌 Project Architecture

**Business Questions From Leadership**  
⬇️  
**Manual Distributor Review**  
⬇️  
**Classify Mapping Outcomes**  
⬇️  
**Python / Pandas**  
⬇️  
**Jupyter Notebook**  
⬇️  
**Consolidate Multiple Workbooks**  
⬇️  
**Clean & Standardize Data**  
⬇️  
**Create Score Ranges**  
⬇️  
**Calculate Mapping Outcomes**  
⬇️  
**Generate Structured Analytical Data**  
⬇️  
**Microsoft Excel**  
⬇️  
**PivotTables**  
⬇️  
**Power Pivot / DAX Measures**  
⬇️  
**Cumulative Sweet-Spot Analysis**  
⬇️  
**Distributor / Worksheet / Score Analysis**  
⬇️  
**Microsoft Power BI**  
⬇️  
**Executive KPI Reporting**  
⬇️  
**Distributor Analysis**  
⬇️  
**Worksheet Analysis**  
⬇️  
**Workload Prioritization**  
⬇️  
**Visual Decision Support**  
⬇️  
**Answer Leadership's Business Questions**  
⬇️  
**Identify Monthly Work Priorities**  
⬇️  
**Improve Team Efficiency**  
⬇️  
**Prevent Additional Backlog**  
⬇️  
**Create Capacity for Larger Data-Quality Initiatives**

---

# ✅ Outcome

This project transformed **several months of manual customer-matching work into a repeatable analytical and business-intelligence framework for managing recurring distributor data**.

More importantly, it began with **specific business questions from leadership**:

> **How much of the monthly workload can be completed efficiently by starting with stronger potential matches?**

> **What is the actual yield from researching lower-quality matches?**

> **Which portions of the process are low-yield?**

> **How can employee time be freed for backlog reduction and larger customer-data quality initiatives?**

Using **Python and Pandas in Jupyter Notebook**, I consolidated completed workbook results and converted individual record-level decisions into structured data that could be analyzed at scale.

Using **Excel PivotTables, Power Pivot, and custom DAX measures**, I analyzed those results across distributors, worksheet types, score ranges, record volumes, final mapping outcomes, and cumulative performance.

Using **Power BI**, I then translated the analytical framework into an interactive dashboard that presented the findings through:

- 📈 **Executive KPIs**
- 📦 **Distributor analysis**
- 📑 **Worksheet analysis**
- 🎯 **Score-range performance**
- 📊 **Workload prioritization**
- 📉 **Cumulative workload-versus-performance analysis**

The analysis demonstrated that the **877 analyzed records were not 877 equal pieces of work**.

Different portions of the dataset had dramatically different:

- 📦 Record volumes
- ⚡ Quick Match rates
- 🔍 Manual Match rates
- 📈 Total Match rates
- ⏱️ Research requirements
- 💡 Potential value per employee hour

The cumulative analysis quantified those tradeoffs.

> ### **Scores from 50–80 covered only 38.1% of the workload while producing 309 successful matches at a 92.5% Total Match Rate.**

> ### **Expanding through 40–80 covered 53.6% of the workload while producing 398 successful matches at an 84.7% Total Match Rate.**

Distributor analysis showed that:

> ### **The five highest-volume distributors accounted for approximately 82.1% of the entire analyzed workload.**

Worksheet analysis showed additional differences:

- **In D365:** highest Total Match Rate at **78.9%**
- **Historic:** highest Quick Match Rate at **40.6%**
- **Default D365:** **48.7% of the entire workload**

The score analysis also revealed an important operational distinction:

> ### **As scores decreased, Quick Match success declined dramatically while successful outcomes became increasingly dependent on manual research.**

That meant the analysis did not simply identify which records were "good" or "bad."

It identified **different types of work and the employee effort associated with them**.

Power BI then made those patterns easier to communicate by converting the analytical results into **KPIs, comparative visualizations, and workload-prioritization reporting**.

The resulting framework could help determine:

- 🎯 **What should be worked first**
- 📦 **Where most monthly volume is coming from**
- ⚡ **Which records can likely be completed quickly**
- 🔍 **Where manual research contributes substantial value**
- 📈 **How much additional coverage is gained by expanding the review threshold**
- ⏱️ **Where additional research begins producing diminishing returns**
- 👥 **How work can be distributed more intelligently across the team**
- 🤖 **Where automation may provide additional value**
- 🗃️ **How monthly efficiency can create capacity for backlog reduction**
- 📊 **How operational performance can be communicated through interactive BI reporting**

Most importantly, the project connected the original leadership questions to a measurable operational strategy:

> ### **Business Question → Historical Data → Python/Pandas → Excel PivotTables → Power Pivot/DAX → Power BI → Quantified Findings → Visual Decision Support → Work Prioritization → Time Savings → Backlog Capacity → Better Customer Data → Downstream Business Value**

Rather than using analytics simply to describe what had already happened, this project used **Python, Pandas, Jupyter Notebook, Excel PivotTables, Power Pivot, DAX, Power BI, and business analysis to answer leadership's questions, communicate the findings, and determine how future work could be performed more efficiently.**
