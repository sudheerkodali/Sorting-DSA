# Sorting
DSA -Sorting in Java Script1.

1.Module introduction <br>
2.selection sort implementation - java script <br>
3.Merge two sorted arrays-theory <br>
4.Merge sort theoty <br>
5.Merge sort - implementation <br>
6.Merge sort complexity analysis <br>
7.Two way partitioning Algorithm <br>
8.Quick sort - Theory <br>
7.Quick sort - Implementation <br>
8.counting sort Algorithm <br>
9.How to make counting sort stable <br>
10.Bubble sort - working <br>
11.Bubble sort implementation - javascript <br>
12.selection sort - working <br>
13.Merge two sorted arrays implementation - javascript <br>
14.Two way partitioning Implementation <br>
15.counting sort - Implementation <br>
16.Radix Sort Imtroduction <br>


# 3.Merge two sorted arrays - theory
![Image of Merge Sort array](./MergesortArray.png)

<p> Now A, B are two different Arrays with different data types </p>
<p> Let take two sorting arrays with A and B to merge them  </p>

# Merge A & B 

![Image of Merge sort array`](./MergesortArray1.png)

<ul>
<li><p> New Array variable called C to combain two arrays A & B in Assending order</p></li>

# How to Merge A & B values with explination 
<ul>
<li><p> First essume that A[i] B[j] with start with sorting with 'i' to 'j' from LEFT to RIGHT</p> 
<p> while as we know the count the DATA TYPES with 0,1,2,3,4, where values are i= [2,5,8,9,10] j=[2,4,3,18] count with [0,1,2,3]</p>
<p> maximum count from LEFT TO RIGHT i=[2,5,8,9,10] j=[2,4,7,18] => that means I to J Assending order SMALL to Higher values.</p>
<p> i=0 => 2 & j=2 :[2]  =>2 is small from starting with 'i' compared to 'j'</p>
<p> j=0 => 2 & i=1 => 5 :[2,2]  =>2 is small from startion with 'j' compared to 'i' and first value 2 carry on </p>
<p> i=1 => 5 & j=1 =>4 :[2,2,4] => 4 is smaller compared to 5 so 'j' comes first and 
' i'</p></li>
</ul>




