# 📘 01 — Excel Fundamentals

This section covers the fundamental Excel concepts required for a Data Analyst.

The goal is to understand how Excel stores, organizes, and works with data before moving to formulas and advanced analysis.

---

## 🎯 Learning Objectives

By the end of this section, I should be able to:

* Understand Excel's basic structure
* Work with cells, rows, and columns
* Understand cell references
* Enter and format data
* Sort and filter datasets
* Create Excel Tables
* Use Find & Replace
* Freeze rows and columns
* Understand basic data types

---

# 1. Excel Basic Structure

## Workbook

A workbook is the complete Excel file.

Example:

`Sales_Analysis.xlsx`

A workbook can contain multiple worksheets.

## Worksheet

A worksheet is an individual sheet inside a workbook.

Example:

* Sales
* Customers
* Products

## Row

Rows run horizontally and are identified by numbers.

```text
1
2
3
4
5
```

## Column

Columns run vertically and are identified by letters.

```text
A    B    C    D

```

## Cell

A cell is the intersection of a row and a column.

Examples:

```text
A1
B5
D10
```

### Cell Address

A cell address consists of:

```text
Column + Row
```

Example:

```text
B5
```

means:

```text
Column B + Row 5
```

---

# 2. Data Types

Excel can contain different types of data.

## Text

```text
Anjali
North
Laptop
```

## Number

```text
100
2500
99.50
```

## Date

```text
25/08/2026
```

## Time

```text
10:30 AM
```

## Boolean

```text
TRUE
FALSE
```

## Errors

Common Excel errors:

```text
#N/A
#VALUE!
#DIV/0!
#REF!
#NAME?
```

---

# 3. Cell References

Cell references are used when working with formulas.

## Relative Reference

Example:

```text
A1
```

A relative reference changes when a formula is copied.

Example:

```text
=A2*10
```

Copied down:

```text
=A3*10
```

---

## Absolute Reference

Example:

```text
$A$1
```

An absolute reference remains fixed when copied.

Example:

```text
=B2*$E$1
```

Here `$E$1` remains fixed.

---

## Mixed Reference

Examples:

```text
$A1
A$1
```

### `$A1`

Column A is fixed, row can change.

### `A$1`

Row 1 is fixed, column can change.

---

# 4. Data Entry

Learn how to:

* Enter data
* Edit data
* Copy data
* Cut data
* Paste data
* Delete data
* Drag and fill
* Undo
* Redo

### Useful Shortcuts

| Shortcut   | Action  |
| ---------- | ------- |
| `Ctrl + C` | Copy    |
| `Ctrl + X` | Cut     |
| `Ctrl + V` | Paste   |
| `Ctrl + Z` | Undo    |
| `Ctrl + Y` | Redo    |
| `Ctrl + F` | Find    |
| `Ctrl + H` | Replace |
| `Ctrl + S` | Save    |

---

# 5. Formatting

Basic formatting includes:

* Font
* Font size
* Bold
* Italic
* Borders
* Fill
* Alignment
* Number format
* Currency
* Percentage
* Date format

### Important

Formatting should make data easier to understand.

Do not use excessive formatting in analytical datasets.

---

# 6. Sort

Sorting arranges data in a particular order.

### Text

```text
A → Z
Z → A
```

### Numbers

```text
Smallest → Largest
Largest → Smallest
```

### Dates

```text
Oldest → Newest
Newest → Oldest
```

### Example

| Salesperson |  Sales |
| ----------- | -----: |
| Rahul       | 50,000 |
| Priya       | 80,000 |
| Amit        | 30,000 |

After sorting Sales from Largest to Smallest:

| Salesperson |  Sales |
| ----------- | -----: |
| Priya       | 80,000 |
| Rahul       | 50,000 |
| Amit        | 30,000 |

---

# 7. Filter

Filtering displays only the records that meet a specific condition.

Example dataset contains:

```text
North
South
East
West
```

Filter:

```text
Region = North
```

Excel will display only North-region records.

### Data Analyst Use Cases

* Find sales from a specific region
* Find orders from a specific month
* Find high-value customers
* Find cancelled orders
* Find a particular product

---

# 8. Excel Tables

An Excel Table converts a normal dataset into a structured table.

### Shortcut

```text
Ctrl + T
```

### Benefits

* Automatic filtering
* Structured references
* Automatic expansion
* Easier formulas
* Easier Pivot Tables
* Better compatibility with Power Query

### Example

| Order ID | Date       | Region | Product  |  Sales |
| -------: | ---------- | ------ | -------- | -----: |
|     1001 | 01/08/2026 | North  | Laptop   | 50,000 |
|     1002 | 02/08/2026 | South  | Mouse    |  1,500 |
|     1003 | 03/08/2026 | North  | Keyboard |  3,000 |

Select the dataset and press:

```text
Ctrl + T
```

---

# 9. Freeze Panes

Freeze Panes keeps important rows or columns visible while scrolling.

For a large dataset:

```text
View → Freeze Panes → Freeze Top Row
```

This keeps the column headers visible.

---

# 10. Find & Replace

## Find

Shortcut:

```text
Ctrl + F
```

Used to find specific data.

Example:

```text
Laptop
```

## Replace

Shortcut:

```text
Ctrl + H
```

Example:

Suppose the dataset contains:

```text
North
NORTH
north
```

You can use Replace to standardize values.

---

# 11. Data Analyst Example

Consider this dataset:

| Order ID | Date       | Region | Product  | Quantity |  Sales |
| -------: | ---------- | ------ | -------- | -------: | -----: |
|     1001 | 01/08/2026 | North  | Laptop   |        2 | 100000 |
|     1002 | 02/08/2026 | South  | Mouse    |        5 |   7500 |
|     1003 | 03/08/2026 | North  | Keyboard |        3 |   9000 |
|     1004 | 04/08/2026 | West   | Laptop   |        1 |  55000 |
|     1005 | 05/08/2026 | East   | Monitor  |        2 |  30000 |

### Practice

1. Convert the dataset into an Excel Table.
2. Sort Sales from largest to smallest.
3. Filter Region = North.
4. Find all Laptop orders.
5. Freeze the top row.
6. Find the word `Mouse`.
7. Change the Sales column to currency format.
8. Add a new order.
9. Sort Quantity from largest to smallest.
10. Remove the filter.

---

# 🧪 Practice Questions

### Basic

1. What is a workbook?
2. What is a worksheet?
3. What is a cell?
4. What is a cell address?
5. What is the difference between a row and a column?

### Cell References

6. What is a relative reference?
7. What is an absolute reference?
8. What is a mixed reference?
9. What does `$A$1` mean?
10. What does `A$1` mean?

### Data Handling

11. How do you sort data?
12. How do you filter data?
13. Why should datasets be converted into Excel Tables?
14. What is Freeze Panes used for?
15. What is the difference between Find and Replace?

---

# ⭐ Important for Data Analysts

Focus especially on:

* Cell References
* Data Types
* Sorting
* Filtering
* Excel Tables
* Find & Replace
* Freeze Panes

These concepts form the foundation for formulas, Pivot Tables, Power Query, and dashboards.

---

# ✅ Completion Checklist

* [ ] Understand Workbook
* [ ] Understand Worksheet
* [ ] Understand Rows & Columns
* [ ] Understand Cells
* [ ] Understand Cell Addresses
* [ ] Understand Data Types
* [ ] Understand Relative References
* [ ] Understand Absolute References
* [ ] Understand Mixed References
* [ ] Practice Data Entry
* [ ] Practice Formatting
* [ ] Practice Sorting
* [ ] Practice Filtering
* [ ] Create Excel Tables
* [ ] Practice Find & Replace
* [ ] Practice Freeze Panes
* [ ] Complete Practice Questions

---

# 🚀 Next Topic

After completing Excel Fundamentals:

**02 — Formulas & Functions**

### Study Order

```text
Learn
   ↓
Open Excel
   ↓
Create the 5-row dataset
   ↓
Practice every topic
   ↓
Complete the checklist
   ↓
Commit to GitHub
   ↓
Move to Module 02
```

