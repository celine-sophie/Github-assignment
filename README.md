  Q1.md( Rules Of Big O Notation
  1. Ignore constants
     When analyzing algorithms for large input sizes, constant factors become insignificant. THe focus is in how the algorithm scales as the input grows

  2. Focus on the dominant term
     In expressions with multiple terms the term with the highest growth rate determines the overall complexity

   3. Drop Non-Dominant Terms
      In combined complexities, only the highest term is considered.

  4. Constant time operations 
     Simple operations like accessing an arrary element by index are 0(1)

  5. Amortized complexity
     Amortized complexity accounts for occasional expensive operations that are spread across multiple inputs.


  Q2.md ( Difference between arrays and Linked lists)

  1. Memory allocation
     Arrays
      Arrays use contiguous memory allocation, meaning elements are stored in adjacent memory allocations
      The size of an arrayis fixed at the time of declaration
      Efficient for accessing elements using indexing

     Linked lists
     Linked lists use dynamic memory allocation meaning elements (nodes) are stored in seperate memory locations connected via pointers
     The size of a linked list can grow or shrinl dynamically
     Extra memory is required for pointers

2. Performance
   Arrays
   Access time: 0(1) (Direct access using index)
   Search time: 0(n) (Linear serach) or 0(log n) (Binary search for sorted arrays)
   Memory Usage: Less memory overhead because no extra pointers are sorted

   Linked lists
   Access time: 0(1) (Sequential access ; must have traverse nodes)
   Search time: 0(n) (Must have traverse from the head)
   Memory usage: More memory is required due to the storage of pointers

3. Insertion and deletion operations
   Arrays
   Insertion: Inserting in the middle requires shifting elements (0(n)time complexity)
   Deletion: Deleting in the middle also requires shifting elements (o(n)time complexity).

   Linked lists
   Insertion: 0(1) at the beginnig, 0(n) at the end (traverse required).
   Deletion: 0(1) at the beginning , 0(n) for arbitary nodes.
   
   
   
   
     

       
