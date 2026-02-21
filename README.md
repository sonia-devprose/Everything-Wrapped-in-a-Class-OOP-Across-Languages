# Everything Wrapped in a Class — OOP Across Languages

In Object-Oriented Programming (OOP), a **class** is the fundamental building block. It serves as a blueprint for creating objects, bundling data and behavior together. However, not all languages enforce the use of classes equally.

---

## Java — Classes Are Mandatory

Java is a purely object-oriented language, meaning **all code must live inside a class** — no exceptions. Even the simplest program requires one.

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

The `main` method, which is the entry point of every Java program, must be defined inside a class. The filename must also match the class name exactly (e.g., `HelloWorld.java`).

**To compile and run:**
```bash
javac HelloWorld.java
java HelloWorld
```

This strict structure is intentional — Java was designed from the ground up around OOP principles, ensuring consistency and scalability as programs grow.

> ⚠️ **Warning:** Even for something as simple as printing "Hello, World!", you must wrap it inside a class. Java's compiler will outright refuse to compile any code that exists outside of one — there are no exceptions, no shortcuts.

---

## JavaScript — Classes Are Optional

JavaScript supports OOP, but it does **not** require classes. You can write and run code at the top level without any class structure.

```javascript
console.log("Hello, World!");
```

**To run in the browser:** paste it in the developer console.

**To run with Node.js:**
```bash
node hello.js
```

JavaScript does have classes (introduced in ES6), but they are a tool you reach for when needed, not a requirement imposed by the language.

---

## Python — Also Optional

Like JavaScript, Python allows top-level code with no class required.

```python
print("Hello, World!")
```

Python supports OOP fully, but its philosophy favors simplicity and flexibility — you use classes when they add value.

---

## Key Takeaway

| Language   | Classes Required? | OOP Style                                      |
|------------|-------------------|------------------------------------------------|
| Java       | ✅ Yes             | Strictly OOP                                   |
| C#         | ✅ Yes             | Strictly OOP                                   |
| JavaScript | ❌ No              | Multi-paradigm (supports OOP, not enforced)    |
| Python     | ❌ No              | Multi-paradigm (fully supports OOP, not enforced) |

Java and C# enforce OOP at the language level, making classes unavoidable. JavaScript and Python fully support OOP — including classes, inheritance, and encapsulation — but are multi-paradigm, meaning you can also write code procedurally without classes. The choice is yours.
