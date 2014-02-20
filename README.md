*This repository is a mirror of the [component](http://component.io) module [gamtiq/object-create-shim](http://github.com/gamtiq/object-create-shim). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/gamtiq-object-create-shim`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# object-create-shim

Simple shim for ECMAScript 5 Object.create

## Installation

Install component:

    npm install -g component

Then:

    component install gamtiq/object-create-shim

## Usage

    var create = require("object-create-shim");
    ...
    var obj1 = Object.create(someParent1);
    var obj2 = create(someParent2);

## Licence

MIT

