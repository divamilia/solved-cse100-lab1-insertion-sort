Download Link: https://assignmentchef.com/product/solved-cse100-lab1-insertion-sort
<br>
<strong>Description </strong>In the first lab assignment, your job is to implement insertion-sort (Yes, this is just a warm-up, and the labs will be increasingly difficult. So heads up!)

<strong>Input structure </strong>The input starts with an integer number which indicates the number of elements (integers) to be sorted, <em>n</em>. Then, the elements follow, one per line.

<strong>Output structure </strong>Recall that Insertion Sort first sorts the first two elements (in non-decreasing order), then the first three elements, and so on. You are asked to output the snapshot of the array at the end of each iteration. More precisely, for each 2 ≤<em>k</em>≤<em>n</em>, output the first <em>k </em>elements (in non-decreasing order) in a separate line where each element is followed by ;. A new line is followed by an enter.

<strong>Examples of input and output:</strong>

<em>Input</em>

6

5

3

2

1

6

4

<em>Output</em>

3;5;

2;3;5;

1;2;3;5;

1;2;3;5;6;

1;2;3;4;5;6;

More precisely, the above output example has 6 lines since a “cout <em>&lt;&lt; </em>endl;” call was made at the end of each of the first 5 lines; those are the only white characters.

See the lab guidelines for submission/grading, etc., which can be found in Files/Labs.