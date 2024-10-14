# Petberry - Pet Services E-Commerce App

**Description**:  
**Petberry** is an e-commerce platform designed specifically for pet services and products. The app allows users to browse, search, and purchase a variety of pet products, as well as connect with service providers for pet-related needs. Pet owners can conveniently manage their pet's needs from the app, making it a one-stop solution for all things pet-related.

**Technologies Used**:
- **Flutter**: Cross-platform mobile development for Android and iOS.
- **GetX (State Management)**: Used for efficient and scalable state management throughout the app.
- **Firebase Realtime Database**: Provides real-time updates for product availability, order status, and user interactions.
- **Firebase Push Notifications**: Ensures users receive updates about promotions, product availability, order tracking, and more.
- **API Integration**: Seamless integration with backend APIs to handle product data, search functionality, and order management.

**Key Features**:
- **Product Search & Filtering**: Users can search for pet products and services with advanced filtering options, such as categories, price range, and product ratings.
- **Push Notifications**: Users receive real-time notifications for order updates, promotions, and personalized pet care tips.
- **Product Recommendations**: Using advanced AI algorithms similar to **Shein**, Petberry recommends products based on user preferences and previous purchases.
- **Responsive UI**: Optimized for all screen sizes with smooth and intuitive navigation.

**Architecture**:
- The app follows a **GetX architecture**, ensuring clean separation between the UI and business logic. This enables scalable development, easier testing, and better performance.
- **Repository Pattern** is employed for handling data interactions with the backend, ensuring all product data, order management, and user interactions are organized in a structured and efficient manner.

**User Flow**:
1. **Browse Products**: Users can browse through a wide range of pet products, from food and toys to grooming and veterinary services.
2. **Search & Filter**: Advanced search and filter options help users find specific products easily.
3. **Real-Time Updates**: Product listings are updated in real-time, ensuring users have the most current information on availability and pricing.
4. **Add to Cart & Checkout**: Users can add items to their cart, proceed to checkout, and pay using secure payment options.
5. **Order Tracking**: After placing an order, users can track their delivery status in real-time, receiving notifications at each step.
6. **Push Notifications**: Notifications alert users about new product arrivals, discounts, and updates on their order status.

**Challenges**:
- **Real-Time Updates**: Ensuring real-time synchronization of product data and order status using **Firebase Realtime Database**.
- **Managing State Efficiently**: Using **GetX** for efficient state management, ensuring smooth navigation and handling of user interactions.
- **Push Notifications**: Integrating **Firebase Cloud Messaging (FCM)** to send notifications for promotions, order updates, and personalized pet care tips.

**App Links**:
- [Google Play Store - Petberry](https://play.google.com/store/apps/details?id=com.genix.petberry)
- [Apple App Store - Petberry](https://apps.apple.com/sa/app/petberry/id6473836274)

**Live Demo**:  
Due to confidentiality, the source code is not available. However, a live demo can be provided during a meeting using an emulator like **Android Studio** or **Xcode** for iOS. You may request access to a testing environment for further review.

