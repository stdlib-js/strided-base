<!--

@license Apache-2.0

Copyright (c) 2020 The Stdlib Authors.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

-->

# Base

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Base strided.

<section class="installation">

## Installation

```bash
npm install @stdlib/strided-base
```

</section>

<section class="usage">

## Usage

```javascript
var ns = require( '@stdlib/strided-base' );
```

#### ns

Base strided.

```javascript
var o = ns;
// returns {...}
```

The following functions are currently exported:

<!-- <toc pattern="*"> -->

<div class="namespace-toc">

-   <span class="signature">[`binary( arrays, shape, strides, fcn )`][@stdlib/strided/base/binary]</span><span class="delimiter">: </span><span class="description">apply a binary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`dmap( N, x, strideX, y, strideY, fcn )`][@stdlib/strided/base/dmap]</span><span class="delimiter">: </span><span class="description">apply a unary function accepting and returning double-precision floating-point numbers to each element in a double-precision floating-point strided input array and assign results to a double-precision floating-point strided output array.</span>
-   <span class="signature">[`dmskmap( N, x, strideX, mask, strideMask, y, strideY, fcn )`][@stdlib/strided/base/dmskmap]</span><span class="delimiter">: </span><span class="description">apply a unary function accepting and returning double-precision floating-point numbers to each element in a double-precision floating-point strided input array according to a corresponding element in a strided mask array and assign results to a double-precision floating-point strided output array.</span>
-   <span class="signature">[`mapBy( N, x, strideX, y, strideY, fcn, clbk[, thisArg] )`][@stdlib/strided/base/map-by]</span><span class="delimiter">: </span><span class="description">apply a unary function to each element retrieved from a strided input array according to a callback function and assign results to a strided output array.</span>
-   <span class="signature">[`mskunary( arrays, shape, strides, fcn )`][@stdlib/strided/base/mskunary]</span><span class="delimiter">: </span><span class="description">apply a unary callback to elements in a strided input array according to elements in a strided mask array and assign results to elements in a strided output array.</span>
-   <span class="signature">[`nullary( arrays, shape, strides, fcn )`][@stdlib/strided/base/nullary]</span><span class="delimiter">: </span><span class="description">apply a nullary callback and assign results to elements in a strided output array.</span>
-   <span class="signature">[`quaternary( arrays, shape, strides, fcn )`][@stdlib/strided/base/quaternary]</span><span class="delimiter">: </span><span class="description">apply a quaternary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`quinary( arrays, shape, strides, fcn )`][@stdlib/strided/base/quinary]</span><span class="delimiter">: </span><span class="description">apply a quinary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`smap( N, x, strideX, y, strideY, fcn )`][@stdlib/strided/base/smap]</span><span class="delimiter">: </span><span class="description">apply a unary function accepting and returning single-precision floating-point numbers to each element in a single-precision floating-point strided input array and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`smskmap( N, x, strideX, mask, strideMask, y, strideY, fcn )`][@stdlib/strided/base/smskmap]</span><span class="delimiter">: </span><span class="description">apply a unary function accepting and returning single-precision floating-point numbers to each element in a single-precision floating-point strided input array according to a corresponding element in a strided mask array and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`ternary( arrays, shape, strides, fcn )`][@stdlib/strided/base/ternary]</span><span class="delimiter">: </span><span class="description">apply a ternary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`unary( arrays, shape, strides, fcn )`][@stdlib/strided/base/unary]</span><span class="delimiter">: </span><span class="description">apply a unary callback to elements in a strided input array and assign results to elements in a strided output array.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
var objectKeys = require( '@stdlib/utils-keys' );
var ns = require( '@stdlib/strided-base' );

console.log( objectKeys( ns ) );
```

</section>

<!-- /.examples -->

<!-- Section for related `stdlib` packages. Do not manually edit this section, as it is automatically populated. -->

<section class="related">

</section>

<!-- /.related -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->


<section class="main-repo" >

* * *

## Notice

This package is part of [stdlib][stdlib], a standard library for JavaScript and Node.js, with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2021. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/strided-base.svg
[npm-url]: https://npmjs.org/package/@stdlib/strided-base

[test-image]: https://github.com/stdlib-js/strided-base/actions/workflows/test.yml/badge.svg
[test-url]: https://github.com/stdlib-js/strided-base/actions/workflows/test.yml

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/strided-base/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/strided-base?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/strided-base.svg
[dependencies-url]: https://david-dm.org/stdlib-js/strided-base/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://gitter.im/stdlib-js/stdlib/

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/strided-base/main/LICENSE

<!-- <toc-links> -->

[@stdlib/strided/base/binary]: https://github.com/stdlib-js/strided-base-binary

[@stdlib/strided/base/dmap]: https://github.com/stdlib-js/strided-base-dmap

[@stdlib/strided/base/dmskmap]: https://github.com/stdlib-js/strided-base-dmskmap

[@stdlib/strided/base/map-by]: https://github.com/stdlib-js/strided-base-map-by

[@stdlib/strided/base/mskunary]: https://github.com/stdlib-js/strided-base-mskunary

[@stdlib/strided/base/nullary]: https://github.com/stdlib-js/strided-base-nullary

[@stdlib/strided/base/quaternary]: https://github.com/stdlib-js/strided-base-quaternary

[@stdlib/strided/base/quinary]: https://github.com/stdlib-js/strided-base-quinary

[@stdlib/strided/base/smap]: https://github.com/stdlib-js/strided-base-smap

[@stdlib/strided/base/smskmap]: https://github.com/stdlib-js/strided-base-smskmap

[@stdlib/strided/base/ternary]: https://github.com/stdlib-js/strided-base-ternary

[@stdlib/strided/base/unary]: https://github.com/stdlib-js/strided-base-unary

<!-- </toc-links> -->

</section>

<!-- /.links -->
