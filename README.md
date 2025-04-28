# cs726-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [CS726 Homework #3 Solved](https://www.ankitcodinghub.com/product/cs-726-homework-3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;117564&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS726 Homework #3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
Please typeset or write your solutions neatly! If we cannot read it, we cannot grade it.

Note: You can use the results we have proved in class – no need to prove them again.

Q 1. Exercise 4 in Chapter 7 of Recht-Wright (on Canvas). [15pts]

Q 2. Consider the unconstrained optimization problem minx∈Rn f(x), where f is an L-smooth convex function. Assume that kx0−x∗k2 ≤ R, for some R ∈ (0,∞), and let . Let x∗ = argminx∈Rn f(x) and x∗ = argminx . You have already shown in previous homework (with possibly minor modifications) that:

.

(i) Prove that Nesterov’s method for smooth and strongly convex minimization applied to f will find a solution xk with iterations. [5pts]

(ii) Using the lower bound for smooth minimization we have proved in class, prove the following lower bound for L-smooth and m-strongly convex optimization: any method satisfying the same assumption as we used in class

(that xk ∈x0 + Lin{∇f(x0),…,∇f(xk−1)}) must take at least iterations in the worst case to construct a point xk such that for any . [10pts]

Coding Assignment

Note: Your code needs to compile without any errors to receive any points. If you are using Python, please follow these rules:

• Please use Python 3.7+.

• Please include a README file describing how to run your code – if we cannot figure out how to run your code within a reasonable time, you will receive zero points for the entire question.

For the coding assignment, in addition to the methods you have implemented in the last homework, you should also implement the following methods:

• The method of conjugate gradients, for the version we have covered in class (also in Nesterov’s book, in Section

1.3.2). You should use the Dai-Yuan rule for βk (the same as the one we have derived in class).

• The Heavy-Ball method, which applies to L-smooth an m-strongly convex functions, and whose updates are defined by:

xk+1 = xk − α1∇f(xk) + α2(xk −xk−1),

where and .

• Nesterov’s method for smooth and strongly convex optimization (any variant you like – the one we saw in class, or the one from Chapter 4 in Recht-Wright).

1

Q 3. The problem instance we will consider first is minx∈Rn f(x), where n = 100 and Mx−bTx + is characterized by:

 2 −1 0 0 … 0 0

−1 2 −1 0 … 0 0

 0 −1 2 −1 … 0 0 M =  0 0 −1 2 … 0 0, b.



 … … … … … … …

0 0 0 0 … −1 2

M and b can be generated in Matlab using:

k = n;

M = diag(2*[ones(k, 1); zeros(n-k, 1)], 0)…

+ diag([-ones(k-1, 1); zeros(n-k, 1)], -1)…

+ diag([-ones(k-1, 1); zeros(n-k, 1)], 1); b = zeros(n, 1); b(1) = b(1) + 1;

Write the code that implements Nesterov’s method for smooth minimization (feel free to reuse the code from last homework), Nesterov’s method for smooth and strongly convex minimization, the method of conjugate gradients, and the heavy ball method. Your code should produce three plots, corresponding to three different values of m: (1) m = 1, (2) m = 0.1, and (3) m = 0.01. Each plot should show the optimality gap (on a logarithmic scale) against the iteration count. Each run should be for 1000 iterations. The initial point for all the methods should be x0 = 0. Discuss your results. Do you observe what you expect from what we saw in class? How does the heavy ball compare to other methods? How about the two variants of Nesterov’s method? [20pts]

Now, modify Nesterov’s method for smooth minimization so that the function value over the iterates is monotonically decreasing (we have discussed in class how to do that). Ensure that your modified method in each iteration decreases the function value by at least as much as the standard gradient descent (with step size 1/L; explain how to achieve this). In how many iterations can your new method produce a point xk with ? (You should provide a theoretical bound.) Produce the same set of plots. Observe what has changed and explain why. [20pts]

Q 4. In this part, you will compare the heavy ball method to Nesterov’s method for smooth and strongly convex optimization. Your problem instance is the following one-dimensional instance: minx∈R f(x), where

if x &lt; 1 if 1 ≤ x &lt; 2 , if x ≥ 2.

Prove that f is m-strongly convex and L-smooth with m = 1 and L = 25. What is the global minimizer of f? (Justify your answer.)

Run Nesterov’s method and the heavy-ball method, starting from x0 = 3.3. Plot the optimality gap of Nesterov’s method and the heavy ball method over 100 iterations. What do you observe? What does this plot tell you? [30pts]

Extra Credit Question

Q 5. Suppose that I give you an algorithm (let’s call it AGD-G) that given an initial point x0 ∈Rn and gradient access to an L-smooth function f : Rn →R (where 0 &lt; L &lt; ∞) after k iterations returns a point xk ∈Rn that satisfies:

.

Note that AGD-G does not need to know the value of L.

Show that you can use AGD-G to obtain an algorithm that for any m-strongly convex and L-smooth function and any can construct a point xk with iterations. Your algorithm should work without the knowledge of the values of L and m. [15pts]

2
