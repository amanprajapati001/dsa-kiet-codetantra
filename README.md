# dsa-kiet-codetantra
A collection of day-wise DSA problem solutions practiced on Codetantra as part of KIET curriculum.



1. Topic: Understanding ArrayList (Constructors & Size)
Image: <img width="1920" height="1080" alt="Array List" src="https://github.com/user-attachments/assets/921d6c6d-f1b3-471b-8555-9300f989b6ac" />

Concepts Covered: Initialization of ArrayLists using different constructors and understanding the difference between capacity and size.<br>
Key Code: Using aList.size() to get the element count and new ArrayList(aList) to copy one list into another.
<br>
<br>

2. Topic: Iteration on ArrayList (Filtering & Loops)
Image: <img width="1920" height="1080" alt="Iteration on ArrayList" src="https://github.com/user-attachments/assets/5fe1c5e2-a6fe-4c70-a6c0-cb23ee72bc4d" />

Concepts Covered: Moving data from command-line arguments into a List and iterating through them using multiple loop types.<br>
Key Code: Implementing a for-each loop for simple printing and a standard for loop with .get(index) for indexed output.
<br>
<br>

3. Topic: Methods in ArrayList (Manipulation)
Image: <img width="1920" height="1080" alt="Methods in ArrayList (CRUD Operations)" src="https://github.com/user-attachments/assets/5131c9ed-95f2-4f9e-a114-8f98946c30e1" />

Concepts Covered: Modifying the contents of a list dynamically.<br>
Key Code: * .remove(index): To delete an element.<br>
.set(index, element): To replace an existing value.<br>
.add(index, element): To insert a value at a specific position.

<br>
<br>
4. Topic: ArrayList Basic Implementation
Image:<img width="1920" height="1080" alt="ArrayList Basic Iteration   Input" src="https://github.com/user-attachments/assets/e0134b28-f198-41a0-9b00-ffb3ec6efe71" />

Concepts Covered: Basic input handling and generic List declaration.<br>
Key Code: List<String> namesList = new ArrayList<String>(); and printing the entire list object directly.

<br>
<br>
5. Topic: Vector Class (Legacy Collection)
Image: <img width="1920" height="1080" alt="Vector Class in Java" src="https://github.com/user-attachments/assets/11a66610-1622-49eb-88bf-c12fe3bccacb" />

Concepts Covered: Using the thread-safe Vector class and accessing elements via an Iterator.<br>
Key Code: Using .addElement() instead of .add() and traversing using itr.hasNext() and itr.next().

<br>
<br>
6. Topic: Stack Data Structure (LIFO)
Image: <img width="1920" height="1080" alt="Data Structure (LIFO)" src="https://github.com/user-attachments/assets/4faf2b4d-5466-4e15-9934-f3f7b8734597" />

Concepts Covered: Implementation of the Last-In-First-Out (LIFO) principle.<br>
Key Code: .push() to add items to the top and .pop() to remove and return the topmost item in a while loop.

<br>
<br>
7. Topic: Set Interface (Unique Elements)
Image: <img width="1920" height="1080" alt="Understanding Set Interface (HashSet:LinkedHashSet)" src="https://github.com/user-attachments/assets/078e8a6b-6a7c-403b-b968-fd24ca5e18c8" />

Concepts Covered: Managing a collection of unique items where duplicates are not allowed.<br>
Key Code: * .remove(Object): Returns a boolean indicating if the removal was successful.<br>
.contains(Object): Checks for the existence of an item within the Set.

<br>
<br>
8. Topic: Understanding Map Interface (Key-Value Pairs)
Image: <img width="1920" height="1080" alt="Understanding Map Interface" src="https://github.com/user-attachments/assets/c28308bd-4078-4abe-a58f-bbebb09743c5" />

Concepts Covered: Storing and managing data in unique key-value pairs using the Map interface.<br>
Key Code: * put(K key, V value): Used to add a new mapping or update an existing value (e.g., changing "IN" from "India" to "Bharat").

<br>
<br>
9. Topic: Queue and Deque Interface (FIFO & Double-Ended)
Image: <img width="1920" height="1080" alt="Queue and Deque Interface" src="https://github.com/user-attachments/assets/8c32707a-7972-4bce-bc3e-530a3d2f667f" />

Concepts Covered: Managing collections designed for holding elements prior to processing, specifically First-In-First-Out (FIFO) and double-ended queues.<br>
Key Code: * poll(): Retrieves and removes the head of the queue.

<br>
<br>
10. Topic: Escape Sequences in Java
Image: <img width="1920" height="1080" alt="Escape Sequences" src="https://github.com/user-attachments/assets/9994dd08-5e49-40fc-8722-b4d799e8d67f" />

Concepts Covered: Using special characters (like backslashes) to include double quotes or new lines within a string literal without causing a syntax error.<br>
Key Operations: \": Used to include a double quote inside a string (e.g., printing "She said, "It is wrongly called..."").

<br>
<br>
11. Topic: Iterating through a Multidimensional Array
Image: <img width="1920" height="1080" alt="Iterating through a multidimensional array" src="https://github.com/user-attachments/assets/3c00b57e-5e89-4072-a43d-84b415359e38" />

Concepts Covered: Using nested enhanced for loops (for-each loops) to traverse a 2D integer array.<br>
Key Operations: <br>
for(int[] row : int2DArr): The outer loop picks each row of the 2D array.<br>
for(int element : row): The inner loop picks each individual integer from that row.

<br>
<br>
12. Topic: Escape Sequences in Java (Part 2)
Image: <img width="1920" height="1080" alt="Escape Sequences" src="https://github.com/user-attachments/assets/bbb484c8-7cf0-44ec-8005-89d136d3d598" />

Concepts Covered: Practical application of escape characters to produce specific text output containing quotes.<br>
Key Operations: The code correctly implements \"BLUE to ensure the output displays a literal double-quote before the word BLUE.

<br>
<br>
13. Topic: Escape Sequences (Complex String Formatting)
Image: <img width="1920" height="1080" alt="Escape Sequences Complex String Formatting" src="https://github.com/user-attachments/assets/3e785dec-2880-497a-9f5b-2faa774ff30b" />


Description: Focuses on formatting complex strings, such as SQL-style INSERT statements, that require multiple internal quotes. <br>
Key Operations: Uses \" multiple times within a single string to surround values like "10" and "Meka" with literal quotes.

