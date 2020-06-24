# WWDC 2020

# General Links
- [iOS 14](https://www.apple.com/ios/ios-14-preview/)
- [iPAD OS](https://www.apple.com/ipados/ipados-preview/)
- [Mac](https://www.apple.com/macos/big-sur-preview/)
- [WatchOS](https://www.apple.com/watchos/watchos-preview/)
- [Keynote Summary](https://www.youtube.com/watch?v=_Q8AKghK44M)


# Sections
* [Xcode 12](#Xcode12)
* [SwiftUI](#SwiftUI)
* [Privacy](#Privacy)
* [In App Purchases](#InAppPurchases)


## Xcode 12
 [Xcode what's new](https://developer.apple.com/xcode/whats-new/)
 
 Xcode 12 includes Swift 5.3 and SDKs for iOS 14, iPadOS 14, tvOS 14, watchOS 7, and macOS Big Sur.

 **Universal apps**
   - A single macOS Universal app includes native binaries for Intel-based Macs and Apple Silicon Macs
   - “Any Mac” destination in the toolbar builds a Universal app, even on Intel-based Macs
   Standard Architectures build setting defaults to Universal, and Xcode offers to upgrade your project if needed
   - Run and debug the Intel binary within a Universal app by selecting “My Mac (Rosetta)” on a Developer Transiton Kit (DTK)
   from the Universal App Quick Start Program
   
   >**NOTE**: The default Xcode 12 beta can be used for development of all platforms except new Apple Silicon Macs. 
   A separate download named “Xcode 12 for macOS Universal Apps beta” contains support for macOS Universal apps, and
   can be run on Intel-based Macs as well as the DTK from the Universal App Quick Start Program. A future beta of 
   Xcode 12 will support all platforms, as well as macOS Universal apps within a single product.

 **Refined user interface for macOS Big Sur**
  - Document tabs open any type of document, including logs, asset catalogs, and UI files, in a lightweight editor tab
  - Toolbar, icons, and sidebar designs match the beautiful new aesthetic of macOS Big Sur
  - Navigator fonts track the size of the system setting or can be manually set to a custom size
  - Organizer is completely redesigned and reports new app metrics, such as hitches in animation and scrolling
  
  **Swift and SwiftUI**
  
  - App lifecycle in SwiftUI enables entire apps to be written completely in SwiftUI for iOS, iPadOS, and macOS
  - WidgetKit built on SwiftUI makes it easy to share code for widgets that run on iOS, iPadOS, and macOS
  - SwiftUI performance is improved throughout, and new Lazy views efficiently handle enormous data sets
  - Multiplatform templates make it easy to share SwiftUI code across all Apple platforms, customized for each
  - SwiftUI Views can be turned into reusable components that appear in the Xcode library and in code completions
  - Swift Package Manager supports resources and localizations, making it great for sharing SwiftUI components
  - Improved Swift language diagnostics make it much easier to understand coding mistakes, especially in SwiftUI code

 **Mac Catalyst**
  - Mac idiom displays your app’s user interface in 100% native Mac size and scale for total customization
  - Additional frameworks and controls are available, including HomeKit and AVCapture
  - Keyboard APIs and OS integration make it easier to completely control your app with the keyboard
  - Apps built with Mac Catalyst automatically inherit the new look and feel of macOS Big Sur
  
  **Other improvements**
  - App clips target creates a small, focused experience from your app that installs quickly
  - StoreKit testing framework and transaction manager make it easy to test and debug in-app purchases
 
 [Xcode release notes](https://developer.apple.com/documentation/xcode-release-notes)
 
 
 [Developer Insider - What's new in Xcode 12](https://developerinsider.co/whats-new-in-xcode-12/)
 
 
 ## SwiftUI
 
 [Hacking with Swift - What's new in SwiftUI for iOS 14?](https://www.youtube.com/watch?v=uitE6bmeFxM)
 
 
 ## Privacy
 
 [Apple Just Castrated The IDFA](https://www.forbes.com/sites/johnkoetsier/2020/06/24/apple-just-castrated-the-idfa-sending-an-80-billion-industry-into-upheaval/#47447e6e1389)
 
 
 ## In App Purchases
 
 [StoreKit Testing Improvements in iOS 14](https://www.revenuecat.com/blog/storekit-testing-in-xcode)
