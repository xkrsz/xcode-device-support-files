# xcode-device-support-files

## - What is this?
This is a handy solution to a common Xcode error that happens when you run your project on a newer/older device/opearating system.

## - I get it, how do I fix this error?
1. Find your missing platform version in this repo.
2. Download `.zip` of this version.
3. Open Applications on your Mac.
4. Right-click on Xcode -> Open Package Contents.
5. Go to `Contents/Developer/Platforms/<platform-of-your-choice>.platform/DeviceSupport`.
6. Extract downloaded `.zip` here.
7. Restart Xcode.
8. Done!
