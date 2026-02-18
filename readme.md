# uBerscore v0.0.18

[![Build Status](https://travis-ci.org/anodynos/uBerscore.png)](https://travis-ci.org/anodynos/uBerscore)
[![Up to date Status](https://david-dm.org/anodynos/uBerscore.png)](https://david-dm.org/anodynos/uBerscore)

An anorthodox, extensible, overloaded, experimental facade of *underscore* facilities & leftovers.

uBerscore.js offers some functionality that underscore/lodash doesn't have (or didn't have at the time of authoring) - its highly build around the great `_`.

Sorry, no documentation before 0.1.x and some features might change.

But do see:

* [`Gruntfile.coffee`](https://github.com/Unity-Billal-mesloub/uBerscore/blob/main/Gruntfile.coffee) written with the wicked [uRequire](https://github.com/Unity-Billal-mesloub/uRequire) configuration, that builds uBerscore's modules in a number of ways, with the most DRY config ever.

Note: [uBerscore-dev.js](https://github.com/Unity-Billal-mesloub/uBerscore/blob/main/build/dist/uberscore-dev.js) and its minified brother are running on the WEB (both with AMD and as plain `<script/>`) and in nodejs through the single-file 'combined' conversion [uRequire](https://github.com/Unity-Billal-mesloub/uRequire) with no other dependencies (but 'lodash').

* [`blending/Blender`](https://github.com/Unity-Billal-mesloub/uBerscore/blob/main/source/code/blending/Blender.coffee) that powers [uRequire](https://github.com/Unity-Billal-mesloub/uRequire)'s versatile [configuration deriving](http://urequire.org/masterdefaultsconfig.coffee#deriving) to get some ideas.

* The wicked [`isEquals/isIquals/isExact/isLike`](https://github.com/Unity-Billal-mesloub/uBerscore/blob/main/source/code/objects/isEqual.coffee), that adds options to `_.isEqual`


