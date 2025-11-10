# HTML-Tables  

## HTML Table Syntax:

```html
<table border="1" align="center" width="50%" height="500px" cellpadding="10" cellspacing="0">
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
    <th>Header 3</th>
  </tr>
  <tr>
    <td>Row-1 Col-1</td>
    <td>Row-1 Col-2</td>
    <td>Row-1 Col-3</td>
  </tr>
  <tr>
    <td>Row-2 Col-1</td>
    <td>Row-2 Col-2</td>
    <td>Row-2 Col-3</td>
  </tr>
</table>

```

This will create a simple **3x3** table with headers.

- ``<table>`` → defines the table
- ``<tr>`` → table row
- ``<th>`` → table header cell (bold & centered by default)
- ``<td>`` → table data cell

Attributes:

- ``border`` : Adds a visible border around the table and cells.
- ``align`` : positions the table (``left``, ``center``, ``right``)
- ``width`` : Sets table width (in % or px)
- ``height`` : Sets table height (in % or px)
- ``cellpadding`` : Adds space inside each cell between the content and the cell border.
- ``cellspacing`` : Sets the space between table cells.

## Basic HTML Table

**Task:**  
Create a simple table with student information.

```html
<!DOCTYPE html>
<html>
<head>
  <title>Basic Table</title>
</head>
<body>
  <h2>Student Information</h2>
  <table border="1">
    <tr>
      <th>Roll No</th>
      <th>Name</th>
      <th>Grade</th>
    </tr>
    <tr>
      <td>1</td>
      <td>Prashant</td>
      <td>A</td>
    </tr>
    <tr>
      <td>2</td>
      <td>Anita</td>
      <td>B+</td>
    </tr>
  </table>
</body>
</html>
```

---

## Adding Table Caption and Alignment

**Task:**  
Add a caption and align the table.

```html
<table border="1" align="center" width="50%">
  <caption><b>Employee Details</b></caption>
  <tr>
    <th>ID</th>
    <th>Name</th>
    <th>Department</th>
  </tr>
  <tr>
    <td>101</td>
    <td>Ravi</td>
    <td>IT</td>
  </tr>
  <tr>
    <td>102</td>
    <td>Sita</td>
    <td>Finance</td>
  </tr>
</table>
```

---

## Formatting Table with Colors and Widths

**Task:**  
Use background colors and set column widths.

```html
<table border="1" width="70%" bgcolor="lightyellow">
  <tr bgcolor="lightblue">
    <th width="20%">S.N.</th>
    <th width="40%">Product</th>
    <th width="40%">Price</th>
  </tr>
  <tr>
    <td>1</td>
    <td>Keyboard</td>
    <td>Rs 20</td>
  </tr>
  <tr>
    <td>2</td>
    <td>Mouse</td>
    <td>Rs 10</td>
  </tr>
</table>
```

---

## Using Rowspan and Colspan

- Rowspan: rowspan="n" → cell spans n rows.

- Colspan: colspan="n" → cell spans n columns.

**Task:**  
Merge cells vertically and horizontally.

```html
<table border="1" cellpadding="10" cellspacing="0">
  <tr>
    <th rowspan="2">Name</th>
    <th colspan="2">Marks</th>
  </tr>
  <tr>
    <th>Math</th>
    <th>Science</th>
  </tr>
  <tr>
    <td>Ramesh</td>
    <td>85</td>
    <td>90</td>
  </tr>
  <tr>
    <td>Sita</td>
    <td>88</td>
    <td>92</td>
  </tr>
</table>
```

---

## Complete Timetable Project

**Objective:**  
Design a **Weekly Class Timetable** using all table concepts.

---
