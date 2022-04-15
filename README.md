# AppleDeviceKit

This is the library that contains nothing but `AppleDevice` Enum with sizes and some meta info for each device. All IPhone, IPad, IPod Devices are covered

# Installation - SPM Only

```bash
https://github.com/paigeshin/AppleDeviceKit
```

# Properties

- logicalWidth => The value you get with `UIScreen.main.bounds`
- logicalHeight => The value you get with `UIScreen.main.bounds`
- physicalWidth
- physicalHeight
- ppi
- scaleFactor
- screenDiagonal
- release

# How to use

```swift
let device = AppleDevice.iPad1stgen
device.logicalHeight
device.logicalWidth
device.release
```
