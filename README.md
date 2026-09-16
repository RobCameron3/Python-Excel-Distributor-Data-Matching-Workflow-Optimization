# 📊 Python & Excel – Distributor Data Matching & Workflow Optimization

### *Data Analysis, Automation & Operational Strategy Project*

> **Transforming months of manual customer-matching data into a Python- and Excel-driven strategy for prioritizing monthly workloads, improving team efficiency, preventing new backlog, and creating capacity to resolve complex historical customer records.**

---

## 🚀 Project Summary

This project transformed **several months of manual distributor/customer matching work into a repeatable, data-driven operational strategy**.

After manually reviewing and classifying customer records across multiple distributor workbooks, I developed a **Python/Pandas workflow in Jupyter Notebook** to consolidate the completed results, clean and organize the data, group match scores into meaningful ranges, and summarize mapping outcomes at scale.

I then brought the Python-generated results into **Microsoft Excel and built PivotTables and performance analyses** to determine how matching success changed across **distributors, workbook types, score ranges, record volumes, and final mapping outcomes**.

The purpose went far beyond reporting historical results. The analysis showed **where the team's limited research time could produce the greatest return**, helping determine which portions of incoming monthly distributor data should be prioritized, how work could be distributed more efficiently across team members, and where low-yield manual research could be reduced.

This was especially important because Solmetex was simultaneously dealing with a **historical customer-mapping backlog**. If incoming monthly records were not processed efficiently, they would simply become additional backlog—and those records become increasingly difficult to resolve as dental practices change ownership, relocate, close, change names, or transition to successor practices.

Ultimately, the project connected technical analysis to a larger business objective:

> **Process monthly data more efficiently → save employee research time → prevent additional backlog → create capacity to resolve historical records → improve customer/account data → provide better information to Sales → support revenue-generating activity.**

---

## ⭐ Project Highlights

- 🐍 Developed a **Python/Pandas workflow in Jupyter Notebook** to consolidate and analyze completed customer-matching results across multiple distributor workbooks.
- 📊 Built **Excel PivotTables and performance analyses** to compare distributors, workbook types, score ranges, record volumes, and final mapping outcomes.
- 🎯 Identified the **highest-value portions of the monthly workload**, giving the team a data-driven basis for deciding which records should receive attention first.
- ⚡ Found that **scores from 40–80 captured 85.5% of Quick Matches while representing only 11.7% of evaluated records**.
- 🔻 Found that **scores below 40 generated only 2.3% of Quick Matches**, highlighting a large portion of the workload with comparatively low Quick Match return.
- 📦 Analyzed **distributor + workbook + score-range combinations** rather than relying on one universal threshold.
- ⏱️ Created a framework for **reducing unnecessary manual research and allocating employee time toward higher-value work**.
- 👥 Made the monthly workload easier to **prioritize and distribute across team members**, helping the same team process incoming records more efficiently.
- 🗃️ Connected monthly efficiency directly to **backlog reduction**: completing current records faster helps prevent them from becoming future backlog while freeing time to research more difficult historical records.
- 🤖 Identified areas where consistent historical matching performance could support **future automation opportunities**.
- 💰 Connected data-team efficiency to downstream business value by improving the customer/account information available for **Sales targeting and revenue-generating outreach**.

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

- ⚡ **Quick Matched**
- 🔍 **Manually researched and matched**
- ➕ **Created as new customer accounts**
- ❌ **Classified as Not Mapped** when sufficient evidence could not be established

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

- 🎯 **Score Range**
- 📊 **Number of Records**
- ⚡ **Quick Matches**
- 🔍 **Manual Matches**
- ➕ **Create New**
- ❌ **Not Mapped**
- 📈 **Overall Match Performance**

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

Not every distributor produced the same type, volume, or quality of data.

Using the PivotTable analysis, I compared distributors and workbook types to determine:

- 📦 Which sources generated the greatest record volume
- ⚡ Which produced the strongest Quick Match results
- 🔍 Which required heavier manual research
- ❌ Which produced larger concentrations of Not Mapped records
- 🎯 Which score ranges were most productive within each source

This was important because a single universal score threshold would not necessarily represent every distributor equally.

Instead, the analysis could identify **specific distributor + score-range combinations** that historically produced stronger results.

This gave the team a clearer expectation of **what type and volume of work could arrive each month and how different distributor files should be approached.**

---

## 🔥 Step 6: Identify the Highest-Value Work

One of the most important outcomes was identifying **where employee time produced the greatest return**.

Rather than assigning equal attention to every record, the analysis showed that some portions of the workload contained a much greater concentration of successful matches.

### 📊 Key Quantitative Findings

> **Scores between 40–80 captured 85.5% of Quick Matches while representing only 11.7% of the evaluated records.**

At the opposite end:

> **Scores below 40 represented a much larger portion of the workload while producing only 2.3% of Quick Matches.**

These results demonstrated that **record volume and record value were not distributed evenly throughout the workload**.

A relatively targeted portion of the data contained the overwhelming majority of Quick Match opportunities, while substantial volumes of lower-scoring records produced comparatively little Quick Match value.

That distinction matters operationally because every record researched requires employee time.

The analysis therefore provided a quantitative basis for asking:

> **Where can the team spend its next hour to complete the greatest amount of meaningful work?**

---

## 🏆 Step 7: Prioritize Workbooks, Distributors & Score Ranges

The analysis expanded beyond overall score performance to identify the **highest-value workbook/distributor and score-range combinations**.

Instead of approaching every monthly file the same way:

> **Receive File → Start at the Top → Review Everything Equally**

The process could become:

> **Receive File → Identify Distributor/Workbook → Evaluate Score Range → Prioritize Historically Productive Segments → Distribute Work Across the Team**

This created a much more strategic approach to the monthly workload.

The historical analysis could help the team understand:

- 📦 **Which distributor files deserve immediate attention**
- 🎯 **Which score ranges should be tackled first**
- 📊 **How much work is likely to fall into each category**
- ⚡ **Where Quick Matches are most concentrated**
- 🔍 **Where manual research is likely to provide value**
- ⏱️ **Where significant employee time may produce limited matching return**
- 👥 **How work can be divided across team members more efficiently**

Rather than simply knowing how the previous month's files performed, the team could use historical patterns to establish **expectations and priorities for future incoming files.**

---

## ⚙️ Step 8: Identify Automation Opportunities

The project also helped identify portions of the matching process that could potentially support greater automation.

By combining:

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

The analysis could therefore help distinguish between:

- 🤖 Records potentially suitable for greater automation
- 👤 Records where human review remained valuable
- 🔍 Records requiring deeper manual research
- ⏱️ Records where extensive research historically produced limited return

---

## ⏱️ Time & Efficiency Impact

The core business value of the project was **time efficiency**.

Customer matching requires employee research time, and that time is limited.

If several team members spend significant portions of their day researching records that historically produce very few successful matches, that time cannot simultaneously be spent on:

- Higher-probability customer matches
- More valuable manual-review opportunities
- Incoming monthly records
- Difficult historical records
- Other data-quality responsibilities

The analysis created a way to use historical results to determine **where employee time should be concentrated.**

### ❌ Before

**Incoming Distributor Data**  
⬇️  
**Large Volume of Records**  
⬇️  
**Significant Manual Review**  
⬇️  
**Employee Research Time Consumed**  
⬇️  
**Unfinished Records Remain**  
⬇️  
**Records Become Additional Backlog**

### ✅ Data-Driven Approach

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
**Reduce Low-Yield Research**  
⬇️  
**Complete More Monthly Work in the Available Time**  
⬇️  
**Create Capacity for Historical Backlog**

### ⏱️ Why Time Matters

In this workflow, **employee time has direct business value**.

The goal was not simply to make an Excel report faster.

The goal was to make the **people performing the actual work more efficient**.

If historical data can identify which records are most likely to produce meaningful results, team members can spend less time repeatedly researching low-yield portions of the workload and more time completing work that moves the process forward.

That means:

> **Less unnecessary research + better prioritization + smarter workload distribution = more completed work from the same available employee hours.**

---

## 🗃️ Backlog Reduction Strategy

The monthly workflow and historical backlog were directly connected.

Every month that incoming distributor records were not completed created **additional records that would eventually require historical research**.

Those records could become more difficult over time because:

- 🏢 Ownership changes
- 🔄 Practice names change
- 🦷 Dentists retire
- 👨‍⚕️ New dentists take over practices
- 📍 Businesses relocate
- 🚪 Practices close
- 🏥 Multiple businesses occupy the same address
- 📑 Customer records become outdated
- 🔁 Duplicate accounts accumulate

A customer relationship that may be relatively straightforward to identify today can become substantially harder to reconstruct years later.

Therefore, improving the monthly process did more than make the current month's work faster.

It helped accomplish **two goals at the same time**:

### 1️⃣ Prevent the backlog from continuing to grow

Process a greater portion of current distributor data before those unresolved records become future historical research.

### 2️⃣ Create capacity to reduce the existing backlog

Time saved through better prioritization can be redirected toward the older records that require deeper investigation.

This is why controlling the monthly workload was essential to addressing the larger historical problem.

---

## 🔄 Operational Impact

The complete workflow created a chain of operational improvements:

**Months of Manual Matching Results**  
⬇️  
**Python/Pandas Consolidation in Jupyter Notebook**  
⬇️  
**Structured Analytical Dataset**  
⬇️  
**Excel PivotTable Analysis**  
⬇️  
**Distributor + Workbook + Score-Range Performance**  
⬇️  
**Identify Highest-Value Monthly Work**  
⬇️  
**Prioritize & Distribute Team Work More Efficiently**  
⬇️  
**Reduce Time Spent on Low-Yield Research**  
⬇️  
**Complete More Incoming Monthly Records**  
⬇️  
**Prevent Additional Backlog**  
⬇️  
**Free Employee Capacity**  
⬇️  
**Resolve More Difficult Historical Records**

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
**Sales Can Better Identify Appropriate Customers to Contact**  
⬇️  
**More Focused Revenue-Generating Outreach**

The project's value therefore extends beyond the immediate data workflow.

> **Saving employee research time allows more records to be processed, reduces unnecessary manual effort, creates capacity for backlog reduction, improves customer information, and supports the teams that use that information for business activity.**

In essence, **time saved in the data process creates capacity elsewhere in the organization.**

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
**Prevent Additional Backlog**  
⬇️  
**Create Capacity for Historical Backlog Reduction**

---

## ✅ Outcome

This project transformed **several months of manual customer-matching work into a repeatable analytical framework for managing Solmetex's recurring distributor data.**

Using **Python and Pandas in Jupyter Notebook**, I consolidated completed workbook results and converted thousands of individual record-level decisions into structured summary data that could be analyzed at scale.

Using **Excel PivotTables**, I analyzed the results across distributors, workbook types, score ranges, record volumes, and final mapping outcomes to identify **where successful matches were concentrated and where employee research time was producing limited returns**.

The analysis produced measurable findings—including the discovery that **40–80 score records captured 85.5% of Quick Matches while representing only 11.7% of evaluated records**, compared with only **2.3% of Quick Matches coming from scores below 40**.

But the most important outcome went beyond those individual percentages.

The project established a method for identifying the **highest-priority distributors, workbooks, and score ranges each month**, giving the team a framework for deciding **what to work first, what results to expect, and how to distribute the workload more efficiently across available employees**.

That efficiency creates a much larger business chain:

> ### **Handle incoming monthly data faster → save employee time → prevent new backlog → free capacity → attack the existing historical backlog → improve customer data → provide better information to Sales → support revenue-generating activity.**

Rather than using Python and Excel simply to describe historical performance, this project used **data to improve how future work could be performed**.

It demonstrates how **Python automation, Pandas data transformation, Jupyter Notebook analysis, Excel PivotTables, operational knowledge, and business reasoning** can be combined to turn months of manual work into a practical strategy for improving an ongoing business process.
