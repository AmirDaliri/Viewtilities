# Viewtilities

**Viewtilities** is a collection of `UIView` utilities. It provides useful extensions that will speed up your workflow
when building your UI.

[![Version](https://img.shields.io/cocoapods/v/Viewtilities.svg?style=flat)](https://cocoapods.org/pods/Viewtilities)
[![License](https://img.shields.io/cocoapods/l/Viewtilities.svg?style=flat)](https://cocoapods.org/pods/Viewtilities)
[![Platform](https://img.shields.io/cocoapods/p/Viewtilities.svg?style=flat)](https://cocoapods.org/pods/Viewtilities)


## Examples
**Round Corners**
```
myView.round(corners: [.all], to: 10)
```
<div style="text-align:center">
<img width="200" alt="round" src="https://user-images.githubusercontent.com/12258850/51417075-6bb40300-1b4a-11e9-8c20-ef2830852d8d.png">
</div>

**Shadow**
```
myView.shadow(offset: .init(width: 0, height: 2), radius: 5, opacity: 0.5)
```
<div style="text-align:center">
<img  width="200" alt="round shadow" src="https://user-images.githubusercontent.com/12258850/51417074-6bb40300-1b4a-11e9-8b90-27ff96188699.png">
</div>

**Border**
```
myView.border(color: .black, width: 1)
```
<div style="text-align:center">
<img width="200" alt="border" src="https://user-images.githubusercontent.com/12258850/51417073-6bb40300-1b4a-11e9-852b-81ca10413dc5.png">
</div>

## Installation

Viewtilities is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'Viewtilities'
```
Then run pod install.

Don't forget to import `Viewtilities` in every file you'd like to use `Viewtilities`.

## Author

gtokman, hello@garytokman.me

## License

Viewtilities is available under the MIT license. See the LICENSE file for more info.
