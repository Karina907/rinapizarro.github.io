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



![](/assets/images/swift_2.png){:height="300px"}

{:height="300px"}

```
var body: some View {
     t:String = "Hello Hommies"
     return t.font(
          .largeTitle)
          .bold()
          .foregroundColor(.red) // regular convention
}
```

### Stacks

- Vstack --> vertical
- HStack --> horizontal 
- ZStack --> depth-based stack

![](/assets/images/swift_3.png){:height="300px"}

Vstack and Hstack can be used simulateniously

![](/assets/images/swift_4.png){:height="300px"}

Hstack also supports alignment. It specifies how views within the HStack should be aligned

- bottom
- center
- firstTextBaseLine
- lastTextBaseLine
- top

Now if you want the entire Hstack to be at the top of the screen, then you need a frame()

