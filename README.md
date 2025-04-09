
# 🛒 Simple Dart Ecommerce CLI App

This is a **simple command-line Ecommerce system** built using Dart. It allows users to manage products, including adding, editing, buying, and selling them — all via terminal interface.

## 📦 Features

- View available products.
- Add new products with name, category, price, and quantity.
- Edit existing product details.
- Buy products (increase quantity).
- Sell products (decrease quantity).
- Exit the program safely.

## 🧾 Product Attributes

Each product has:
- `name`: Product name.
- `category`: Product category (e.g., Electronics, Clothing).
- `price`: Unit price (must be > 0).
- `quantity`: Stock count (must be > 0).

## 🚀 How to Run

1. Install Dart SDK from [https://dart.dev/get-dart](https://dart.dev/get-dart)
2. Save the code in `main.dart`
3. Run via terminal:
```bash
dart run
```

## 🖼 Example

```text
1 - Show Menu
2 - Add Product
3 - Edit Product
4 - Buy Product
5 - Sell Product
6 - Exit
Choice => 2
Enter product name: Phone
Enter category: Electronics
Enter price: 999.99
Enter quantity: 5
Product added successfully!
```

## 📁 Files

```
📁 project/
 ┣ 📄 main.dart
 ┗ 📄 README.md
```

## 💡 To Improve

- Save/load from file
- Add search/filter
- Categories view
- GUI with Flutter
- Auth for admin/customers

## 👨‍💻 Author

**Abdullah Zahran**
