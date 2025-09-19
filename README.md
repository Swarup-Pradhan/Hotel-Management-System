# 🏨 Hotel Management System (Java)

This project is a **console-based Hotel Management System** written in **Java**.  
It allows customers to book rooms, order food, check availability, checkout, and generate bills.  
The system also saves booking details in a file (`backup`) to maintain persistence between runs.

---

## 📌 Features
- **Room Types**  
  - Luxury Double Room  
  - Deluxe Double Room  
  - Luxury Single Room  
  - Deluxe Single Room  

- **Room Management**
  - Book a room  
  - Display room features  
  - Display room availability  
  - Deallocate (checkout) with bill generation  

- **Food Ordering**
  - Sandwich – Rs. 50  
  - Pasta – Rs. 60  
  - Noodles – Rs. 70  
  - Coke – Rs. 30  

- **Billing**
  - Calculates room charges + food charges  
  - Displays an itemized bill  

- **Data Persistence**
  - Uses Java Serialization (`ObjectOutputStream` & `ObjectInputStream`)  
  - Saves all hotel data to `backup` file  
  - Reloads data when program restarts  

---

## 🛠️ Technologies Used
- **Java SE** (Core Java)  
- **OOP Concepts** (Inheritance, Exception Handling, Serialization, Multithreading)  
- **File Handling** (for backup and restore)  

---

## 🚀 How to Run
1. Clone this repository or copy the code into your local machine.  
2. Compile the program:
   ```bash
   javac Main.java
   ```

3. Run the program:

   ```bash
   java Main
   ```

---

## 📖 Menu Options

When you run the program, you’ll see the following menu:

```
1. Display room details
2. Display room availability
3. Book a room
4. Order food
5. Checkout
6. Exit
```

---

## 📂 File Structure

```
.
├── Main.java          # Main class to run the program
├── backup             # Auto-generated file to store hotel data
└── README.md          # Project documentation
```

---

## 👨‍💻 Author

* **Your Name**
  💼 GitHub: [Swarup-Pradhan](https://github.com/Swarup-Pradhan)
  📧 Email: [your-email@example.com](mailto:your-email@example.com)

---

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

✨ This README is ready to be used.  
Do you want me to also add **example screenshots of console output** (bill, booking, etc.) to make it look more professional?
```
