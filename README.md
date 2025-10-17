A linked list is a linear data structure where elements (called nodes) are connected using pointers (links).
Each node stores:

The data

A reference (pointer) to the next node

Unlike arrays or lists, linked lists don’t store elements in contiguous memory.

📦 Types of Linked Lists

Singly Linked List — Each node points to the next node only.

Doubly Linked List — Each node points to both next and previous nodes.

Circular Linked List — The last node points back to the first node.

<img width="1536" height="1024" alt="ChatGPT Image Oct 17, 2025, 07_13_52 PM" src="https://github.com/user-attachments/assets/630c618b-a337-4858-8a1d-022a57a9c16e" />



🧭 Advantages

✅ Dynamic size (no need to predefine length)

✅ Efficient insertions/deletions (no shifting elements)

⚠️ Disadvantages

❌ Random access not allowed (must traverse sequentially)

❌ More memory (each node needs extra pointer storage)
