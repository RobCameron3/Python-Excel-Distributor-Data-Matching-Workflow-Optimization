# 📊 Python & Excel – Distributor Data Matching & Workflow Optimization

### *Data Analysis, Automation & Operational Strategy Project*

---

## 🌎 Overview

Solmetex receives recurring customer data from dental distributors that must be **matched to existing customer accounts, manually researched, created as new accounts, or left unmapped when sufficient evidence cannot be found**.

Over several months, I manually reviewed distributor workbooks and classified thousands of customer records based on their final mapping outcomes. This created a historical dataset showing **what types of records the company receives, which records can be resolved efficiently, and where significant manual research is required**.

I then developed a **Python/Pandas workflow in Jupyter Notebook** to consolidate the completed workbook data and transform months of manual review into structured summary data.

The Python output was brought into **Microsoft Excel**, where I created **PivotTables and performance analyses** across distributors, worksheet types, score ranges, record volumes, and mapping outcomes.

The ultimate goal was not simply to report what had already happened. It was to use historical performance to develop a **repeatable strategy for handling incoming monthly distributor data more efficiently**, prevent additional backlog from accumulating, and create more team capacity to address Solmetex's more difficult historical customer-mapping backlog.

---

## 🎯 Objective

Determine **what types of customer records Solmetex should expect each month and how the team should prioritize and distribute that workload**.

Rather than treating every incoming record equally, the project focused on answering:

> **Which distributors, workbook types, and match-score ranges generate the greatest volume and strongest matching opportunities, and how can those patterns be used to process the monthly workload more efficiently?**

The objective was to turn months of completed manual matching work into a **data-driven framework for deciding what should be worked first, where manual research provides value, and where automation or prioritization could save employee time.**

---

## ❓ Business Challenge

Solmetex was working through a **historical customer-mapping backlog** while continuing to receive new distributor data every month.

This created two connected problems.

### 📥 Recurring Monthly Data

New distributor records continuously needed to be:

- ⚡ Quick Matched
- 🔍 Manually researched and matched
- ➕ Created as new customer accounts
- ❌ Classified as Not Mapped when sufficient evidence could not be established

Without an efficient process for handling the recurring monthly workload, unfinished records would simply become **additional backlog**.

### 🗃️ Historical Backlog

The historical backlog was more difficult to resolve than current incoming records.

Older dental records may involve practices that have:

- 🏢 Changed ownership
- 📍 Relocated
- 🚪 Closed
- 🦷 Been succeeded by another dentist or practice
- 🔄 Changed business names
- 🤝 Merged with another organization
- 🏥 Begun sharing an address with another practice
- 📑 Accumulated duplicate or outdated customer information

These records often require significantly more research because the business associated with an old transaction may no longer appear the same way today.

This created the central operational problem:

> **The team could not effectively reduce the historical backlog without first developing an efficient way to control the new distributor data arriving every month.**

---

## 🔍 Step 1: Manual Customer Matching & Classification

I spent several months working directly through distributor workbooks and researching customer records.

Each record had to be evaluated to determine whether the distributor customer corresponded to an existing Solmetex account.

The workflow tracked several important fields, including:

- ⚡ **Quick Match (Y/N)**
- 🔍 **Manual Review Required (Y/N)**
- ✅ **Manual Match (Y/N)**
- 📋 **Final Mapping Status**
- 🎯 **Match Score**
- 📅 **Invoice / activity information**
- 📦 **Distributor**
- 📑 **Worksheet / record type**

The final mapping outcomes included:

- ⚡ **Quick Match**
- 🔍 **Manual Match**
- ➕ **Create New**
- ❌ **Not Mapped**

This manual work created the historical foundation needed to understand **which types of records were actually producing successful mappings.**

---

## 🐍 Step 2: Python & Jupyter Notebook Data Pipeline

After completing the manual analysis, I developed a **Python workflow in Jupyter Notebook using Pandas** to consolidate and analyze the completed workbook results.

Instead of manually counting outcomes across numerous worksheets, Python transformed the completed work into a structured analytical dataset.

### Python/Pandas was used to:

- 📂 Read data across multiple distributor workbooks
- 🔗 Consolidate completed records into a unified dataset
- 🧹 Clean and standardize fields
- 🏷️ Interpret final mapping outcomes
- 🎯 Convert individual match scores into defined score ranges
- ⚡ Count Quick Matches
- 🔍 Count Manual Matches
- ➕ Count Create New outcomes
- ❌ Count Not Mapped outcomes
- 📦 Group results by distributor
- 📑 Group results by worksheet type
- 📊 Generate summary datasets for further analysis

This converted **months of individual manual decisions into structured data that could be analyzed at scale.**

---

## 🎯 Step 3: Match-Score Range Analysis

Individual customer records contained calculated match scores.

Rather than evaluating thousands of individual scores independently, I grouped those scores into defined ranges so I could measure how mapping performance changed as scores decreased.

This made it possible to compare:

**Score Range**
+
**Number of Records**
+
**Quick Matches**
+
**Manual Matches**
+
**Create New**
+
**Not Mapped**
+
**Overall Match Performance**

The purpose was to determine whether certain portions of the score distribution consistently produced more valuable results than others.

---

## 📊 Step 4: Excel PivotTable Analysis

After Python generated the consolidated summary data, I transferred the output into **Microsoft Excel and built PivotTables** to make the results easier to analyze and communicate.

The PivotTables broke performance down across multiple dimensions, including:

- 📦 **Distributor**
- 📑 **Worksheet type**
- 🎯 **Match-score range**
- 📊 **Total records**
- ⚡ **Quick Matches**
- 🔍 **Manual Matches**
- ➕ **Create New**
- ❌ **Not Mapped**
- 📈 **Match percentages**
- 📋 **Final mapping outcomes**

This allowed me to move beyond looking at individual customer records and instead evaluate the **performance of the entire matching workflow**.

---

## 📈 Step 5: Distributor & Workbook Performance

Not every distributor produced the same type or quality of data.

Using the PivotTable analysis, I compared distributors and workbook types to determine:

- 📦 Which sources generated the greatest record volume
- ⚡ Which produced the strongest Quick Match results
- 🔍 Which required heavier manual research
- ❌ Which produced larger concentrations of Not Mapped records
- 🎯 Which score ranges were most productive within each source

This was important because a single universal score threshold would not necessarily represent every distributor equally.

Instead, the analysis could identify **specific distributor + score-range combinations** that historically produced stronger results.

---

## 🔥 Step 6: Identify the Highest-Value Work

One of the most important outcomes was identifying **where employee time produced the greatest return**.

Rather than assigning equal attention to every record, the analysis showed that some portions of the workload contained a much greater concentration of successful matches.

### 📊 Key Finding

> **Scores between 40–80 captured 85.5% of Quick Matches while representing only 11.7% of the evaluated records.**

At the opposite end:

> **Scores below 40 represented a much larger portion of the workload while producing only 2.3% of Quick Matches.**

This demonstrated that **record volume and record value were not distributed evenly throughout the workload.**

The analysis therefore provided a quantitative basis for determining where the team's attention could produce the greatest number of successful outcomes in the least amount of time.

---

## 🏆 Step 7: Identify Priority Workbooks & Score Ranges

The analysis was expanded beyond overall score performance to identify the **highest-value workbook/distributor and score-range combinations**.

This allowed the monthly workload to be approached more strategically.

Instead of:

> **Receive file → Start at the top → Review everything equally**

The process could become:

> **Receive file → Identify distributor/workbook → Evaluate score range → Prioritize historically productive segments → Distribute work accordingly**

The analysis could therefore identify the **top-performing workbooks and score ranges that should receive priority attention each month**.

This was especially valuable because the historical data provided an indication of **what types of results the team could expect from future monthly distributor files.**

---

## ⚙️ Step 8: Identify Automation Opportunities

The project also helped identify portions of the matching process that could potentially support greater automation.

By analyzing:

**Distributor**
+
**Score Range**
+
**Record Volume**
+
**Historical Match Performance**

I could identify groups where matching behavior was consistently strong.

Minimum-record safeguards were also considered so that extremely small samples would not incorrectly appear to represent reliable automation opportunities.

This created a more targeted framework for evaluating automation rather than assuming that **one score threshold should apply to every distributor and every record type.**

---

## ⏱️ Time & Efficiency Impact

The core value of the project was **time efficiency**.

Customer matching requires employee research time, and that time is limited.

If team members spend large amounts of time researching portions of the dataset that historically produce very few successful matches, less time remains for records with stronger matching potential or for addressing the historical backlog.

The project created a way to use historical data to determine **where employee time should be concentrated.**

### Before

**Incoming Distributor Data**  
⬇️  
**Large Volume of Records**  
⬇️  
**Significant Manual Review**  
⬇️  
**Employee Research Time Consumed**  
⬇️  
**Unfinished Records Become Additional Backlog**

### Data-Driven Approach

**Incoming Distributor Data**  
⬇️  
**Identify Distributor / Workbook**  
⬇️  
**Apply Historical Score-Range Findings**  
⬇️  
**Prioritize Highest-Value Records**  
⬇️  
**Distribute Work More Efficiently Across the Team**  
⬇️  
**Complete Monthly Work Faster**  
⬇️  
**Create Capacity for Historical Backlog**

In this process, **time has direct business value**.

Reducing unnecessary research means the same team can process more meaningful records without simply increasing labor hours.

---

## 🗃️ Backlog Reduction Strategy

The monthly workflow and historical backlog were directly connected.

Every month that incoming distributor records were not completed created **additional records that would eventually require historical research**.

Those records could become more difficult over time because:

- Ownership changes
- Practice names change
- Dentists retire
- New dentists take over practices
- Businesses relocate
- Practices close
- Multiple businesses occupy the same address
- Customer records become outdated
- Duplicate accounts accumulate

Therefore, improving the monthly process did more than make the current month's work faster.

It helped **prevent the future backlog from growing while simultaneously creating additional capacity to attack the existing backlog.**

---

## 🔄 Operational Impact

The project established a chain of operational improvements:

**Months of Manual Matching Results**  
⬇️  
**Python/Pandas Consolidation in Jupyter Notebook**  
⬇️  
**Structured Summary Data**  
⬇️  
**Excel PivotTable Analysis**  
⬇️  
**Distributor + Workbook + Score-Range Performance**  
⬇️  
**Identify Highest-Value Monthly Work**  
⬇️  
**Distribute Team Work More Efficiently**  
⬇️  
**Reduce Time Spent on Low-Yield Research**  
⬇️  
**Process Incoming Monthly Data Faster**  
⬇️  
**Prevent Additional Backlog**  
⬇️  
**Create Capacity to Resolve Historical Backlog**

---

## 💰 Downstream Business Impact

Customer matching is not simply a data-cleaning exercise.

The matching process helps establish **which customer, dental practice, dentist, or organization is associated with distributor activity**.

Improving that information creates a downstream chain:

**More Accurate Customer Matching**  
⬇️  
**Cleaner Customer / Account Data**  
⬇️  
**Better Understanding of Customer Activity**  
⬇️  
**More Useful Information for Sales**  
⬇️  
**Sales Can Better Identify Which Customers to Contact**  
⬇️  
**More Focused Revenue-Generating Outreach**

This means improvements in matching efficiency can create value beyond the data team.

**Saving employee research time allows more records to be processed, improves the customer information available to other teams, and ultimately supports revenue-generating business activity.**

---

## 🛠️ Key Skills Demonstrated

- 🐍 **Python**
- 🐼 **Pandas**
- 📓 **Jupyter Notebook**
- 📊 **Microsoft Excel**
- 📈 **PivotTables**
- 🧮 **Advanced Excel Analysis**
- 📂 **Multi-Workbook Data Consolidation**
- 🧹 **Data Cleaning & Transformation**
- 🔗 **Entity Resolution / Customer Matching**
- 🎯 **Score-Range Segmentation**
- 📊 **KPI & Performance Analysis**
- ⚙️ **Workflow Optimization**
- 🤖 **Automation Opportunity Analysis**
- 🔍 **Manual Data Validation**
- 🧠 **Root-Cause Analysis**
- 💡 **Business Process Analysis**

---

## 💻 Tools Used

| Tool | Application |
|---|---|
| **Python** | Automated data processing and analysis |
| **Pandas** | Workbook consolidation, cleaning, grouping, and aggregation |
| **Jupyter Notebook** | Python development and analytical workflow |
| **Microsoft Excel** | Analysis, reporting, and presentation |
| **PivotTables** | Distributor, workbook, score-range, and outcome analysis |
| **Excel Formulas** | Classification, calculations, and workflow metrics |

---

## 📌 Project Architecture

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
**Generate Summary Data**  
⬇️  
**Excel PivotTables**  
⬇️  
**Distributor / Workbook / Score Analysis**  
⬇️  
**Identify Monthly Work Priorities**  
⬇️  
**Improve Team Efficiency**  
⬇️  
**Create Capacity for Backlog Reduction**

---

## ✅ Outcome

This project transformed **several months of manual customer-matching work into a repeatable analytical framework for managing Solmetex's recurring distributor data.**

Using **Python and Pandas in Jupyter Notebook**, I consolidated the completed workbook results and converted record-level decisions into structured summary data.

Using **Excel PivotTables**, I analyzed that data across distributors, workbook types, score ranges, record volumes, and final mapping outcomes to identify **where successful matches were concentrated and where employee research time was producing limited returns**.

The analysis produced measurable findings—including the discovery that **40–80 score records captured 85.5% of Quick Matches while representing only 11.7% of evaluated records**, compared with only **2.3% of Quick Matches coming from scores below 40**.

More importantly, the project established a method for identifying the **highest-priority workbooks, distributors, and score ranges each month**, allowing work to be distributed more efficiently across the team.

That efficiency creates a larger business benefit:

> **Handle incoming monthly data faster → prevent new backlog → free employee time → attack the existing historical backlog → improve customer data → provide better information to Sales → support revenue-generating activity.**

The project demonstrates how **Python automation, Excel analytics, operational knowledge, and business reasoning can be combined to turn historical data into a practical strategy for improving an ongoing business process.**
