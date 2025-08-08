# DrawBubbleShapesView

**DrawBubbleShapesView** — Drawing message bubbles with tails (like iMessage) and creating custom shapes with ease in your iOS app using Swift.

---

## ✨ Features

- 📦 Simple and lightweight custom UIView subclass
- 💬 Supports message-style chat bubbles with tails
- 🖌️ Easily draw your own shapes programmatically
- 🎯 Built with Swift for iOS

---

## 📦 Installation

### CocoaPods

To install it using [CocoaPods](https://cocoapods.org), add the following line to your `Podfile`:

```ruby
pod 'Draw-Custom-Shape-View'
```

Then run:

```bash
pod install
```

---

## 🚀 Usage

### Import the module:

```swift
import Draw_Custom_Shape_View
```

### Example: Create a chat bubble

```swift
let bubbleView = ChatBubbleView(frame: CGRect(x: 50, y: 100, width: 200, height: 80))
bubbleView.tailPosition = .left // or .right
bubbleView.fillColor = .systemBlue
self.view.addSubview(bubbleView)
```

> 💡 You can also subclass and create your own shapes by overriding the draw method.

---

## ✅ Requirements

- iOS 11.0+
- Swift 5.0+

---

## 🙌 Contributions

Pull requests are welcome! Feel free to open issues for suggestions or bugs.

---

## 📬 Contact

Created with by [Paresh Mangukiya](https://github.com/pkmangukiya)
