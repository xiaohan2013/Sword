# Sword

made SVG super easy.

Examples of introduction [the website](http://alloyteam.github.io/Sword/)

Examples of Application [the website](http://alloyteam.github.io/Sword/china.html) 


# Install

the file is  here: [sword.js](https://raw.githubusercontent.com/AlloyTeam/Sword/master/dist/sword.js) or [sword.min.js](https://raw.githubusercontent.com/AlloyTeam/Sword/master/dist/sword.min.js)

You can also install it via npm:

```html
npm install alloysword
```

Sword can be used in the CommonJS/AMD module definition environment, but also directly through the script tag reference in your page ,such as:

```html
<script src="sword.js"></script>
```

you can get the Sword module by synchronizing require in the AMD module definition environment:

```javascript
define(function (require) {
    var Sword = require('sword');
});
```

or asynchronous require：

```javascript
require([ 'sword' ], function (Sword) {
});
```

or  require in the CommonJS module definition environment:

```javascript
var Sword = require('sword');
```

# Many thanks to
* [observe.js](https://github.com/kmdjs/observejs)

# License
This content is released under the [MIT](http://opensource.org/licenses/MIT) License.
