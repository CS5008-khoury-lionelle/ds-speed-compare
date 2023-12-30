# Report for Data Structure Speed Comparison Homework

Make sure to answer every question in this homework. You should not bullet point your answers, but
instead write them as a full report format. This doesn't mean you have to be wordy, as concise is good,
but it does mean you need to use proper grammar, spelling, and be complete. For question that just
ask for a short answer, answer accordingly. Make sure to include references where appropriate.


## Algorithmic Analysis - Big $O$

Complete the Big O table below for the following functions. You may use any resource you like, but
for the SortedVector and SortedList, you should use the Big O for the functions you wrote in the
the homework. Both Single and Double Linked List you can assume head and tail pointers are available. 
Don't forget to use latex math notation (example in the table).



### Big $O$ Table

| - | Add/Insert | Remove | Search/Find | Sort  | Add Front | Add Back | Remove Front | Remove Back |  Get by Index |
| ------ | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: | :------: |
| Vector | $O(n)$ |  |  |  |  |  |  |  | |
| Single Linked List |  |  |  |  |  |  |  |  | |
| Double Linked List |  |  |  |  |  |  |  |  | |
| Sorted Vector |  |  |  |  |  |  |  |  | |
| Sorted Single Linked List |  |  |  |  |  |  |  |  | |
| Sorted Double Linked List |  |  |  |  |  |  |  |  | |
| Binary Search Tree |  |  |  |  | - | - | - | - | - |



For Sort, we are asking for the Big $O$ for taking the current data structure and writing it 'sorted' to a file. However, not the file writes. For example, if you have a vector of 1000 elements, and you want to write it to a file, you would need to sort it first. So, the Big $O$ for this would be the Big $O$ for sorting. For BST, you have to convert the tree to a sequential structure, so the cost of doing that.  


### Worst Case vs. Average Case
There are a few functions whose worse case is very different than the average case. Name at least two of them, and explain why the worse case is so much worse than the average case. 

1. 
2. 


## Empirical Analysis - Speed Comparison



## References
Add your references here. A good reference includes an inline citation, such as [1] , and then down in your references section, you include the full details of the reference. Computer Science research often uses [IEEE] or [ACM Reference format].

[1] Reference info, date, etc.