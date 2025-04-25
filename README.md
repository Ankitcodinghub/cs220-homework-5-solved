# cs220-homework-5-solved



**<span style='color:red'>TO GET THIS SOLUTION VISIT:</span>** https://www.ankitcodinghub.com/product/cs220-solved/

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;128036&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS220 Homework 5 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">
            
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
            5/5 - (4 votes)    </div>
    </div>
&nbsp;

Objective:

Build the two Assembly Language programs described below, which will test your understanding of Assembly programs for our HACK architecture. Highly recommend you go through the simulator tutorial for assembly programs before attempting the homework.

Grading method:

Div.asm:

In this program, you will be implementing the division operation by successively subtracting the dividend and divisor to reach a quotient result. Write an assembly program to perform the division of two integers (stored at R0 and R1) and store the result in R2. You can perform multiplication through successive subtraction. For example:

16 / 3 = 16 – 3 – 3 – 3 – 3 – 3 = 0 (remainder 1)

a. First write Java code using a loop to perform the successive subtraction.

Assume the following:

int R0 = 16; int R1 = 3; int R2 = 0; // R2 holds the result of R0 / R1 (after using successive subtraction in a loop) // You do not have to submit the Java code, it is meant to help you translate into assembly.

b. Next, convert the high-level Java code into assembly code (named div.asm). This is the code you will copy/paste to the Word document you submit. Please ensure *every* section of Assembly code is documented with a comment.

CS220.asm:

Here are two screen shots indicating the expected output:

a) Regular Challenge

b) Extra-Credit Challenge w/ Centering (+ 20 points extra credit)

What do you turn in?

Create one Word document (or PDF) with the following in order:

1. The Div.asm source code (make sure to comment every section of code)

2. A screen shot (entire window) containing the output from running the Div.asm code with R0 initialized to 16 and R1 initialized to 3. The correct result of 5 should be shown in R2. Be sure to comment your code and end the program with an infinite loop to prevent NOOP slides.

3. The CS220.asm source code (make sure to comment every section)

4. A screen shot containing the output from running the CS220.asm code in the CPUEmulator (take screen shot of entire window).

Program Working? Well built? Documentation?
