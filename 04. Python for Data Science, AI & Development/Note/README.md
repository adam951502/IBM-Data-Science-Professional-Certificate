# 4. Python for Data Science, AI & Development

---

# Week01 - Python Basics

## **Types**

By using the function `type()`

- data type
    - **int**
        - 1 ,2,3
    - **float**
        - 0.1, 0.23
    - **str**
        - `“hello world”`
    - boolean
        - `True` / `False`
        - `int(True)` → `1` / `int(False)` → `0`
        - `bool(1)` → `True` / `bool(0)` → `False`
- typecasting
    - `float(2)` → `2.0`
    - `int(1.9)` → `1` (loss info)
    - `int("1")` → `1`
    - `int("A")` → `error`
    - `str(1)` → `“1”`

## **Expressions and Variables**

- Expressions
    - operations
        - + (summation sign)
        - - (subtraction sign)
        - * (asterisk)
        - / (forward slash)
        - // (round → integer part only)
    - operands():
        - `x+y` → `x`, `y` are operands
        - `+` → operator
- Variables
    - `my_variable = 1`
    - **Please use the meaningful name when naming a variable!**
    - It is common to use the underscore to represent the start of a new word

## ****String Operations****

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%201.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%202.png)

- Select every two characters: `Name[::2]`:`"McalJcsn"`

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%203.png)

- Slicing: `Name[0:5:2] : "Mca"`

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%204.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%205.png)

- `\n` : new line

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%206.png)

- `\t` : tap

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%207.png)

# Week02 - Python Data Structures

## **List and Tuples**

### Tuples

- compound data type (複合數據類型)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%208.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%209.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2010.png)

- concatenate tuples by adding them

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2011.png)

- Last number assigned in the tuples is not counted!
    - The last index is one less than we want!

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2012.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2013.png)

- the tuples are immutable (不可改變的)
    - When we want to sort it (or changethe tuple), we have to create a new tuple!
    - **The contents of a tuple cannot change once they have been created in Python due to the immutability of tuples!!!!!!**

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2014.png)

- Tuple Nesting

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2015.png)

### List

- List could be changed (mutable)
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2016.png)
    
- `.extend()`
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2017.png)
    
- `.append()`
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2018.png)
    
- ************`extend()`will add all the elements in the end of list, `append()`will only append one element in the end of list**
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2019.png)
    
- `del()` → delete the element in the list
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2020.png)
    
- `split()`could convert the string to list
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2021.png)
    
- Aliasing(**混疊**)
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2022.png)
    
    - Once change the list A, list B will also be changed. Because these two variables reference to the same list `["hard work", 10, 1.2]`
        - `["hard work", 10, 1.2]` → `["banana", 10, 1.2]`
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2023.png)
        
- By solving the problem in aliasing, we could use “clone” method
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2024.png)
    

## Comparison between tuples and lists

|  | Python Lists | Python Tuples |
| --- | --- | --- |
| 1 | List are mutable | Tuples are immutable |
| 2 | Iterations are time-consuming | Iterations are comparatively Faster |
| 3 | Inserting and deleting items is easier with a list. | Accessing the elements is best accomplished with a tuple data type. (immutability) |
| 4 | Lists consume more memory | Tuple consumes less than the list |
| 5 | Lists have several built-in methods. | A tuple does not have many built-in methods because of immutability |
| 6 | A unexpected change or error is more likely to occur in a list. | In a tuple, changes and errors don't usually occur because of immutability. |

## Dictionaries

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2025.png)

- key is used to look for the value
    - E.g. `DICT['Back in Black'] : '1980'`
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2026.png)
    
- Functions
    - `DICT['Graduation']='2007'` : add the key and value pair
    - `del(DICT['Thriller'])`
    - `'The Bodyguard' in DICT` → return boolean
    - `DICT.keys()`
    - `DICT.values()`

## Sets

- The most important properties of sets are that the elements in the sets are all **unique**, and **no order.**
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2027.png)
    
- Only showing the unique elements
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2028.png)
    
- type casting
    
    when you assign a value of one primitive data type to another type
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2029.png)
    
- venn diagram (**文氏圖**)
    
    venn diagram is a common tool to represent the sets
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2030.png)
    
- Functions
    - `A.add()`
    - `A.remove()`
    - `"AC/DC" in A` → return `True / False`
    - **intersection (交集)**
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2031.png)
        
    - **union (聯集)**
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2032.png)
        
    - `A.issubset()` → if so, will return `True`
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2033.png)
        

# Week03 - Python Programming Fundamentals

## **Conditions and Branching**

- conditions
    - e.g. `==` → return `True / False`
- branching
    - `if/else`
        
        ```python
        age = 17
        if (age > 18):
        		print("you can enter")
        elif(age == 18):
        		print("go see Pink Floyd")
        else:
        		print("go see Meat Loaf")
        print("move on")
        ```
        
- Logic Operators
    - `and, not, or,` ...
    - `or`
    
    ```python
    album_year = 1990
    if (album_year < 1980) or (album_year > 1989):
    		print("The Album was made in the 70's ot 90's")
    else:
    		print("The Album was made in the 1980's")
    ```
    
    - 

## **Loops**

- `range(N)` → `0, 1, 2,..., N-1`
- for loop
    - example
        
        ```python
        squares = ["red", "yellow", "green", "purple", "blue"]
        
        for i in range(0,5):
        		squares[i] = "white"
        ```
        
    - `enumerate`
        
        ```python
        squares = ["red", "yellow", "green", "purple", "blue"]
        
        for i, square in enumerate(squares ):
        		square
        		i
        ```
        
- while loop
    - example
        
        ```python
        squares = ["orange", "orange", "purple","orange", "blue"]
        new_squares = []
        i = 0
        while(squares[i]=="orange"):
        		new_squares.append(squares[i]) 
        		i += 1
        ```
        

## **Functions**

- Python built-in functions
    - `len()`
    - `sum()`
    - `sort()` vs. `sorted()`
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2034.png)
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2035.png)
        
- building function
    - collecting arguments
    
    ```python
    def ArtistNames(*names):
    		for name in names:
    				print(name)
    ArtistName("Adam", "Jack", "Lulu")
    ```
    
    - global variables vs local variables
        - global: create outside of a function
        - local: variable created within the function
            
            Could use `global` to assign a variable to become global variable
            
        
        ```python
        def Thriller():
        		Date = 1982     # local
        		
        		# create global variable within the function
        		global Var 
        		Var = 30
        
        		return (Date)
        Date = 2017         # global
        print(Thriller())
        print(Date)
        ```
        

## **Exception Handling**

- An exception handler the program knew how to deal with this type of error and was able to output the error message to continue along with the program.
- `try/except`
    
    ```python
    try:
    	getFile = open('myfile', 'r')
    	getFile.write("My file for exception handling.")
    except IOError:
    	print("Unable to open or read the data in the file.")
    # show the unknown type of error
    except: 
    	print("Some other error occrred!")
    # Show a notification when the program executed properly
    else: 
    	print("The file was written successfully!")
    # tell the program to close the file no matter the end result, and showing the message
    finally:
    	getFile.close()
    	print("File is now closed.")
    ```
    

## **Objects and Classes**

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2036.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2037.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2038.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2039.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2040.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2041.png)

![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2042.png)

- Attributes and Objects
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2043.png)
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2044.png)
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2045.png)
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2046.png)
    
    ```python
    RedCircle = Circle(10,"red") # object constructor
    ```
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2047.png)
    
    - The way of changing atrribute
        
        ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2048.png)
        
- Method
    
    ![Untitled](4%20Python%20for%20Data%20Science,%20AI%20&%20Development%20fb79c5b5d8c54f00a6cb88a01b41417c/Untitled%2049.png)
    

# Week04 - Working with Data in Python

### Reading & Writing Files with Open

```python
File1 = open("/resources/data/Example2.txt","w")

# second argument 
	# "r", reading
	# "w", writing
	# "a", appending
```

Use `with`function is a better way to open the file → when jump outside of the block, the program will close the file automatically

```python
with open("Example1.txt", "r") as File1:
	file_stuff = File1.read()
	print(file_stuff)
print(File1.closed)
print(file_stuff)
```

- `readline` function
    - `readline()` → get the first line of the text
    - `readlines(16)` → get the first 16 elements in the file

### Pandas

### Numpy in Python

# Week05 - APIs, and Data Collection

## ****REST APIs, Webscraping, and Working with Files****

# Final Exam

In Python what statement would print out the first two elements “Li” of “Lizz”?

**1 / 1 point**

**print(name[0:2])**

**print(name[2:0])**

**print(name[1:2])**

**Correct**

****2.****Question 2

If **var** = “**01234567**” what Python statement would print out only the odd elements?

**1 / 1 point**

**print(var[1::2])**

**print(var[2::2])**

**print(var[3::1])**

**Correct**

****3.****Question 3

What is the Python find() method used for?

**1 / 1 point**

**The method finds the starting index of a substring**

**The method finds the ending index of a substring**

**The method finds every second index of a substring**

**Correct**

****4.****Question 4

What is the type of the following: **1.0**

**1 / 1 point**

**float**

**str**

**int**

**Correct**

****5.****Question 5

What will happen if you cast a float to an integer?

**1 / 1 point**

**Nothing happens**

**It will remove decimal point**

**An error will occur**

**Correct**

****6.****Question 6

What following code segment would produce an output of “0”?

**1 / 1 point**

**1//2**

**1/2**

**Correct**

****7.****Question 7

In Python 3 what does regular division always result in?

**1 / 1 point**

**Float**

**Int**

**Correct**

****8.****Question 8

Dictionary items can be:

**1 / 1 point**

**Numerous data types**

**Stored in duplicate keys**

**Only one data type**

**Correct**

****9.****Question 9

What is the syntax to obtain the first element of the tuple?

A=('a','b','c')

**1 / 1 point**

**A[0]**

**A[1]**

**A[:]**

**Correct**

****10.****Question 10

What is the result of the following operation: **'1,2,3,4'.split(',')** ?

**1 / 1 point**

**'1','2','3','4'**

**('1','2','3','4')**

**['1','2','3','4']**

**'1234'**

**Correct**

****11.****Question 11

**Lists are:**

**0 / 1 point**

**Not mutable**

**Mutable**

**Unordered**

**Not indexed**

**Incorrect**

****12.****Question 12

What happens with this segment of code: **a=set(A)** ?

**1 / 1 point**

**It casts the list “a” to the set “A”**

**It casts the list “A” to the set “a”**

**It returns an error**

**Correct**

****13.****Question 13

What value of x will produce the output?

## **Hi**

## **Mike**

**x=**

**if(x!=1):**

**print('Hello')**

**else:**

**print('Hi')**

**print('Mike')**

**0 / 1 point**

**x=6**

**x=1**

**x="7"**

**Incorrect**

****14.****Question 14

What is an error that occurs during the execution of code?

**1 / 1 point**

**Error messages**

**Exception handling**

**Exception**

**Finally**

**Correct**

****15.****Question 15

What add function would return ‘4’ ?

**1 / 1 point**

**def add(x): return(x+x) add(2)**

**def add(x): return(x+x+x) add('1')**

**def add(x): return(x+x) add('4')**

**Correct**

****16.****Question 16

What function returns a sorted list?

**1 / 1 point**

**sort()**

**find()**

**sorted()**

**lower()**

**Correct**

****17.****Question 17

What segment of code would output the following?

3

6

9

**1 / 1 point**

**A=['1','2','3'] for a in A: print(2*a)**

**A=[1,2,3] for a in A: print(3*a)**

**A=[1,2,3] for a in A: print(2*a)**

**Correct**

****18.****Question 18

What is the output of the following?

for i in range(1,5): if (i!=2): print(i)

**1 / 1 point**

**1
3
4**

**1
2
3
4**

**2**

**Correct**

****19.****Question 19

Consider the class Rectangle, what are the data attributes?

class Rectangle(object):
        def __init__(self,width=2,height =3,color='r'):
                                  self.height=height
                                  self.width=width
                                  self.color=color
    def drawRectangle(self):
                       import matplotlib.pyplot as plt
                       plt.gca().add_patch(plt.Rectangle((0, 0),self.width, self.height ,fc=self.color))
                       plt.axis('scaled')
                       plt.show()

**1 / 1 point**

**drawRectangle**

**self.height, self.width,self.color**

**__init__**

**Correct**

correct

****20.****Question 20

What line of code would produce the following: array([0, 0, 0, 0, 0]) ?

**1 / 1 point**

**a=np.array([0,1,0,1,0]) b=np.array([1,0,1,0,1]) a*b**

**a=np.array([0,1,0,1,0]) b=np.array([1,0,1,0,1]) a+b**

**a=np.array([0,1,0,1,0]) b=np.array([1,0,1,0,1]) a-b**

**Correct**

****21.****Question 21

What is the result of the following lines of code?

a=np.array([10,9,8,7,6]) a+1

**1 / 1 point**

**array([101,91,81,71,61])**

**array([11,10,9,8,7])**

**array([9, 8, 7, 6, 5])**

**Correct**

****22.****Question 22

What does the following line of code select along with the headers ‘Artist’, ‘Length’ and ‘Genre’ from the dataframe **df**?

y=df[['Artist','Length','Genre']]

**1 / 1 point**

**Rows**

**Columns**

**The entire dataframe**

**Correct**

****23.****Question 23

Consider the file object: **File1.**What would the following line of code output?

file1.readline(4)

**1 / 1 point**

**It would output the entire text file**

**It would output the first 4 lines from the text file**

**It would output the first 4 characters from the text file**

**Correct**

****24.****Question 24

Which line of code is in the mode of append?

**1 / 1 point**

**with open("Example.txt","r") as file1:**

**with open("Example.txt","w") as file1:**

**with open("Example.txt","a") as file1:**

**Correct**

****25.****Question 25

What is the extraction of data from a website?

**1 / 1 point**

**Web crawling**

**Webscraping**

**Data mining**

**Correct**