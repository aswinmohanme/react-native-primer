# Introduction to React and Friends

> React is a declarative, efficient, and flexible JavaScript library for building user interfaces.

That's what the official [React](https://reactjs.org/) website defines React, but it's much more.

React is a library \(not a framework\) for building Rich interactive User Interfaces declaratively. React is used extensively by Facebook, Instagram and couple of other high profile sites.

React is highly performant, and it's design encourages reusable code.

## React React

User Interfaces built with React automatically re-render whenever the data that it depends on changes. This makes creating interactive UI's a whole lot easier. Change the data and React takes care of rendering the components that depend on the changed data also called state.

Interfaces made with React basically follow this pattern

* Render using given state
* Change state
* Render using given state

React walks through every rendered component on  the screen and finds out which components depend on the changed state. Then it figures out which components absoultely requires re-rendering and renders them. In the end you get performant user interfaces that React to state changes.

## React Native

React revolutionized the way web application were being built. It bought never before performance to the web world, and broke away from the conventional MVC model that was plaguing Web Application development. It was like the new kid in the block who bought with him new ideas and new fashion to the hood. 

But the Mobile landscape was a different story. 

### Native Curse

Unlike the web where a single code-base can run happily on any supported web browser, you had to have seprate codebases for each platform. Each platform \(namely Android and IOS\*\) had very different programming languages,  seprate developer toolings and seprate librariers. The two codebases even though implementing the same functionalily looked like they were from different species. 

Each function had to be implemented in both platforms in two different languages which lead to the different bugs that slowed down feature additions in large applications. These problems lead to the development of CPMAD.

### Early CPMAD Solutions

In the land of CPMAD's React Native is actually a new comer. There were numerous solutions before it but none got anywhere near the traction that React Native got.

Most were just web applications whose buttons where styled with css to look like crappy Native implementations, that run in a bundled web browser. The performance was horrendeous.

### Where React Native Shines

React Native is just React running on a Native Bridge. The UI Components are implemented separately on the Native side exposed under a unified JavaScript API. We write our code in JS and the native side runs it. This artitecture has numerous benefits.

* Near Native Performance
* Easier Development
* Real Native Look of Application

A React Native app is basically a Native App and you get Cross Platform for free. Any reasons not to learn about it?

It's often said that for React Native we actually need to learn React first. Well for this guide I chose not to put React as a prerequisite, Reac t and React Native are not so different and we can pick up React along the way.



> \\*  Nop Windows  Phone doesn't count here.



