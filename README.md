# Laza-ECommerce
### Laza is a simplified, functional e-commerce Minimum Viable Product (MVP) built using Flutter and Firebase. The application leverages the Laza UI Kit for its design and integrates with the Platzi Fake Store API for product data.
----------------------------------------------------------------------------------------------------------------------------------------------------------------
# App-Functional

## Interest Selection
### When the app is opened for the first time, users can choose whether they are interested in men's or women's fashion to personalize their shopping experience.

![male or female](https://github.com/user-attachments/assets/f17e2169-7ce6-4ef2-a36a-0b5fe4304f66)
## User Authentication
### Existing users can log in using email and password or sign in with third-party providers such as Google through Firebase Authentication.

![sign in](https://github.com/user-attachments/assets/05f64617-051f-4f21-8ba5-3cc874d2bc8d)
## User Registration
### New users can create an account by entering their email, password, and confirming the password using Firebase Authentication.

![signup](https://github.com/user-attachments/assets/066a2065-e7bf-4e43-ad38-4f6b382be9cc)
## Password Recovery
### If a user forgets their password, they can reset it by receiving a recovery link via their registered email address.

![reset pass](https://github.com/user-attachments/assets/21267326-0bd9-4dd4-ae0d-8db51c917cb9)
## Home Page
### The home page displays a list of available products, allowing users to browse and select the items they like.

![homepage](https://github.com/user-attachments/assets/7eb95ef8-b72a-4bb3-b5e6-a50c4c5bcf84)
## Add to Cart
### When a user selects a product, it is automatically added to the cart, where they can later view all selected items.

![add to cart](https://github.com/user-attachments/assets/427c47e8-7b19-439c-88ce-9ca5b2c4e281)

# Advanced Features (Enhanced User Experience)

## User Profile
### Users can view their profile page, which displays their personal information used during registration.

![profile](https://github.com/user-attachments/assets/4d8c1d80-d9ff-4d68-9a44-4837ab842c17)
## Order History
###Users can view their order history, including previously purchased items along with their order dates and total prices.

![order history](https://github.com/user-attachments/assets/55473566-7c2f-4c9c-b238-e26e172523f8)
## Notification Management
### Users can manage the notifications they receive, customizing their preferences directly within the app.

![notification](https://github.com/user-attachments/assets/70d54839-3cd7-4bf6-b182-141e767d7024)
## Location & Currency Settings
### Users can update their location, which adjusts delivery options and automatically changes the currency displayed in the app.

![location](https://github.com/user-attachments/assets/4041bf1c-c0e2-4910-a5f1-ea4e3a1c1a14)
## Dark Mode
### Users can switch to dark mode for a more comfortable viewing experience in low-light environments.

![darkmode](https://github.com/user-attachments/assets/21a620ed-ffa8-4acc-bf98-1bbb5ab655d3)
## Help & FAQ
###Users can access a dedicated section for help, frequently asked questions, and their answers to get support within the app.

![help and su](https://github.com/user-attachments/assets/20793358-bcf7-4c50-a889-7276af15a5fe)
## Security & Privacy
### Users can access a dedicated page to manage security settings and privacy preferences for their account.

![WhatsApp Image 2025-12-26 at 11 27 02 PM](https://github.com/user-attachments/assets/4a34f2d0-d522-44ea-83e9-e45831f8add2)

# Resource-Structure

## Architecture
### The project follows a **modular and clean structure** to maintain readability and scalability. The main folders and their responsibilities are:
lib
/models # Data structures for products, users, and cart items
/screens # UI pages: Auth, Home, Product Details, Cart, Favorites, Profile
/services # API and Firebase logic
/widgets # Reusable UI components
/builds/apk # Android app-release.apk
/docs/screenshots # Screenshots for each implemented feature
/appium_tests # Automation scripts for Auth and Cart flows
/video # Demo screen recording

### Key Modules

- **Authentication**: Firebase email/password signup, login, password reset, and auto-login.
- **Onboarding & Entry**: Optional onboarding screen; directs unauthenticated users to login/signup, authenticated users to home.
- **Home & Catalog**: Fetches product data from Platzi API, displays a list, includes local search filtering.
- **Product Listing & Details**: Shows image, title, price, description; supports adding to cart or favorites.
- **Cart & Favorites**: Persistent Firestore storage for carts and favorites; supports quantity updates and removal.
- **Profile & Settings**: Displays user email, allows logout.
- **Error Handling & Empty States**: Basic alerts, loading indicators, empty states for cart/favorites.

**State Management**: Provider & StreamBuilder for reactive UI updates.  
---
## Setup 
### Prerequisites
- Flutter SDK installed  
- VS Code or Android Studio  
- Android Emulator or real devic

## Conclusion

Laza is a **functional e-commerce MVP** that demonstrates essential mobile app development skills:

- Integration with **Firebase** for authentication and persistent data storage  
- API integration with **Platzi Fake Store API** for dynamic product data  
- **Clean and modular architecture**, ensuring maintainability and scalability  
- Provides a **smooth user experience** with basic cart, favorites, and profile manag



































