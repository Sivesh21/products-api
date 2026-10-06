classDiagram
    -class Product {
    -Long id
    -String name
    +Product()
    +Product(Long id, String name, double price)
    +getId() Long
    +getName() String
    +getPrice() double
    }