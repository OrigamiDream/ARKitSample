ARKit Sample
==============

In this repo you will find a sample application combining OpenTok and ARKit.

The sample uses SceneKit to model and render the virtual world. The OpenTok video stream will be renderer in a SceneKit node.

If you want to know more about the sample, please read [the blog post](https://tokbox.com/blog/build-live-video-app-arkit/) which accompanies this sample

Running the sample
-------------------

* Install OpenTok sdk by using CocoaPods

`$ pod install`

* Gather OpenTok session credencial from your [account portal](https://tokbox.com/account) and fill the that in the `ViewController.swift` file

```swift
let kApiKey = ""
let kToken = ""
let kSessionId = ""
```

* Setup your provisioning profile for Debug at the project page in Xcode

* Run in a real device. Since the sample is using metal, **iOS Simulator is not supported**
