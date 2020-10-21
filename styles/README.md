# html & tooling - sass

Live version: lewd-steel.surge.sh (plz use on a desktop)

I really hit a big creative block for this guide and decided to try to demonstrate sass features using fruits and vegetables using grids...
The aspects I found neatest working with sass were:

* Nested blocks
* Variables for commonly used values such as colors and sizes
* Split up sections in different files such as header and footer
* Extend, lets selectors 'inherit' properties from another selector (currently not using that)
* Mathematical operators such as +, -, /, * and % allow calculations within the css file
* Mixins, sort of functions in css that allow you to pass in parameters into css blocks.

The main thing I took away from this exercise is how you can reuse blocks of styles and insert new values for them by using mixins for example.
And the capability of seperating the css in different files helps keeping the styles organized.