# Mortgage Calculator (Java)

This is a simple command-line Java application that calculates the monthly mortgage payment based on user input.

## 📌 Purpose

The program allows users to input loan details and calculates the monthly payment using the standard mortgage formula. It also validates user input to ensure values are within realistic ranges.

## ⚙️ Features

* User input validation for:

  * Principal amount ($1,000 – $1,000,000)
  * Annual interest rate (1% – 30%)
  * Loan period (1 – 30 years)
* Calculates monthly mortgage payment
* Formats output as currency
* Uses loops to ensure correct input

## 🧮 How it works

The program:

1. Prompts the user to enter:

   * Loan amount (principal)
   * Interest rate
   * Loan duration
2. Converts annual interest into monthly interest
3. Calculates total number of payments
4. Applies the mortgage formula
5. Displays the monthly payment in a formatted currency

## ▶️ How to run

1. Compile the program:

```
javac Main.java
```

2. Run the program:

```
java Main
```

## 🛠️ Technologies Used

* Java
* Scanner (for user input)
* NumberFormat (for currency formatting)

## 💡 Example

```
Principal ($1K - $1M): 100000
Annual Interest Rate: 5
Period (Years): 10
Mortgage: $1,060.66
```

## 🚀 Possible Improvements

* Add a graphical user interface (GUI)
* Allow users to view total interest paid
* Support different currencies
* Save results to a file

## 📄 License

No license specified.
