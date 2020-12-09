# tiny
the tiniest npm module

# install
npm install @widelec2/tiny

# usage
const tiny = require("@widelec2/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
