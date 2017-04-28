# MGTwitterVideoUploader 🐦

[![Version](https://img.shields.io/cocoapods/v/MGTwitterVideoUploader.svg?style=flat)](http://cocoapods.org/pods/MGTwitterVideoUploader)
[![License](https://img.shields.io/cocoapods/l/MGTwitterVideoUploader.svg?style=flat)](http://cocoapods.org/pods/MGTwitterVideoUploader)
![iOS 8.0+](https://img.shields.io/badge/iOS-8.0%2B-blue.svg?style=flat-square)
![Swift 3.0+](https://img.shields.io/badge/Swift-3.0%2B-orange.svg?style=flat-square)

## Installation

### CocoaPods

MGTwitterVideoUploader is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'MGTwitterVideoUploader'
```

### Manual

Drop the classes inside of MGTwitterVideoUploader/Classes into your project.

## Usage

```swift
let twitterUploader = MGTwitterVideoUploader()
twitterUploader.successCallback = { message in
// Handle success
}
twitterUploader.errorCallback = { error in
// Handle error
}

twitterUploader.postVideo(videoURL: URL(fileURLWithPath: videoPath), withStatus: textView.text)
```

## Project Details

### Requirements
* Swift 3.0
* Xcode 8.0+
* iOS 8.0+

### Contributing
Feel free to collaborate with ideas 💭, issues ⁉️ and/or pull requests 🔃.

If you use MGTwitterVideoUploader in your app I'd love to hear about it and feature your animation here!

### Author

Marcos Griselli | <a href="url"><img src="./Resources/twitterIcon.png" height="15" width="17" ></a> [@marcosgriselli](https://twitter.com/marcosgriselli)


[![Twitter Follow](https://img.shields.io/twitter/follow/marcosgriselli.svg?style=social)](https://twitter.com/marcosgriselli)

### License

> Copyright (c) 2017 Marcos Griselli

> Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

> The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
