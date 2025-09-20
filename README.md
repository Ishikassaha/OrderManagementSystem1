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

<img width="1815" height="792" alt="Screenshot 2025-09-20 083127" src="https://github.com/user-attachments/assets/173d84d4-9f98-4af6-83b2-61b9d1cd9b11" />
<img width="511" height="495" alt="Screenshot 2025-09-20 083140" src="https://github.com/user-attachments/assets/04ceebcc-8281-42b1-bce1-777f6ade9197" />
<img width="1777" height="710" alt="Screenshot 2025-09-20 083534" src="https://github.com/user-attachments/assets/64ad0acc-38bc-479a-9d6b-da725a11ab78" />
<img width="406" height="742" alt="Screenshot 2025-09-20 083559" src="https://github.com/user-attachments/assets/ed02cc26-8966-496c-9e5f-1de65c5af2a6" />
<img width="469" height="789" alt="Screenshot 2025-09-20 083621" src="https://github.com/user-attachments/assets/1fad7507-837e-47e5-99ff-8d1aec53c158" />
<img width="457" height="672" alt="Screenshot 2025-09-20 083635" src="https://github.com/user-attachments/assets/e0128892-b01a-43a2-8d2f-557a2ae4470a" />





