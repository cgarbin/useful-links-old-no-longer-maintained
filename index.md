---
layout: default
---

# Mobile Development
	
## iOS

* Best training: [Stanford class](http://web.stanford.edu/class/cs193p/cgi-bin/drupal/) 
* Best tutorials: [Ray Wenderlich site](https://www.raywenderlich.com/)
* [Open source libraries](https://maniacdev.com/) 
* WWDC transcripts, searchable
   * [From Apple, covers 2015+](https://developer.apple.com/search/?q=wwdc&type=Videos)
   * [Independent, covers older WWDCs](http://asciiwwdc.com/) 
* [Usage stats (unofficial)](https://david-smith.org/iosversionstats/) 
   * [Official, but not updated as often](https://developer.apple.com/support/app-store/) 
* iOS 9
   * [iOS 9 sampler](https://github.com/shu223/iOS-9-Sampler)
* Auto-layout
   * [Great hands-on tutorial](http://www.raywenderlich.com/113768/adaptive-layout-tutorial-in-ios-9-getting-started) 
   * [Stack view in iOS 9](http://www.raywenderlich.com/114552/uistackview-tutorial-introducing-stack-views) 
* [How different screen resolutions work](http://www.paintcodeapp.com/news/iphone-6-screens-demystified)
* UI performance
   * [User interface: offscreen rendering, alpha channels, shadows](https://yalantis.com/blog/mastering-uikit-performance/)
* [Objective C 2015 changes: generics, nullability](https://medium.com/the-traveled-ios-developers-guide/objective-c-in-2015-3cb7dab3690c) 
* Code guidelines/recommendations
   * [Futurice](https://github.com/futurice/ios-good-practices) 
* Patterns for large apps
   * [MVVM](https://www.objc.io/issues/13-architecture/mvvm/) 
   * [Other patterns](http://khanlou.com/2014/09/8-patterns-to-help-you-destroy-massive-view-controller/) 
      * Somewhat old
* Swift
   * [Functional programming in Swift](https://www.raywenderlich.com/82599/swift-functional-programming-tutorial)

## Android

* [Google's training site](https://developer.android.com/training/index.html) 
* [Usage stats](https://developer.android.com/about/dashboards/index.html)
* [Android M](https://developer.android.com/preview/index.html)

## Cross platform

* [Good Smashing Magazine article on combining native and web, with a real-life example](https://www.smashingmagazine.com/2016/02/building-first-class-app-leverages-website-case-study/) 
* [Smashing Magazine's comparison of native, PhoneGap (Cordova), Appcelerator (somewhat dated - 2013)](http://www.smashingmagazine.com/2013/11/four-ways-to-build-a-mobile-app-part1-native-ios/) 
* [Matching the platform's user experience](https://medium.com/space-camp/cross-platform-uis-for-mobile-meteor-apps-6f12b583b205) 

### Cordova

* [Cordova main site](https://cordova.apache.org/)
* [Tutorial](https://ccoenraets.github.io/cordova-tutorial/)

### Reactive Native

* [Reactive native main site](http://www.reactnative.com/)
* Tutorials:
   * [Facebook](https://facebook.github.io/react-native/docs/tutorial.html) 
   * [Ray Wenderlich](http://www.raywenderlich.com/99473/introducing-react-native-building-apps-javascript) 
* Other articles
   * [https://www.smashingmagazine.com/2016/04/consider-react-native-mobile-app/]
* Supports Android as of Sep/2015
* Doesn't support table views? That's a bummer for iOS… UIs won't look close to the native UIs.
   * https://github.com/facebook/react-native/issues/332

### ionic

* [ionic main site](http://ionicframework.com/)
* [ionic2 in beta](http://blog.ionic.io/announcing-ionic-framework-2-beta/)
   * Using AngularJS2
* [Tutorials](http://ionicframework.com/getting-started/) 
   * [The ionic book](http://ionicframework.com/docs/guide/) 
   * [Crash course video (one year old)](https://www.youtube.com/watch?v=C-UwOWB9Io4&feature=youtu.be) 
* Emphasis on good UI design
* Built on top of Cordova and AngularJS
   * [Hybrid](https://www.airpair.com/javascript/posts/switching-from-ios-to-ionic) 
* [Share apps with other users (e.g. testers)](http://view.ionic.io/) 

### Meteor

* [Meteor main site](https://www.meteor.com/)
* Offers also the backend, not only the app side (based on Node.js)
* Offers its own framework (blaze), but also claims to integrate with AngularJS and React Native
* [Somewhat old thread on it](https://news.ycombinator.com/item?id=8651367) 

### Xamarin

* https://xamarin.com/ 
* C# (pretty much everything else is JavaScript)
* Also targets the desktop (Windows and Mac)
* [Paid](https://store.xamarin.com/) (per developer, per device platfrom)

### NativeScript

* https://www.nativescript.org/
* [Review from a developer](http://www.agingcoder.com/programming/2015/10/15/second-thoughts-on-nativescript-react-native-and-mobilenativejavascript-in-general/) 
* [Backed by Telerik](http://www.telerik.com/nativescript/faq)
* Difference to Cordova, according to the FAQ
   * PhoneGap framework is using the browser's layout and rendering engine to display the UI of the application. NativeScript is using the native platform default rendering and layout engine to display the UI of the application. This means that the applications using NativeScript framework are exposing exactly the same UX as natively written applications. The other major difference is that with PhoneGap model you need to write a plugin to access the native capabilities of the platform, while with NativeScript the native APIs are available out of the box.
* [Compared to Ionic](https://blog.nraboy.com/2015/11/nativescript-vs-ionic-framework-should-you-switch/) 

## Mobile web development test

* http://mobiletest.me/ - specific device testing, paid, 30-day trial
* https://developer.chrome.com/devtools/docs/device-mode - Chrome device emulation mode
* https://www.google.com/webmasters/tools/mobile-friendly/ 
* https://validator.w3.org/mobile/ 
* http://ready.mobi/ 

## Articles

* http://www.smashingmagazine.com/2015/09/rapid-app-development-buzzworthy-spelling-bee-app/
* https://www.airpair.com/javascript/posts/switching-from-ios-to-ionic 


# Web Development
	
## General training

* [Udacity](https://www.udacity.com/courses/web-development) 
* http://www.frontendhandbook.com/index.html 
* https://github.com/maxogden/art-of-node 

## JavaScript

* Best references
   * [Eloquent JavaScript (learning)](http://eloquentjavascript.net/) 
   * [Mozilla](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide)
* Quick scripting
   * https://jsfiddle.net/ 
   * http://codepen.io/ 
* New features in ES6
   * [Overview, comparing with ES5](http://es6-features.org/#PromiseCombination) 
   * Promises: how are they different from callback? 
      * Guaranteed execution; chaining; better error handling
      * [HTML5 tutorial](http://www.html5rocks.com/en/tutorials/es6/promises/) 
      * [Parse's what's so great](http://blog.parse.com/learn/engineering/whats-so-great-about-javascript-promises/) 
      * [Stackoverflow's "just callbacks"](http://stackoverflow.com/questions/22539815/arent-promises-just-callbacks) 

## CSS

* [Browser support - caniuse](http://caniuse.com/) 
* [CSS Tricks](https://css-tricks.com/)
* [Mind blowing CSS](https://css-tricks.com/how-i-live-coded-my-most-hearted-codepen-demo/) 
* LESS vs. Sass
   * [Comprehensive](https://css-tricks.com/sass-vs-less/) 
   * [Side by side](https://gist.github.com/chriseppstein/674726) 

## HTML5

* [Browser support](http://caniuse.com/) 
* [Mobile support](http://mobilehtml5.org/) 

## AngularJS

* [Tutorial](https://docs.angularjs.org/tutorial) 
* [What is so good in AngularJS?](https://www.airpair.com/#6-1-the-good-parts) 
   * Two-way data binding
   * Backed by Google, constantly improving
   * Lots of community activity around it
   * Seems to force a better separation of concerns from the start
* [Comparison with other frameworks](https://www.airpair.com/js/javascript-framework-comparison) 
* What is new in AngularJS 2.0?
   * [Overview](http://ng-learn.org/2014/03/AngularJS-2-Status-Preview/#what_is_angularjs_20_all_about) 
      * If you do it right on mobile, if you tackle loading times, performance and other mobile challenges first, then desktop becomes a much easier task.
   * [Mobile first !!](http://angularjs.blogspot.com/2014/03/angular-20.html) 
* AngularJS + Bootstrap: 
   * https://scotch.io/tutorials/how-to-correctly-use-bootstrapjs-and-angularjs-together 
   * http://mgcrea.github.io/angular-strap/# 
* [Angular and React comparison](https://medium.com/@housecor/angular-2-versus-react-there-will-be-blood-66595faafd51#.i80t0u66y) 

## ReactJS

* [Tutorial](https://scotch.io/tutorials/learning-react-getting-started-and-concepts) 
* How does this compete with AngularJS?
   * Backed by Facebook (vs. AngularJS backed by Google)
   * Seems to concentrate more on the UI part
   * JSX: HTML mixed with JavaScript
   * Virtual DOM: selective rendering of subtrees - only what has changed
   * React can be rendered on the server
      * Good for SEO
   * https://www.codementor.io/reactjs/tutorial/react-vs-angularjs 

## electron

* http://electron.atom.io/ 
* Tutorials
   * [Quick start](https://github.com/atom/electron/blob/master/docs/tutorial/quick-start.md) 
   * [All tutorials](https://github.com/atom/electron/tree/master/docs/tutorial) 
* Deploy JavaScript as a desktop app - packages Chromium
* Microsoft Visual Studio Code uses it
* How to encapsulate the app? How big is it? How to update it?

## Node.js/io.js

* [Learning](http://eloquentjavascript.net/20_node.html) 
* Is Dart an alternative or something else?
   * Not clear. Best resource so far for [comparison](https://www.youtube.com/watch?v=NHsmiY0rFS8) 

## Polymer/web components

* [Why is this better than an AngularJS directive?](http://www.binpress.com/blog/2014/06/26/polymer-vs-angular/) 
   * Polymer encapsulates styles (JS + HTML + CSS). AngularJS directive don't do that (but may in the future).
* Polymer catalogs:
   * https://www.polymer-project.org/1.0/ 
   * https://customelements.io/ 
* Polymer starter kit: https://developers.google.com/web/tools/polymer-starter-kit/ 
* How is this different from AngularJS directives?
   * AngularJS doesn't encapsulate the HTML/CSS, so not self-contained UI element
   * But AngularJS 2.0 may get closer to web components or at least use them as part of the framework
   * [Polymer vs. AngularJS](http://www.binpress.com/blog/2014/06/26/polymer-vs-angular/) 

## Polyfill

* Cross-browser compatibility (not only, but mostly)
* [List of lots of them](https://github.com/Modernizr/Modernizr/wiki/HTML5-Cross-Browser-Polyfills) 
   * Watch for license model

## Web development test

* [Browser stack](https://www.browserstack.com/)

# Design (interaction, VD)	

## Key terms

* Discoverability: ability to find key information
* Affordance: how the user perceives that an action is possible (cultural conventions, constraints, …), also used to say that a control behaves as its appearance suggests it behaves
   * Donald Norman says it's been [used out of context](http://www.jnd.org/dn.mss/affordances_and.html) 
   * https://www.interaction-design.org/literature/book/the-glossary-of-human-computer-interaction/affordances 

## References

* [Smashing Magazine](http://www.smashingmagazine.com/)
   * The best site for client developmetn, if you are allowed to pick only one 
* Apple videos
   * [Designing intuitive user experiences](https://developer.apple.com/videos/wwdc/2014/#211)   
   * [Design with animation](https://developer.apple.com/videos/wwdc/2015/?id=803) 
* [Nielsen Group](http://www.nngroup.com/articles/) 
   * [The iconic article: how people read on the web](http://www.nngroup.com/articles/how-users-read-on-the-web/) 
* [Fastco Design](http://www.fastcodesign.com/)
   * Generic design, not only computers

## Books and other training material

* Books
   * The Design of Everyday Things
   * Don't Make Me Think (and Rocket Surgery Made Easy)
      * [Summary (unofficial)](http://www.uxbooth.com/articles/10-usability-lessons-from-steve-krugs-dont-make-me-think/) 
      * https://www.sensible.com/dmmt.html
      * Also offers one-day workshops on usability test
   * About Face
   * Designing with the Mind in Mind
* Other material
   * http://uxoslo.com/2014/01/27/5-brilliant-ted-talks-that-will-make-you-a-better-ux-designer/ 
   * https://www.thoughtworks.com/insights/blog/how-become-great-ux-designer-5-easy-steps 

## Sample from other apps

* [UA archives](http://uxarchive.com/ (updates seems to have been far and between?))
* [Mobile Patterns[(http://www.mobile-patterns.com/) 
* http://pttrns.com/ 
* http://inspired-ui.com/ 
* http://androidniceties.tumblr.com/ 
* http://androidpttrns.com/ 
* http://zurb.com/patterntap 

## Responsive design/adaptive design 

Progressive enhancement; graceful degradation

* The basics:
   * Everything resizable
   * Hide content (add navigation to get to it)
   * But… Should also not even serve assets that are not applicable to a device, e.g. large image for small device
* Media queries
   * https://developer.mozilla.org/en-US/docs/Web/CSS/Media_Queries/Using_media_queries 
   * https://developers.google.com/web/fundamentals/layouts/rwd-fundamentals/use-media-queries?hl=en 
* Responsive vs. adaptive
   * http://www.fastcodesign.com/3038367/9-gifs-that-explain-responsive-design-brilliantly
      * Best explanation ever
   * https://developer.mozilla.org/en-US/Apps/Design/UI_layout_basics/Responsive_design_versus_adaptive_design 
      * Responsive design works on the principle of flexibility. The idea is that a single fluid design based upon media queries, flexible grids, and responsive images can be used to create a user experience that flexes and changes based on a multitude of factors. The primary benefit is that each user experiences a consistent design. One drawback is a slower load time.
      * Adaptive design is more like the modern definition of progressive enhancement. Instead of one flexible design, adaptive design detects the device and other features, and then provides the appropriate feature and layout based on a predefined set of viewport sizes and other characteristics. This can result in a lack of consistency across platforms and devices, but the load time tends to be faster.
* Progressive enhancement degradation
   * http://www.w3.org/wiki/Graceful_degradation_versus_progressive_enhancement 
* Guidelines, patterns
   * http://bradfrost.com/blog/web/responsive-nav-patterns/
      * http://bradfrost.com/blog/web/complex-navigation-patterns-for-responsive-design/
   * http://www.smashingmagazine.com/2011/01/guidelines-for-responsive-web-design/ 
      * Good theory mixed with code
   * https://developers.google.com/web/fundamentals/layouts/rwd-fundamentals/index?hl=en
      * More direct advice for implementation
      * See also Udacity class referred to in the article
   * http://www.1stwebdesigner.com/overview-of-breakpoints-in-responsive-web-design/
      * Somewhat simple, but good as a short overview of breakpoints

## Prototyping

* Invision
   * Supports chat for reviews
   * [Will add animation](http://blog.invisionapp.com/motion-prototypeanimation/) 
   * [Will add styles, can export them](http://blog.invisionapp.com/insight-ui-designers-developers-collaboration/)
* [Atomic](https://atomic.io/) -- launched Sep/2015
   * Compared to Invision: supports animation and version control

## Onboardig + teaching marks

* Submit video to the app store! Free training, accessible to everyone.
* http://www.smashingmagazine.com/2014/08/mobile-onboarding-beginners-guide/
* http://www.mobile-patterns.com/coach-marks 
* http://uxarchive.com/tasks/onboarding 
* http://inspired-ui.com/tagged/coach_marks 

## Anticipatory design

* Fewer choices
   * Anticipatory design is fundamentally different: decisions are made and executed on behalf of the user. The goal is not to help the user make a decision, but to create an ecosystem where a decision is never made—it happens automatically and without user input. The design goal becomes one where we eliminate as many steps as possible and find ways to use data, prior behaviors and business logic to have things happen automatically, or as close to automatic as we can get.
* [Fewer choices](http://www.fastcodesign.com/3045039/the-next-big-thing-in-design-fewer-choices) 
* [Smashing Magaize article](http://www.smashingmagazine.com/2015/09/anticipatory-design/)

## Design with personas

* https://www.interaction-design.org/literature/book/the-encyclopedia-of-human-computer-interaction-2nd-ed/personas
   * See article for some cons as well
* http://www.smashingmagazine.com/2014/08/a-closer-look-at-personas-part-1/ 

## Checklist for UX review

* Who are the target personas or actors?
* How often will they use it?
* What is the mental model of the user?
* What is the context? Laptop in the office, or mobile on the road?
* What is the prioritization of the flow?
* What are the goals? 

## Articles

* [Microinteractions](https://medium.com/ux-planet/microinteractions-the-secret-to-great-app-design-4cfe70fbaccf#.2rgvzpb7o)

# Data Visualization	

* [D3](http://d3js.org/)
* [Edward Tufte](http://www.edwardtufte.com/tufte/)
* [Flowing Data](http://flowingdata.com/) 
* [Information is beatiful](http://www.informationisbeautiful.net/) 
* [Junk charts](http://junkcharts.typepad.com/) 
* [Data visualization](http://datavisualization.ch/) 
* [Chart porn](http://chartporn.org/) 
* [Cool infographics](http://www.coolinfographics.com/) 

# General

## RESTful APIs

* [Great tutorial](http://www.drdobbs.com/web-development/restful-web-services-a-tutorial/240169069?pgno=1) 

## Best places to learn

* [Codecademy](https://www.codecademy.com/) 
* [Udacity](https://www.udacity.com/)

## Agile

* [Kanban overview and comparison with Scrum](https://www.atlassian.com/agile/kanban)
