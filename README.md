# TurboMart Admin

![TurboMart Admin Banner](screenshots/banner.png)

## Overview
TurboMart Admin is a powerful Android application designed for administrators to manage an online grocery and essentials store. The app provides a seamless interface for adding, editing, and managing products, categories, and orders, all in real-time using Firebase as the backend. It is inspired by modern e-commerce admin panels and is built to be fast, intuitive, and secure.

## Features
- **Admin Authentication**: Secure phone number-based login with OTP verification.
- **Product Management**: Add, edit, and delete products with multiple images, categories, units, and types.
- **Category Management**: Organize products into various categories for easy browsing.
- **Order Management**: View, update, and track customer orders with real-time status changes and notifications.
- **Search & Filter**: Powerful search and filtering for products by name, price, category, and type.
- **Real-time Notifications**: Send and receive order status notifications using Firebase Cloud Messaging.
- **Modern UI**: Clean, responsive, and user-friendly interface with smooth navigation and dialogs.

## Tech Stack
- **Kotlin** (Android)
- **MVVM Architecture**
- **Firebase Authentication**
- **Firebase Realtime Database**
- **Firebase Cloud Messaging**
- **Retrofit** (for API calls)
- **Coroutines & LiveData**

## Screenshots
Below are some screenshots of the TurboMart Admin app in action:

| Login | Dashboard | Add Product | Orders | Edit Product | Notifications | Categories |
|-------|-----------|-------------|--------|--------------|---------------|------------|
| ![Login](screenshots/login.png) | ![Dashboard](screenshots/dashboard.png) | ![Add Product](screenshots/add_product.png) | ![Orders](screenshots/orders.png) | ![Edit Product](screenshots/edit_product.png) | ![Notifications](screenshots/notifications.png) | ![Categories](screenshots/categories.png) |

> _Replace these images with your actual screenshots in the `screenshots` folder._

## Getting Started
1. **Clone the repository**
   ```bash
   git clone <your-repo-link>
   ```
2. **Open in Android Studio**
3. **Configure Firebase**
   - Add your `google-services.json` in the `app/` directory.
4. **Build & Run**
   - Connect your device or start an emulator.
   - Click `Run` in Android Studio.

## Folder Structure
```
TurboMartAdmin/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/example/admindiyabatti/  # Main source code
│   │   │   ├── res/                              # Resources (layouts, drawables, etc.)
│   │   │   └── AndroidManifest.xml
│   └── google-services.json
├── screenshots/                                  # Place your screenshots here
├── build.gradle.kts
└── ...
```

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](LICENSE)

---

> **TurboMart Admin** – Manage your online store with ease! 