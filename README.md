# PBLJ_6_Kapil-E18497-

### Easy Level:

**Program Objective:**
Sort a list of Employee objects by age using lambda expressions.

**Input:**
A list of Employee objects with the following attributes: name (String), age (int), and salary (double).

Example input:

```java
List<Employee> employees = Arrays.asList(
    new Employee("Alice", 30, 50000),
    new Employee("Bob", 25, 40000),
    new Employee("Charlie", 35, 60000)
);
```

**Output:**
The list of employees sorted by age in ascending order.

```java
[
    Employee{name='Bob', age=25, salary=40000},
    Employee{name='Alice', age=30, salary=50000},
    Employee{name='Charlie', age=35, salary=60000}
]
```

---

### Medium Level:

**Program Objective:**
Filter students scoring above 75%, sort them by marks in descending order, and display their names.

**Input:**
A list of Student objects with the following attributes: name (String), marks (int).

Example input:

List<Student> students = Arrays.asList(
    new Student("John", 80),
    new Student("Mary", 70),
    new Student("Alice", 90),
    new Student("Bob", 65)
);
```

**Output:**
The names of students who scored above 75%, sorted by marks in descending order.

[
    Alice,
    John
]
```

---

### Hard Level:

**Program Objective:**
Process a large dataset of products using streams. Perform operations like grouping products by category, finding the most expensive product in each category, and calculating the average price of all products.

**Input:**
A list of Product objects with the following attributes: name (String), category (String), price (double).

Example input:


List<Product> products = Arrays.asList(
    new Product("Laptop", "Electronics", 1200),
    new Product("Smartphone", "Electronics", 800),
    new Product("Table", "Furniture", 150),
    new Product("Chair", "Furniture", 100),
    new Product("TV", "Electronics", 900),
    new Product("Sofa", "Furniture", 500)
);
```

**Output:**
1. **Grouping products by category:**

{
    Electronics=[Laptop, Smartphone, TV],
    Furniture=[Table, Chair, Sofa]
}
```

2. **Most expensive product in each category:**


{
    Electronics=Laptop,
    Furniture=Table
}
```

3. **Average price of all products:**


Average price: 675.0
```

--- 

These theoretical outputs illustrate how lambda expressions and streams can be used to perform common tasks like sorting, filtering, and aggregating data efficiently in Java.
