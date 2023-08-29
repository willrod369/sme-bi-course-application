# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [ Done ] Add datasets used to the `datasets/` folder

#### Files

- [ Done ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ Done ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`

#### Learning Objective

Building a Financial Formula (Profit & Loss Statement) in Excel

#### Context

Knowing how to derive financial statements from raw journal entries is fundamental for anyone serious about understanding business, finance, and accounting. Doing so in a way that is performant, reduces memory size, and is easier to manage and administer is simply smart for themselves and their career. This lesson maximizes students’ potential and prowess in both finance and Excel by guiding them through robust financial reporting (Profit & Loss Generation)

#### Steps to be executed by the student (max 6)

•	Step 1: Insert Report Key
•	Step 2: Find the Indicator based on the Report Key
•	Step 3: Return Accounts based on the Report Key
•	Step 4: Find the Account Type based on the Account
•	Step 5: Calculate the Amount based on the Account & Account Type
•	Step 6: Consolidate with LET


#### Exercise question:
What is the Gross Margin (Report Key = 3)? 

#### End goal:

![image](https://github.com/willrod369/sme-bi-course-application/assets/137422487/7029a5bc-1d2e-4b7c-9768-074dda7b2abf)


## 2nd VM Exercise

#### Dataset

- [ Done ] Add datasets used to the `datasets/` folder

#### Files

- [ Done ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course.
- [ Done ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`

#### Learning Objective

Building a Financial Formula (Balance Sheet) in Excel

#### Context

Knowing how to derive financial statements from raw journal entries is fundamental for anyone serious about understanding business, finance, and accounting. Doing so in a way that is performant, reduces memory size, and is easier to manage and administer is simply smart for themselves and their career. This lesson maximizes students’ potential and prowess in both finance and Excel by guiding them through robust financial reporting (Balance Sheet Generation). 

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

•	Step 1: Copy & Paste P&L Formula (exercise 1, lesson 3.1)
•	Step 2: Update Report Key
•	Step 3: Update ExceptionIndicator and AccountsArray for balance sheet tables
•	Step 4: Remove Debits and Credits start filter
•	Step 5: Add Asset, Liability, and Owners Equity arrays
•	Step 6: Produce new BS Equation: If exception, A – (L+OE), else (L+OE) - A


#### Exercise question:
What are Total Assets (Report Key = 7)? 

#### End goal:

![image](https://github.com/willrod369/sme-bi-course-application/assets/137422487/06f31988-b75f-433d-bdf9-949d07803eca)


