Angular Hammer v2
=================

Forked from [angular-hammer](https://github.com/randallb/angular-hammer), updated to support [Hammer.js v1.0.1+](https://github.com/EightMedia/hammer.js).

Within an Angular.js application, allows you to specify custom behaviour on Hammer.js touch events.

Usage, currently as attribute only:

    hm-tap="{expression}"

You can change the default settings by adding a second attribute with options:

    hm-tap-opts="{drag: false, transform: false}"

Include the angular-hammer.js file, and add `hmTouchevents` to your app’s dependencies.

Requires Hammer.js, tested with `v1.0.1 - 2013-02-26`.