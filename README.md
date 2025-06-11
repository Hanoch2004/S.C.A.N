# S.C.A.N
Flutter based Product Scanner

A **Flutter application** that scans product barcodes and fetches detailed product information from the [OpenFoodFacts API](https://world.openfoodfacts.org). The app provides nutritional data, ingredients, additives, Nutri-Score, NOVA score, and more — all presented in a clean, user-friendly interface.

---

## Features

* **Barcode Scanning & Manual Entry**
  Scan product barcodes using the device camera or enter barcodes manually.

* **Comprehensive Product Details**
  Retrieve and display:

  * Product Name
  * Product Image
  * Full Nutritional Information (calories, fats, sugars, proteins, etc.)
  * Nutri-Score with visual representation (A to E)
  * NOVA Group Classification (1 to 4) with icons
  * Ordered List of Ingredients
  * Additives List and Analysis Details

* **Intuitive & Responsive UI**

  * Clean Material Design with smooth animations
  * Expandable and collapsible info sections
  * Responsive for Android & iOS

* **Open Source & Extensible**
  Easily extend the app or integrate it with other Flutter projects.

---

## Installation

1. Clone the repository:

```
git clone https://github.com/your-username/product_scanner_app.git
cd product_scanner_app
```

2. Get dependencies:

```
flutter pub get
```

3. Run the app:

```
flutter run
```

---

## API Reference

This app uses the [OpenFoodFacts API](https://world.openfoodfacts.org/data) to fetch product data.

* GET Product by Barcode:

  ```
  https://world.openfoodfacts.org/api/v0/product/{barcode}.json
  ```

---

## Contributions

Contributions, suggestions, and improvements are warmly welcomed.
Feel free to:

* Star this repository
* Report Issues
* Open Pull Requests

---

## License

This project is licensed under the [MIT License](LICENSE).

---

## Resources

* [Flutter Documentation](https://docs.flutter.dev/)
* [OpenFoodFacts API Docs](https://wiki.openfoodfacts.org/API)
* [Barcode Scanner Flutter Plugin](https://pub.dev/packages/barcode_scan2)
* [Flutter Cookbook](https://docs.flutter.dev/cookbook)

---

## Author

**D. Hanoch Raj**
[GitHub]((https://github.com/Hanoch2004)) • [LinkedIn](https://linkedin.com/in/your-profile)

---

## Acknowledgements

Thanks to:

* [OpenFoodFacts](https://world.openfoodfacts.org)
* Flutter & Dart Community
* Open Source Contributors

---
