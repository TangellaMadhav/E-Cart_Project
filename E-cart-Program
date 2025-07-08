package main

import (
	"fmt"
)

type Product struct {
	Id    int
	Name  string
	Brand string
	Price float64
}

// Add Product Function using Id - $Madhav
func AddProduct(products map[int]Product, id int, name, brand string, price float64) {
	products[id] = Product{
		Id:    id,
		Name:  name,
		Brand: brand,
		Price: price,
	}
}

// Delete Product Function using Id - $Madhav
func DeleteProduct(products map[int]Product, id int) {
	delete(products, id)
}

// Update Product Function using Id - $Madhav
func UpdateProduct(products map[int]Product, oldId, newId int) {
	if product, ok := products[oldId]; ok {
		delete(products, oldId)
		product.Id = newId
		products[newId] = product
	}
}

// Cart Function to print product - $Madhav
func Cart(products map[int]Product) {
	for _, p := range products {
		fmt.Printf("ID: %-15d | Name: %-20s | Brand: %-20s | Price: %.2f\n", p.Id, p.Name, p.Brand, p.Price)
	}
}

func main() {
	products := map[int]Product{
		1: {Id: 1, Name: "Mobile", Brand: "Samsung-Galaxy", Price: 29999},
		2: {Id: 2, Name: "Laptop", Brand: "Dell-Inspiron", Price: 59999},
		3: {Id: 3, Name: "Tablet", Brand: "Apple-iPad", Price: 39999},
	}

	fmt.Println("Welcome to the $Madhav-Dashboad20 E-Commerce Products!")
	Cart(products)

	fmt.Println("\nAdding a New Product")
	AddProduct(products, 4, "Smartwatch", "Apple-Watch", 19999)
	Cart(products)

	fmt.Println("\nDeleting Product from the list")
	DeleteProduct(products, 3)
	Cart(products)

	fmt.Println("\nUpdating Product from the list")
	UpdateProduct(products, 4, 3)
	Cart(products)

	fmt.Println("\nThank you for using the $Madhav-Dashboad20 E-Commerce Products!")
	fmt.Println("\nVisit Again!")
}
