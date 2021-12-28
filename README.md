# Overview
This is a collection of pre-built library dependencies for LÖVE on Apple platforms.

# Building LÖVE for macOS
Get this repository as well as [love2d/love](https://github.com/love2d/love).

Move, copy, or symlink the `love-apple-dependencies/macOS/Frameworks` folder into the `love/platform/xcode/macosx` folder (making sure that the `Frameworks` folder is visible inside the `macosx` folder).

Open `love.xcodeproj` in `love/platform/xcode` and build the `love-macosx` target.

# Building LÖVE for iOS
Get this repository as well as [love2d/love](https://github.com/love2d/love).

Move, copy, or symlink the `love-apple-dependencies/iOS/include` and `love-apple-dependencies/iOS/libraries` folders into the `love/platform/xcode/ios` folder (making sure that the `include` and `libraries` folders are visible inside the `ios` folder).

Open `love.xcodeproj` in `love/platform/xcode` and build the `love-ios` target.
