# LinkedIn-Posts
All the PDF files to my LinkedIn Posts

[1. Exploring Parent-Child Relationship in SQL? 👩‍💻 ](https://www.linkedin.com/feed/update/urn:li:activity:7210071709310164992/)  
[GitHub File](https://github.com/akadambi12/LinkedIn-Posts/blob/main/Parent%20Child%20relationship%20SQL.pdf) 

If you're new to the concept of Parent-Child relationship in SQL, this post is going to give you a valuable insight into this tricky concept.

Think of a family tree! You have a grandparent, parents, and children. In SQL, a Parent-Child relationship is like a family tree for data. 

Here's how it works-
Parent: This is like a parent in a family. It is a record (a row in a table) that can have one or more children. For example, in a company, a manager (parent) can have many employees (children).

Child: This is like a child in a family. It is a record that has a parent. For example, an employee (child) works under a manager (parent).

Visualizing the Relationship-
Imagine you have a big box of building blocks. You start with one big block (the parent), and then you connect smaller blocks (the children) to it. Each child block can also have its own smaller blocks connected to it, creating a tree-like structure.

I'd like to explain a problem that I've solved this week from Chris Perry's SQL Short Reads which was a bit of a thinker! : Problem 10 from the Medium stack.

For each category ID, retrieve the category ID, parent category ID, category name, category description, parent category name, and parent category description. Include all category IDs even if a parent category doesn’t exist. Each row should consist of child category and parent category (i.e., 1 level above the child) data. Alias the parent category name as “parent_category_name” and the parent category description as “parent_category_description.” Sort the result set by the child category ID, ascending.

Some typical queries used on Parent - Child Tree include:
1. Listing All category of 1 parent category
2. Listing a Parent Node For a Child Node: Self Join
3. Get a Generation Number (or Tree Level) for Each Node : CTEs

The queries below clearly demonstrate each of the approaches from simple to complex. The second approach is the correct solution for this problem. However, I went one step ahead and used recursive CTE to generate the tree level for clarity. 


[2. Essential Insights for Financial Analysts](https://www.linkedin.com/feed/update/urn:li:activity:7191130949160456193/)

[GitHub file ](https://github.com/akadambi12/LinkedIn-Posts/blob/main/Insights%20for%20Fianancial%20Data%20Analysts.pdf)
Continuing from last week's post on fundamental tools like SQL, Python, R, Tableau, and Excel: https://lnkd.in/eNdHXu9t and also some financial sector-specific tools and concepts, I'm excited to share a new post busting Financial Jargon, and making it easy to understand by taking the example of FinCap Solutions, a hypothetical fintech organization based in NYC that specializes in investment management, personal finance advisory, and corporate financial consulting. Serving a global clientele, FinCap exemplifies the intricacies and opportunities within the financial sector.

Navigating the financial landscape demands a firm understanding of core concepts, crucial for any analyst looking to make an impact. Here’s a distilled overview, illuminated by examples from FinCap Solutions:

- Assets and Liabilities: From the liquidity of cash equivalents to the valuation of fixed assets, understanding what a company owns versus what it owes is foundational.
- Investment Vehicles: Whether it’s bonds providing steady income or stocks offering a share in company profits, knowing how to manage these can significantly influence financial outcomes.
- Financial Statements: The balance sheet, income statement, and cash flow statement are the maps that guide corporate strategy and decision-making.
- Performance Metrics: Metrics like EBITDA, ROI, and various profit margins provide snapshots of a company’s health and operational success.
- Market Dynamics: Grasping the nuances of capital markets, the role of institutional investors, and the strategies behind mutual and hedge funds are vital for robust financial analysis.

[3. Types of Healthcare Data](https://www.linkedin.com/posts/anupama-kadambi12_insights-for-healthcare-data-analysts-activity-7185729045039337473-2ckV?utm_source=share&utm_medium=member_desktop)

[GitHub File ](https://github.com/akadambi12/LinkedIn-Posts/blob/main/Types%20of%20Healthcare%20Data.pdf)

Through independent research and hands-on experience, I've accumulated valuable insights that are pivotal for anyone starting or transitioning into healthcare data analysis. 

To aid fellow professionals, I've compiled a concise guide that covers essential knowledge and handy cheat sheets tailored for healthcare data analysts. This guide is designed to demystify the complexities of the field and provide practical tools to help you thrive. 

Whether you're a newcomer or looking to deepen your expertise, I hope this resource empowers you to make impactful contributions to healthcare through data.

I have personally worked on a project focusing on predictive analytics: "Predicting patient Readmission" based on a dataset containing heath stats of diabetic patients. 

I have particularly focused on Data Cleaning and Feature Engineering for this dataset containing 100,000+ records and 49 features. 

I have also performed Exploratory Data Analysis to visualize patient metrics.
Feel free to drop your opinion in the comments and also check out my project on Github! 
https://lnkd.in/eWKd6akA

[4. What comes after SQL, Python and R?](https://www.linkedin.com/posts/anupama-kadambi12_what-comes-after-sql-python-and-r-activity-7189317348921593856-9LPK?utm_source=share&utm_medium=member_desktop)

[GitHub File ](https://github.com/akadambi12/LinkedIn-Posts/blob/main/What%20comes%20after%20SQL%2C%20Python%20and%20R%3F.pdf)

After a week of analyzing healthcare data, I've compiled a guide to help anyone interested in starting a career in finance.

To be a successful financial analyst, you need to know not only fundamental tools like SQL, Python, R, Tableau, and Excel but also some financial sector-specific tools and concepts. Here are some of them:

1. Bloomberg Terminal: A powerful platform for financial data analysis, used to track market trends, securities, and financial news.

2. FactSet: A financial research and data platform used for investment analysis, portfolio management, and risk assessment.

3. Financial Modeling: Skills in building financial models, including discounted cash flow (DCF), leveraged buyout (LBO), and mergers and acquisitions (M&A) modeling.

4. Accounting Software: Knowledge of accounting software like QuickBooks or SAP to manage financial records and generate financial reports.

5. Statistical Analysis Tools: Advanced tools for statistical analysis, such as SAS or SPSS, can help with in-depth financial data analysis.

Equipped with these tools and concepts, you'll be ready to navigate the financial sector as a data analyst and take the next step toward becoming a successful financial analyst. 


