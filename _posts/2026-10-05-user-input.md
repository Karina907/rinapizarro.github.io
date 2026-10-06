---
layout: post
title: User Input
categories: swift
description: This guide will teach out handling user input in Swift.
---
### TextField

The TextField is a view that takes user input in an input field. It allows the user to enter from text or numbers, which results in an editable text interface. 

![](/assets/images/swift_6.png){:height:300}

- The first argument is the placeholder Text. This provide information to the user as to what should be entered in the field. 
- There are also State variables. State variables are variables that can be managed locally and contain mutable data with a view. This is important because views are immutable and cannot change their values. However, @State wrapper tells Swift to move the variable's memory storage outside the structure. This basically means that a variable can be changed at runtime. 
- The state variables are bound to the TextField object. As the user updated the TextField, the state variable will also be updated.

