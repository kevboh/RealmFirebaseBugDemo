# RealmFirebaseBugDemo
A demo of an iOS compilation error when using both Realm and Firebase in a react native project

## Steps to Reproduce

1. `react-native init MyProject`
2. `cd MyProject/`
3. `yarn add realm`
4. `react-native link realm`
5. `cd ios/`
6. `pod init` and add `pod 'Firebase/Core'` and `pod 'Firebase/Firestore'` to the Podfile
7. `react-native run-ios`
