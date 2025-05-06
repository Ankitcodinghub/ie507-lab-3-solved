# ie507-lab-3-solved
**TO GET THIS SOLUTION VISIT:** [IE507 Lab 3 Solved](https://www.ankitcodinghub.com/product/ie507-lab-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;97663&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;IE507 Lab 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this session, we will investigate how to query different solvers in Pyomo and check the error (or warning) messages. We will see how to modify various aspects of the optimization problem depending on the solver status or according to emerging needs.

Pyomo provides some options to reset sense of the optimization problem (to max or min), reset upper and lower bounds of variables, add new variables, add/deactivate constraints and add/deactivate objective functions.

We will also practice modeling optimization problems with integer variables in this lab. Integer optimization problems are those where some or all variables can take only integer values in the solution. When all the constraints and the objective function in a problem are linear, we call it an Integer Linear Program or Mixed-Integer Linear Program (MILP).

MILPs are used to model many problems, and have found even more applications than linear opti- mization. Though MILPs differ from LPs only in terms of integrality constraints on the variables, MILPs are in fact much harder to solve than LPs.

Please follow the instructions given below:

• Please use different notebooks for solving different problems.

• The notebook name for Exercise 1 should be YOURROLLNUMBER IE507 Lab3 Ex1.ipynb.

• Similarly, the notebook name for Exercise 2 should be YOURROLLNUMBER IE507 Lab2 Ex2.ipynb. • Please post your doubts in MS Teams or Moodle so that TAs can clarify.

For more details on pyomo, please consult https://pyomo.readthedocs.io/en/stable/index. html.

There are only 2 exercises in this lab. Try to solve all problems on your own. If you have difficulties, ask the Instructors or TAs.

Only the questions marked [R] need to be answered in the notebook. You can either print the answers using print command in your code or you can write the text in a separate text tab. To add text in your notebook, click +Text. Some questions require you to provide proper explanations; for such questions, write proper explanations in a text tab.

After completing this lab’s exercises, click File → Download .ipynb and save your files to your local laptop/desktop. Create a folder with name YOURROLLNUMBER IE507 Lab3 and copy your .ipynb files to the folder. Then zip the folder to create YOURROLLNUMBER IE507 Lab3.zip. Then upload only the .zip file to Moodle.

The deadline for today’s lab submission is tomorrow, 3rd September 2020, 11 59 PM Indian Standard Time (IST).

</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab Lab 03

Exercise 1: Resolving LP using different options [15 marks] Consider the optimization problem denoted (OP):

min x1 −x2 +x3 s.t. x1 ≥1,×2 ≥1,×3 ≥2, 2×1 −x2 +2×3 ≤4, 2×1 −3×2 +x3 ≤−5, −x1 +x2 −2×3 ≤−1.

</div>
<div class="column">
2-September-2019

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Solve the problem (OP) using cbc solver and glpk solver. Check the solver status and solver termination criterion for both solvers. Are they meaningful? Explain possible reasons for the solver status and solver termination criterion message.</li>
<li>In order to address the issue faced during solving problem (OP), you decide to use only cbc solver and intend to perform the following resolution steps independent of each other and check the result of the solver in each case.
<ol>
<li>(a) &nbsp;Change the optimization problem to a maximization problem and re-solve.</li>
<li>(b) &nbsp;Add an upper bound on x2 as x2 ≤ 5 and re-solve.</li>
<li>(c) &nbsp;Add a new constraint x2 − x3 ≤ 6 and re-solve.</li>
<li>(d) &nbsp;Deactivate the objective of problem (OP) and construct a new objective of the form min x1 + x2 + x3 and deactivate the constraint 2×1 − 3×2 + x3 ≤ −5 and add a different constraint x1 + x2 ≥ 25.</li>
</ol>
In each of the above resolution steps (a)-(d), explain the solver termination condition and solver status message and provide possible reasons for the messages obtained. Whenever you get optimal solutions, print the values of the objective function value, values of decision variables and print if the constraints are active or not.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 03 2-September-2019

Exercise 2: A first example of MILP [20 marks]

As a student in IITB, you are involved in selecting courses for completing your course requirements. You also want to make sure that the courses you select are interesting to you. Suppose that there are ten courses C1, C2, . . ., C10 being offered this semester. By completing each course you get the following credits:

Course Credit

<ol start="0">
<li>C0 &nbsp;2</li>
<li>C1 &nbsp;3</li>
<li>C2 &nbsp;5</li>
<li>C3 &nbsp;4</li>
<li>C4 &nbsp;6</li>
<li>C5 &nbsp;6</li>
<li>C6 &nbsp;8</li>
<li>C7 &nbsp;8</li>
<li>C8 &nbsp;6</li>
<li>C9 &nbsp;4</li>
<li>C10 &nbsp;6</li>
</ol>
You must gather at least 26 credits this semester. However your course selection depends on the

following constraints:

<ul>
<li>You must register for at least 5 courses and can register for up to a maximum of 9 courses this semester.</li>
<li>Courses C5 and C7 run during the same slots.</li>
<li>Courses C3 and C9 run during the same slots.</li>
<li>If you register for course C7 you cannot register for course C2.</li>
<li>If you register for courses C10 you must register for course C1.</li>
<li>Among the courses C0, C1, you must register for at least one course and can only register for at most one course.</li>
<li>Among the courses C2, C4, you can only register for at most one course.</li>
<li>Among the courses C8, C10, you can only register for at most one course.</li>
</ul>
<ol>
<li>[R] Write a mathematical model so that you can maximize your credits to be accumulated this semester. Explain how to design the model variables and indicate which variables are integers. (We usually replace the notation x ∈ R by x ∈ Z to denote that variable x is integer).</li>
<li>Use pyomo to construct your model.</li>
<li>[R] Solver your MILP using cbc solver and report the optimal values of the variables and the objective function value.</li>
<li>[R] Let us now compare it to a linear program. Suppose we remove the restrictions that the variables in the above problem are integers. Solve this modified problem and report the optimal values of the variables and the objective function value.</li>
<li>[R] Can the solution of the MILP be obtained by merely rounding the solution of the LP? Why or why not?</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
IE507, Modeling and Computation Lab

Lab 03 2-September-2019

6. [R] Suppose a new course C11 with 9 credits is introduced, but the course timing for C11 overlaps with the course timings of C7, C8, how will you change your model to include this new constraint?

7. [R] Solve the modified MILP and report the optimal values of the variables and objective function value.

8. [R] Solve the modified MILP by removing the integer constraints on the variables and check if the solution of the modified MILP can be obtained by merely rounding the solution of the corresponding modified LP? Explain.

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
</div>
