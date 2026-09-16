📊 Python & Excel – Distributor Data Matching & Workflow Optimization
(Data Analysis, Automation & Operational Strategy Project)
🌎 Overview

Solmetex receives recurring customer data from dental distributors that must be matched to existing customer accounts or researched manually. I spent several months reviewing this data, classifying mapping outcomes, and analyzing how the workload differed by distributor, worksheet type, match-score range, and final mapping status.

I then developed a Python/Pandas workflow in Jupyter Notebook to consolidate the completed workbook data and built Excel PivotTable analyses to determine which portions of the monthly workload could be handled most efficiently.

The project ultimately established a repeatable strategy for processing incoming monthly distributor data, creating capacity for the team to address a more difficult historical customer-mapping backlog.

🎯 Objective

Determine what types of records Solmetex should expect each month and how the team should prioritize them.

Rather than treating every incoming record equally, the goal was to answer:

Which distributors and score ranges generate the greatest volume and strongest matching opportunities, and how should that information be used to distribute monthly work across the team?

Solving the recurring monthly workload was critical because any records that were not completed would become additional backlog.

❓ Business Challenge

Solmetex was working through a customer-mapping backlog while continuing to receive new distributor data every month.

The historical backlog was substantially harder to resolve than normal incoming records. Dental practices can change ownership, relocate, close, transition to successor dentists, or coexist with other practices at the same address. Older records therefore often require extensive research and can also contain duplicate or outdated account information.

The team could not efficiently reduce that backlog if new monthly records continued accumulating faster than they could be processed.

The first problem was therefore not simply “How do we clear the backlog?”

It was:

“How do we create an efficient and predictable process for handling the recurring monthly workload so today's records don't become tomorrow's backlog?”

💡 Solution

I manually reviewed the distributor workbooks over several months and classified records according to their actual mapping outcomes, including Quick Match, Manual Match, Create New, and Not Mapped. The workflow explicitly tracked Quick Matches, completion of manual review, manual-match outcomes, and the resulting final mapping status.

I then used Python, Pandas, and Jupyter Notebook to consolidate those completed results and transform the manual work into structured analytical data.

Using Excel PivotTables and additional analysis, I compared:

Distributor × Worksheet Type × Score Range × Record Volume × Mapping Outcome

This allowed me to identify where the workload was actually concentrated and which combinations consistently produced useful matches.

📊 Key Results

The analysis identified the highest-priority workbooks/distributors and score ranges, giving the team a data-driven way to determine where monthly review time should be concentrated instead of distributing work blindly.

More importantly, the analysis established what Solmetex could reasonably expect from incoming distributor files each month.

For example, one analysis found that the 40–80 score range contained 85.5% of Quick Matches while representing only 11.7% of the records being evaluated. Records below 40 represented a much larger portion of the workload while producing only 2.3% of Quick Matches.

I also analyzed distributor × score-range combinations, rather than assuming one universal score threshold worked equally well for every distributor. Minimum-record safeguards were incorporated so small samples would not be mistaken for meaningful high-performing segments.

That provided a framework for determining:

Where should we start? → What should be prioritized? → What can be handled quickly? → What requires manual research? → How should the workload be distributed across the team?

🔄 Operational Impact

The project created a chain reaction across the broader customer-data process:

Monthly distributor data
↓
Prioritize distributors & score ranges
↓
Increase efficient matching / reduce unnecessary research
↓
Prevent new monthly records from becoming backlog
↓
Create capacity to attack the historical backlog
↓
Improve customer/account information available to downstream teams
↓
Help Sales identify the appropriate practices/accounts to contact

This matters because customer matching is not an isolated data-cleaning exercise. Accurately determining which dental practice, dentist, or organization a distributor record belongs to improves the customer information available to the business.

That information can ultimately help the Sales team identify the correct customers and opportunities to pursue, connecting better data management to revenue-generating activity.

🗃️ Why the Backlog Was More Difficult

Historical records become progressively harder to resolve.

A dental office associated with an old record may have:

changed ownership,
moved locations,
closed,
been succeeded by another dentist or practice,
changed its business name,
begun sharing an address with another practice, or
accumulated duplicate/outdated customer records.

That means historical research can require reconstructing the relationship between the customer at the time of the original transaction and the business occupying that location today.

By first creating a structured way to control the recurring monthly workload, the team could devote more time to these complicated historical cases rather than continuously adding new unresolved records to the backlog.

✅ Outcome

This project transformed several months of manual matching work into a repeatable operational framework for managing Solmetex's monthly distributor data.

Instead of simply reporting historical performance, the analysis showed which areas of the incoming workload should receive attention first, how work could be distributed more effectively across the team, where automation could potentially reduce manual effort, and what types of matching results the business could expect each month.

Most importantly, controlling the recurring workload created a path toward addressing the company's more complicated historical customer-mapping backlog—improving the underlying customer data that ultimately supports downstream business and Sales activity.
