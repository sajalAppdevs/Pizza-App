# Pizza App 🍕

A beautiful and modern Flutter-based food delivery application that specializes in pizzas and other delicious food items. The app features a clean, intuitive user interface with smooth animations and a responsive design.

## Features

- **Beautiful Starter Page**: Engaging welcome screen with a background image and clear call-to-action
- **Menu Categories**: Browse through different food categories including:
  - Pizza
  - Burger
  - Kebab
  - Dessert
  - Salad
- **Pizza Varieties**: Explore various pizza options:
  - Neapolitan Pizza
  - Chicago Pizza
  - Detroit Pizza
  - Sicilian Pizza
  - Greek Pizza
- **Detailed Food Pages**: Each food item features:
  - High-quality images
  - Detailed descriptions
  - Pricing information
- **Smooth Navigation**: Intuitive navigation between pages with smooth transitions
- **Shopping Cart**: Easy access to shopping cart from any screen

## Technical Details

### Dependencies

- Flutter SDK: >=2.17.6 <3.0.0
- cupertino_icons: ^1.0.2
- flutter_lints: ^2.0.0 (dev dependency)

### Assets

- **Images**: Various food images stored in the `images/` directory
- **Custom Fonts**: Roboto font family with variations:
  - Roboto-Bold
  - Roboto-Light
  - Roboto-Regular

## Getting Started

1. **Prerequisites**:
   - Install Flutter (>=2.17.6)
   - Set up your preferred IDE (Android Studio/VS Code)

2. **Installation**:
   ```bash
   # Clone the repository
   git clone [repository-url]

   # Navigate to project directory
   cd Pizza-App

   # Install dependencies
   flutter pub get
   ```

3. **Run the app**:
   ```bash
   flutter run
   ```

## Project Structure

```
lib/
├── main.dart          # Application entry point
├── menu_page.dart     # Main menu with food categories
├── stater_page.dart   # Welcome/starter page
└── submenu_page.dart  # Detailed food item page
```

## Contributing

Feel free to fork the project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
