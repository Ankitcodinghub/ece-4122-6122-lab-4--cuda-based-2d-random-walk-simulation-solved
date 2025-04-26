# ece-4122-6122-lab-4--cuda-based-2d-random-walk-simulation-solved
**TO GET THIS SOLUTION VISIT:** [ECE 4122/6122 Lab 4- CUDA-based 2D Random Walk Simulation Solved](https://www.ankitcodinghub.com/product/ece-4122-6122-lab-4-cuda-based-2d-random-walk-simulation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;127131&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;ECE 4122\/6122 Lab 4- CUDA-based 2D Random Walk Simulation Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (2 votes)    </div>
    </div>
Category: CUDA

Objective:

Implement a CUDA program to simulate a 2D random walk. A random walk is a mathematical process that describes a path consisting of a sequence of random steps. In this assignment, you will simulate a large number of walkers taking steps either north, south, east, or west on a grid, and calculate the average distance they travel from the origin.

Description:

Create a C++ application using CUDA that takes as program input arguments the Number of Walkers, and the number of steps each walker needs to take on a 2D integer grid. Use command line flags to distinguish Number Walkers (-W) and (-I) for number of steps. All the walkers start at the origin (0, 0). Your application should implement three functions that internally use different memory models to perform the calculations.

1. (30 pts) cudaMalloc

2. (30 pts) cudaMallocHost

3. (30 pts) cudaMallocManaged

Your application should output to the console screen the total time each function took to perform the calculations and the average distance of the walkers from the origin and then exit.

(10 pts) Minimizing calculation times for all three functions.

Sample Program Flow:

&gt;Lab4 -W 1000 -I 10000

&gt; Normal CUDA memory Allocation:

&gt;(4 spaces) Time to calculate(microsec): ???

&gt;(4 spaces) Average distance from origin: ???.???

&gt; Pinned CUDA memory Allocation:

&gt;(4 spaces) Time to calculate(microsec): ???

&gt;(4 spaces) Average distance from origin: ???.???

&gt; Managed CUDA memory Allocation:

&gt;(4 spaces) Time to calculate(microsec): ???

&gt;(4 spaces) Average distance from origin: ???.???

&gt;Bye

Turn-In Instructions

Zip up your file(s) into Lab4.zip and upload this zip file on the assignment section of Canvas.

Grading Rubric:

AUTOMATIC GRADING POINT DEDUCTIONS PER PROBLEM:

Element Percentage Deduction Details

Does Not Compile 40% Code does not compile on PACE-ICE!

Does Not Match Output Up to 90% The code compiles but does not produce correct outputs.

Clear Self-Documenting Coding Styles Up to 25% This can include incorrect indentation, using unclear variable names, unclear/missing comments, or compiling with warnings. (See Appendix A)

LATE POLICY

Element Percentage Deduction Details

Appendix A: Coding Standards

Indentation:

When using if/for/while statements, make sure you indent 4 spaces for the content inside those. Also make sure that you use spaces to make the code more readable. For example:

for (int i; i &lt; 10; i++)

{ j = j + i;

}

If you have nested statements, you should use multiple indentions. Each { should be on its own line (like the for loop) If you have else or else if statements after your if statement, they should be on their own line.

for (int i; i &lt; 10; i++)

{

if (i &lt; 5) { counter++; k -= i; } else

{ k +=1; } j += i;

}

Camel Case:

This naming convention has the first letter of the variable be lower case, and the first letter in each new word be capitalized (e.g. firstSecondThird).

This applies for functions and member functions as well!

The main exception to this is class names, where the first letter should also be capitalized.

Variable and Function Names:

Your variable and function names should be clear about what that variable or function represents. Do not use one letter variables, but use abbreviations when it is appropriate (for example: “imag” instead of

“imaginary”). The more descriptive your variable and function names are, the more readable your code will be. This is the idea behind self-documenting code.

File Headers:

Every file should have the following header at the top

/*

Author: your name

Class: ECE4122 or ECE6122 (section)

Description:

What is the purpose of this file?

*/

Code Comments:

1. Every function must have a comment section describing the purpose of the function, the input and output parameters, the return value (if any).

2. Every class must have a comment section to describe the purpose of the class.

3. Comments need to be placed inside of functions/loops to assist in the understanding of the flow of the code.
