# Track ECG Privacy Policy

**Effective date:** October 4, 2026  
**Developer:** Aidan Maldonado  
**Application:** Track ECG for Polar H10

## Data used by the app

Track ECG receives measurements from a connected Polar H10, including ECG, heart rate, RR intervals, accelerometer readings, battery status, and device connection details. Saved recordings include timestamps and recording metadata.

With the Workouts feature, Track ECG can also record workout activity, intervals, GPS coordinates, distance, speed, and altitude. GPS recording requires location permission.

The app stores preferences such as language, appearance, units, and heart-rate zone settings.

## Storage

Recordings are stored in the app's local storage on the iPhone. The reviewed app source contains no developer-operated account system, analytics service, advertising tracking, or automatic upload of recordings to a developer-operated server. The developer does not automatically receive sensor recordings or location data.

Locally stored data may be included in device backups according to iOS backup settings.

## Bluetooth and location

Bluetooth access is used to discover and connect to the Polar H10 and receive sensor measurements. Location access is used to record routes and related measurements during outdoor workouts. Location tracking can continue in the background during an active outdoor workout when iOS permits.

## Apple Health

With permission, Track ECG can read authorized Health data, including workouts, routes, date of birth, resting heart rate, heart rate, distance, step counts, and energy measurements. Date of birth and resting heart rate can be used to suggest heart-rate zone settings. Other authorized measurements may be used for workout information and exports.

Track ECG can write completed workouts, heart-rate samples, supported distance measurements, and workout routes to Apple Health. Raw ECG and accelerometer recordings are retained in the app's local files.

Apple Health access is controlled through iOS and the Health app. Revoking access prevents future authorized reads or writes. Data already saved in Apple Health is managed separately through Apple Health.

## Purchases

Apple processes the optional Workouts purchase through StoreKit. Track ECG checks purchase status to enable purchased features. The app does not receive payment-card details.

## Exports and sharing

You choose when to export or share recordings. Exports can contain sensitive health measurements and, for outdoor workouts, location data. Files shared with another app, email provider, or cloud service are handled according to the chosen destination's privacy practices.

## Deletion and retention

You can delete locally saved recordings in **History**. Deleting a local recording does not automatically delete a corresponding workout in Apple Health. Deleting a workout in Apple Health does not automatically delete the local Track ECG recording.

Removing Track ECG can remove recordings stored only within the app. Copies in device backups, Apple Health, and export destinations must be managed separately.

## Third-party services

Track ECG uses the Polar BLE SDK and Apple's Bluetooth, location, HealthKit, StoreKit, and sharing services. Apple and any export destination handle information according to their respective policies.

## Medical use

Track ECG records and displays measurements. It is not intended to diagnose or treat a medical condition.

## Questions and updates

For general questions, use the [support repository](https://github.com/aidanjmaldonado/trackecg-support). Do not share private health data in public issues. Updates to this policy will be published here with a revised effective date.
