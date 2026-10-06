---
layout: post
title: SwiftUI Basics
categories: swift
description: This post will cover the basics of SwiftUI
---
### ContentView.html

- defines structure of UI screen
- uses view protocol (thus, it must use body property of type view)
- body must return a single instance of view (example. string)

![](/assets/images/swift_1.png){:height="300px"}

### Modifiers

- Modifiers are a function that that you apply to a view or the output of another modifier. For example, the modifier .largeTitle belongs to the Front class. In the example below, we have transformed our preceeding code to include the modifier.



![](/assets/images/swift_2.png)

{:height="300px"}

```
var body: some View {
     t:String = "Hello Hommies"
     return t.font(
          .largeTitle) // regular convention
}
```

