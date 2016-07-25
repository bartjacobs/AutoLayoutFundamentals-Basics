### Auto Layout Fundamentals: Basics

#### Author: Bart Jacobs

Apple introduced Auto Layout several years ago during WWDC. Before the introduction of Auto Layout, developers programmatically laid out the user interface, positioning views by defining their frames and autoresizing masks.

The downside of this approach is obvious. Every view in the view hierarchy needed to be positioned and the positions recalculated for every change, such as a rotation of the device. Before Auto Layout, that was the only option for developers.

Auto Layout is a layout system that is **descriptive** and built on **constraints**. The developer tells the **layout engine** how to lay out the user interface. Instead of telling the layout engine that a button needs to be positioned at a specific location, the developer describes where it should be positioned.

A layout is defined by constraints. To position a label in the top left of its parent view, constraints are applied that describe the position of the label. The layout engine takes the constraints, transforms them into linear equations, and sets the frames of the elements of the user interface. This approach only works if the constraints eliminate any ambiguity about the position of the label. Under the hood, the label is positioned by setting its frame.

Auto Layout describes the position of a user interface element, regardless of the device model or orientation. The layout engine inspects the constraints and lays out the user interface.

This tutorial teaches you the basics of Auto Layout. You learn how to define constraints in Interface Builder and resolve issues. Let us get started with a simple project in Xcode.

**Read this article on [Cocoacasts](https://cocoacasts.com/auto-layout-fundamentals-basics/)**.
