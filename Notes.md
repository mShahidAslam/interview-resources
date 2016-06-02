# Interview-prep

Best source -> https://github.com/bsikander/getting-a-gig

# Linked List:
- Data structure to hold data of any type and size
  **Advantages:**
  - Insertion in O(1). 
  > Insertion consists of two functions Find + insert. Insert is always O(1) but find always makes the difference. If we have the pointer then find is O(1) otherwise find will be O(n) which makes the overall time of insert to be O(n). <-- [Good implementations will  always keep the pointer to the last node](http://stackoverflow.com/questions/1933085/linked-list-insertion-running-time-confusion)
  - Access is O(n)
  
  **Disadvantages**
  - Memory waste for extra pointers
  
  
  
# Concepts:
- **Constant Time**:
"Constant time" has the same meaning as "O(1)", which doesn't mean that an algorithm runs in a fixed amount of time,
it just means that it isn't proportional to the length/size/magnitude of the input. i.e., for any input, it can be computed 
in the same amount of time (even if that amount of time is really long).

[Linear + Constant Time]([https://www.quora.com/Difference-between-linear-time-and-constant-time-in-Data-structure)


## HashTable/HashMap
- Hashing used for storing and retrieving information as fast as possible.
- Array can be used as hashtable if our set of possible options is limited. Direct addressing can be used to access elements.
- The process of mapping the keys to a location is called hashing
- One simple hash function can be (key % hash table size)
- Components of hashing are Hash Table, Hash Function, Collisions, Collision Resolution Techniques

##### Hash Table
- Hash table is generalization of array.
- Used when we have less locations and more possible keys. So, use hashtable when the keys stored is small relative to the number of possible keys.

##### Hash Function
- Minimize Collision
- 
http://www.cs.rmit.edu.au/online/blackboard/chapter/05/documents/contribute/chapter/05/linear-probing.html
