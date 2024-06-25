# LinkedIn-Posts
All the PDF files to my LinkedIn Posts

[1. Exploring Parent-Child Relationship in SQL? 👩‍💻 ](https://www.linkedin.com/feed/update/urn:li:activity:7210071709310164992/)  [GitHub File](https://github.com/akadambi12/LinkedIn-Posts/blob/main/Parent%20Child%20relationship%20SQL.pdf) 

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
