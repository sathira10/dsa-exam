# Data Structures

A data structure is a structure used to organize & store a collection of one or more items of information that are usually related in some way.

## Aspects of a Data Structure
1. Definition
2. Operations (API)
3. Storage (Internal Representation)

## Classification

### Linear vs Non Linear
- Linear (organized using a sequence structure) - Arrays, Lists, Stacks, Queues
- Non Linear (organized using a non-sequential structure) - Trees, Heaps, Graphs

### Static vs Dynamic
- Static (fixed size, usually sequential too) - Arrays, Stacks, Queues
- Dynamic (no fixed size) - List, Stacks, Queues, Trees, Heaps, Graphs

### Indexed vs Linked (Non-indexed)
- Indexed (one or more indexes into the structure) - Arrays, Matrices (2D Arrays), n-D arrays
- Linked (data nodes are connected by links) - List, Stacks, Queues, Trees, Graphs.

## Memory Management

### Static
compiler allocates a fixed amount of memory space for storage

**Disadvantages**
- Size is fixed
- When not full, memory space is wasted
- Resizing is inefficient

### Dynamic
amount of data that has to be dealt with is unknown at compile time. Can grow or shrink in size.

Usually the "new" keyword is used to create one. Pointers (C++) or references (C#, Java) are used here.

## Abstract Data Types (ADTs)
a data type together with a set of operations which define how the type may be manipulated.

> example - set of positive integers with +, -, * operations



# Algorithms

An algorithm in its most general sense is a sequence of steps/instructions designed to solve a problem or achieve a goal.

## Efficiency  
Two types of Efficiency
1. Time: how fast an algorithm runs for a given size of input data.
2. Space: how much extra storage space the algorithm requires.

Try to optimize both. There’s often a trade-off between the two.

## Choosing an Algorithm
We might choose a less efficient algorithm for the following reasons
- **simpler to understand** (e.g. uses for-loops, rather than recursion)
- **simpler to implement** (uses arrays, rather than lists, graphs, etc)
- **an implementation already exists** (such as in a software library, e.g. .NET class libraries, Java’s JDK, or C++’s Standard Template library.)

## Types of Algorithms

### Brute Force


### Divide-and-conquer


### Greedy

