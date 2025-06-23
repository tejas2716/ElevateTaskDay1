#---Welcome to Java Console Calculator--

#Developed by: Tejas Sathe
#MailId - sathetejas111@gmail.com

#Project Description
This is a **simple Java console-based calculator** that performs **basic arithmetic operations** such as:
- Addition
- Subtraction
- Multiplication
- Division

It continuously asks for operations and numbers until the user enters `'='` to exit.

---

##Features
- Accepts user input safely using `Scanner`  
- Handles invalid input gracefully  
- Prevents division by zero  
- Uses loops and exception handling (`try-catch`)  
- Keeps running total and allows continuous operations

---

#Technologies Used
- Java 8 or higher
- Any Java IDE (VS Code, IntelliJ IDEA, Eclipse)
- Terminal/Command Prompt

---

#How to Run

1. Clone or download this project.
2. Open the folder in your IDE.
3. Compile and run the file `CalculatorTester.java`.

#Example Flow:

```text
---Welcome to Java Console Calculator---
Enter initial number: 10
Enter operator (+, -, *, /) or '=' to exit: +
Enter next number: 5
Current Result: 15.0
Enter operator (+, -, *, /) or '=' to exit: /
Enter next number: 0
Error: Cannot divide by zero.
Current Result: 15.0
Enter operator (+, -, *, /) or '=' to exit: =
Final Result: 15.0
Thanks for using the calculator!
