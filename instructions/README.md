# HW Instructions

👉🏽 **Task** 👈🏽

:star: **Goal** :star:

## 📝 Grading Rubric


1. Learning ()
   * 
2. Approaching  ()
   * 
3. Meets  ()
   * 
4. Exceeds  ()
   * 


AG - Auto-graded  
MG - Manually graded

### Submission Reminder 🚨
For manually graded elements, we only guarantee time to submit for a regrade **IF** you submit by the **DUE DATE**. Submitting late may mean it isn't possible for the MG to be graded before the **AVAILABLE BY DATE**, removing any windows for your to resubmit in time. While it will be graded, it is always best to *submit by the due date*, so you have full opportunity to improve your grade.


## 📚 Resources


### Linked List Resources
* [Linked List Visualization]
* [Geek for Geeks: Linked List Data Structure]
* [Learn C: Linked List Tutorial]
* [Geeks for Geeks: Difference between LinkedList and Vector]

### BST Resources

* [Ordering Differences of DFS]
* [BFS vs DFS Binary Tree]
* [Difference Between BFS and DFS]
* [DFS Traversal of a Tree Using Recursion]
* [Tree Traversal BFS and DFS]
* [Visual BST]

### Markdown Resources
* [Latex Math]- For symbols you can use in markdown math (mathjax)
* [Tables Generator] - Helps convert csv to markdown tables
* [image markdown] - To help include images in your report


### Makefile

* [GNU Make Manual]

You will notice for this assignment, we added a [Makefile](../Makefile). A Makefile is a file that contains a set of instructions for the make program to execute. The make program is a program that is used to automate the build process of a program. In this case, we are using it to automate the compilation of our program. This helps when you have multiple files, and you want to compile them all at once. If you have used gradle or maven in java, this is similar to those tools (arguably those tools are inspired by `make`).

If you view the file, you will see comments on each line for what it does. You can simply type "make" in the same
directory as the Makefile, and it will follow those rules. You can use `make clean` to remove the executable and object files. This Makefile has targets setup up for each of the applications you will be writing. You can run `make` to compile all of them, or `make <target>` to compile a specific one. For example, `make test-bst` will compile the binary search tree test application.

For windows, you may need to install [make](https://gnuwin32.sourceforge.net/packages/make.htm). However, it is highly recommended make in a linux environment for this assignment, as we have other linux commands we recommend using to make (no pun intended) your life easier. If you are using windows, you can use the [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10) to get a linux environment. If you are using a Mac, you already have a linux like environment.

---

[Linked List Visualization]: https://visualgo.net/en/list
[Geek for Geeks: Linked List Data Structure]: https://www.geeksforgeeks.org/data-structures/linked-list/
[Learn C: Linked List Tutorial]: https://www.learn-c.org/en/Linked_lists
[Geeks for Geeks: Difference between LinkedList and Vector]: https://www.geeksforgeeks.org/difference-between-vector-and-list/

[Latex Math]: https://en.wikibooks.org/wiki/LaTeX/Mathematics
[Tables Generator]: https://www.tablesgenerator.com/markdown_tables
[image markdown]: https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#images

[Ordering Differences of DFS]: https://en.wikipedia.org/wiki/Depth-first_search#Output_of_a_depth-first_search
[Depth First Search]: https://en.wikipedia.org/wiki/Depth-first_search
[Breadth First Search]: https://en.wikipedia.org/wiki/Breadth-first_search
[Visual BST]: https://visualgo.net/en/bst
[BFS vs DFS Binary Tree]: https://www.geeksforgeeks.org/bfs-vs-dfs-binary-tree/
[Difference Between BFS and DFS]: https://www.geeksforgeeks.org/difference-between-bfs-and-dfs/ 
[DFS Traversal of a Tree Using Recursion]: https://www.geeksforgeeks.org/dfs-traversal-of-a-tree-using-recursion/
[Tree Traversal BFS and DFS]: https://www.codingeek.com/data-structure/tree-traversal-bfs-and-dfs-introduction-explanation-and-implementation/
[GNU Make Manual]: https://www.gnu.org/software/make/manual/make.html