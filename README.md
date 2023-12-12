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

![Image of Merge sort array`](./MergesortArray2.png)


<li><p> First essume that A[i] B[j] with start with sorting with 'i' to 'j' from LEFT to RIGHT</p></li>
<li><p> while as we know the count the DATA TYPES with 0,1,2,3,4, where values are i= [2,5,8,9,10] j=[2,4,7,18] count with [0,1,2,3]</p></li>
<li><p> maximum count from LEFT TO RIGHT i=[2,5,8,9,10] j=[2,4,7,18] => that means I to J Assending order SMALL to Higher values.</p></li>
  
<li><p> i=0 => 2 & j=0 =>2 :[2]  =>2 is small from starting with 'i' compared to 'j'</p></li>
<li><p> j=0 => 2 & i=1 =>5 :[2,2]  =>2 is small compared to'5' so 'j' value comes first and value 2 is forwoded</p></li>
<li><p> i=1 => 5 & j=1 =>4 :[2,2,4] => 4 is smaller compared to 5 so 'j' comes first and value 2,2 is forwored</p></li>
<li><p> i=1 => 5 & j=2 =>7 :[2,2,4,5] => 5 is smaller compared to 7 so 'i' comes first and value 2,2,4 is forworded</p></li>
<li><p> till the Highest number comes and it ends with [2,2,4,5,7,8,9,18]</p></li>

# Merge two sorted Arrays and the values are 

![Image of Merge sort array`](./MergesortArray3.png)
<p>when we compare the array values between A & B , combain with c then the values look in the above picture</p>


