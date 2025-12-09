# CMPS 6610 Extra Credit Answers
  
In this extra credit assignment, we will test and review concepts you
   have learned since the midterm exam. Please add your written answers
   to `answers.md` which you can convert to a PDF using
   `convert.sh`. Alternatively, you may scan and upload written
   answers to a file named `answers.pdf`.



1. **Algorithmic Paradigms**
My favorite algorithmic paradigm is the divide and conquer strategy. The divide and conquer strategy in my opinion is the simplest paradigm to understand and solve problems with. Its can be applied in many circumstances and it influences many of the other paradigms. My favorite application of the divide and conquer strategy is the multiplication of two polynomials using FFT( Fast Fourier Transform). This application of multiplying two polynomials can be used in many places outside mathematics like signal procesing and so on. The strength of divide and conquer lies in its adaptability making it a go to approach to create an efficient algorithm.


2. **Divide and Conquer**
No, a problem that can be solved with divide and conquer does not necessarily have a optimal substructure. This is because there are problems which only one choice rather a multitude of choices to choose from.

This can be observed with merge sort:
1. An unsorted array is split into two subproblems. These subproblems are sorted individually
2. After the array is merged again on completion of step-1 the algorithm checks if the array still remains unsorted. It swaps the elements on each other if they are in the wrong order.

In this case the subproblems can be sorted only one way. While Divide and Conquer is developing a solution for the larger problem from a smaller problem in this case the answer is either the right and wrong choice.  


3. **Randomization**

- 3a. 
Here based on the question the work done by quicksort is O(nlogn) meaning that the expected event X of quicksort taking place <= c1 x nlogn

The probability that is being calculated is:

$P[X>=c2*n^2] <= E[X]/c2*n^2$ (Here a is $\delta(n^2)$ because this the least amount of work taken to complete event X that is quicksort)

<= $c1*nlogn/c2*n^2$

<= $c1.nlogn/c2^n^2$ = $O(\log n/n)$

- 3b.

Similarly as 3a except this time a = $10^c n\log n$

$P[X>=cn\log n] <= E[X]/10^c n\log n$ (Here a is $\omega(n^2)$ because this the least amount of work taken to complete event X that is quicksort)

<= $c1*n\log n/10^c n\log n$

<= $c1.n\log n/10^c n\log n$ <= $c1 / 10^c$ = O($1/10^c$)


4. **Greedy Algorithms**

5. **Dynamic Programming**

6. **Graphs**
