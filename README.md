IDEAOA02 - Which is not a property of an algorithm?

The execution time and the memory needed for a algorithm must be percisely defined.

IDEAOA03 – Which statement below is wrong?

A data structure is a piece of information (a physical instantiation of a data type)

IDEAOA04 – Which statement is correct concerning to the complexity of algorithm?

The complexity of an algorithm is a measure of the amount of time and space required by the algorithm for an input of a given size n

IDEAOA05 – When evaluating algorithm’s complexity, which approach makes possible an evaluation that is independent of the hardware and software environments?

Theoretical approach

IDEAOA06 – What is time complexity of an algorithm?

The amount of time that the algorithm needs to run for an input of a given size n.

IDEAOA08 – Which statement is wrong concerning to the best-case time complexity of an algorithm?

The best-case is used frequently to analyze the time complexity of algorithms.

IDEAOA09 – Which statement is wrong concerning to the average-case time complexity of an algorithm?

The average-case is easy to determine.

IDEAOA10 – Which statement is wrong concerning to the worst-case time complexity of an algorithm?

At the worst-case the algorithm takes more time to finish than it does at the average-case and best-case

IDEAOA11 – Which one determines the asymptotic behavior of the function T(n)?

The leading term.

IDEAOA12 – Which notation represents the upper-bound of the grow rate of a function?

Big-Oh notation

IDEAOA14 – Suppose that the estimated time complexity of algorithm A and algorithm B is TA(N) and TB(N) respectively. How can we compare the time complexity of A and B?

We compare the grow rate of the leading terms of TA(N) and TB(N).

IDELI01 - Which statement below is wrong in the context of list data structure?

List can be implemented using an array or a collection of linked nodes

IDELI02 – In the ADT of the list data structure, getLength() method returns a/an ______ value?

Integer

IDELI03 – In the ADT of the list data structure, isEmpty() method returns a/an _______ value?

Boolean.

IDELI04 – Which statement is correct about array-based list?

Array-based is faster than linked-list in case of accessing list’s items.

IDELI05 – Which statement is correct about linked-list?

Elements of linked-list can be located dinamically and discontinuously.

IDELI06 – In the ADT of the list data structure, remove(int post) method will?

Remove an item at the pos position form the list.

IDELI07 – In a single linked-list, if a NodeX(data,next) is a tail which is the value of the X’s next?

0

IDELI08 – In a Singly Linked List that have only one node X, which value does X.getNext() return?

The head it self

IDELI09 – Suppose that X is a node in the middle of the Singly Linked List. Complete the code below to delete all nodes after X from the list?X.setNext( _____ );

null.

IDELI10 – Suppose that X is a node in the middle of the Singly Linked List. Complete the code below to delete one node after X from the list?X.setNext( _____ );

X.getNext().

IDELI11 – Complete the code below to insert a new node X at the POS position of a Singly Linked List?

Y.getNext().

IDELI12 – Complete the code below to travel from the head node to the POS position of a Singly Linked List?

c=c.getNext()

IDELI13 – In a Circle linked-list, if a NodeX(data,next) is a tail which is the value of the X’s next?

Head

IDELI14 – Which is the common form of a node X in a Doubly Linked List?

X(data, prev, next)

IDELI15 – Which is common form of a node X in a Singly Linked List?

X(data, next)

IDELI16 – A mathematical-model with a collection of operations defined on that model is called?

Abstract Data Type.

IDESOA02 - Which statement below is wrong about comparison sorting algorithms?

The time complexity of some comparison sorting algorithms can be faster than O(NlogN).

IDESOA03 – Which statement below is wrong in the context of linear sorting algorithm?

The sorted order is determined based on the comparisons between sort keys

IDESOA04 – In a stable sort algorithm …?

The relative order of elements with equal keys are maintained.

IDESOA05 – Merge sort and Quick sort are …?

Based on Divide and Conquer approach.

IDESOA06 – Which sorting algorithm locates the largest (or smallest) key and its index in each sort pass?

Selection sort

IDESOA07 – Which statement is wrong about Insertion sort?

We must shift several elements to make place for the inserted one

IDESOA08 – Which sorting algorithm scans and exchanges any pair of elements that is out-of-order?

Insertion sort.

IDESOA09 – Which statement is wrong concerning to the Heap data structure?

In a min-heap the parent node value is always greater than or equal to its children’s values.

IDESOA10 – In Merge sort algorithm…?

The input array is divided into two parts at the middle of the array

IDESOA011 – Which statement is wrong about Quick sort?

A merge algorithm is needed to combine two partitioned arrays

IDESOA14 – Suppose that we are using Radix sort on N elements, each element has P digits in base b (each digit is in the range [0 .. B-1]), and couting sort algorithm is used to sort the digits. What is the time complexity of the Radix sort algorithm?

O(P(N+B)).

IDESOA15 – What is an operation in which a list of elements is arranged either in ascending order or in descending order?

Sorting.

IDESOA16 – Which of the following sorting algorithm does not have a worst case time complexity of O(n^2)?

Merge sort

IDESQ01 - Which statement below is wrong concerning to stack data structure?

It is a First In First Out (FIFO) list

IDESQ02 – Which statement below is wrong about queue data structure?

enqueue() and dequeue() operations must be performmed at one end of the queue.

IDESQ03 – In the ADT of the Stack data structure, push() method is used to

add an item to the stack

IDESQ04 – Which statement is correct about array-based stack?

top is the last item of the array.

IDESQ06 – In the ADT of the Queue data structure, dequeue() method will?

Remove an item from the queue at the front position.

IDESQ07 – In ADT of the Queue data structure, enqueue() method will?

Add a new item to the queue at the rear position.

IDESQ08 – Which statement is wrong about array-based circular queue?

when front=rear the queue is full.

IDESQ09 – Complete the code for the enqueue() method in array-based circular queue?

rear=(rear+1)%maxSize

IDESQ10 – Complete the code for the dequeue() method in array-based circular queue?

front=(front+1)%maxSize

IDESQ11 – Which statement is wrong about list-based queue?

Queue is empty when front=rear

IDESQ12 – Which of the following statement is true?

The contents of a queue can wrap around , while those of a stack can not

IDESQ13 – Suppose you push 10, 20, 30, 40 onto a stack, then you pop three items. Which one is left on the stack?

10

IDESQ14 – Suppose you enqueue 10, 20, 30, 40 onto a queue, then you dequeue three items. Which one is left on the queue?

40

IDESQ15 – The end which a new element gets added to a queue is called

Rear

IDESQ16 – What is the result of the following operation on the stack S: S.peek(S.push(X))?

X.

DESQAS01 – What is the worst-case time for linear search finding a single item in an array?

Linear time.

IDESQAS03 – What is the worst-case time for finding a key in a hash table (assume that there is no collision)?

Constant time.

IDESQAS04 – What additional requirement is placed on an array, so that binary search may be used to search for a key?

The array must be sorted.

IDESQAS05 – What is the best definition of a collision in a hash table?

Two entries with different keys have the same exact hash value.

IDESQAS06 – A separate chaining hash table has an array size of 512. What is the maximum number of entries that can be placed in the table?

512.

IDESQAS08 – Which of the following is not an application of the queue data structure?

Evaluating a posfix expression

IDESQAS10 – Consider a hash table of size seven, with starting index zero, and a hash function h(k)=(3k+4) mod 7. What is the address of the key k=10?

3 or 6

IDESQAS11 – Complete the code below to search for key in an array using linear seach algorithm?

i.

IDESQAS12 – In a hash table of the size N using linear probing, what is the probing hash function hi(k)?

hi(k)=(h(k)+i) mod N.

IDESQAS13 – Given the following input (4322, 1334, 1471, 9679, 1989, 6171, 6173, 4199) and the hash function: h(k)=k mod 10. Which of the following statements are true?

4199 and 9679 hash to the same value.

IDESQAS14 – In the context of seach algorithms, which of the following statements are true?

Binary search is faster than linear search, but it requires a sorted array.

IDESQAS15 – Which of the following statements is used in binary search algorithm to halve the array?

middle=(left + right)/2

IDHLI01 – Suppose that you want to sort a singly linked list, each list’s item is a large object. which of the following sort algorithms should be used to minimum the time complexity?

Insertion sort.

IDHLI02 – Method reverse() below is used to reverse the order of items in a Singly Linked List. Please complete the code of the method?

head=prev

IDHLI03 – Consider a Singly Linked List contains N nodes (N > 8), a method f1() is designed to find the 8th node from beginning, and method f2() is designed to find the 8th node from end. Which is the time complexity of f1() and f2()?

O(1) and O(N)

IDHLI04 – Method deleteTail() below is used to delete the last node in a Singly Linked List. Please complete the code of the method?

beforeTail.setNext(null)

IDHLI05 – Method tailToFront() below moves the last node of a Singly Linked List into the front of the list. Please complete the code of the method?

beforeTail.setNext(null); tail.setNext(head); head=tail;

IDHSOA01 – Selection sort is used to sort an array in the descending order. When does the worst case occur?

The array is already sorted in the ascending order.

IDHSOA02 – Insertion sort is used to sort an array in the descending order. When does the best case occur?

The array is already sorted in the descending order.

IDHSOA03 –Given an array A that is almost sorted (only one or two elements are misplaced). Which sorting algorithm gives the best time efficiency when applied on A?

Insertion sort

IDHSOA04 – Which of the following sorting algorithms has the minimum number of swap operations in general?

Insertion sort

IDHSOA05 – Consider a modified version of Merge sort where the input array is partitioned at the position one-third of the length N of the array. What is the recurrence of this algorithm?

T(N)=2T(N/3)+O(N)

IDHSOA06 – Which of the following sorting algorithms has the lowest worst case time complexity?

Merge sort

IDHSOA07 – Consider an array A where the items are in the range from 1 to n^3. Which of the following sorting algorithms gives the best time efficiency when applied on A?

Radix sort

IDHSQAS01 – What data structure would you mostly likely see in a non-recursive implementation of a recursive algorithm?

Stack.

IDHSQAS03 – Which of the following is a hash function?

Quadratic probing

IDHSQAS04 – If h(k) is any hash function and is used to hash N keys into a table of size M, where N < M, the expected number of collisions involving a particular key X is?

Less than 1.

IDHSQAS05 - The process of accessing data stored in a serial access memory is similar to manipulating data on a?

Stack.

IDMAOA01 – What is the time complexity of the following algorithm with respect to the input size N

O(N^2)

IDMAOA02 – What is the time complexity of the following algorithm with respect to the input size N

O(N)

IDMAOA03 – What is the time complexity of the following algorithm with respect to the input size N

O(N)

IDMAOA05 – What is the time complexity of the following algorithm with respect to the input size N

O(N)

IDMAOA06 – Estimate the time complexity in Big-Oh notation, with respect to the input size N, for the code

O(N^3)

IDMAOA07 – Estimate the time complexity in Big-Oh notation, with respect to the input size N for the code below

O(1000N)

IDMAOA08 – Estimate the time complexity in Big-Oh notation, with respect to the input size N for the code below

O(N^3)

IDMAOA09 – Estimate the time complexity in Big-Oh notation, with respect to the input size N for the code below

O(N^2)

IDMAOA10 – Estimate the time complexity in Big-Oh notation, with respect to the input size N for the code below

O(N^3)

IDMAOA11 – Estimate the time complexity in Big-Oh notation, with respect to the input size N for the code below

O(N^5)

IDMAOA12 – Consider two algorithms which have the time complexity in Big-Oh notation below. Which statement is correct?

Two algorithm are equivalent in term of time efficiency.

IDMAOA13 – Consider three algorithms which have the time complexity in Big-Oh notation below. Please arrange these algorithms in the ascending order of time efficiency (the slowest algorithm is the first one in the order).

Algorithm 3, Algorithm 1, Algorithm 2

IDMAOA14 – Consider three algorithm which have the time complexity in Big-Oh notation below. Please arrange these algorithms in the descending order of time efficiency (the fastest algorithm is the first one in the order).

Algorithm 2, Algorithm 1, Algorithm 3

IDMAOA15 – Estimate the time complexity in Big-Oh notation, with respect to the input size N for the code below

O(N^2)

IDMLI02 – In a Singly Linked List implementation, what do we do when assigning head to null?

Delete all nodes from the list

IDMLI03 – In an Array-based list, what does this code do to the list?

Remove an item from the list

IDMLI04 – In a Singly Linked List implementation, what does this code to to the list?

Remove the node at the pos position from the list

IDMLI05 – In an Array-based list, what does this code do to the list?

insert an item to the list

IDMLI06 – Consider method F in Java and a singly linked list L below. Suppose that H is the head node of the list L. What is the result if we call F(H)?

A’-->‘B’-->‘C’-->‘D’-->‘E’-->‘F’

IDMLI07 – Consider method F in Java and a singly linked list L below. Suppose that H is the head node of the list L. What is the result if we call F(H)?

F’-->‘E’-->‘D’-->‘C’-->‘B’-->‘A

IDMLI08 - Consider method F in Java and a singly linked list L below. Suppose that H is the head node of the list L. What is the result if we call F(H)?

A’-->‘C’-->‘E’

IDMLI09 - Consider method F in Java and a singly linked list L below. Suppose that H is the head node of the list L. What is the result if we call F(H)?

E’-->‘C’-->‘A’

IDMLI10 - Consider method F in Java and a singly linked list L below. Suppose that H is the head node of the list L. What is the result if we call F(H.getNext())?

B’-->‘D’-->‘F’

IDMLI11 – Consider method F in Java and a singly linked list L below. Suppose that H is the head node of the list L. What is the result if we call F(H.getNext())?

F’-->‘D’-->‘B’

IDMLI12 – What is the number of comparisons needed in the worst case to search for a given node in a Singly Linked List of the length N nodes?

N

IDMSOA01 – Selection sort algorithm is used to sort the array A={23,78,45,8,32,56} in the ascending order. What are the items of A after 03 sort pass?

A={23,32,8,45,56,78}

IDMSOA02 – Insertion sort algorithm is used to sort the array A={23,78,45,8,32,56} in the ascending order. What are the items of A after 03 sort pass?

A={8,23,45,78,32,56}

IDMSOA03 – Bubble sort algorithm is used to sort the array A={23,78,45,8,32,56} in the ascending order. What are the items of A after 03 sort pass?

A={8,23,32,45,56,78} (đáp án đúng là {8, 23,32,45,78,56 } cái này gần nhất nên chắc là ok :3)

IDMSOA05 – A sorting algorithm is used to sort the array A={51,11,56,83,20,26,33}. The item of A in each sort pass are listed below. Which sorting algorithm is used?

Insertion sort

IDMSOA06 – A sorting algorithm is used to sort the array A={83,8,12,72,71,65,5}. The item of A in each sort pass are listed below. Which sorting algorithm is used?

Bubble sort

IDMSOA08 – Which array represents a Min-Heap?

A={2,5,9,8,10,13,12,22,50}

IDMSOA09 – Which array represents a Max-Heap?

A={78,56,45,32,23,8,15}

IDMSOA10 – An array A contains integer item in the range 0 to 5. A={1,2,5,3,2}. Counting sort algorithm is used to sort A. What is the content of the counting array C before we used the information form C to creates the sorted result array B?

C={0,1,3,4,4,5}

IDMSOA11 – An array contains integer items, each item has 03 digits. A={170,145,275,900,802}. Radix sort algorithm is used to sort A. What is the content of A after the second sort pass?

A={900,802,145,170,275}

IDMSOA12 – The Merge method in Merge sort algorithm is used to combine two sorted array A={3,27,38,43} and B={9,10,82}. What is the result array C?

C={3,9,10,27,38,43,82}

IDMSOA13 – Heap sort algorithm is used to sort the array A={15,19,10,7,17,16} in the ascending order (using a Max-Heap). What is the content of A after calling BuildHeap() method?

A={19,17,16,7,15,10}

IDMSQ01 – A stack S has 05 character items, S={“A”,“B”,“C”,“D”,“E”} where “E” is the top of S. What is the content of S if we perform the following list of operations on the stack: push(“F”) –-> pop() –-> pop() –-> pop() –-> push(“D”)?

S={“A”,“B”,“C”,“D”}

IDMSQ02 A queue Q has 05 character items, Q={“A”, “B”, “C”, “D”, “E”} where “E” is the rear and “A” is the front of the queue. What is the content of Q if we perform the following list of operations on the queue: enqueue(“F”)-->dequeue()-->dequeue()-->dequeque()-->enqueue(“D”)?

Q={“D”, “E” ,“F” ,“D”}

IDMSQ03 – A stack S has 05 character items, S={“5”, “4”, “3”, “2”, “1”} where “1” is the top of S. Which operations must be perform to change S into a new state: S={“5”, “4”, “2”, “3”, “1”}?

pop()-->pop()-->pop()-->push(“2”)-->push(“3”)-->push(“1”)

IDMSQ04 – A queue Q has 05 character items, Q={“5”, “4”, “3”, “2”, “1”} where “1” is the front and “5” is the rear of Q. Which operations must be perform to change Q into a new state: Q={“3”, “2”, “1”, “4”, “5”}?

enqueue(“4”)-->enqueue(“5”)-->dequeue()-->dequeue()

IDMSQ05 In method F below, the stack s contains character items. Which is the result if we call method F with the input string text=“datastructure”?

Erutcurtsatad

IDMSQ07 – One difference between a queue and a stack is:

Queues use two ends of the structure; stacks use only one.

IDMSQ08 – In an array-based stack, which operation has time complexity O(N) in the worst-case?

No operation that has time complexity O(N).

IDMSQ09 – In an array-based circular queue, which operation has time complexity O(N) in the worstcase?

No operation that has time complexity O(N).

IDMSQ10 – Suppose that you are implementing an operation named multiDequeue(int k) on a queue contains integer items. This operation will perform dequeue() k times and return the result of the kth dequeue(). Please complete the code of the operation?

m=m-1

IDMSQ11 – Suppose that you are implementing an operation name multiPop(int k) on a stack contains integer items. This operation will perform pop() k times and return the result of the kth pop(). Please complete the code of the operation?

m=m-1

IDMSQ12 A queue q has 5 items. How many items left in q after executing: q.enqueue(q.dequeue())?

5

IDMSQ13 – In Java the run-time error “Array index out of bound” is reported when a program try to access an array with an index that is outside the valid boundaries of the array. Which of the following data structure may give the “Array index out of bound” error, even though the current number of elements in it, is less than its size.

Simple array-based queue.

IDMSQAS01 – Which is the prefix notation of the following infix expression((8+2)*(5+7)-10)*9+3?

8 2 + 5 7 +* 10 -9*3+

IDMSQAS02 – Which is the prefix notation of the following infix expression:5 + (7 + 9*3)*(2+8)?

+ 5 * + 7 * 9 3+ 2 8

IDMSQAS03 – Evaluate the following expression:8 7 + 6 4 + * 2 3 7 + * - 1 -?

129

IDMSQAS04 – Evaluate the following expression:*-*+7 3 + 9 1 * 5 + 2 8 3?

150

IDMSQAS05 – Method F below takes a number n as an argument, and use a stack s to do processing. What does the method do in general?

Print binary representation of n.

IDMSQAS06 – In the following list of number: 8 17 25 35 41 52 60 75 86. How many comparisons would binary search take to find 52?

3

IDMSQAS07 – In the following list of number: 8 17 25 35 41 52 60 75 86. How many comparisons would linear search take to find 52?

6

IDMSQAS08 – The keys 12, 18, 13, 2, 3, 23, 15 and 5 are inserted into an initially empty hash table of length 10 using close hashing with hash function: h(k)=k mod 10 and linear probing. What is the resultant hash table?

B

IDMSQAS09 – The keys 12, 18, 13, 2, 3, 23, 15 and 5 are inserted into an initially empty hash table of length 10 using open hashing with hash function: h(k)=k mod 10 and separate chaining. What is the resultant hash table?

A

IDMSQAS10 – Consider a hash table of size seven, with starting index zero, and a hash function: h(k)=(3k+4) mod 7. Assuming the hash table is initially empty, which of the following is the contents of the table when the sequence 1, 3, 8, 10 is inserted into the table using close hasing with linear probing? Note that ‘-’ denotes an empty location in the table.

1, 8, 10, -, -, -, 3

IDMSQAS11 – A characteristic of the data that binary search uses but linear search ignores is the?

Order of the elements of the list.

![image](https://user-images.githubusercontent.com/107268056/173106191-3be7dc99-3fe0-4c98-9795-96ca885486d5.png)


