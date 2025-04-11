# Magic-square

# Introduction to Magic Squares

Magic squares are ancient mathematical puzzles full of charm. Below is a detailed introduction:

## 1. What is a Magic Square?
A Magic Square is an n×n square matrix composed of distinct numbers that satisfies:
- The sum of numbers in each row and column is equal  
- The sum of numbers in both main diagonals is also equal  
- Typically uses consecutive natural numbers from 1 to n² (some variations may allow repeated numbers)

## 2. Key Concepts
### Magic Constant
The common sum of each row/column/diagonal. Calculation formula:  
`Magic Constant = n(n² + 1)/2`  
- 3×3 Magic Square: Magic Constant = 15  
- 4×4 Magic Square: Magic Constant = 34  

### Classification by Order
1. **Odd-order** (e.g., 3×3, 5×5)  
2. **Doubly even-order** (4×4, 8×8, i.e., multiples of 4)  
3. **Singly even-order** (6×6, 10×10, i.e., even numbers not multiples of 4)

---

## Odd-Order Magic Squares
**Note**: *After downloading and running the program, view the detailed step-by-step example diagram on the program webpage.*  
**Note**: *Create a magic square.xlsx file by inputting numerical values, including detailed step-by-step reference tables.*
Program download address：[https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip](https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip)

### Step-by-step explanation for creating a 5x5 odd-order magic square:
#### Table: A-Single  
Fill number 1 in the first cell of the top row, then fill increasing odd numbers spaced apart until reaching the square number 25.  
picture

#### Table: B-Dual  
Fill number 2 in the last cell of the bottom row, then fill increasing even numbers spaced apart until reaching 24 (square number minus one).  
picture

#### Table: C-Spaced  
Insert blank rows and columns between each existing row and column.  
picture

#### Table: D-Shift  
1. Connect the midpoints of the four edges to form a diamond-shaped frame.  
2. Numbers outside the diamond frame are folded into the frame along the diagonal axis like paper folding.  
pictureA
pictureB

#### Table: E-Merged  
Rotate the diamond frame 45 degrees to align, then copy the numbers within the frame to a new table.  
picture

**Complete**: Batch verify sum values using 'Auto Sum' in the 'Home' tab at the top right of the xls sheet.

---

## Single-Even Magic Square
**Singly even**: Even numbers not divisible by 4 (e.g., 6,10,18...)  
**Note**: *After downloading and running the program, view the detailed step-by-step example diagram on the program webpage.*  
**Note**: *Create a magic square.xlsx file by inputting numerical values, including detailed step-by-step reference tables.*
Program download address：[https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip](https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip)

### Step-by-step explanation for creating a 6x6 singly even magic square:
#### Table:A-Half 3  
Introduce the creation of a single even 6 divided by 2 to form a 3 magic square.  
picture

#### Table:B-4x Minus 3  
Multiply each value of the 3 magic square by 4 and subtract 3.  
picture

#### Table:C-Split Table  
Split the 3 magic square into Table A and Table B with alternating values.  
picture

#### Table:D-Forward Order  
Expand each value in Table A with 4 adjacent numbers to form sub-squares.  
Increment by 1 in forward order: sub-square top row `[n+0, n+1]`, bottom row `[n+2, n+3]`.  
picture

#### Table:E-Reverse Order  
Decrement by 1 in reverse order: sub-square top row `[n+3, n+2]`, bottom row `[n+1, n+0]`.  
pictureA
pictureB

#### Table:F-Adjust  
1. Swap left-right in first row's sub-squares, ignoring last corner.  
2. Swap top-bottom in last column's sub-squares, ignoring last corner.  
3. Swap left-right in bottom-right corner of last row.  
4. Swap top-bottom in bottom-left corner of first column.  
pictureA
pictureB
pictureC

**Complete**: Batch verify sum values using 'Auto Sum' in the 'Home' tab at the top right of the xls sheet.  
picture

---

## Double-Even Magic Square
**Doubly even**: Even numbers divisible by 4 (e.g., 8,12,16...)  
**Note**: *After downloading and running the program, view the detailed step-by-step example diagram on the program webpage.*  
**Note**: *Create a magic square.xlsx file by inputting numerical values, including detailed step-by-step reference tables.*

Program download address：[https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip](https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip)

### Step-by-step explanation for creating an 8x8 doubly even magic square:
#### Table:A-Single  
Introducing the creation of a doubly even 8 magic square divided by 2 into 4 magic squares.  
picture

#### Table:B-4x Minus 3  
Each value of the 4 magic square is multiplied by 4 and then subtracted by 3.  
picture

#### Table:C-Upper Section  
Expand each value into 4 adjacent numbers:  
Top row `[n+0, n+3]`, bottom row `[n+2, n+1]`.  
Example with n=1: Small square's top row `[1, 4]`, bottom row `[3, 2]`.  
picture

#### Table:D-Lower Section  
Expansion method for the lower section:  
Top row `[n+3, n+0]`, bottom row `[n+1, n+2]`.  
picture

**Complete**: Batch verify sum values using 'Auto Sum' in the 'Home' tab at the top right of the xls sheet.  
picture
