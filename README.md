# 🌡️ Smart Temperature Converter (Java)

## 📌 Project Overview

The **Smart Temperature Converter** is a console-based Java application that converts temperature values between:

- Celsius (°C)
- Fahrenheit (°F)
- Kelvin (K)

This project was developed as part of my **Software Development Internship** to demonstrate strong fundamentals in Java, input validation, and problem-solving.

---

## 🚀 Features

✔ Accepts flexible input formats:
- `25C`
- `32 F`
- `300K`
- `25` (asks for unit automatically)

✔ Handles:
- Negative values
- Decimal values
- Invalid input formats
- Unit validation
- Continuous execution until user exits

✔ Regex-based smart input detection  
✔ Exception handling for safe execution  
✔ Kelvin negative value validation  
✔ Clean formatted output  

---

## 🛠 Technologies Used

- Java
- Scanner Class
- Regular Expressions (Pattern & Matcher)
- Switch Case
- Loops
- Exception Handling

---

## 🧠 How It Works

1. Takes user input.
2. Detects if input contains number + unit.
3. If only number is entered, prompts for unit.
4. Validates input using Regular Expressions.
5. Performs temperature conversion.
6. Displays results in formatted output.

---

## 🧮 Conversion Formulas Used

- Celsius → Fahrenheit = (C × 9/5) + 32  
- Celsius → Kelvin = C + 273.15  
- Fahrenheit → Celsius = (F − 32) × 5/9  
- Kelvin → Celsius = K − 273.15  

---

## 📷 Sample Execution
