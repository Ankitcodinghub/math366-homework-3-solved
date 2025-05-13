# math366-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [MATH366 Homework 3 Solved](https://www.ankitcodinghub.com/product/math366-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92277&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;MATH366 Homework 3 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
<strong>Problem 1: </strong>A “<em>matrix norm</em>” is a way of assigning a numerical measurement to a matrix. If <em>A </em>∈ R<em><sup>n</sup></em><sup>×<em>m </em></sup>is a matrix the four commonly used norms are denoted by,

<h1>||<em>A</em>||<sub>1</sub><em>,</em>||<em>A</em>||<sub>∞</sub><em>,</em>||<em>A</em>||<sub>2</sub><em>,</em>||<em>A</em>||<em><sub>F</sub></em></h1>
There are different types of matrix norms, each useful in their own context.

Let <em>A </em>∈ R<em><sup>n</sup></em><sup>×<em>m</em></sup>. The “<em>Frobenius norm</em>” is defined as follows,

(square root of the sum of squares, which is how you compute the norm of a vector in multivariable calculus). Sometimes the Frobenius norm is also called the Euclidean norm and can also be denoted by ||<em>A</em>||<em><sub>E</sub></em>.

The “<em>1-norm</em>” is defined as,

!

(in other words, add up all the columns in absolute value, and out of all those column sums, pick the largest number).

The “∞-<em>norm</em>” is defined as,

!

(in other words, add up all the numbers in the rows with absolute value, and out of all those row sums, pick the largest number).

1

Finally, the 2-norm is the most difficult to define,

||<em>A</em>||<sub>2 </sub>= max(<em>σ</em><sub>1</sub><em>,σ</em><sub>2</sub><em>,…,σ<sub>m</sub></em>)

where the <em>σ<sub>k </sub></em>are the “<em>singular values</em>” of <em>A</em>, i.e.

<em>σ</em><em>k </em>= p<em>λ</em><em>k</em>(<em>A</em><em>tA</em>)

Simply put, calculate the eigenvalues of <em>A<sup>t</sup>A</em>, the largest of the radicals of the eigenvalues is the 2-norm of the matrix.

Create a code in R called:

mat.norm(A,type=c(‘‘one’’,‘‘inf’’,‘‘F’’,‘‘2’’))

which calculates the matrix norm depending on which type of norm you want to use.

<strong>Problem 2: </strong>Another method for approximating roots is called <em>Newton’s method</em>. Suppose <em>f</em>() is some function for which we wish to find a root. Let <em>g</em>() denote the <u>derivative </u>of <em>f</em>(). Newton’s method proceeds by first making an initial guess <em>x</em><sub>0 </sub>(a “<em>guess</em>” is just an arbitrary starting value). We then construct the sequence,

(<em>x</em><sub>0</sub><em>,x</em><sub>1</sub><em>,x</em><sub>2</sub><em>,…,x<sub>n</sub></em>)

defined by the rule that,

The last number in this sequence, <em>x<sub>n</sub></em>, will be a good approximation for the root.

Write a code in R called newtons.method(f,g,x0,n) which calculates the last term in the sequence of approximations.

2
