# RecordARFace
[![Platform](https://img.shields.io/cocoapods/p/RecordARFace.svg?style=flat)](https://cocoapods.org/pods/RecordARFace)
![arkit](https://img.shields.io/badge/ARKit-2.0-brightgreen.svg) 
![swift](https://img.shields.io/badge/swift-4.2-orange.svg) 
[![Version](https://img.shields.io/cocoapods/v/RecordARFace.svg?style=flat)](https://cocoapods.org/pods/RecordARFace)
[![License](https://img.shields.io/cocoapods/l/RecordARFace.svg?style=flat)](https://cocoapods.org/pods/RecordARFace)

## Introduction

0.5 ~ I added the input program of the keyboard with my eyes.
To change the mode of AR, please light the space, then track your face and eyes.

It is in the sample ViewDidload.

### Calculator function
```ruby
cView.onlyCalculator()
```

### keyboard function
```ruby
cView.onlyEyeData() 
```

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.
It operates on actual machine.
We can authenticate the face, mask the face with AR, and record the masked image.

Face tracking is available only on iOS devices with a front-facing TrueDepth camera (see iOS Device Compatibility Reference). 

The function of tracking eye movements can be confirmed on the actual machine from ios 12.

## Image
<img src="https://user-images.githubusercontent.com/16457165/50737574-57990900-120e-11e9-9f7e-ac8d030757a8.gif"  width="330" height="720"><img src="https://user-images.githubusercontent.com/16457165/50793605-1b4bd280-130c-11e9-89bb-3db584ce6108.png" width="330" height="720">

<img src="https://user-images.githubusercontent.com/16457165/52259146-0d1dc000-2965-11e9-9860-232657a7ba9d.gif"  width="330"  height="720"><img src="https://user-images.githubusercontent.com/16457165/54484843-70c6d180-48b1-11e9-93c5-9968d8dac99b.gif"  width="330"  height="720">
## Installation

RecordARFace is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'RecordARFace'
```

## Author

daisukenagata, dbank0208@gmail.com

## License

RecordARFace is available under the MIT license. See the LICENSE file for more info.
