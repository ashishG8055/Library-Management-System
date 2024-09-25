Library Management System
Features
Add New Items: Add books, magazines, and DVDs to the library catalog.
Check Out Items: Register the checkout of items and track due dates.
Return Items: Process the return of items and calculate any overdue fines.
Manage Overdue Fines: Calculate and update fines for overdue items.
Search Items: Search for items by title, author, or category.
Getting Started
Prerequisites
Python 3.x
No additional libraries are required.
Installation
Clone this repository:
git clone https://github.com/ashishG8055/LIBRARY-MANAGEMENT-SYSTEM.git
Navigate to the project directory:
cd library-management-system
Run the program:
python main.py
Usage
Adding New Items
To add a new item to the library, run the add_item function and provide details such as title, author, and category.

Checking Out Items
To check out an item, use the check_out function and specify the item ID and the user details. The system will automatically set a due date.

Returning Items
When an item is returned, use the return_item function. The system will calculate any overdue fines if the item is returned past the due date.

Searching for Items
To search for items, use the search_items function and provide the search criteria (title, author, or category).

Example
from library import Library

library = Library()

# Add new items
library.add_item("Book Title", "Author Name", "Book")
library.add_item("Magazine Title", "Author Name", "Magazine")

# Check out an item
library.check_out(item_id=1, user_id=123)

# Return an item
library.return_item(item_id=1)

# Search for items
results = library.search_items(title="Book Title")
Author
Name: Ashish Gaikwad

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Thanks to the open-source community for their contributions and support.
Special thanks to Python for making this project possible.
