<div align="center">

<img src="assets/app_logo.png" width="110" alt="GoRide Driver app logo" />

# GoRide Driver

### Flutter driver application for ride requests, trip operations, maps, and live service delivery

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)](https://flutter.dev)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=111827)](https://firebase.google.com)
[![Google Maps](https://img.shields.io/badge/Google_Maps-4285F4?style=flat-square&logo=googlemaps&logoColor=white)](https://developers.google.com/maps)

</div>

## Overview

GoRide Driver is the service-provider side of the GoRide platform. It supports driver onboarding, vehicle information, incoming and active orders, map-based trip handling, intercity and freight services, wallet operations, and customer communication.

## Product capabilities

- Driver authentication, onboarding, and document upload.
- Vehicle and bank-information management.
- New, accepted, active, and completed order states.
- Live map and trip-tracking workflows.
- Intercity, parcel, and freight services.
- Wallet, withdrawal history, payments, chat, and reviews.
- Push and local notifications with localized application UI.

## Technical foundation

- Flutter and Dart.
- Firebase Authentication, Cloud Firestore, Cloud Storage, and Firebase Messaging.
- Google Maps, geolocation, and polyline routes.
- GetX controllers with Provider-backed theme preferences.
- Local notifications, cached network images, and HTTP integrations.

## Local setup

Supply Firebase and platform configuration belonging to an authorized development project, then run:

```bash
flutter pub get
flutter run
```

Do not commit private keys, service-account files, or unrestricted production credentials.

## Related repository

The paired rider experience is available in [GoRide Customer](https://github.com/27dandash/GoRide_customer).

## Maintainer

[Abdelrahman Dandash](https://github.com/27dandash) - Flutter Developer
