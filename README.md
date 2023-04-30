Download Link: https://assignmentchef.com/product/solved-cs2400-lab-4
<br>
File streams, loops, if statements, value-returning functions, void functions.

<strong>Step 1:  Set up a separate directory for this lab. </strong>

First create a subdirectory called lab4.

<ol>

 <li>Type        cd 2400/Labs</li>

 <li>Type mkdir lab4</li>

 <li>Type cd lab4</li>

</ol>

<strong>Step 2: Program </strong>

Write a C++ program that repeatedly inputs students’ scores and determines the letter grades. The scores should be stored in a file called “scores.txt”. For each score, output the score along with its letter grade. Your program should count the number of A’s, B’s, etc. Use five counters (<em>aCount, bCount, etc</em>). See main program below.

The letter grade is determined based on the following scale:

&gt;= 90 (A), &gt;= 80 (B), &gt;= 70(C), &gt;= 60(D), &gt;= 0(F).

Output all frequencies.

<strong>Your program <em>must</em>, at least, include the following functions: </strong>

<ul>

 <li>A function (<em>getG</em>rade) that takes a score as a parameter and returns a letter grade. o char getGrade(double score); //prototype</li>

 <li>A void function to print the score and the grade.</li>

</ul>

o void printGrade(double score, char grade);

<ul>

 <li>A void function to print the frequencies.</li>

</ul>

void printFrequencies(int aCount, int bCount,                   int cCount, int dCount, int fCount);

<strong>Main Program: </strong>

int main() {      double score;

int aCount = 0, bCount = 0, cCount = 0, dCount = 0, fCount = 0;

//open the file for input     //get the first score       while(not end of file) {            char grade = getGrade(score);            //output the score and the grade

//determine which counter is updated

//get the next score

}




//output the frequencies

}

<strong>Sample Input File: </strong>

44 55 66 77 88 99 50

60 70 80 90 78.5 99.5

<strong>Sample output: </strong>

Score: 44.0, Grade: F

Score: 55.0, Grade: F

Score: 66.0, Grade: D

Score: 77.0, Grade: C

Score: 88.0, Grade: B

Score: 99.0, Grade: A

Score: 50.0, Grade: F

Score: 60.0, Grade: D

Score: 70.0, Grade: C

Score: 80.0, Grade: B

Score: 90.0, Grade: A

Score: 78.5, Grade: C

Score: 99.5, Grade: A




Grade  Frequency

—————-

<ul>

 <li>3</li>

 <li>2</li>

 <li>3</li>

 <li>2</li>

</ul>

F        3