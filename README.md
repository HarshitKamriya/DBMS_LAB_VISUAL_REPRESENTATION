# 📊 DBMS SQL Queries - Complete Output Documentation

## 📖 Overview

This folder contains comprehensive SQL query execution outputs from Database Management Systems (DBMS) Lab sessions - Semester 4 at NIT Srinagar. All queries have been executed and their results are documented in SQL Workbench-style output format.

---

## 📁 Files in This Folder

### 1. **SQL_WORKBENCH_OUTPUT.html** 🎯 [MAIN FILE]
**Interactive SQL Workbench-style visualization of all query results**

- Complete visual representation of query execution
- Professional SQL Workbench dark theme styling
- Color-coded SQL syntax highlighting
- Organized by Lab sections (LAB 1-9)
- Hover effects and responsive design
- Full table results with proper formatting
- Execution time displayed for each query
- Status messages and row count information

**How to use:**
1. Open the HTML file in any web browser
2. Scroll through each lab section
3. View SQL queries with their results
4. Print to PDF for documentation

---

### 2. **QUERY_COMPILATION.md** 📋 [REFERENCE GUIDE]
**Comprehensive text-based compilation of all queries and results**

- All 60+ queries from LAB 1 through LAB 9
- Organized by lab and topic
- SQL code blocks with syntax highlighting
- Expected output in table format
- Summary statistics
- Key concepts learned
- Quick reference for each query type

**How to use:**
1. Open in any text editor or markdown viewer
2. Search for specific query types (JOIN, GROUP BY, etc.)
3. Copy queries for reference or testing
4. Use as study material

---

## 🧪 COMPLETE LAB BREAKDOWN

### LAB 1: INSERT, SELECT, UPDATE, ALTER
**Topics:** Data Insertion, Basic Queries, Column Operations, Data Modification
- Database creation
- Table creation
- INSERT operations (single & multiple records)
- SELECT with columns
- UPDATE operations
- ALTER TABLE (ADD COLUMN, MODIFY COLUMN)

**Key Queries:** 10  
**Key Concepts:** DDL, DML, Basic Data Manipulation

---

### LAB 2: JOINS, FOREIGN KEYS & DELETE
**Topics:** Relationships, JOIN Operations, Data Deletion, Foreign Keys
- Create related tables (student, course)
- Establish foreign key constraints
- INNER JOIN operations
- DELETE operations
- Multi-table relationships

**Key Queries:** 5  
**Key Concepts:** JOINS, FOREIGN KEYS, Referential Integrity

---

### LAB 3: DEPARTMENT & STUDENT MANAGEMENT
**Topics:** Department Management, DISTINCT Queries, Multi-table Data
- Department table creation
- Multiple student records insertion
- DISTINCT keyword usage
- Large dataset management
- Data validation

**Key Queries:** 5  
**Key Concepts:** Data Organization, DISTINCT, Large Datasets

---

### LAB 4: ENROLLMENTS WITH AGGREGATES & JOINS
**Topics:** Complex Relationships, Aggregate Functions, Multi-table JOINS
- Student, Course, Enrollment table relationships
- Multiple table insertion
- Complex JOIN operations (3-table JOIN)
- SUM aggregate function
- Real-world enrollment scenario

**Key Queries:** 7  
**Key Concepts:** Aggregate Functions, Complex Joins, Data Integrity

---

### LAB 5: DELETE CASCADE & AGGREGATE FUNCTIONS
**Topics:** Advanced Aggregation, Foreign Key Constraints, Data Deletion
- Foreign key constraints (ON DELETE CASCADE)
- AVG() function
- MAX() function
- MIN() function
- COUNT() function

**Key Queries:** 6  
**Key Concepts:** Aggregate Functions, Constraint Management

---

### LAB 6: GROUP BY & HAVING CLAUSES
**Topics:** Data Grouping, Conditional Aggregation, Salary Analysis
- GROUP BY clause
- HAVING clause for filtering groups
- Aggregate functions with grouping
- ORDER BY with GROUP BY
- Department-wise analysis

**Key Queries:** 5  
**Key Concepts:** GROUP BY, HAVING, Grouped Aggregates

---

### LAB 7: NESTED QUERIES & SUBQUERIES
**Topics:** Advanced Query Composition, Subqueries, Correlated Queries
- Nested SELECT statements
- Highest/Second-highest values
- Department averages comparison
- Company-wide comparisons
- Conditional subqueries

**Key Queries:** 8  
**Key Concepts:** Subqueries, Nested Queries, Scalar Subqueries

---

### LAB 8: EXISTS, IN & ADVANCED QUERIES
**Topics:** Set Operations, Existence Checking, Pattern Matching Prep
- IN operator with subqueries
- NOT IN operations
- EXISTS operator
- NOT EXISTS operator
- Supplier-Parts-Catalog relationships
- NULL value handling

**Key Queries:** 10  
**Key Concepts:** EXISTS, IN, Set Operations, Complex Filtering

---

### LAB 9: ADVANCED QUERIES & PATTERN MATCHING
**Topics:** NULL Handling, Pattern Matching, String Operations
- IS NULL checks
- IS NOT NULL checks
- LIKE operator (begins with)
- NOT LIKE operator
- String pattern matching
- Wildcard usage

**Key Queries:** 4  
**Key Concepts:** NULL Handling, LIKE, Pattern Matching

---

## 📊 QUERY STATISTICS

| Metric | Count |
|--------|-------|
| **Total Queries** | 60+ |
| **LABs Covered** | 9 |
| **SELECT Queries** | 28 |
| **INSERT Queries** | 14 |
| **UPDATE Queries** | 5 |
| **ALTER Queries** | 3 |
| **DELETE Queries** | 2 |
| **CREATE Queries** | 8+ |
| **JOIN Types** | 6 |
| **Aggregate Functions** | 5 |

---

## 🎯 SQL CONCEPTS QUICK REFERENCE

### DDL (Data Definition Language)
```sql
CREATE DATABASE
CREATE TABLE
ALTER TABLE
DROP TABLE
DESCRIBE TABLE
SHOW CREATE TABLE
```

### DML (Data Manipulation Language)
```sql
INSERT INTO
SELECT
UPDATE
DELETE
```

### Query Clauses
```sql
WHERE
GROUP BY
HAVING
ORDER BY
LIMIT
DISTINCT
```

### JOIN Types
```sql
INNER JOIN
LEFT JOIN
RIGHT JOIN
FULL OUTER JOIN
NATURAL JOIN
CROSS JOIN
SELF JOIN
```

### Aggregate Functions
```sql
SUM()
AVG()
MAX()
MIN()
COUNT()
```

### Advanced Operators
```sql
IN / NOT IN
EXISTS / NOT EXISTS
LIKE / NOT LIKE
IS NULL / IS NOT NULL
BETWEEN
```

---

## 🔍 HOW TO USE THESE FILES

### For Learning:
1. Start with QUERY_COMPILATION.md for theoretical understanding
2. Look at HTML file for visual execution flow
3. Try executing queries in your own database
4. Compare results with provided outputs

### For Reference:
1. Use Ctrl+F in markdown file to search query types
2. Navigate HTML file to find specific LAB sections
3. Copy SQL from markdown and adapt to your needs
4. Verify results match documented output

### For Documentation:
1. Print HTML to PDF for professional documentation
2. Export markdown to multiple formats (HTML, PDF, DOCX)
3. Screenshot HTML sections for assignments
4. Use as evidence of completed lab work

### For Practice:
1. Create new databases and test queries
2. Modify queries to work with different data
3. Combine multiple query patterns
4. Build progressively complex queries

---

## 📈 PROGRESSION PATH

1. **Basic Operations** → LAB 1
   - Learn database and table creation
   - Master INSERT and SELECT

2. **Relationships** → LAB 2-3
   - Understand FOREIGN KEY constraints
   - Practice JOINS
   - Learn data organization

3. **Aggregation** → LAB 4-6
   - Master aggregate functions
   - Learn GROUP BY and HAVING
   - Practice complex queries

4. **Advanced Queries** → LAB 7-9
   - Learn subqueries and nested queries
   - Master EXISTS and IN operators
   - Understand pattern matching

---

## ✨ KEY TAKEAWAYS

### Most Important Patterns:

1. **JOIN Pattern**
   ```sql
   SELECT cols FROM table1 
   JOIN table2 ON table1.id = table2.id
   ```

2. **GROUP BY Pattern**
   ```sql
   SELECT col, AGGREGATE() FROM table
   GROUP BY col
   HAVING condition
   ```

3. **Subquery Pattern**
   ```sql
   SELECT * FROM table
   WHERE col = (SELECT ... FROM table)
   ```

4. **EXISTS Pattern**
   ```sql
   SELECT * FROM table1
   WHERE EXISTS (SELECT * FROM table2 WHERE ...)
   ```

5. **LIKE Pattern**
   ```sql
   SELECT * FROM table
   WHERE col LIKE 'pattern%'
   ```

---

## 🛠️ TOOLS USED FOR GENERATION

- **Database System:** MySQL/MariaDB
- **Query Execution:** Direct SQL execution
- **Output Format:** HTML5 + CSS3 styling
- **Documentation:** Markdown format
- **Visualization:** Professional SQL Workbench theme

---

## 📝 NOTES FOR STUDENTS

- All queries have been tested and verified
- Results shown are for reference only
- Your actual results may vary based on data
- Practice modifying queries for better understanding
- Combine multiple patterns for complex problems
- Always validate NULL handling in production queries

---

## 📞 DOCUMENT INFORMATION

| Property | Value |
|----------|-------|
| **Subject** | Database Management Systems |
| **Semester** | IV |
| **Institution** | NIT Srinagar |
| **Generated Date** | May 31, 2026 |
| **Total Pages** | ~50+ (HTML) |
| **File Format** | HTML + Markdown |
| **Compatibility** | All modern browsers |

---

## ✅ VERIFICATION CHECKLIST

- [x] All LAB 1-9 queries included
- [x] SQL syntax properly highlighted
- [x] Results verified and accurate
- [x] Execution times documented
- [x] Query count verified (60+)
- [x] All concepts covered
- [x] Professional formatting applied
- [x] Cross-browser compatibility
- [x] Print-friendly layout
- [x] Search functionality included

---

## 🎓 LEARNING OUTCOMES

After studying these labs, you should be able to:

✓ Create and manage databases and tables  
✓ Write efficient INSERT, SELECT, UPDATE, DELETE queries  
✓ Use various types of JOINS effectively  
✓ Work with aggregate functions and GROUP BY  
✓ Write and optimize subqueries  
✓ Use advanced operators (EXISTS, IN, LIKE)  
✓ Handle NULL values properly  
✓ Optimize query performance  
✓ Understand data relationships  
✓ Implement referential integrity  

---

## 📞 Support

For questions about specific queries:
1. Check the table of contents in QUERY_COMPILATION.md
2. Look for similar patterns in the HTML file
3. Review the concept explanations in the quick reference
4. Cross-reference with SQL documentation

---

**Last Updated:** May 31, 2026  
**Status:** ✓ Complete  
**Quality:** Production Ready

---

*Document created as part of DBMS Lab coursework - NIT Srinagar*
