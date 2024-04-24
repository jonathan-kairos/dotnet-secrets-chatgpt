# Inventory Tracker CRUD App Requirements

## Functional Requirements

### 1. Create
- Allow users to add new items to the inventory with details such as name, description, quantity, and price.
  - **Constraints:**
    - All fields are required.
    - Name cannot be longer than 32 characters.
    - Description cannot be longer than 150 characters.
    - Quantity cannot be more than 100 items.
    - Price cannot be more than $1000.

### 2. Read
- Display a list of all inventory items with their details.

### 3. Update
- Allow users to edit existing inventory items.

### 4. Delete
- Allow users to remove items from the inventory.

## Non-Functional Requirements

1. **Data Validation**
   - Validate user input to ensure data integrity and prevent errors.
   
2. **User Interface**
   - Create a user-friendly interface for easy navigation and interaction.

3. **Performance**
   - Ensure the app can handle a reasonable amount of inventory items without significant performance degradation.
   - Utilize efficient data structures and querying mechanisms suitable for an in-memory database to maintain high performance.

## Additional Features (Optional)

1. **Search**
   - Allow users to search for specific items in the inventory using a search bar or query system.
   
2. **Sorting**
   - Provide options to sort the inventory list based on different criteria (e.g., name, quantity, price).

3. **Filters**
   - Allow users to apply filters to the inventory list (e.g., show only items with low stock).

## Technical Specifications

- **Framework:** .NET 6
- **Database:** Use Entity Framework Core with an in-memory database provider like `Microsoft.EntityFrameworkCore.InMemory` for development and testing purposes. This will simulate database operations without the need for external database management systems.


# Prompts Used to Generate the Application
1. What .NET project should I use for these app requirements?
2. How to create complex user interfaces?
3. Detailed plan to create the web app in MVC.
4. Configuration of Entity Framework Core to use an in-memory database provider.
5. Command input in Visual Studio for `dotnet add package Microsoft.EntityFrameworkCore.InMemory`.
6. Compatibility of `Microsoft.EntityFrameworkCore.InMemory` with .NET 6.
7. Installation of the latest 6.x version for `Microsoft.EntityFrameworkCore.InMemory`.
8. Code implementation.
9. Inventory page link in the app bar.
10. Prepopulating an in-memory database in .NET MVC.
11. Seeding an in-memory database using Entity Framework Core in .NET 6 MVC application.
12. Generating 100 random inventory items without hardcoding.
13. Adding a red alert icon on rows where items have 10 items or fewer.
14. Adding a dollar sign to the price display.
15. Option to cancel edits and return to the table.
16. Ensuring unique item names during addition.
17. Creating a page to track changes in the Inventory Items table.
18. Including history change records in Create, Edit, and Delete views.
19. Adding InventoryHistory to the header bar.
