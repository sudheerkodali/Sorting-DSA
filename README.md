# Sorting

## DSA -Sorting in Java Script1

| No.| Questions                                                                                                                                                               |
| ---| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    | **Sorting-concepts**                                                                                                                                                    |      
| 1  | [Module-Introduction](#)                                                                                                                                                |
| 2  | [Selection-sort-implementation-java-script](#)                                                                                                                          |
| 3  | [Merge two sorted arrays-theory](#)                                                                                                                                     |
| 4  | [Merge-sort-theory](#)                                                                                                                                                  |
| 5  | [Merge-sort-implementation](#)                                                                                                                                          |
| 6  | [Merge-sort-complexity-analysis ](#)                                                                                                                                    |
| 7  | [Two-way-partitioning-Algorithm](#)                                                                                                                                     |
| 8  | [Quick-sort - Theory](#)                                                                                                                                                |
| 9  | [Quick-sort - Implementation](#)                                                                                                                                        |
| 10 | [counting-sort-Algorithm ](#)                                                                                                                                           |
| 11 | [How-to-make-counting-sort-table](#)                                                                                                                                    |
| 12 | [Bubble-sort-work](#)                                                                                                                                                   |
| 13 | [Bubble-sort-implementation](#)                                                                                                                                         |
| 14 | [Selection-sort-working](#)                                                                                                                                            |                                                                                        
| 15 | [Merge-two-sorted-arrays-implemention](#)                                                                                                                               |
| 16 | [Two-way-partitioning-implementation-programming](#)                                                                                                                    |
| 17 | [Count-sort-implementation](#)                                                                                                                                          |                                                                                                                 
| 18 | [Radix-sort-introduction](#)                                                                                                                                            |
| 19 | [Radix-sort-implementation](#)                                                                                                                                          |








<!--1.Module introduction <br>
2.selection sort implementation - java script <br>
3.Merge two sorted arrays-theory <br>
4.Merge sort theory <br>
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
16.Radix Sort Imtroduction <br>-->

| 3  | [Merge two sorted arrays-theory](#)     
![Image of Merge Sort array](./MergesortArrays/MergesortedArray.png)

<p> Now A, B are two different Arrays with different data types </p>
<p> Let take two sorting arrays with A and B to merge them  </p>

# Merge A & B 

![Image of Merge sort array`](./MergesortArrays/MergesortedArray1.png)

<ul>
<li><p> New Array variable called C to combain two arrays A & B in Assending order</p></li>

# How to Merge A & B values with explination 

![Image of Merge sort array`](./MergesortArrays/MergesortedArray2.png)


<li><p> First essume that A[i] B[j] with start with sorting with 'i' to 'j' from LEFT to RIGHT</p></li>
<li><p> while as we know the count the DATA TYPES with 0,1,2,3,4, where values are i= [2,5,8,9,10] j=[2,4,7,18] count with [0,1,2,3]</p></li>
<li><p> maximum count from LEFT TO RIGHT i=[2,5,8,9,10] j=[2,4,7,18] => that means I to J Assending order SMALL to Higher values.</p></li>
  
<li><p> i=0 => 2 & j=0 =>2 :[2]  =>2 is small from starting with 'i' compared to 'j'</p></li>
<li><p> j=0 => 2 & i=1 =>5 :[2,2]  =>2 is small compared to'5' so 'j' value comes first and value 2 is forwoded</p></li>
<li><p> i=1 => 5 & j=1 =>4 :[2,2,4] => 4 is smaller compared to 5 so 'j' comes first and value 2,2 is forwored</p></li>
<li><p> i=1 => 5 & j=2 =>7 :[2,2,4,5] => 5 is smaller compared to 7 so 'i' comes first and value 2,2,4 is forworded</p></li>
<li><p> Till the Highest number comes and it ends with [2,2,4,5,7,8,9,18]</p></li>

# Merge two sorted Arrays and the values are 

![Image of Merge sort array](./MergesortArrays/MergesortedArray3.png)

<li><p>when we compare the array values between A & B , combine with C then the values look in the above picture</p></li>

| 4  | [Merge-sort-theory](#)  

![Merge sort theory](./Mergesort/Mergesort.png)

# combination of values

![merge sort theoty](./Mergesort/Mergesort1.png)


# Added values to Merge sort

![Merge sort theory](./Mergesort/Mergesort2.png)


| 14 | [Selection-sort-working](#)   

# 14.1
![Select-sort-work](./selectionSortworking/image1.png)

# 14.2
![Select-sort-work](./selectionSortworking/image2.png)

# 14.3
![Select-sort-work](./selectionSortworking/image3.png)

# 14.4
![Select-sort-work](./selectionSortworking/image4.png)

# 14.5
![Select-sort-work](./selectionSortworking/image5.png)

| 10  | [Countsort](#)  
![Image of Countsort](./Countsort/image1.png)
<p> Let us assume that count sort is not a comparision, however it is the array that we can not count from the range </p>
<p>It would be the certain range between [0,k] we can not expect  the range in count sort but to some expect  from this range like negative range or number,in an Array </p>

# countsort
![Image of Countsort](./Countsort/image2.png)
<p> Let we determine the number range array A=[2,5,1,4,4,2,6] => count=[0,1,2,3,4,5,6,7,8] </p>
<p> itterate to A with count values for instance A = 2 value in count =[0,0,1,0,0,0,0,0,0] </p>
<p> itterate to A with count values for instance A = 5 value in count =[0,0,1,0,0,1,0,0,0] </p>
<p> itterate to A with count values for instance A = 1 value in count =[0,1,1,0,0,1,0,0,0] </p>
<p> itterate to A with count values for instance A = 4 value in count =[0,1,1,0,1,1,0,0,0] </p>
<p> itterate to A with count values for instance A = 4 value in count =[0,1,1,0,2,1,0,0,0] Here 4 comes two times and the value of 4 is 2 </p>
<p> itterate to A with count values for instance A = 2 value in count =[0,1,2,0,2,1,0,0,0] 
Here 2 value comes two times and the value of 2 is 2 times occurs </p>

# count num in order
![Image of Countsort](./Countsort/image3.png)
<p> itterate to A with count values for instance A = 6 value in count =[0,1,2,0,2,1,1,0,0] </p>
<p> The count values of 7, 8 are 0,0-----------------------------count=[0,1,2,0,2,1,1,0,0]</p>

# cumulative sum
![Image of Countsort](./Countsort/image4.png)
<p > Cumulative sum final result add result value from left 0, 0+1=1,1+2=3,3+0=3,3+2=5,5+1=6,6+1=7,7+0=7,7+0=7 </p>-------------count=[0,1,3,3,5,6,7,7,7] is called cumelative sum </p>

# Final count
![Image of Countsort](./Countsort/image5.png)

<p> New result value array formula is K, COUNT[K]: [K-1], for instance [k =2] , [k-2-1-1], [k=5, K-1=5-1=4], </p>
<P> Counting sort count the number of elements </P>
<p> Complexity would be 'LINEAR'</p>


