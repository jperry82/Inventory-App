# Inventory Management System

The Inventory Management System is an Android application designed to help users efficiently track, manage, and organize their inventory items. The app is particularly useful for small business owners, warehouse managers, and individuals who want to keep their stock levels in check. It also offers the option to receive SMS notifications for low inventory levels, ensuring you never run out of essential items.

## Features

- **User Authentication:** Secure login system with options for new users to create an account.
- **Inventory Management:** Easily add, update, and delete inventory items.
- **Adjust Quantity:** Modify the quantity of existing items directly within the app.
- **SMS Notifications:** Enable or disable SMS alerts for low inventory levels based on user preference.
- **User-Friendly Interface:** Simple and intuitive design that follows Android Material Design principles.

## Installation

### Prerequisites

- Android Studio installed on your system.
- An Android device or emulator running Android 5.0 (Lollipop) or higher.

### Steps

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/inventory-management-system.git
   ```
2. **Open the Project:**
   - Open Android Studio.
   - Choose "Open an existing Android Studio project" and select the cloned repository.

3. **Build and Run:**
   - Connect your Android device via USB or use an emulator.
   - Click `Run` or press `Shift + F10` in Android Studio to build and launch the app.

## Usage

1. **Login:** Use your credentials to log in. If you don’t have an account, you can create one.
2. **Manage Inventory:** 
   - Add new items by tapping the "Add Item" button.
   - Adjust quantities or delete items as needed using the "Adjust Qty" button.
3. **Enable/Disable SMS Notifications:** Toggle SMS notifications through the "Enable/Disable SMS" button for low stock alerts.

## Permissions

The app requires the following permissions:

- **SEND_SMS:** To send SMS notifications for low inventory alerts.
- **INTERNET:** For potential future updates involving cloud sync (not currently implemented).
- **READ_EXTERNAL_STORAGE/WRITE_EXTERNAL_STORAGE:** For backup and restore features (if implemented in future updates).

## Supported Platforms

- Android 5.0 (Lollipop, API level 21) and above.

## Contributing

We welcome contributions from the community! If you would like to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature-or-bugfix-branch
   ```
3. Commit your changes and push them to your forked repository.
4. Create a pull request explaining your changes.

## License

This project is not licensed.

## Contact

For any inquiries or feedback, please contact jperry204@gmail.com
