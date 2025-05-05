# cop3503-lab-1---introduction-to-c-solved
**TO GET THIS SOLUTION VISIT:** [COP3503 Lab 1 – Introduction to C++ Solved](https://www.ankitcodinghub.com/product/cop3503-lab-1-introduction-to-c-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;30332&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COP3503 Lab 1 – Introduction to C++ Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (5 votes)    </div>
    </div>
<strong>Overview </strong>

This assignment’s purpose is to get you a bit more familiar with C++ and start digging into its basic constructs. You are going to take several Java files and convert them into a single C++ program.

<strong>Description </strong>

The three files you are going to work from are as follows:

<ul>
<li>java</li>
<li>java</li>
<li>java</li>
</ul>
You are going to combine the functionality of these three files into a single program, with a basic menu prompt. Typically in C++, header files contain the prototypes of functions, while .cpp files contain the definitions. You are going to follow that convention, writing the code for this assignment across 3 files:

<ul>
<li>cpp</li>
<li>cpp</li>
<li>h</li>
</ul>
The first thing your program will need is some sort of prompt for the person using the application (aka “the user”). Not all programs need this human-centered element, it is good practice for you to do so (i.e. it’s a requirement in this assignment). Nothing too complicated, just a simple menu, like this:

<ol>
<li>Quadratic Root</li>
<li>Grade Calculator</li>
<li>Credit Card Validator Enter a number:</li>
</ol>
After getting a number (and verifying that it not only IS a number, but is within the valid range), you will call the appropriate function:

QuadraticRoot();

GradeCalculator();

CreditCardValidator();

The details of what each function should do are in the next sections.

&nbsp;

&nbsp;

&nbsp;

<h1>Quadratic Root Tool</h1>
The roots of a quadratic equation in form of 𝒂𝒙<sup>𝟐 </sup>+ 𝒃𝒙 + 𝒄 = 𝟎 can be obtained using these formulae:

−𝑏+√𝑏<sup>2</sup>−4𝑎𝑐&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; −𝑏−√𝑏<sup>2</sup>−4𝑎𝑐

𝒓𝟏= and 𝒓𝟐=

2𝑎&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2𝑎

𝒃<sup>𝟐</sup> − 𝟒𝒂𝒄 is called the discriminant of the quadratic equation. If it is <strong>positive</strong>, the equation has two real roots; if it is <strong>zero</strong>, the equation has one root. If it is <strong>negative</strong>, the equation has no real roots.

The QuadraticRoot() function will prompt the user to enter values for <em>a</em>, <em>b</em>, and <em>c </em>and displays the result based on the discriminant. If the discriminant is positive, display two roots. If the discriminant is 0, display one root. Otherwise, display “The equation has no real roots.”

Some sample runs:

Enter a, b, c: 1.0 3 1

The equation has two roots: -0.38166 and -2.61803

Enter a, b, c: 1 2.0 1

The equation has one root: -1

Enter a, b, c: 1 2 3

The equation has no real roots.

<h1>Grade Calculator</h1>
The GradeCalculator() function will read student scores, get the best score (bestScore) from them, and then assign letter grades based on the following scheme:

A: [bestScore, bestScore – 10]

B: [bestScore – 10, bestScore – 20]

C: [bestScore – 20, bestScore – 30]

D: [bestScore – 30, bestScore – 40]

E: Lower than bestScore – 40

The function should ask for a number, indicating how many scores to calculate. After that, a number of scores equal to that number will need to be entered (ex: enter a 3, and then 3 scores). A sample run:

Enter the number of students: 4

Enter 4 scores: 40 55 70 58

Student 1 – Score: 40, Letter: C

Student 2 – Score: 55, Letter: B

Student 3 – Score: 70, Letter: A

Student 4 – Score: 58, Letter: B

&nbsp;

&nbsp;

&nbsp;

<h2>Credit Card Validator</h2>
Credit card numbers follow certain patterns. A credit card number must have between 13 and 16 digits. In addition, cards have prefixes by type:

<ul>
<li>– Visa</li>
<li>– Mastercard</li>
</ul>
37 – American Express

6 – Discover

In 1954, Hans Luhn of IBM proposed an algorithm for validating credit card numbers. The algorithm is useful to determine whether a card is entered correctly or whether a credit card is scanned correctly by a scanner. Credit card numbers are generated following this validity check, commonly known as the Luhn check. The Luhn check can be described as follows. Consider the card number 4388576018402626:

<ol>
<li>Double every second digit from right to left. If doubling of a digit results in a two digit number, add up the digits to get a single-digit number.</li>
</ol>
&nbsp;

<ol start="2">
<li>Now add all single-digit numbers from Step 1.</li>
</ol>
4 + 4 + 8 + 2 + 3 + 1 + 7 + 8 = 37

<ol start="3">
<li>Add all digits in the odd places from right to left in the card number.</li>
</ol>
6 + 6 + 0 + 8 + 0 + 7 + 8 + 3 = 38

<ol start="4">
<li>Add the results from the previous two steps.</li>
</ol>
37 + 38 = 75

<ol start="5">
<li>If the result of the addition is divisible by 10, the card number is valid; otherwise, it is invalid. For example, the number 4388576018402626 is invalid, but the number 4388576018410707 is valid.</li>
</ol>
The CreditCardValidator() function will ask the user for a credit card number, and then display whether or not that number is valid. A problem this is made of many smaller steps. Oftentimes breaking a single function into multiple functions makes it easier to understand and implement the solution. To that end, use the following functions:

// Return true if the card <em>number </em>is valid.

<strong>bool </strong><strong>isValid</strong>(<strong>long long </strong><strong>number</strong>)

&nbsp;

// Get the result of Step 2. <strong>int </strong><strong>sumOfDoubleEvenPlace</strong>(<strong>long long </strong><strong>number</strong>)

// Return this <em>number </em>if it is a single digit; otherwise, return

// the sum of the two digits.

<h3>int getDigit(int number)</h3>
&nbsp;

// Return sum of odd-place digits in <em>number</em>. <strong>int </strong><strong>sumOfOddPlace</strong>(<strong>long long </strong><strong>number</strong>)

// Return true if the <em>digit </em>is a prefix for this <em>number</em>.

<h3>bool prefixMatched(long long number, int digit)</h3>
&nbsp;

// Return the number of digits in <em>number </em><strong>int </strong><strong>getSize</strong>(<strong>long long </strong><strong>number</strong>)

&nbsp;

// Return the first <em>numDigits </em>digits from <em>number</em>. If the no. of

// digits in <em>number </em>is less than <em>numDigits</em>, return <em>number</em>.

<h3>long getPrefix(long long number, int numDigits)</h3>
&nbsp;

Here are example runs of the program:

Enter a credit card number: 4388576018410707 4388576018410707 is valid.

Enter a credit card number: 4388576018402626 4388576018402626 is invalid.

<h2>Conversion Tips</h2>
<ul>
<li>None of the functions in the C++ version will exist in a class. They will all exist in global space.</li>
<li>In Java, the “long” data type is 64-bits in length.</li>
<li>In C++, the “long” data type is AT LEAST as large as an integer (but possibly not any larger). A “long long” is a 64-bit variable type, and large enough to hold a credit card number.</li>
<li>Keywords like “public” and “static” on functions serve very specific purposes–in classes.</li>
<li>In C++, if you don’t know the size of an array at compile time, you need to dynamically allocate it. A common alternative to that is using a vector&lt;&gt;, which is an expandable array. The vector&lt;&gt; data type can take an integer as a parameter to its constructor, which determines its size. After that, you can access elements using brackets [] just like an array. Vectors can do a bit more (and we’ll discuss them later in the semester), but this will suffice for now.</li>
</ul>
