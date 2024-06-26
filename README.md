# Overview
This is a collection of pre-built library dependencies for LÖVE on Apple platforms.

## Versions

This repository uses git tags for the library dependencies of a specific released version of LÖVE.

For in-development versions of LÖVE, there may be a branch in this repository corresponding to a similar branch in the love repository.

## Building LÖVE for macOS
Get this repository as well as [love2d/love](https://github.com/love2d/love).

Move, copy, or symlink the `love-apple-dependencies/macOS/Frameworks` folder into the `love/platform/xcode/macosx` folder (making sure that the `Frameworks` folder is visible inside the `macosx` folder).

Open `love.xcodeproj` in `love/platform/xcode` and build the `love-macosx` target.

## Building LÖVE for iOS
Get this repository as well as [love2d/love](https://github.com/love2d/love).

Move, copy, or symlink the `love-apple-dependencies/iOS/libraries` folder into the `love/platform/xcode/ios` folder (making sure that the `libraries` folder is visible inside the `ios` folder).

Open `love.xcodeproj` in `love/platform/xcode` and build the `love-ios` target.
