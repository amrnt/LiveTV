# LiveTV

Simple OS X application allowing you to watch some live free TV
channels (French, English, Italian).

This product is buggy, mainly for educational purposes and certainly not
maintained. Use it at your own risks.

## Usage

The easy way: 

* download the app: https://github.com/downloads/mattetti/LiveTV/LiveTV.zip
* unzip 
* double click.

The "harder way": 

* install Xcode 4.x
* install MacRuby http://macruby.org
* clone this repo
* compile the app

Compilation info: There are 2 schemes: LiveTV and Deployment.
LiveTV compiles the code in JIT mode and runs it. 
The Deployment scheme compiles AOT the app and insert the MacRuby framework in the app to make it truly standalone.
You first need to build the LiveTV scheme before running the
Deployment scheme.


## Details

The application is a native OS X Cocoa application written in MacRuby
http://macruby.org You can learn more about MacRuby via my book: http://amzn.to/tVx4ng

The code is very simple and straight forward (currently under 100 LOC).
If you decide to help the project, check the TODO list and learn more
about the following Cocoa classes:

* NSOutlineView
* QTMovieView
* QTMovieView
* NSProgressIndicator

## TODO list

* Full screen mode (in the meantime, maximize the window and close the
  outline view).
* Disable screensaver
* Apple remote control support
* Airplay support
* EPG support (to know what's being broadcast, what's coming up next..)
* Recording (not sure QTMovie allows that. Scheduled recordings might also be nice)
* Channel updates via internet
* Add more channels and more languages
* Custom channels (add your own feeds)
* Real time chat (for whoever wants to play with Node.js + Heroku)
* Screenshot
* Multiple simultaneous players (watch 2 soccer games at the same time)
* Misc hacks
* ad supported version so I can become super rich and move back to France (j/k)

## Thanks

Thanks to Patrick Crowley for the current icon, hopefully, we'll come up
with something better ;)
