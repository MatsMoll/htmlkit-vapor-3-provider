# HTMLKit-Vapor-3-Provider

A provider that makes it possible to use [HTMLKit](https://github.com/vapor-community/HTMLKit) with Vapor 3.

## Usage

Add this as a dependencies in your `Package.swift` file.
```swift
.package(url: "https://github.com/MatsMoll/htmlkit-vapor-3-provider.git", from: "1.0.0-beta.3")
...
// And remember to add BootstrapKit to your target
.target(
    name: "YourProject",
    dependencies: ["HTMLKitVaporProvider"]),
```
