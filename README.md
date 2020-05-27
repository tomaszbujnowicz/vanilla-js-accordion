# 🚀 A dependency-free Vanilla JS accordion

### Accessible Vanilla JS accordion that can be easily enabled/disabled on specific breakpoints.

Based on [Houdini](https://github.com/cferdinandi/houdini) accordion script by Chris.
 
### Requirements

* A browser

* No Node.js, Yarn, NPM, Webpack, Gulp, Parcel, Laravel Mix, etc...

* No dependencies, no automation build tools, nada.  

### Quick start: Installation

Copy/paste and use.

### Why?

I was looking for an accessible Vanilla JS accordion that could be easily enabled/disabled on specific breakpoints. It should be accessible (ARIA attributes) and when destroyed the markup should be restored to its original state.
I didn't find 100% match but I found excellent Houdini accordion script written by Chris that was very close. 

**Changes comparing to the original script:**

* Smooth height animation instead of basic display none/block
* Fix the destroy function so it works properly
* Init/destroy accordion on specific breakpoints using JS resize with debounce function

**For the demo purpose we have the following setup:**

* Accordion is enabled for 768px and below and 1200px and above
* Breakpoints can be easily customized in the theme
* CSS: Autoprefixer online settings: last 2 versions
* Resize to see it in action

## Kudos 👏

All credits should go to [Chris](https://github.com/cferdinandi/houdini)  since he wrote Houdini and I only slightly modified it to fit my needs.

## Copyright and license

Copyright 2020 Tomasz Bujnowicz under the [MIT license](http://opensource.org/licenses/MIT).