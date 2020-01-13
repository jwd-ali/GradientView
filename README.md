# GradientView
Use gradient easily from interface builder or code.

![CocoaPods](https://cocoapod-badges.herokuapp.com/v/GradientViewInspectable/badge.png)

<p align="center">
<a href="https://imgflip.com/gif/3lyjwq"><img src="https://i.imgflip.com/3lyjwq.gif" title="Gradient View"/>
</p>


Installation
------------

Use [CocoaPods](http://cocoapods.org).

```ruby
pod 'GradientViewInspectable'
```
Usage
-----
In code 

```swift
     let view = GradientView(frame: CGRect(x: 0, y: 50, width: 50))
     view.startColor = .blue   
     view.startColor = viewColor.topColor
     view.endColor = viewColor.bottomColor
```

In Interface builder
```
Change view class to GradientView and you are good to go.
```

License
-------

GradientViewInspectable is under [MIT](https://opensource.org/licenses/MIT). See [LICENSE](LICENSE) file for more info.
