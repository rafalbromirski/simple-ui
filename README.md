# Simple.ui

---

### View it online: [demo](http://paranoida.github.com/simple-ui/)

Nope, it's not another framework. This is a set of (IMO) the most popular components used in many web applications. These components can act as a "core" for a fresh development, are fully customizable and the markup is minimal so you can use them as you please. You don't have to worry about browser issues as they were tested against cross-browser & cross-platform compatibility:

- Chrome
- Safari
- Mobile Safari (iDevices)
- Firefox
- Opera
- IE8+

**Simple.ui** works with Ruby on Rails, just copy sass directory content into your `assets/stylesheets` and remove `config.rb`.

---

#### Components:

- **badges**
- **boxes**
- **buttons**
- **inputs**
- **labels**
- **progress bar** - native html5 element (custom appearance only for **webkit** based browser)
- **tables**

#### Core:

- **base**
- **typography**
- **variables** - default values
	- `$ui-base-color`: #000;
	- `$ui-base-color-opposite`: #fff;
	- `$ui-border-width`: 2px;
	- `$ui-font-color`: `$ui-base-color`;
	- `$ui-font-family`: "Helvetica Neue", Helvetica, Arial, "Lucida Grande", sans-serif;
    - `$ui-button-height`: 35px;
    - `$ui-input-height`: `$ui-button-height`;
    - `$ui-select-height`: `$ui-button-height`;
	
	- `$page-width`: 800px;

#### Pages:

- **content** - style rules for particular layout

---


### To do:	

- **Grid** 
- **Icons**

Do you want them?


### Changelog:

- **1.0** - First version released

---

### Preview:


![Simple.ui](http://paranoida.github.com/simple-ui/simpleui.png)

---


## License:

The MIT license

Copyright &copy; 2013 [Rafal Bromirski](http://paranoida.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
