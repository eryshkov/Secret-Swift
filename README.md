#  Secret Swift

<div align = "center">
<img src="/screens/1.jpeg" width="30%">     
<img src="/screens/2.jpeg" width="30%">     
</div>

<p align="center">
<img src="https://img.shields.io/badge/Swift-4.2-orange.svg" alt="Swift 4.2"/>
<img src="https://img.shields.io/badge/Xcode-10%2B-brightgreen.svg" alt="XCode 10+"/>
<img src="https://img.shields.io/badge/platform-iOS-green.svg" alt="iOS"/>
<img src="https://img.shields.io/badge/iOS-12%2B-brightgreen.svg" alt="iOS 12"/>
<img src="https://img.shields.io/badge/licence-MIT-lightgray.svg" alt="Licence MIT"/>
</p>

[Demo video here](https://youtu.be/rG4LznpiASM)

## Main functionality
* simple keychain app with TouchID and FaceID authentication
* uses `LocalAuthentication`
* using `adjustForKeyboard()` method
* uses `KeychainWrapper`
* uses observer for `willResignActiveNotification` event
* uses `LAContext`, `canEvaluatePolicy` and `evaluatePolicy` with `.deviceOwnerAuthenticationWithBiometrics`

## License

This project is licensed under the MIT License.