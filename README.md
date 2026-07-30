# E-commerce — Flutter Shop App

A Flutter e-commerce UI app for Android and iOS, built on the free
[FlutterShop template](https://github.com/abuanwar072/E-commerce-Complete-Flutter-UI)
by [The Flutter Way (Abu Anwar)](https://www.flutterlibrary.com/templates/e-commerce-app).
I used this project to study and adapt a large, well-organized Flutter UI codebase —
the underlying screen designs and structure are the template author's work, not mine.

This is a UI kit: there is no backend wired up. Screens use mock data, and it is meant to
be connected to a backend of your choice (Firebase, WordPress, a custom API, ...).

<p align="center">
  <img src="readme image/Device_frame.png" alt="E-commerce app home and product details pages" style="width: 1100px; height: auto;">
</p>

<p align="center">
  <img src="readme image/FlutterShop_Intro.gif" alt="App preview" style="width: 643px; height: auto;">
</p>

## Stack

- Flutter (Dart SDK >= 3.2)
- `flutter_svg`, `cached_network_image`, `flutter_rating_bar`, `animations`,
  `form_field_validator`, `flutter_widget_from_html_core`, `url_launcher`
- Light and dark themes, custom fonts (Plus Jakarta, Grandis Extended)

## Run locally

```bash
flutter pub get
flutter run
```

## Screens

The app includes 100+ screens across these areas (all with light/dark theme support):

### Onboarding

- Onboarding Choose item
- Onboarding Add to cart
- Onboarding Pay online
- Onboarding Track order
- Onboarding Find store
- Notification permission
- Select language

### Authentication

- Log in
- Forgot password
  - Choose verification method
  - Verification code
- Set new password
- Done reset password
- Sign up
  - Setup profile
  - Verification code
- Successfully sign up
- Terms and conditions
- Enable fingerprint
- Enable face ID

### Product

- Product page
  - Notify when available (Out of stock)
  - Buy Now
  - Product details
  - Product reviews
  - Add review
  - Shipping methods
  - Product return policy
  - Product size guide
  - Store Pickup Availability
  - Added to cart message

### Main Page

- Home page
- On sales page
- Kids product page
- Brand page
- Discover Page (Categories)
- Bookmark products page

### Search

- Recent search (Search history)
- Search suggestions
- Search filters (size, color, brand, price, sort)
- Search results / product not found

### Cart

- Products on Cart
- Empty cart
- Choose address
- Review & payment
- Checkout / Payment method (select card, pay with cash, use credit)
- Thanks for order
- Add new card

### Profile

- Account (normal and pro versions)
- Profile / edit profile
- Notifications (empty, enable, options)
- Select Language
- Addresses (empty, add new)
- Add number / verification code
- Selected location
- Payment (cards, empty payment)
- Wallet (empty, history)
- Help & Chat (support)
- Preferences

### Order

- Account Orders: processing (with cancel), canceled, delivered

### Error & Permission

- Notification permission, no notification
- No internet, server error
- Location permissions
- No search result, empty order list, no address, empty payment, empty wallet

## Credits

- Template: [FlutterShop — E-commerce Complete Flutter UI](https://github.com/abuanwar072/E-commerce-Complete-Flutter-UI) by Abu Anwar / The Flutter Way
- Docs: [FlutterShop documentation](https://abu-anwar.gitbook.io/fluttershop-doc)
- Tutorial: [YouTube playlist on building the template](https://youtube.com/playlist?list=PLxUBb2A_UUy8OlaNZpS2mfL8xpHcnd_Af)
