# attribute

attribute management

[![attribute](https://nodei.co/npm/modulex-attribute.png)](https://npmjs.org/package/modulex-attribute)
[![NPM downloads](http://img.shields.io/npm/dm/modulex-attribute.svg)](https://npmjs.org/package/modulex-attribute)
[![Build Status](https://secure.travis-ci.org/kissyteam/attribute.png?branch=master)](https://travis-ci.org/kissyteam/attribute)
[![Coverage Status](https://img.shields.io/coveralls/kissyteam/attribute.svg)](https://coveralls.io/r/kissyteam/attribute?branch=master)
[![Dependency Status](https://gemnasium.com/kissyteam/attribute.png)](https://gemnasium.com/kissyteam/attribute)
[![Bower version](https://badge.fury.io/bo/modulex-attribute.svg)](http://badge.fury.io/bo/modulex-attribute)
[![node version](https://img.shields.io/badge/node.js-%3E=_0.10-green.svg?style=flat-square)](http://nodejs.org/download/)

[![browser support](https://ci.testling.com/kissyteam/attribute.png)](https://ci.testling.com/kissyteam/attribute)

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
