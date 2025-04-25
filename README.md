# Infinite Numerical Magic Square 

# Introduction to Magic Squares

Magic squares are ancient mathematical puzzles full of charm. Below is a detailed introduction:

## 1. What is a Magic Square?
A Magic Square is an n×n square matrix composed of distinct numbers that satisfies:
- The sum of numbers in each row and column is equal  
- The sum of numbers in both main diagonals is also equal  

## 2.  Classification by Order
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

#### Table: B-Dual  
Fill number 2 in the last cell of the bottom row, then fill increasing even numbers spaced apart until reaching 24 (square number minus one).  
  ![B4-2](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%A5%87%E9%98%B6%E8%A7%A3%E8%AF%B4-2.png?format=raw )

#### Table: C-Spaced  
Insert blank rows and columns between each existing row and column.  


#### Table: D-Shift  
1. Connect the midpoints of the four edges to form a diamond-shaped frame.  
2. Numbers outside the diamond frame are folded into the frame along the diagonal axis like paper folding.  
 ![B4-3](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%A5%87%E9%98%B6%E8%A7%A3%E8%AF%B4-3.png?format=raw)
![B4-4B](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%A5%87%E9%98%B6%E8%A7%A3%E8%AF%B4-4B.png?format=raw )


#### Table: E-Merged  
Rotate the diamond frame 45 degrees to align, then copy the numbers within the frame to a new table.  
 ![B4-5](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%A5%87%E9%98%B6%E8%A7%A3%E8%AF%B4-5.png?format=raw )

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


#### Table:B-4x Minus 3  
Multiply each value of the 3 magic square by 4 and subtract 3.  
   ![2](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-2.png?format=raw)


#### Table:C-Split Table  
Split the 3 magic square into Table A and Table B with alternating values.  
  ![3](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-3.png?format=raw)



#### Table:D-Forward Order  
Expand each value in Table A with 4 adjacent numbers to form sub-squares.  
Increment by 1 in forward order: sub-square top row `[n+0, n+1]`, bottom row `[n+2, n+3]`.  
 ![4](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-3A.png?format=raw)



#### Table:E-Reverse Order  
Decrement by 1 in reverse order: sub-square top row `[n+3, n+2]`, bottom row `[n+1, n+0]`.  
![5](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-4A.png?format=raw)

![5B](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-4C.png?format=raw)

#### Table:F-Adjust  
1. Swap left-right in first row's sub-squares, ignoring last corner.  
2. Swap top-bottom in last column's sub-squares, ignoring last corner.  
3. Swap left-right in bottom-right corner of last row.  
4. Swap top-bottom in bottom-left corner of first column.  
![6](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-5A.png?format=raw)

![6a](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-5B.png?format=raw )

![6b](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-5C.png?format=raw)

**Complete**: Batch verify sum values using 'Auto Sum' in the 'Home' tab at the top right of the xls sheet.  
![7](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8D%95%E5%81%B6%E8%A7%A3%E8%AF%B4-6.png?format=raw)


---

## Double-Even Magic Square
**Doubly even**: Even numbers divisible by 4 (e.g., 8,12,16...)  
**Note**: *After downloading and running the program, view the detailed step-by-step example diagram on the program webpage.*  
**Note**: *Create a magic square.xlsx file by inputting numerical values, including detailed step-by-step reference tables.*

Program download address：[https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip](https://github.com/jiqi136/Magic-square/releases/download/untagged-8e3467f4e2a4ee5e386f/Infinite.Numerical.Magic.Square.V1.1.zip)

### Step-by-step explanation for creating an 8x8 doubly even magic square:
#### Table:A-Single  
Introducing the creation of a doubly even 8 magic square divided by 2 into 4 magic squares.  

#### Table:B-4x Minus 3  
Each value of the 4 magic square is multiplied by 4 and then subtracted by 3.  
 ![2](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8F%8C%E5%81%B6%E8%A7%A3%E8%AF%B4-2.png?format=raw)



#### Table:C-Upper Section  
Expand each value into 4 adjacent numbers:  
Top row `[n+0, n+3]`, bottom row `[n+2, n+1]`.  
Example with n=1: Small square's top row `[1, 4]`, bottom row `[3, 2]`.  
  ![3](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8F%8C%E5%81%B6%E8%A7%A3%E8%AF%B4-3.png?format=raw )


#### Table:D-Lower Section  
Expansion method for the lower section:  
Top row `[n+3, n+0]`, bottom row `[n+1, n+2]`.  

![4](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8F%8C%E5%81%B6%E8%A7%A3%E8%AF%B4-4.png?format=raw)



**Complete**: Batch verify sum values using 'Auto Sum' in the 'Home' tab at the top right of the xls sheet.  

![5](https://sourceforge.net/u/jier136/code/ci/main/tree/%E5%8F%8C%E5%81%B6%E8%A7%A3%E8%AF%B4-5.png?format=raw)
   

