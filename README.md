# podForceUpdate
CocoaPods Cleanup and Setup Process
To clean up and set up CocoaPods:

```sh
rm -rf ~/Library/Caches/CocoaPods Pods ~/Library/Developer/Xcode/DerivedData/* 
pod deintegrate 
pod setup 
pod install
