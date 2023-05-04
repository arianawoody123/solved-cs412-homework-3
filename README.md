Download Link: https://assignmentchef.com/product/solved-cs412-homework-3
<br>
<h1>Programming Assignment</h1>

This question aims to provide you a better understanding of the frequent pattern mining and the closed/maximal pattern mining.

<ol>

 <li>Implement a frequent pattern mining algorithm (e.g., the Apriori algorithm or FPGrowth) to mine the frequent patterns from a transaction dataset.</li>

 <li>Implement a closed pattern mining algorithm to mine the closed frequent patterns from the same transaction dataset. An easy way is to write code based on the frequent patterns you got from part 1.</li>

 <li>Implement a maximal pattern mining algorithm to mine the maximal frequent patterns from the same transaction dataset. An easy way is to write code based on the frequent patterns you got from part 1.</li>

</ol>

<h2>Input Format</h2>

The input dataset is a transaction dataset.

The first line of the input corresponds to the minimum support.

Each following line of the input corresponds to one transaction. Items in each transaction are seperated by a space.

Please refer to the sample input below. In sample input 0, the minimum support is 2, and the dataset contains 3 transactions and 5 item types (A, B, C, D and E).

<strong>Constraints</strong>

NA

<h2>Output Format</h2>

The output are the frequent patterns you mined out from the input dataset.

Each line of the output should be in the format:

Support       [ frequent      pattern ]

Support       [ frequent      pattern ]

. . . . . .

The frequent patterns should be ordered according to their support from largest to smallest. Ties should be resolved by ordering the frequent patterns according to the alphabetical order.

First print all the frequent patterns for part 1, then the closed frequent patterns for part 2 and last the maximal frequent patterns for part 3. Each part should be separated by an empty line.

Please refer to the sample output below. In sample output 0, the first 9 patterns are the frequent patterns for part 1, the following 3 patterns are the closed frequent patterns for part 2 and the last 2 patterns are the maximal frequent patterns for part 3.

<h2>Sample Input 0</h2>

2

B A C E D

A C

C B D

<h2>Sample Output 0</h2>

3 [C] 2 [A]

2 [A C] 2 [B]

2 [B C]

2 [B C D]

<ul>

 <li>[B D] 2 [C D] 2 [D]</li>

 <li>[C]</li>

</ul>

2 [A C]

2 [B C D]

2 [A C]

2 [B C D]

<h2>Sample Input 1</h2>

2

data mining

frequent pattern mining mining frequent patterns from the transaction dataset closed and maximal pattern mining

<h2>Sample Output 1</h2>

4 [ mining ]

2 [ frequent ]

2 [ frequent mining ]

2 [ mining pattern ]

2 [ pattern ]

4 [ mining ]

2 [ frequent mining ] 2 [ mining pattern ]

2 [ frequent mining ]

2 [ mining pattern ]