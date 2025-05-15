# cse340---final-exam-2025-solved
**TO GET THIS SOLUTION VISIT:** [CSE340 – Final Exam 2025 Solved](https://www.ankitcodinghub.com/product/cse340-final-exam-2025-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;134415&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE340 - Final Exam 2025 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<h1>EVEN ASU ID AND LAST DIGIT 0</h1>
<strong>PROBLEM 1 (20 points) </strong>Consider the following type declarations:

TYPE

T1 : int

T2 : structure {a: float;}

T3 : structure {b: int; a: pointer to T4;}

T4 : structure {a: T1;&nbsp; b: pointer to T3;}

T5 : function of T3 returns T7;

T6 : function of T4 returns T8;

T7 : array [1][10] of T6

T8 : array [1][10] of T5

<ol>
<li><strong>(10 points)</strong> Which types are structurally equivalent? Show the step by step table.</li>
</ol>
Now Consider the following variable declarations in conjunction to the above type declarations:

VAR&nbsp; x : T2; y : T2; z : T3; w : T4;

u, v : pointer to T1; p : pointer to T4;

<ol start="2">
<li><strong>(10 points, 2.5 points each)</strong> Assume that assignments between variables are allowed if the types of the variables are equivalent. For each of the following, list all type equivalence schemes under which the expression is valid. Consider <u>name equivalence</u>, <u>internal name equivalence</u>, and <u>structural equivalence</u> for each case. Assume that if two variables are equivalent under name equivalence, they are also equivalent under internal name equivalence.</li>
</ol>
<ul>
<li>x = y;</li>
<li>u = v;</li>
<li>w = z;</li>
<li>p = w.b;</li>
</ul>
<strong>PROBLEM 2 (20 points, 4 points each) </strong>

fun f (a, b, c, d) = a(c,d) + b[c[d]] &gt; 1.1

The abstract syntax tree of f is the following:

Fill in the blank, reducing all types to basic types and type constructors if possible:

<ul>
<li>Type of a =</li>
<li>Type of b =</li>
<li>Type of c =</li>
<li>Type of d =</li>
<li>Type of f =</li>
</ul>
<strong>PROBLEM 3 (20 points)</strong> Consider the following code in C syntax (use static scoping):

# include &lt;stdio.h&gt; int g (int n)

{ n = 2; return n*2;

}

int f (int x, int y)

{ int i; int j; i = x * y; j = y; x = x * 3; y = i – 2; return g(x);

}

int main ()

{ int a[3] = {1, 0, 3}; int b = 2; int c = f(a[b], b);

printf (“%d -%d -%d -%d -%d\n”, b, a[0], a[1], a[2], c); return 0;

}

&nbsp;

<ul>
<li><strong>(10 points)</strong> If parameters are passed by value, the output of this program is (Explain by showing the call arguments to each function)</li>
</ul>
&nbsp;

<ul>
<li><strong>(10 points)</strong> If parameters are passed by reference, the output of this program is (explain with box and circle)</li>
</ul>
<strong>PROBLEM 4 (20 points, 4 points each) </strong>Fully b-reduce the following expressions, show b reduction steps.

<strong>&nbsp;</strong>

<ol>
<li>(𝜆𝑎. 𝜆𝑒. 𝑎 𝑒)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝑎&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑒&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑥)</li>
</ol>
&nbsp;

<ol start="2">
<li>(𝜆𝑎. 𝜆𝑖. 𝑎 𝑖)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝜆𝑎. 𝑖&nbsp;&nbsp; 𝑎)</li>
</ol>
&nbsp;

<ol start="2">
<li>(𝜆𝑒. 𝜆𝑥. 𝜆𝑦. 𝑏&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝑎&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑏&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑐))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝜆𝑎. 𝜆𝑖.&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑎&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑖)</li>
</ol>
<em>&nbsp;</em>

<ol start="4">
<li>(𝜆𝑎. 𝜆𝑖. 𝑖&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑎)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝑎𝑙𝑝ℎ𝑎)(𝜆𝑎. 𝑎 𝑎)</li>
</ol>
&nbsp;

<ol start="5">
<li>((𝜆𝑒. 𝑒&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑒)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝜆𝑎. 𝑎))&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; (𝑎&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 𝑒)</li>
</ol>
&nbsp;
