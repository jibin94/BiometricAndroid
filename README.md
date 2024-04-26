## Android Biometric
3 Different authentication types for biometric authentication:
- Strong: This type of authentication requires the user to provide a strong biometric, like a fingerprint or iris scan, which is harder to fake or bypass. It offers a high level of security and is suitable for apps handling sensitive data or transactions.
- Weak: Weak biometric authentication includes less secure methods like face recognition, which might be easier to bypass or trick compared to strong authentication methods. This type of authentication is suitable for apps with lower security requirements.
- Device credential: This authentication type doesn’t involve biometrics but instead relies on the device’s security, like a PIN, password, or pattern. It can be used as a fallback option when biometric authentication isn’t available or suitable for the user or device.

## Code Overview
- The main logic is implemented in the `MainActivity.java` file.
- `BiometricManager` is used to check the availability and status of biometric authentication.
- `BiometricPrompt` is utilized to handle the authentication process and callbacks.
- The UI is created using XML layout files (`activity_main.xml`).

## Dependencies
- AndroidX Biometric Library: Used for biometric authentication.
- Android Support Library: Provides compatibility for older Android versions.
- Android Material Components: Used for UI components and design.