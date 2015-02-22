[js-in-situ-sort-spec](http://aureooms.github.io/js-in-situ-sort-spec)
==

Sorting code bricks for JavaScript.

[![NPM license](http://img.shields.io/npm/l/aureooms-js-in-situ-sort-spec.svg?style=flat)](https://raw.githubusercontent.com/aureooms/js-in-situ-sort-spec/master/LICENSE)
[![NPM version](http://img.shields.io/npm/v/aureooms-js-in-situ-sort-spec.svg?style=flat)](https://www.npmjs.org/package/aureooms-js-in-situ-sort-spec)
[![Bower version](http://img.shields.io/bower/v/aureooms-js-in-situ-sort-spec.svg?style=flat)](http://bower.io/search/?q=aureooms-js-in-situ-sort-spec)
[![Build Status](http://img.shields.io/travis/aureooms/js-in-situ-sort-spec.svg?style=flat)](https://travis-ci.org/aureooms/js-in-situ-sort-spec)
[![Coverage Status](http://img.shields.io/coveralls/aureooms/js-in-situ-sort-spec.svg?style=flat)](https://coveralls.io/r/aureooms/js-in-situ-sort-spec)
[![Dependencies Status](http://img.shields.io/david/aureooms/js-in-situ-sort-spec.svg?style=flat)](https://david-dm.org/aureooms/js-in-situ-sort-spec#info=dependencies)
[![devDependencies Status](http://img.shields.io/david/dev/aureooms/js-in-situ-sort-spec.svg?style=flat)](https://david-dm.org/aureooms/js-in-situ-sort-spec#info=devDependencies)
[![Code Climate](http://img.shields.io/codeclimate/github/aureooms/js-in-situ-sort-spec.svg?style=flat)](https://codeclimate.com/github/aureooms/js-in-situ-sort-spec)
[![NPM downloads per month](http://img.shields.io/npm/dm/aureooms-js-in-situ-sort-spec.svg?style=flat)](https://www.npmjs.org/package/aureooms-js-in-situ-sort-spec)
[![GitHub issues](http://img.shields.io/github/issues/aureooms/js-in-situ-sort-spec.svg?style=flat)](https://github.com/aureooms/js-in-situ-sort-spec/issues)

Example usage:

```js
compare = require( "aureooms-js-compare" ) ;
sort = require( "aureooms-js-in-situ-sort-spec" ) ;

/** quicksort using hoare partitioning */
quicksort = sort.__quicksort__( sort.hoare ) ;

a = [ 1 , 6 , 5 , 3 , 2 , 4 ] ;

quicksort( compare.increasing , a , 0 , a.length ) ;

a ; // [ 1 , 2 , 3 , 4 , 5 , 6 ]

quicksort( compare.decreasing , a , 0 , a.length ) ;

a ; // [ 6 , 5 , 4 , 3 , 2 , 1 ]

// but also

/** binary heapsort */
heapsort = sort.__heapsort__( 2 ) ;
/** ternary heapsort */
heapsort = sort.__heapsort__( 3 ) ;
/** quicksort (lomuto) */
quicksort = sort.__quicksort__( sort.lomuto ) ;
/** dualpivotquicksort (yaroslavskiy) */
quicksort = sort.__dualpivotquicksort__( sort.yaroslavskiy ) ;
/** insertionsort */
insertionsort = sort.insertionsort ;
/** selectionsort */
selectionsort = sort.selectionsort ;
/** bubblesort */
bubblesort = sort.bubblesort ;
```

Reference:

  - https://kluedo.ub.uni-kl.de/frontdoor/index/index/docId/3463

***( forked from [js-sort](https://github.com/aureooms/js-sort) )***
