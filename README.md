# StoreHelper

- [Quick Start](https://github.com/russell-archer/StoreHelper/blob/main/Documentation/quickstart.md) - `StoreHelper` tutorial 
- [Guide](https://github.com/russell-archer/StoreHelper/blob/main/Documentation/guide.md) - `StoreHelper` and `StoreKit2` in-depth
- [Demo](https://github.com/russell-archer/StoreHelperDemo) - Example **Xcode 13** `StoreHelper` project

> **Note: StoreHelper has been tested on Xcode 14 Beta 2 with iOS 16 and seems to work as expected.**

## Overview of StoreHelper

`StoreHelper` is a Swift Package Manager (SPM) package that enables developers to 
easily add in-app purchase support to **iOS 15/macOS 12 SwiftUI** apps.

`StoreHelper` is used to provide in-app purchase support in **Writerly** (iOS/macOS), which is available on the [App Store](https://apps.apple.com/app/writerly/id1143101981?ls=1).

`StoreHelper` provides the following features:

- Multi-platform SwiftUI support for purchasing **Consumable**, **Non-consumable** and **Subscription** products
- Supports **transaction validation**, **pending ("ask to buy") transactions**, **cancelled** and **failed** transactions
- Supports customer **refunds** and management of **subscriptions**
- Provides detailed **transaction information and history** for non-consumables and subscriptions
- Support for direct App Store purchases of **promoted in-app purchases**

## License

MIT license, copyright (c) 2022, Russell Archer. This software is provided "as-is" 
without warranty and may be freely used, copied, modified and redistributed, including 
as part of commercial software. 

See [License](https://github.com/russell-archer/StoreHelper/blob/main/LICENSE.md) for details.

## Requirements

`StoreHelper` uses Apple's `StoreKit2`, which requires **iOS 15**, **macOS 12** and **Xcode 13** or higher.

## Adding the Package to your Project

- Open your project in Xcode
- Select **File > Add Packages...**
- Paste the URL of the `StoreHelper` package into the search box: https://github.com/russell-archer/StoreHelper
- Click **Add Package**
- Xcode will fetch the package from GitHub and then display a confirmation. Click **Add Package**
