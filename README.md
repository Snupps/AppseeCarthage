# AppseeCarthage a wrapper for Appsee to use with Carthage

[![](https://img.shields.io/badge/carthage-compatible-brightgreen.svg)](https://github.com/Carthage/Carthage)

##Requirements

**AppseeCarthage** is a dynamic framework, so it requires **iOS 8 or later**

##Installation

You can install the framework using **Carthage** or like a normal embedded framework.

###Carthage

Just add to your *Cartfile*

```
github "Snupps/AppseeCarthage" ~> 2.3

```

##How to use it

First you need to import the Framework:

```swift

import Appsee

```
Appsee's documentation states to start the service like this:

```swift

//Appsee
Appsee.start(....)

```
