# ObjectOrientedPrograming

This C# console application exemplifies Object-Oriented Programming principles through a simplified credit management system. The program allows for the management of customers and the provision of various types of credits.

## Usage

1. **Compile and Run:**
   - Compile the program using a C# compiler.
   - Run the compiled executable file.

2. **Understanding the Code:**
   - `Program.cs` contains the entry point of the application and demonstrates various functionalities.
   - `CreditManager.cs` defines a base class and interfaces for credit management.
   - `Customer.cs`, `Person.cs`, and `Company.cs` represent different types of customers.
   - `CustomerManager.cs` handles customer operations and credit provision.

3. **Functionality:**
   - The program demonstrates inheritance, interfaces, and abstraction.
   - Different credit types such as teacher, military, and car credits are implemented.
   - Customers can be managed, and credits can be provided based on their type.

## Classes and Interfaces

- **`CreditManager`**: Base class for credit management. Implements methods for calculating and saving credit details.
- **`ICreditManager`**: Interface defining methods for calculating and saving credit details.
- **`BaseCreditManager`**: Abstract class implementing `ICreditManager`. Provides a template method for calculating credit and a default implementation for saving.
- **`TeacherCreditManager`**, **`MilitaryCreditManager`**, **`CarCreditManager`**: Concrete classes implementing `BaseCreditManager` for specific types of credits.
- **`Customer`**: Base class representing a customer. Contains properties for customer details.
- **`Person`**: Derived class from `Customer`, representing an individual customer. Contains additional properties such as first name, last name, and national identity.
- **`Company`**: Derived class from `Customer`, representing a corporate customer. Contains properties such as company name and tax number.
- **`CustomerManager`**: Manages customers and credit operations. Accepts a customer and a credit manager as parameters.

## Notes

- The code includes commented-out sections that demonstrate alternative approaches or unused functionality.
- IoC (Inversion of Control) container usage is illustrated but currently commented out.
- The program mainly serves as an educational example and may require enhancements for production use.
