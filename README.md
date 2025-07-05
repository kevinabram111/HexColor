# HexColor

A simple Swift library that makes it easy to convert hex strings into `UIColor` or `Color` in Swift and SwiftUI.

🟣 Whether you're building UIKit or SwiftUI apps, HexColor helps you streamline color setup using familiar `#RRGGBB` or `#RRGGBBAA` formats.

---

## 🚀 Installation

### ✅ Option 1: Add via Xcode GUI (Recommended)

1. Open your Xcode project.
2. Go to **File** > **Add Packages...**
3. Enter the repository URL: https://github.com/kevinabram111/HexColor.git
4. Select the latest version and click **Add Package**.

> ℹ️ Make sure the `Package.swift` file in your repo uses the **same name as the folder** (i.e., `HexColor`) or the import will fail.

---

### 💻 Option 2: Add via Swift Package Manager (Manual)

If you prefer editing `Package.swift` directly:

```swift
dependencies: [
    .package(url: "https://github.com/your-username/HexColor.git", from: "1.0.0")
]
```

And add "HexColor" as a dependency to your target:

```swift
.target(
    name: "YourTarget",
    dependencies: ["HexColor"]
)
```

## 🎨 Usage

```swift
import HexColor
import SwiftUI

let uiColor = UIColor(hex: "#3498db")
let swiftUIColor = Color(hex: "#3498db")
```

Supports hex codes with:
	•	#RRGGBB
	•	#RRGGBBAA

## 📝 Related Article
Curious about the journey and how this works under the hood?

👉 Read the Medium article here: https://kevinabram1000.medium.com/how-to-build-and-share-your-own-swift-library-with-swift-package-manager-1905fcc4716b

