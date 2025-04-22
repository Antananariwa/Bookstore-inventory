Activity 10.1: Array Manipulation Practice
Project Description:

This activity will help students practice creating, manipulating, and sorting arrays in PHP. Students will create a simple inventory management system for a small bookstore.

Instructions:

1. Create a PHP file named bookstore_inventory.php.

2. Define an associative array called $inventory with at least 5 books. Each book should have the following properties: title, author, price, and quantity.

3. Implement the following functions:

a. addBook($inventory, $title, $author, $price, $quantity) : Adds a new book to the inventory.
b. removeBook($inventory, $title) : Removes a book from the inventory by its title.
c. updateQuantity($inventory, $title, $newQuantity) : Updates the quantity of a book in the inventory.
d. sortInventory($inventory, $sortBy) : Sorts the inventory by the specified property (title, author, price, or quantity).
4. Use the print_r() function to display the inventory after each operation.

Test your functions by adding books, removing a book, updating quantities, and sorting the inventory in different ways.
