# SweetCurtain
A framework that provides CurtainController. CurtainController is a container view controller that implements a content-curtain interface. 

[![Platform](https://img.shields.io/badge/platform-ios-blue.svg?style=flat%20)](https://developer.apple.com/iphone/index.action)
[![Swift 5.1](https://img.shields.io/badge/Swift-5.1-orange.svg?style=flat)](https://developer.apple.com/swift/) 

## Overview
A SweetCurtain framework provides a curtain controller.
A Curtain Controller is a container view controller that manages two child view controllers in a content-curtain interface. In this type of interface, the primary view controller (the content) is covered with the secondary view controller (the curtain).

When building your app’s user interface, the curtain controller is typically the root view controller of your app’s window, but it may be embedded in another view controller. The curtain controller has no significant appearance of its own. Most of its appearance is defined by the child view controllers you install. You can configure the child view controllers using Interface Builder or programmatically using the init(content: curtain:) initializer. The child view controllers can be custom view controllers or other container view controller, such as navigation controllers.

> **Note**: You can push a curtain controller onto a navigation stack. Also, its children can be contained in the navigation controller or tab bar controller.  But remember that curtain always covers the content. For example, if the content embed in the navigation controller, the curtain will cover the navigation bar too.

When displayed onscreen, the curtain controller works with its Delegation objects to manage the content changes and to messaging of its curtain changes.
Also, the curtain controller provides the curtain object to manage the curtain's properties.

## Features
- Coefficient oriented metrics.
- Friendly content changes mechanism.
- Works with storyboard and code.
- So easy to setup and use.
- Compatible with safe area.
- Compatible with scroll view.
- Compatible with horizontal scroll or swipe.
- Designed by the principle of iOS UI components.
