# attribute

attribute management

[![attribute](https://nodei.co/npm/modulex-attribute.png)](https://npmjs.org/package/modulex-attribute)
[![NPM downloads](http://img.shields.io/npm/dm/modulex-attribute.svg)](https://npmjs.org/package/modulex-attribute)
[![Build Status](https://secure.travis-ci.org/modulex/attribute.png?branch=master)](https://travis-ci.org/modulex/attribute)
[![Coverage Status](https://img.shields.io/coveralls/modulex/attribute.svg)](https://coveralls.io/r/modulex/attribute?branch=master)
[![Dependency Status](https://gemnasium.com/modulex/attribute.png)](https://gemnasium.com/modulex/attribute)
[![node version](https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square)](http://nodejs.org/download/)

## example

```javascript
var Attribute = require('modulex-attribute');
var X = Attribute.extend({
},{
    ATTRS:{
        x: {
            getter:function(){
                return 1;
            }
        }
    }
});
var y = new X();
y.get('x') // => 1
```
