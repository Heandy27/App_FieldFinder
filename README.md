# Field Finder App ( Published on the App Store)
[![Download on the App Store](https://tools.applemediaservices.com/api/badges/download-on-the-app-store/black/en-us)](https://apps.apple.com/ec/app/field-finder/id6746458682?l=en-GB)

**Field Finder** is a mobile app developed with SwiftUI that helps users find nearby soccer fields and allows field owners to manage and publish their establishments with ease.  
This app was developed in collaboration with my brother and focuses on enhancing the experience of both players and field owners.

<div style="display: flex; justify-content: center; align-items: center;">
<img src="https://i.postimg.cc/7LcqZfcZ/home.png" alt="map" width="200">
<img src="https://i.postimg.cc/k5Vdz743/tabbar.png" alt="details" width="200">
<img src="https://i.postimg.cc/NFvYRZQh/perfifl.png" alt="favorites" width="200">
<img src="https://i.postimg.cc/G3vbb3jb/login.png" alt="search" width="200">

<img src="https://i.postimg.cc/QdY3fFjJ/registeruserview.png" alt="map" width="200">
<img src="https://i.postimg.cc/bwyyCXkp/establishment-view.png" alt="details" width="200">
<img src="https://i.postimg.cc/vmDQyW0K/fieldview.png" alt="search" width="200">
<img src="https://i.postimg.cc/vZ0QCPt9/fielddetailview.png" alt="favorites" width="200">

<img src="https://i.postimg.cc/6qVKczQ8/perfilview.png" alt="map" width="200">
<img src="https://i.postimg.cc/DydfPfWx/establishmetnregister.png" alt="details" width="200">
<img src="https://i.postimg.cc/X734qM2d/registerestablishmentview.png" alt="search" width="200">
<img src="https://i.postimg.cc/pXZxn077/registerfieldview.png" alt="favorites" width="200">

</div>

---

## 📱 Features

- **MapKit:** View nearby fields on a dynamic map using the user's real-time location.
- **Dark Mode & Light Mode support:** Automatically adapts to the user's system appearance.
- **Favorites:** Mark and save your favorite fields for quick access.
- **Search:** Look up fields by name or location.
- **Login:** Basic login system with token-based authentication.
- **API REST:** Communicates with a backend (built with Vapor) to fetch field data and manage users.
- **MVVM:** Architecture with clear separation between View, ViewModel, and business logic.
- **Async/Await:** Modern Swift concurrency for API requests.
- **Secure Session:** Session handling using `Keychain`
- **Onboarding & Feature Tips with TipKit:** Displays contextual tips to guide users through the app.
- **Backend built with Vapor:** Swift-based server-side framework that powers the API.
- **Unit Testing:** XCTest used for testing:
  - **Repository layer**
  - **Use Cases**
  - **Network services**
  - **ViewModels**
- **Internationalization & Localization:** Supports **English** and **Spanish** with `Localizable.strings`.
---

## 🛠 Technologies

- SwiftUI
- Xcode
- MapKit
- CoreLocation
- REST API
- MVVM
- Async/Await
- Keychain
- **XCTest** (unit testing)

---

## 🚀 Installation

1. Clone this repository:
   ```bash
   https://github.com/Heandy27/App_FieldFinder.git
2. Open the project in Xcode.
3. Run the project on a simulator or physical device.

## Usage

### Testing
The project includes unit tests for:
  - **Repositories:** Validating data fetching and transformation logic.
  - **UseCases:** Ensuring business rules and conditions are met.
  - **Network Services:** Testing API calls and network behavior (mocked).
  - **ViewModels:** Verifying state changes and output bindings.

<hr></hr>
Thank you for reviewing my app. If you want to know more about me or my work, you can find me on these social networks:<br></br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heandy27/) 
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/Heandy27)
