This project is a well-structured Order Management System (OMS) built using Java, HashSet, and custom exceptions. Here's a detailed overview:

Key Features1. CRUD Operations: The system supports Create, Read, Update, and Delete operations for items in the order management system.
2. Search and Sort: Items can be searched by name, and sorted by name and price using custom comparators.
3. Unique Item IDs: HashSet ensures that item IDs are unique, preventing duplicate items.
4. Custom Exceptions: The system uses custom exceptions to handle errors, such as duplicate items and item not found.
5. Menu-Driven Interface: The console-based interface provides an interactive way to perform operations.

Classes and InterfaceThe project consists of multiple classes and an interface:

1. Item: Represents an item with ID, name, and price.
2. OrderOperations: Interface defining methods for CRUD operations, search, and sort.
3. Order: Implements the OrderOperations interface and provides the actual implementation for CRUD operations, search, and sort.
4. SortByName and SortByPrice: Custom comparators for sorting items by name and price.
5. DuplicateItemException and ItemNotFoundException: Custom exceptions for handling duplicate items and item not found errors.

Tools and Technologies1. Language: Java 25
2. IDE: IntelliJ IDEA
3. Collections: HashSet for storing unique items
4. Sorting: Custom comparators (SortByName, SortByPrice)
5. I/O: Console-based interaction

Benefits1. Efficient Item Management: HashSet ensures unique item IDs, and custom exceptions handle errors effectively.
2. Flexible Sorting and Searching: Custom comparators enable sorting by name and price, and searching by name.
3. Interactive Console Interface: The menu-driven interface provides an easy-to-use way to perform operations.

Overall, this project demonstrates a well-structured and efficient Order Management System using Java, HashSet, and custom exceptions.
