**Backtick is a console for bookmarklets and scripts**, packaged as a Chrome extension. For a better explanation, try out the demo at [backtick.io/](http://backtick.io). The extension is free to use, but it will occasionally nag you to install the [$5 Backtick license](http://goo.gl/LkPHMG).

*[MIT Licensed](http://opensource.org/licenses/MIT) 2013 Joel Besada*

#### Developing
If you want to play around with the code, you'll want to install [Grunt](http://gruntjs.com/) first. With that installed,
just run `grunt build` to compile everything. You'll then want to import the `dist` folder as an unpacked extension in Chrome.

#### Why are you open sourcing this?
Because that's just something I like to do to contribute back to the community. It also forces me to write cleaner code. (Well, in theory at least)

#### But wait, couldn't I just clone this repo and remove the nag dialog?
Yes, you absolutely could. That's why I've made it [extra easy for you](https://github.com/JoelBesada/Backtick/blob/master/extension/license.coffee#L2), just flip that boolean to true and you're good to go. However, a nicer option would be to actually buy [the license](http://goo.gl/LkPHMG) to support the continued development of Backtick.

