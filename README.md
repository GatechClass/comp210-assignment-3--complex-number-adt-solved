# comp210-assignment-3--complex-number-adt-solved
**TO GET THIS SOLUTION VISIT:** [Comp210 Assignment 3- Complex Number ADT Solved](https://mantutor.com/product/comp210-a3-complex-number-adt-solved/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;115090&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Comp210 Assignment 3- Complex Number ADT Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
The package a3 contains a Java interface for the complex number abstract data type. Refer here for a refresher on complex numbers:

https://en.wikipedia.org/wiki/Complex_number

Complete the implementation for the data type started in ComplexNumberImpl. The ADT is being modeled as an immutable type which means that the multiply and add methods should create new instances to return as their result.

Use the statically defined EQUALS_EPSILON as the epsilon bound for testing equality of the real and imaginary parts in your implementation of equals. The named constant I is also defined for your convenience if you should need it.

The functional specification of the ADT is as follows:

create: DOUBLE x DOUBLE =&gt; COMPLEX

Canonical operation for creating a new complex number given the magnitudes of its real and imaginary parts. real: COMPLEX =&gt; DOUBLE

Returns the magnitude of the real part.

imag: COMPLEX =&gt; DOUBLE

Returns the magnitude of the imaginary part.

absolute: COMPLEX =&gt; DOUBLE

Absolute value (see wikipedia page)

add: COMPLEX x COMPLEX =&gt; COMPLEX

Addition (see wikipedia page)

multiply: COMPLEX x COMPLEX =&gt; COMPLEX

Multiplication (see wikipedia page)

equals: COMPLEX x COMPLEX =&gt; BOOLEAN

Equality test. Two complex numbers are equal if both their real and imaginary parts are within EQUALS_EPSILON of each other.

In a3test, complete the tests for the following axiomatic analysis (you’ll need to come up with the right hand sides):

real(create(A,B)) = ???? imag(create(A,B)) = ???? absolute(create(A,B)) = ???? add(create(A,B), C) = ????? add(C, create(A,B)) = ????? multiply(create(A,B), C) = ????? multiply(C, create(A,B)) = ????? equals(create(A,B), C) = ?????

equals(C, create(A,B)) = ?????

You are encouraged to make each test as complete as you can think of, testing several different values and trying to cover corner cases. Feel free to add additional tests if you would like.
