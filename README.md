# Policy Management System for an Insurance Company
This is a Python-based Policy Management System designed for an insurance company to manage policyholders, products, and payments. The system provides functionalities for policy managers to perform various tasks such as registering policyholders, managing policy products, processing payments, sending reminders, and calculating penalties.

# Features
* Policyholder Management: Register, suspend, and reactivate policyholders.
* Product Management: Create, update, and remove/suspend policy products.
* Payment Management: Process payments, send reminders, and calculate penalties.

# File Structure
* policyholder.py: Contains the Policyholder class for managing policyholder-related operations.
* product.py: Contains the Product class for managing policy product-related operations.
* payment.py: Contains the Payment class for managing payment-related operations.
* main.py: Demonstrates the functionality of the Policy Management System by creating instances of policyholders, products, and payments and displaying their account details.

# Getting Started
 To run the Policy Management System:
 * Ensure you have Python installed on your system. You can download it from here.
 * Clone the repository to your local machine: https://github.com/PAUL-byte-spec/-Policy-Management-System-for-an-Insurance-Company.git
 * Navigate to the project directory: cd policy-management-system
 * Run the main script: python main.py

# Usage

  # Policyholder Management:
  * Create a new Policyholder instance by providing necessary details such as name, policy number, etc.
  * Use the register() method to register a new policyholder.
  * Use the suspend() method to suspend a policyholder.
  * Use the reactivate() method to reactivate a suspended policyholder.

  # Product Management:
  * Create a new Product instance by providing details such as product ID, name, description, etc.
  * Use the create() method to create a new product.
  * Use the update() method to update product details.
  * Use the remove() method to remove/suspend a product.

  # Payment Management:
  * Create a new Payment instance by providing details such as amount, due date, payment method, etc.
  * Use the process() method to process the payment.
  * Use the send_reminder() method to send payment reminders.
  * Use the calculate_penalty() method to calculate late payment penalties.

# Additions: Example
from policyholder import Policyholder
from product import Product
from payment import Payment

# Create policyholder
policyholder1 = Policyholder("Agoroma Paul", "P123456789", ...)
policyholder2 = Policyholder("Agoroma Julie", "P987654321", ...)

# Register policyholders
policyholder1.register()
policyholder2.register()

# Create product
product1 = Product("PROD001", "Car Insurance", "Comprehensive coverage for vehicles", ...)

# Create payment
payment1 = Payment(100, "2024-02-15", "Credit Card", ...)

# Process payment
payment1.process()

# Display account details
print(policyholder1)
print(policyholder2)
print(product1)




  

