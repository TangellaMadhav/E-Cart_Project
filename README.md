🛒 Madhav-Dashboard20: E-Commerce Product Manager
Welcome to the $Madhav-Dashboard20 E-Commerce Products CLI Tool — a simple command-line application written in Go that demonstrates adding, deleting, updating, and displaying products in an e-commerce dashboard using a map-based data structure.

🧾 Features
Add new products to the catalog.

Delete products using their ID.

Update a product's ID.

View all current products in a clean tabular format.

📂 Project Structure
Product struct holds product details like Id, Name, Brand, and Price.

CRUD functions:

AddProduct() – Adds a new product.

DeleteProduct() – Deletes a product using its ID.

UpdateProduct() – Updates an existing product's ID.

Cart() – Displays all current products in a user-friendly format.

main() – Demonstrates the workflow.

📦 Sample Output
bash
Copy
Edit
Welcome to the $Madhav-Dashboad20 E-Commerce Products!
ID: 1               | Name: Mobile            | Brand: Samsung-Galaxy     | Price: 29999.00
ID: 2               | Name: Laptop            | Brand: Dell-Inspiron       | Price: 59999.00
ID: 3               | Name: Tablet            | Brand: Apple-iPad          | Price: 39999.00

Adding a New Product
ID: 1               | Name: Mobile            | Brand: Samsung-Galaxy     | Price: 29999.00
ID: 2               | Name: Laptop            | Brand: Dell-Inspiron       | Price: 59999.00
ID: 3               | Name: Tablet            | Brand: Apple-iPad          | Price: 39999.00
ID: 4               | Name: Smartwatch        | Brand: Apple-Watch         | Price: 19999.00

Deleting Product from the list
ID: 1               | Name: Mobile            | Brand: Samsung-Galaxy     | Price: 29999.00
ID: 2               | Name: Laptop            | Brand: Dell-Inspiron       | Price: 59999.00
ID: 4               | Name: Smartwatch        | Brand: Apple-Watch         | Price: 19999.00

Updating Product from the list
ID: 1               | Name: Mobile            | Brand: Samsung-Galaxy     | Price: 29999.00
ID: 2               | Name: Laptop            | Brand: Dell-Inspiron       | Price: 59999.00
ID: 3               | Name: Smartwatch        | Brand: Apple-Watch         | Price: 19999.00

Thank you for using the $Madhav-Dashboad20 E-Commerce Products!
Visit Again!
🚀 Getting Started
Requirements
Go 1.18 or higher installed

Run the Project
bash
Copy
Edit
go run main.go
🤝 Contribution
Feel free to fork this repo, improve functionality, or add new features like:

Product search

Price filter

Exporting data to CSV/JSON

PRs are welcome!

🧑‍💻 Author
Developed by Madhav — building practical GoLang solutions.
