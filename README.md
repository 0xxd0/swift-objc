# objc-swift

objc-swift is a swift style extension for Cocoa Framework.

- [Extended](#extended)
- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)

## Extended

- Swift let, var support for pure C
- Swift defer support for pure C
- Default Protocol Implementations for Objective-C

## Requirements

- iOS 8.0+ / macOS 10.10+ / tvOS 9.0+ / watchOS 2.0+
- Xcode 8.3+

## Installation

### CocoaPods

To integrate Cocoa.Swift into your Xcode project using CocoaPods, specify it in your `Podfile`:

```ruby
source 'https://github.com/CocoaPods/Specs.git'
platform :ios, '11.0'
use_frameworks!

target '<#Your Target Name#>' do
    pod 'objc-swift', '~> 0.1.0'
end
```

Then, run the following command:

```bash
$ pod install
```

## License

Cocoa.Swift is released under the [MIT licenss](https://github.com/0xxd0/objc-swift/blob/master/LICENSE).
