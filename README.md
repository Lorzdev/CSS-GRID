# CSS GRID

The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.
#

### Grid Elements
- a grid layout consists of a parent element, with one or more child elements.
``` html
<div class="grid-container">
  <div class="grid-item">1</div>
  <div class="grid-item">2</div>
  <div class="grid-item">3</div>
  <div class="grid-item">4</div>
  <div class="grid-item">5</div>
  <div class="grid-item">6</div>
  <div class="grid-item">7</div>
  <div class="grid-item">8</div>
  <div class="grid-item">9</div>
</div>
```
### Display Property
- an HTML element becomes a grid container when its display property is set to grid or inline-grid.

 Example
``` css
 .grid-container {
  display: grid;
}
```
``` css
.grid-container {
  display: inline-grid;
}
```
 `grid-template-columns `, &  `grid-template-rows `
 
These properties define the structure of the grid by specifying the size and number of columns and rows.

 Example
``` css
 .grid-container {
  grid-template-columns: 200px 1fr 100px; /* 3 columns: fixed, flexible, fixed */
  grid-template-rows: 150px auto; /* 2 rows: fixed height, automatic size */
}
```

- `1fr` means "one fraction" of the available space.
- You can also use values like `px`, `%`, `em`, and `auto` to control dimensions.


`grid-gap` or` gap`

 - Adds spacing between rows and columns.
   
 Example
``` css
.grid-container {
  grid-gap: 20px; /* 20px spacing between both rows and columns */
  /* or */
  gap: 20px 10px; /* 20px row gap, 10px column gap */
}
```
`grid-auto-rows` & `grid-auto-columns`

- Defines the default size for any automatically created rows or columns.
  
 Example
 ``` CSS
.grid-container {
  grid-auto-rows: 100px; /* Any new row will be 100px tall */
  grid-auto-columns: 50px; /* Any new column will be 50px wide */
}
 ```

`grid-template-areas`

- Names specific areas within the grid to make layouts more readable and structured.

 Example
 ``` CSS
.grid-container {
  grid-template-areas: 
    "header header header"
    "sidebar content content"
    "footer footer footer";
}
 ```
#

### SAMPLE OUTPUT  CSS GRID
i use 5 pages using css grid

#### List of Products
![image](https://github.com/user-attachments/assets/cf162615-d9dd-4b89-8729-d6831645ad70)

#### List of Employees
![image](https://github.com/user-attachments/assets/64128669-e28d-493c-88ba-61ada090ea4b)

#### List of Students
![image](https://github.com/user-attachments/assets/2146a393-8cd1-44d4-bb69-badd426ce918)

#### List of Courses
![image](https://github.com/user-attachments/assets/4a959f72-1d5e-4b2c-883e-82b97c247cfb)

#### List of Projects
![image](https://github.com/user-attachments/assets/4a8fb63f-a0e0-4e98-817a-5a53f5b9effb)






  
