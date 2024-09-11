---
num: "Lecture 17"
desc: "Wrap up / Review"
ready: true
lecture_date: 2024-09-11 09:30:00.00-7:00
---

Recorded Lecture: [9_11_24](https://drive.google.com/file/d/1B3FWSlLQeFVKWQBjit02I45U_tq-mBla/view?usp=drive_link)

```
High-Level Final Review

Logistics
* In-person Thursday 9/12 @ 9:30am - 10:50am, BIOEN 1001
* Bring a writing utensil and Student ID
    * Please write LEGIBLY (if we can't read it, we won't
    grade it)
    * Closed Book Exam (no notes, book, electronic devices)
* The final exam is cummulative, but with a heavier emphasis
on post-midterm material
* Types of questions
    * True / False (if False, BRIEFLY explain)
    * Short Answer
        * Briefly define, describe, state, ...
    * Write code satisfying a certain specification
    * Given some algorithm we covered, fill in the blank to
    make it work.
    * Draw diagrams, do worked examples, etc.

Topics
* Python Basics
    * Types
        * int, float, boolean, strings, lists, sets, dict, ..
        * conversion functions (int(), float(), str(), ...)
        * Mutable and immutable
    * Relational / logical operators (==, <, <=, >, and, or, ..)
    * Python Lists
        * Supporting methods (count, pop, append, ...)
    * Understanding under-the-hood functionality of dictionaries vs
    lists
    * List / String slicing [:]
    * Strings
        * Supporting methods (replace, split, find, strip, ...)
    * Function definitions
    * Control structures
        * If, else, elif, for, while

* Testing
    * Test Driven Development (TDD)
    * pytest
* Python Errors
    * Syntax vs Runtime
* Exceptions
    * Exception types (NameError, TypeError, ZeroDivisionError, ...)
    * Exception handling
        * try / except / raise
        * Flow of execution
        * Passing exceptions to function caller
        * Catching multiple exceptions
        * Catching inherited type exceptions
* Object Oriented Programming
    * Defining Python Classes and methods
    * Class constructors
        * Defining / initializing default parameters
    * Shallow vs. Deep equality
        * Overloading __eq__ method
    * Overload operators
        * __str__, __add__, __le__, ...
    * Inheritance
        * Knowing the implementation and behavior of fields / methods
        and how to override inherited methods
        * Know the patter on how to construct inherited objects
        * Know the hierarchy of types (how this affects exception
        handling)
        * Know how to explicitly call super / base class methods
* Algorithm Analysis and O-notation
    * Know how to derive the O-notation for various data structures
    and code segments
* Binary Search
    * Search for items in a SORTED list
    * Know implementation and O-notation
* Recursion
    * Understand how recursive algorithms are managed by the call
    stack
    * Able to derive O-notation for various recursive functions
* Linear Data Structures
    * Know implementations (as covered in textbook/lecture) and
    and O-notations for various functionality of data structures
        * Stacks, Queues, Deques, Linked Lists, Ordered Linked Lists
* Sorting Algorithms
    * Know the implementation and O-notation (best and worst-case)
    of various sorting algorithms
        * Bubble Sort (including the optimized version), Selection
        Sort, Insertion Sort, Merge Sort, Quick Sort
* Trees
    * Terminology
    * Know min-heap / max-heap data structure implementation (and
    underlying list representation)
    * Binary Trees
        * Know the nodes and references implementation
        * Tree traversals: pre, in, post order traversals
    * Binary Search Trees
        * BST property
        * Insertion (and how the order affects the structure)
        * Know various BST method implementations (put, get)
        * Know deletion on the conceptual level
            * Various cases, worked examples
```