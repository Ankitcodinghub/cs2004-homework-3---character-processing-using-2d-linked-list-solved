# cs2004-homework-3---character-processing-using-2d-linked-list-solved
**TO GET THIS SOLUTION VISIT:** [CS2004 Homework 3 – Character Processing using 2D Linked List Solved](https://www.ankitcodinghub.com/product/cs2004-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;109386&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS2004 Homework 3 – Character Processing using 2D Linked List Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
Your program should be a robust one such that you have to consider all relevant programmer mistakes and extreme cases; you are expected to take actions accordingly!

Introduction

In this homework, you are asked to implement a two-dimensional character processor that will read some words from an input file and store them in a two-dimensional linked list structure. Each row in this 2D data structure is a linked list that stores a word character by character; i.e. each node of a row stores one character of the word. Moreover, the characters of the words are also vertically connected via some other pointers, which makes the data structure two-dimensional. Your program will also process and manipulate the data structure via some operations and member functions such as displaying all or certain rows/columns, sorted insertion, deleting certain rows/columns. The program details will be explained in the subsequent sections.

The Program Flow

At the very beginning, the program asks the user for the input file name. The user enters the file name and if the file is not successfully opened, the program keeps reading the file name over and over again until it is opened successfully. This file stores some words (assume all lowercase letters), line by line. Then, the program should read each word of the file and stores in the 2D data structure in ascending alphabetical order with respect to the first letter. After that, the program prompts a menu that contains a list of operations. The menu provides 7 different options, and the options from 1 to 6 can be chosen in any order several times. When one of the options from 1 to 6 is entered, the corresponding operation is performed and then the next menu option is read. This continues until the user chooses the seventh option (Clear the matrix and exit) to delete the 2D data structure and end the program. In case the user enters a wrong menu option, an error message is displayed. Actually, the construction of the data structure by reading the file and the abovementioned menu logic are implemented by us and given to you as a cpp file that contains the main function. In this main function, we call several member functions for the class that you will implement.

The menu options and the corresponding operations are explained below.

1. Display the full Matrix:

When this option is selected, the entire 2D data structure should be displayed row by row, starting with the topmost one.

2. Display the full matrix in reverse order

When this option is selected, the entire matrix should be displayed again row by row but in reverse order, i.e., starting with the bottommost row and going up one by one. The characters in the rows will be displayed in normal order (not reverse). Please remark that this option is for display purposes only; the data structure itself will not change.

Hint: you can make use of recursion here.

3. Display all the rows starting with a specific character

When this option is selected, the program will ask the user to enter a character. Then, the program will display all the rows that start with this character.

4. Display all the columns starting with a specific character

When this option is selected, the program will ask the user to enter a character. Then, the program will display all the columns that start with this character.

5. Delete all the rows starting with a specific character

When this option is selected, the program will ask the user to enter a character. Then, all the rows that start with this character will be deleted. This option should also display the total number of rows deleted.

6. Delete all the columns starting with a specific character

When this option is selected, the program will ask the user to enter a character. Then, all the columns that start with this character will be deleted. This option should also display the total number of columns deleted.

7. Clear the data structure and exit

When this option is selected, the program should delete all the dynamic memory allocations for the data structure and exit the program.

The Data Structure to be used

In this homework, you are asked to implement the two-dimensional linked list data structure as a class (named TwoDLinkedList) with one private data member, which is a pointer to the head node of the data structure (the one at the top-left). The node struct of this data structure must have the following data members (if you want, you can add constructors to the struct).

struct node

{ char data; node *right; node *down;

};

The right pointer points to the node on the right on a row; whereas, the down pointer points to the node at the same position of the row below. The right pointer of the last node of each row is NULL. Similarly, the down pointer of the bottom node of each column is also NULL. In this way, we generate a matrix shaped 2D linked data structure. In this data structure, the number of nodes in all of the rows are the same. A generic form of such a structure is given in Figure 1. An example data structure with 4 rows and 5 columns is given in Figure 2.

Figure 1. A generic form of the 2D data structure

Figure 2. An example 2D data structure with 4 rows and 5 columns

No other multiple data containers (built-in array, dynamic array, vector, matrix, 2D array, etc.) can be used. Do not use string data type to avoid these restrictions. The only places of using string are (i) as file names, and (ii) while reading the words from the file (in the insertion member function, you will use a string parameter to pass the word to the function and process it while creating a row of the 2D data structure).

Reading the File and Creating the Data Structure

While reading the words from the input file, your program should add each word (line) in a separate row of the 2D data structure, where each character is stored in a node. While doing so, your program should maintain ascending order for the rows according to (only) the first character of the row. If there is a tie with the first characters (i.e. having two or more words that start with the same character, you will not check the second characters, etc. If there is such a tie, then the new word should be inserted before the first row that starts with that character. An example file and the resulting 2D structure is given in Figure 3. In this example data structure, “week” is above “weak”, because first “weak” is added to the data structure and when “week” is read, it is inserted above “weak” as both start with “w”.

Figure 3. A visualization of the data structure after reading the input from file “in4.txt” and inserting them in the 2D data structure according to the insertion rules.

Note2: Please assume that the file contains all lowercase letters and there are no whitespaces before, within and after the words. You do not need to check this.

Provided main cpp file and the requested class implementation

We have provided the main function of this homework to you within the homework pack. You have to use it directly and without any modifications other than adding an #include line for your class header file (make sure that the header file name that you #include matches the physical file name, if you update the file names to follow the naming convention just before the submission).

As you see from the provided main function, the file opening/reading logic, construction of the data structure via calling a class member function, menu logic are all implemented. What you have to do is to write the class’ header and implementation files so that they work with the given main function.

The member functions used in main are self-explanatory and match with the menu operations. The only member function not used in the menu options is add_row_sorted function, which takes a string and inserts its characters to the 2D data structure as described in the sections above. We expect you explore the member function prototypes and requirements by analyzing the given main program and the explanations in this homework document.

If you need more member functions, other than the ones that we use in main, you are more than welcome to write. However, please first read the “Object Oriented Design Manifest” part below.

In the main function, after each input we use the command cin.ignore(numeric_limits&lt;streamsize&gt;::max(),’ ‘); so that extra characters in

the line are discarded. In this way, for each input line after the menu is displayed, only one (the first) character is read. This eliminates some unexpected behaviors in wrong data entry and makes your program more robust.

In the main, we did not make input check if the characters are digits (for menu) and lowercase letters (for row/column display/delete options). The reason for the latter case is that if the character entered is not a lowercase letter, no row/column can start with it and no display/deletion is done (of course, if the corresponding member functions are implemented properly). For the menu option, although it is a digit, we read as character and if the entered character is not a digit, the code gives an invalid menu option message, as expected.

Object Oriented Design Manifest

We believe it is clear that you have to apply proper object oriented design principles in this homework, but our past experience says that most of the students are either unaware or not willing to follow these principles. Thus, we wanted to manifest some important rules about the class design and implementation.

2) Another important rule of object oriented programming is to hide the details of the class from the programmer that uses this class. Particularly for this homework, this means that in any free function and in main function, we should not reach the head of the data structure directly. We have to make all of the updates, searches, etc. in main program through the member functions. Yes, technically it is possible and really easy to write a member function that returns head so that we can freely manipulate the data structure in the main program, but this is totally against the spirit behind object oriented programming and we do not do this. Actually, since you are not allowed to change main, we guarantee that you will not manipulate the data structure using head in main, but we wanted to make this clarification here.

3) In a separate cpp file, you have to have the member function implementations. If you want to have some extra free functions to help the implementation of the member functions, also write them in this file (not in main file). If you will write some helper free functions, please remark that the rule #2 above is also valid for free functions.

4) Class and struct definitions will be in a header file.

5) Yes, you will also submit the main file; so totally you will submit three files (two cpp, one h).

Some Important Rules

In order to get a full credit, your programs must be efficient and well presented, presence of any redundant computation or unnecessary memory usage or bad indentation, or missing, irrelevant comments are going to decrease your grades. You also have to use understandable identifier names, informative introduction and prompts. Modularity is also important; you have to use functions wherever needed and appropriate. Since using classes is mandated in this homework, a proper object-oriented design and implementation will also be considered in grading.

Please do not use any non-ASCII characters (Turkish or other) in your code.

/* Begin: code taken from ptrfunc.cpp */

…

/* End: code taken from ptrfunc.cpp */

Walk-through Example

A walk-through run of the program is shown in Table 1. The example given in the table assumes that data from “in4.txt” file and has been successfully read and stored in the data structure.

Table 1. Walk through example

Chosen Option Effect Output Explanation

(input, if any)

The figure on the left is a visualization of the data structure storing the input from the “in4.txt” text

file. *

1 book week weak The content of the data structure is displayed on the screen in its 2D representation

2 weak week book The content of the data structure is reversely displayed on the screen. (You can think of it as flipping the matrix across the x-axis).

3 week weak The program displays all the rows that start with the input char (here, w).

w

4 o e e

o e a The program displays all the columns that start with the input char (here, o).

o

5 The program deletes all the rows that start with the input char (here, b).

b

1 week weak The content of the data structure is displayed on the screen

6 The program deletes all the columns that start with the input char (here, e).

e

1 wk wk The content of the data structure is displayed on the screen

7 The data structure is cleared, and the program terminates

* Note that the rows of the matrix are sorted alphabetically according to the first letters. Thus, book is at the first row. As there is a tie between week and weak according to their first letter w, the rule that the program followed was to insert the new word (in case of a tie) before the existing one. And as the word weak appears first in the file and therefore added first to the data structure, when the word week is to be inserted in the matrix, it was inserted before the row of word weak.

Sample Runs

Sample runs are given below, but these are not comprehensive, therefore you have to consider all possible cases to get full mark. Inputs are shown in bold and italic.

The sample input files are provided in the homework pack.

Sample Run 1:

Please enter the file name: in9.txt

Please enter the number of the option from the list below:

1. Display the full matrix

2. Display the full matrix in reverse order

3. Display all the rows starting with a specific character

4. Display all the columns starting with a specific character

5. Delete all the rows starting with a specific character

6. Delete all the columns starting with a specific character

7. Clear the data structure and exit

Please enter a menu option: 1

aardvarks

Please enter a menu option: 6

Please enter first character of the columns to delete: a

The number of deleted columns is: 3

Please enter a menu option: 1

rdvrks

Please enter a menu option: 6

Please enter first character of the columns to delete: r

The number of deleted columns is: 2

Please enter a menu option: 1

dvks

Please enter a menu option: 7 Clearing the data structure and exiting the program…

Sample Run 2:

Please enter the file name: in9_2

Please enter the file name: in9_2.txt

Please enter the number of the option from the list below:

1. Display the full matrix

2. Display the full matrix in reverse order

3. Display all the rows starting with a specific character

4. Display all the columns starting with a specific character

5. Delete all the rows starting with a specific character

6. Delete all the columns starting with a specific character

7. Clear the data structure and exit

Please enter a menu option: 1

macaroons vacancies

Please enter a menu option: 3

Please enter first character of the rows to display: h

Please enter a menu option: 3

Please enter first character of the rows to display: v

vacancies

Please enter a menu option: 4

Please enter first character of the columns to display: o

o c o i

Please enter a menu option: 4

Please enter first character of the columns to display: t

Please enter a menu option: 4

Please enter first character of the columns to display: r

r n

Please enter a menu option: 6

Please enter first character of the columns to delete: o

The number of deleted columns is: 2

Please enter a menu option: 5

Please enter first character of the rows to delete: m

The number of deleted rows is: 1

Please enter a menu option: 1

vacanes

Please enter a menu option: 7

Clearing the data structure and exiting the program…

Sample Run 3:

Please enter the file name: in4.txt

Please enter the number of the option from the list below:

1. Display the full matrix

2. Display the full matrix in reverse order

3. Display all the rows starting with a specific character

4. Display all the columns starting with a specific character

5. Delete all the rows starting with a specific character

6. Delete all the columns starting with a specific character

7. Clear the data structure and exit

Please enter a menu option: 1

book week weak

Please enter a menu option: 6

Please enter first character of the columns to delete: j

The number of deleted columns is: 0

Please enter a menu option: 6

Please enter first character of the columns to delete: k

The number of deleted columns is: 1

Please enter a menu option: 1

boo wee wea

Please enter a menu option: 2

wea wee boo Please enter a menu option: 5

Please enter first character of the rows to delete: d

The number of deleted rows is: 0

Please enter a menu option: 5

Please enter first character of the rows to delete: b

The number of deleted rows is: 1

Please enter a menu option: 1

wee wea

Please enter a menu option: 6

Please enter first character of the columns to delete: q

The number of deleted columns is: 0

Please enter a menu option: Q

Invalid input. You need to enter a valid menu option.

Please enter a menu option: 6

Please enter first character of the columns to delete: H

The number of deleted columns is: 0

Please enter a menu option: 6

Please enter first character of the columns to delete: w

The number of deleted columns is: 1

Please enter a menu option: 1

ee ea

Please enter a menu option: 7

Clearing the data structure and exiting the program…

Sample Run 4:

Please enter the file name: int.txt

Please enter the file name: in2.txt

Please enter the number of the option from the list below:

1. Display the full matrix

2. Display the full matrix in reverse order

3. Display all the rows starting with a specific character

4. Display all the columns starting with a specific character

5. Delete all the rows starting with a specific character

6. Delete all the columns starting with a specific character

7. Clear the data structure and exit

Please enter a menu option: 1

be hi he is if on pi we

Please enter a menu option: 3

Please enter first character of the rows to display: i

is if

Please enter a menu option: 5 Please enter first character of the rows to delete: i

The number of deleted rows is: 2

Please enter a menu option: 1

be hi he on pi we

Please enter a menu option: 4

Please enter first character of the columns to display: e

e i e n i e

Please enter a menu option: 6

Please enter first character of the columns to delete: e

The number of deleted columns is: 1

Please enter a menu option: 1

b h h o p w

Please enter a menu option: 6

Please enter first character of the columns to delete: b

The number of deleted columns is: 1

Please enter a menu option: 1

Please enter a menu option: 7

Clearing the data structure and exiting the program…

What and where to submit (PLEASE READ, IMPORTANT) – Same as before except 1st line

You have to submit your class’ implementation file, header file and the file that contains the main function.

Submissions guidelines are below. Some parts of the grading process might be automatic. Students are expected to strictly follow these guidelines in order to have a smooth grading process. If you do not follow these guidelines, depending on the severity of the problem created during the grading process, 5 or more penalty points are to be deducted from the grade.

Name your cpp file that contains your main program using the following convention:

“SUCourseUserName_YourLastname_YourNames_HWnumber.cpp”

Your SUCourse user name is your SUNet user name which is used for checking sabanciuniv e-mails (not the numeric one). Do NOT use any spaces, non-ASCII and Turkish characters in the file name. For example, if your SUCourse user name is cago, name is Çağlayan, and last name is Özbugsızkodyazaroğlu, then the file name must be:

Cago_Ozbugsizkodyazaroglu_Caglayan_hw2.cpp

Actually, it does not matter whether you use uppercase of lowercase letters in the file names.

Cago_Ozbugsizkodyazaroglu_Caglayan_hw2_myfuncs.cpp or

You will receive zero if your compressed zip file does not expand or it does not contain the correct files. The naming convention of the zip file is the same. The name of the zip file should be as follows:

SUCourseUserName_YourLastname_YourNames_HWnumber.zip

For example, zubzipler_Zipleroglu_Zubeyir_hw2.zip is a valid name, but

Hw2_hoz_HasanOz.zip, HasanOzHoz.zip

are NOT valid names.

Submit via SUCourse ONLY! You will receive no credits if you submit by other means (e-mail, paper, etc.).

Successful submission is one of the requirements of the homework. If, for some reason, you cannot successfully submit your homework and we cannot grade it, your grade will be 0.

Good Luck!

Albert Levi, Ahmed Salem
