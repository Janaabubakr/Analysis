# Analysis
question (1,b)
naive Iterative Method: a loop that runs 'n' times in the naive method. so O(n) is the time complexity.
The divide-and-conquer strategy is made by recursion.The recurrence relation can be solved to determine the time complexity.T(n) = 2T(n/2) + O(1) is the recurrence relation, and it matches the Master Theorem Case 2 form.so O(log n) is the complexity

The naive iterative method should show a linear increase in execution time.
The divide-and-conquer method should show a logarithmic increase in execution time.Discussion on Real-Time Diagram:




question (2)
Merge Sort: The  complexity of the Merge Sort algorithm is O(n log n).
Binary Search: The  complexity of Binary Search is O(log n).
Merge Sort is the main component of the complete algorithm, and O(n log n) is the time complexity.
The time complexity of the Merge Sort is O(n log n).
The time complexity of the Binary Search is O(log n).
Both have multiplied time complexities because of the divide-and-conquer strategy.
The total time complexity is therefore O(n log^2 n).
Relation of Recurrence:
T(n) = 2T(n/2) + O(n) is the recurrence relation for Merge Sort, which is the Master Theorem Case 2 and the complexity is  O(n log n).
O(log n) is the constant time complexity of Binary Search.