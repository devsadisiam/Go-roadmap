# 🚀 **Go (Golang) Learning Roadmap - 6 Months**  

A structured **6-month plan** to learn **Go (Golang)** from **beginner to advanced** and become a professional software developer.  

---

## 📌 **Month 1: Go Basics**  

### **🗓️ Week 1: Introduction to Go**  
- ✅ What is Go and why learn it?  
- ✅ Installing and setting up Go  
- ✅ Writing and running your first Go program  
- ✅ Understanding Go program structure  

💡 **Example:**  
```go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

---

### **🗓️ Week 2: Variables, Data Types & Constants**  
- ✅ Declaring variables (`var`, `:=` syntax)  
- ✅ Understanding data types (int, float, string, boolean)  
- ✅ Working with constants (`const`)  

💡 **Example:**  
```go
var name string = "John"
age := 25
const Pi = 3.1416
```

---

### **🗓️ Week 3: Operators & Control Structures**  
- ✅ Arithmetic, comparison, and logical operators  
- ✅ Conditional statements (`if`, `else`, `switch`)  

💡 **Example:**  
```go
if age >= 18 {
    fmt.Println("You are an adult")
} else {
    fmt.Println("You are a minor")
}
```

---

### **🗓️ Week 4: Loops & Functions**  
- ✅ `for` loop (with range, break, and continue)  
- ✅ Defining and calling functions  
- ✅ Using `defer`, `panic`, and `recover`  

💡 **Example:**  
```go
func add(a int, b int) int {
    return a + b
}
```

---

## 📌 **Month 2: Working with Data**  

### **🗓️ Week 5: Arrays & Slices**  
- ✅ Declaring and using arrays  
- ✅ Dynamic arrays using slices  

💡 **Example:**  
```go
numbers := []int{1, 2, 3, 4}
fmt.Println(numbers[0]) // Output: 1
```

---

### **🗓️ Week 6: Maps & Structs**  
- ✅ Key-value pairs with maps  
- ✅ Defining and using structs  

💡 **Example:**  
```go
type Person struct {
    Name string
    Age  int
}

p := Person{Name: "Alice", Age: 30}
```

---

### **🗓️ Week 7: Pointers**  
- ✅ Understanding memory addresses  
- ✅ Passing by reference  

💡 **Example:**  
```go
func changeValue(x *int) {
    *x = 20
}
```

---

### **🗓️ Week 8: Error Handling**  
- ✅ Using `error` type  
- ✅ Custom error handling  

💡 **Example:**  
```go
func divide(a, b int) (int, error) {
    if b == 0 {
        return 0, fmt.Errorf("cannot divide by zero")
    }
    return a / b, nil
}
```

---

## 📌 **Month 3: Intermediate Topics**  

### **🗓️ Week 9: Goroutines & Concurrency**  
- ✅ Introduction to goroutines  
- ✅ Using `sync.WaitGroup`  

💡 **Example:**  
```go
go fmt.Println("This runs in a goroutine")
```

---

### **🗓️ Week 10: Channels**  
- ✅ Sending and receiving data using channels  
- ✅ Buffered channels  

💡 **Example:**  
```go
ch := make(chan int)
go func() { ch <- 42 }()
fmt.Println(<-ch)
```

---

### **🗓️ Week 11: File Handling**  
- ✅ Reading & writing files  
- ✅ Working with JSON & CSV  

💡 **Example:**  
```go
data, _ := ioutil.ReadFile("file.txt")
fmt.Println(string(data))
```

---

### **🗓️ Week 12: Interfaces & Polymorphism**  
- ✅ Implementing interfaces  
- ✅ Understanding polymorphism  

💡 **Example:**  
```go
type Animal interface {
    Speak() string
}
```

---

## 📌 **Month 4: Advanced Topics**  

### **🗓️ Week 13: Web Development with Go**  
- ✅ Creating an HTTP server  
- ✅ Handling requests & responses  

💡 **Example:**  
```go
http.HandleFunc("/", func(w http.ResponseWriter, r *http.Request) {
    fmt.Fprintln(w, "Hello, World!")
})
```

---

### **🗓️ Week 14: Building REST APIs**  
- ✅ Creating an API  
- ✅ Using `gorilla/mux` for routing  

---

### **🗓️ Week 15: Working with Databases**  
- ✅ Connecting Go with PostgreSQL/MySQL  
- ✅ Performing CRUD operations  

---

### **🗓️ Week 16: Authentication & Security**  
- ✅ Implementing JWT authentication  
- ✅ Secure coding best practices  

---

## 📌 **Month 5: Project-Based Learning**  

### **🗓️ Week 17: Building a CLI App**  
- ✅ Using `cobra` to create command-line applications  

---

### **🗓️ Week 18: Building a Web App with Gin**  
- ✅ Using `Gin` framework  

---

### **🗓️ Week 19: Deploying with Docker**  
- ✅ Writing a `Dockerfile`  
- ✅ Running Go applications inside containers  

---

### **🗓️ Week 20: Deploying Go Applications**  
- ✅ Deploying on **Heroku, AWS, DigitalOcean**  

---

## 📌 **Month 6: Becoming an Expert**  

### **🗓️ Week 21: Testing in Go**  
- ✅ Writing unit tests  
- ✅ Using `GoMock` for testing  

---

### **🗓️ Week 22: Open Source Contribution**  
- ✅ Finding Go projects on GitHub  
- ✅ Making contributions  

---

### **🗓️ Week 23: Best Practices in Go**  
- ✅ Writing clean, efficient code  
- ✅ Optimizing performance  

---

### **🗓️ Week 24: Job Preparation & Freelancing**  
- ✅ Practicing Go interview questions  
- ✅ Building a strong portfolio  
- ✅ Applying for jobs & freelancing  

---

# 🎯 **Final Goal:**  
✅ **By the end of this roadmap, you will be job-ready** as a **Go Developer** and can start working in software firms or freelancing! 🚀  

---

## **📌 How to Use This Roadmap?**  
1️⃣ **Follow the weekly lessons** and practice the examples.  
2️⃣ **Build real projects** to gain hands-on experience.  
3️⃣ **Contribute to open source** and improve your skills.  
4️⃣ **Apply for jobs** or start freelancing to earn as a Go developer.  

---

### ⭐ **Like this roadmap? Give it a star on GitHub! 🌟**  
