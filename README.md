# stat4710j-homework-2-solved
**TO GET THIS SOLUTION VISIT:** [STAT4710J Homework #2 Solved](https://www.ankitcodinghub.com/product/stat4710j-homework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;126130&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;STAT4710J  Homework #2 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Properties of Simple Linear Regression

We saw that the θ0 = θˆ0 and θ1 = θˆ1 that minimize the average L2 loss for the simple linear regression model are:

Or, rearranging terms, our predictions ˆy are:

Prove, using the equation for ˆy above, that = 0 (meaning the sum of the residuals is zero).

Answer.

(b) (1 point) Using your result from part (a), prove that ¯y = y¯ˆ.

Answer.

1

Homework #2 2

(c) (1 point) Prove that (¯x,y¯) is on the simple linear regression line.

Answer.

Geometric Perspective of Least Squares

2. (4 points) We also viewed both the simple linear regression model and the multiple linear regression model through linear algebra. The key geometric insight was that if we train a model on some design matrix X and true response vector Y, our predicted response Yˆ = Xθˆ is the vector in span(X) that is closest to Y (Yˆ is the orthogonal projection of Y onto the span(X)).

In the simple linear regression case, our optimal vector θ is θˆ = [θˆ0,θˆ1]T, and our design matrix is

This means we can write our predicted response vector as .

Note, in this problem, ~x refers to the n-length vector [x1,x2,…,xn]T. In other words, it is a feature, not an observation.

For this problem, assume we are working with the simple linear regression model, though the properties we establish here hold for any linear regression model that contains an intercept term.

Hint: Recall, we define the residual vector as e = Y − Yˆ, and e = [e1,e2,…,en]T.

Answer.

(b) (1 point) Explain why the vector ~x (as defined in the problem) and the residual vector e are orthogonal. Hint: Two vectors are orthogonal if their dot product is 0.

Answer.

(c) (1 point) Explain why the predicted response vector Yˆ and the residual vector e are orthogonal.

Answer.

Properties of a Linear Model With No Constant Term

Suppose that we don’t include an intercept term in our model. That is, our model is now

yˆ = γx,

where γ is the single parameter for our model that we need to optimize. (In this equation, x is a scalar, corresponding to a single observation.)

As usual, we are looking to find the value ˆγ that minimizes the average L2 loss (mean squared error) across our observed data {(xi,yi)},i = 1,…,n:

3. (2 points) Use calculus to find the minimizing ˆγ. That is, prove that

Note: This is the slope of our regression line, analogous to θˆ1 from our simple linear regression model.

Answer.

4. (4 points) For our new simplified model, our design matrix X is:

.

Therefore our predicted response vector Yˆ can be expressed as Yˆ = γ~xˆ . (~x here is defined the same way it was in Question 2.)

Earlier in this homework, we established several properties that held true for the simple linear regression model that contained an intercept term. For each of the following four properties, state whether or not they still hold true even when there isn’t an intercept term. Be sure to justify your answer.

(a) (1 point)

Answer.

(b) (1 point) The column vector ~x and the residual vector e are orthogonal.

Answer.

(c) (1 point) The predicted response vector Yˆ and the residual vector e are orthogonal.

Answer.

(d) (1 point) (¯x,y¯) is on the regression line.

Answer.

MSE “Minimizer”

5. (6 points) Recall from calculus that given some function g(x), the x you get from solving

= 0 is called a critical point of g – this means it could be a minimizer or a maximizer for g. In this question, we will explore some basic properties and build some intuition on why, for certain loss functions such as squared L2 loss, the critical point of the empirical risk function (defined as average loss on the observed data) will always be the minimizer.

Given some linear model f(x) = γx for some real scalar γ, we can write the empirical risk of the model f given the observed data {xi,yi},i = 1,…,n as the average L2 loss, also known as mean squared error (MSE):

.

(a) (1 point) Let’s break the function above into individual terms. Complete the following sentence by filling in the blanks using one of the options in the parenthesis following each of the blanks:

The mean squared error can be viewed as a sum of n (linear/quadratic/logarithmic/exponential) terms, each of which can be treated as a function of

(xi/yi/γ).

Answer.

(b) (1 point) Let’s investigate one of the n functions in the summation in the MSE.

Define for i = 1,…,n. Recall from calculus that we can use the 2nd derivative of a function to describe its curvature about a certain point (if it is facing concave up, down, or possibly a point of inflection). You can take the following as a fact: A function is convex if and only if the function’s 2nd derivative is non-negative on its domain. Based on this property, verify that gi is a convex function.

Answer.

(c) (1 point) Briefly explain in words why given a convex function g(x), the critical point we get by solving = 0 minimizes g. You can assume that is a function of x (and not a constant).

Answer.

(d) (2 points) Now that we have shown that each term in the summation of the MSE is a convex function, one might wonder if the entire summation is convex given that

it is a sum of convex functions.

Let’s look at the formal definition of a convex function. Algebraically speaking, a function g(x) is convex if for any two points (x1,g(x1)) and (x2,g(x2)) on the

function,

g(cx1 + (1 − c)x2) ≤ cg(x1) + (1 − c)g(x2)

for any real constant 0 ≤ c ≤ 1.

The above definition says that, given the plot of a convex function g(x), if you connect 2 randomly chosen points on the function, the line segment will always lie on or above g(x) (try this with the graph of y = x2).

i. (1 point) Using the definition above, show that if g(x) and h(x) are both convex functions, their sum g(x) + h(x) will also be a convex function.

Answer.

ii. (1 point) Based on what you have shown in the previous part, explain intuitively why the sum of n convex functions is still a convex function when n &gt; 2.

Answer.

(e) (1 point) Finally, using the previous parts, explain why in our case that, when we solve for the critical point of the MSE by taking the gradient with respect to the parameter and setting the expression to 0, it is guranteed that the solution we find will minimize the MSE.

Answer.

Congratulations! You have finished Homework 2!
