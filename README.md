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


<details>
  <summary>
    About stdlib...
  </summary>
  <p>We believe in a future in which the web is a preferred environment for numerical computation. To help realize this future, we've built stdlib. stdlib is a standard library, with an emphasis on numerical and scientific computation, written in JavaScript (and C) for execution in browsers and in Node.js.</p>
  <p>The library is fully decomposable, being architected in such a way that you can swap out and mix and match APIs and functionality to cater to your exact preferences and use cases.</p>
  <p>When you use stdlib, you can be absolutely certain that you are using the most thorough, rigorous, well-written, studied, documented, tested, measured, and high-quality code out there.</p>
  <p>To join us in bringing numerical computing to the web, get started by checking us out on <a href="https://github.com/stdlib-js/stdlib">GitHub</a>, and please consider <a href="https://opencollective.com/stdlib">financially supporting stdlib</a>. We greatly appreciate your continued support!</p>
</details>

# Base

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Base strided.



<section class="usage">

## Usage

```javascript
import ns from 'https://cdn.jsdelivr.net/gh/stdlib-js/strided-base@deno/mod.js';
```
The previous example will load the latest bundled code from the deno branch. Alternatively, you may load a specific version by loading the file from one of the [tagged bundles](https://github.com/stdlib-js/strided-base/tags). For example,

```javascript
import ns from 'https://cdn.jsdelivr.net/gh/stdlib-js/strided-base@v0.1.0-deno/mod.js';
```

You can also import the following named exports from the package:

```javascript
import { binary, binaryAddonDispatch, binaryDtypeSignatures, binarySignatureCallbacks, cmap, dmap, dmap2, dmskmap, dmskmap2, dtypeEnum2Str, dtypeResolveEnum, dtypeResolveStr, dtypeStr2Enum, mapBy, mapBy2, maxViewBufferIndex, metaDataProps, minViewBufferIndex, mskunary, mskunaryAddonDispatch, mskunaryDtypeSignatures, mskunarySignatureCallbacks, nullary, nullaryAddonDispatch, offsetView, quaternary, quinary, reinterpretComplex128, reinterpretComplex64, smap, smap2, smskmap, smskmap2, ternary, unary, unaryAddonDispatch, unaryBy, unaryDtypeSignatures, unarySignatureCallbacks, zmap } from 'https://cdn.jsdelivr.net/gh/stdlib-js/strided-base@deno/mod.js';
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

-   <span class="signature">[`binaryAddonDispatch( addon, fallback )`][@stdlib/strided/base/binary-addon-dispatch]</span><span class="delimiter">: </span><span class="description">dispatch to a native add-on applying a binary function to two input strided arrays.</span>
-   <span class="signature">[`binaryDtypeSignatures( dtypes1, dtypes2, dtypes3[, options] )`][@stdlib/strided/base/binary-dtype-signatures]</span><span class="delimiter">: </span><span class="description">generate a list of binary interface signatures from strided array data types.</span>
-   <span class="signature">[`binarySignatureCallbacks( table, signatures )`][@stdlib/strided/base/binary-signature-callbacks]</span><span class="delimiter">: </span><span class="description">assign callbacks to binary interfaces according to type promotion rules.</span>
-   <span class="signature">[`binary( arrays, shape, strides, fcn )`][@stdlib/strided/base/binary]</span><span class="delimiter">: </span><span class="description">apply a binary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`cmap( N, x, strideX, y, strideY, fcn )`][@stdlib/strided/base/cmap]</span><span class="delimiter">: </span><span class="description">apply a unary function to a single-precision floating-point strided input array and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`dmap( N, x, strideX, y, strideY, fcn )`][@stdlib/strided/base/dmap]</span><span class="delimiter">: </span><span class="description">apply a unary function to a double-precision floating-point strided input array and assign results to a double-precision floating-point strided output array.</span>
-   <span class="signature">[`dmap2( N, x, strideX, y, strideY, z, strideZ, fcn )`][@stdlib/strided/base/dmap2]</span><span class="delimiter">: </span><span class="description">apply a binary function to double-precision floating-point strided input arrays and assign results to a double-precision floating-point strided output array.</span>
-   <span class="signature">[`dmskmap( N, x, strideX, mask, strideMask, y, strideY, fcn )`][@stdlib/strided/base/dmskmap]</span><span class="delimiter">: </span><span class="description">apply a unary function to a double-precision floating-point strided input array according to a strided mask array and assign results to a double-precision floating-point strided output array.</span>
-   <span class="signature">[`dmskmap2( N, x, strideX, y, strideY, mask, strideMask, z, strideZ, fcn )`][@stdlib/strided/base/dmskmap2]</span><span class="delimiter">: </span><span class="description">apply a binary function to double-precision floating-point strided input arrays according to a strided mask array and assign results to a double-precision floating-point strided output array.</span>
-   <span class="signature">[`dtypeEnum2Str( dtype )`][@stdlib/strided/base/dtype-enum2str]</span><span class="delimiter">: </span><span class="description">return the data type string associated with a strided array data type enumeration constant.</span>
-   <span class="signature">[`dtypeResolveEnum( dtype )`][@stdlib/strided/base/dtype-resolve-enum]</span><span class="delimiter">: </span><span class="description">return the enumeration constant associated with a supported strided array data type value.</span>
-   <span class="signature">[`dtypeResolveStr( dtype )`][@stdlib/strided/base/dtype-resolve-str]</span><span class="delimiter">: </span><span class="description">return the data type string associated with a supported strided array data type value.</span>
-   <span class="signature">[`dtypeStr2Enum( dtype )`][@stdlib/strided/base/dtype-str2enum]</span><span class="delimiter">: </span><span class="description">return the enumeration constant associated with a strided array data type string.</span>
-   <span class="signature">[`mapBy( N, x, strideX, y, strideY, fcn, clbk[, thisArg] )`][@stdlib/strided/base/map-by]</span><span class="delimiter">: </span><span class="description">apply a unary function to each element retrieved from a strided input array according to a callback function and assign results to a strided output array.</span>
-   <span class="signature">[`mapBy2( N, x, strideX, y, strideY, z, strideZ, fcn, clbk[, thisArg] )`][@stdlib/strided/base/map-by2]</span><span class="delimiter">: </span><span class="description">apply a binary function to each pair of elements retrieved from strided input arrays according to a callback function and assign results to a strided output array.</span>
-   <span class="signature">[`maxViewBufferIndex( N, stride, offset )`][@stdlib/strided/base/max-view-buffer-index]</span><span class="delimiter">: </span><span class="description">return the maximum accessible index based on a set of provided strided array parameters.</span>
-   <span class="signature">[`metaDataProps( meta, dtypes, obj, bool )`][@stdlib/strided/base/meta-data-props]</span><span class="delimiter">: </span><span class="description">define non-enumerable read-only properties which expose strided array function meta data.</span>
-   <span class="signature">[`minViewBufferIndex( N, stride, offset )`][@stdlib/strided/base/min-view-buffer-index]</span><span class="delimiter">: </span><span class="description">return the minimum accessible index based on a set of provided strided array parameters.</span>
-   <span class="signature">[`mskunaryAddonDispatch( addon, fallback )`][@stdlib/strided/base/mskunary-addon-dispatch]</span><span class="delimiter">: </span><span class="description">dispatch to a native add-on applying a unary function to an input strided array according to a mask strided array.</span>
-   <span class="signature">[`mskunaryDtypeSignatures( dtypes1, dtypes2[, options] )`][@stdlib/strided/base/mskunary-dtype-signatures]</span><span class="delimiter">: </span><span class="description">generate a list of masked unary interface signatures from strided array data types.</span>
-   <span class="signature">[`mskunarySignatureCallbacks( table, signatures )`][@stdlib/strided/base/mskunary-signature-callbacks]</span><span class="delimiter">: </span><span class="description">assign callbacks to masked unary interfaces according to type promotion rules.</span>
-   <span class="signature">[`mskunary( arrays, shape, strides, fcn )`][@stdlib/strided/base/mskunary]</span><span class="delimiter">: </span><span class="description">apply a unary callback to elements in a strided input array according to elements in a strided mask array and assign results to elements in a strided output array.</span>
-   <span class="signature">[`nullaryAddonDispatch( addon, fallback )`][@stdlib/strided/base/nullary-addon-dispatch]</span><span class="delimiter">: </span><span class="description">dispatch to a native add-on applying a nullary function.</span>
-   <span class="signature">[`nullary( arrays, shape, strides, fcn )`][@stdlib/strided/base/nullary]</span><span class="delimiter">: </span><span class="description">apply a nullary callback and assign results to elements in a strided output array.</span>
-   <span class="signature">[`offsetView( x, offset )`][@stdlib/strided/base/offset-view]</span><span class="delimiter">: </span><span class="description">return a typed array view having the same data type as a provided input typed array and starting at a specified index offset.</span>
-   <span class="signature">[`quaternary( arrays, shape, strides, fcn )`][@stdlib/strided/base/quaternary]</span><span class="delimiter">: </span><span class="description">apply a quaternary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`quinary( arrays, shape, strides, fcn )`][@stdlib/strided/base/quinary]</span><span class="delimiter">: </span><span class="description">apply a quinary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`reinterpretComplex128( x, offset )`][@stdlib/strided/base/reinterpret-complex128]</span><span class="delimiter">: </span><span class="description">reinterpret a `Complex128Array` as a `Float64Array`.</span>
-   <span class="signature">[`reinterpretComplex64( x, offset )`][@stdlib/strided/base/reinterpret-complex64]</span><span class="delimiter">: </span><span class="description">reinterpret a `Complex64Array` as a `Float32Array`.</span>
-   <span class="signature">[`smap( N, x, strideX, y, strideY, fcn )`][@stdlib/strided/base/smap]</span><span class="delimiter">: </span><span class="description">apply a unary function to a single-precision floating-point strided input array and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`smap2( N, x, strideX, y, strideY, z, strideZ, fcn )`][@stdlib/strided/base/smap2]</span><span class="delimiter">: </span><span class="description">apply a binary function to single-precision floating-point strided input arrays and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`smskmap( N, x, strideX, mask, strideMask, y, strideY, fcn )`][@stdlib/strided/base/smskmap]</span><span class="delimiter">: </span><span class="description">apply a unary function to a single-precision floating-point strided input array according to a strided mask array and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`smskmap2( N, x, strideX, y, strideY, mask, strideMask, z, strideZ, fcn )`][@stdlib/strided/base/smskmap2]</span><span class="delimiter">: </span><span class="description">apply a binary function to single-precision floating-point strided input arrays according to a strided mask array and assign results to a single-precision floating-point strided output array.</span>
-   <span class="signature">[`ternary( arrays, shape, strides, fcn )`][@stdlib/strided/base/ternary]</span><span class="delimiter">: </span><span class="description">apply a ternary callback to strided input array elements and assign results to elements in a strided output array.</span>
-   <span class="signature">[`unaryAddonDispatch( addon, fallback )`][@stdlib/strided/base/unary-addon-dispatch]</span><span class="delimiter">: </span><span class="description">dispatch to a native add-on applying a unary function to an input strided array.</span>
-   <span class="signature">[`unaryBy( arrays, shape, strides, fcn, clbk[, thisArg] )`][@stdlib/strided/base/unary-by]</span><span class="delimiter">: </span><span class="description">apply a unary function to each element retrieved from a strided input array according to a callback function and assign results to a strided output array.</span>
-   <span class="signature">[`unaryDtypeSignatures( dtypes1, dtypes2[, options] )`][@stdlib/strided/base/unary-dtype-signatures]</span><span class="delimiter">: </span><span class="description">generate a list of unary interface signatures from strided array data types.</span>
-   <span class="signature">[`unarySignatureCallbacks( table, signatures )`][@stdlib/strided/base/unary-signature-callbacks]</span><span class="delimiter">: </span><span class="description">assign callbacks to unary interfaces according to type promotion rules.</span>
-   <span class="signature">[`unary( arrays, shape, strides, fcn )`][@stdlib/strided/base/unary]</span><span class="delimiter">: </span><span class="description">apply a unary callback to elements in a strided input array and assign results to elements in a strided output array.</span>
-   <span class="signature">[`zmap( N, x, strideX, y, strideY, fcn )`][@stdlib/strided/base/zmap]</span><span class="delimiter">: </span><span class="description">apply a unary function to a double-precision floating-point strided input array and assign results to a double-precision floating-point strided output array.</span>

</div>

<!-- </toc> -->

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```javascript
import objectKeys from 'https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@deno/mod.js';
import ns from 'https://cdn.jsdelivr.net/gh/stdlib-js/strided-base@deno/mod.js';

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

This package is part of [stdlib][stdlib], a standard library with an emphasis on numerical and scientific computing. The library provides a collection of robust, high performance libraries for mathematics, statistics, streams, utilities, and more.

For more information on the project, filing bug reports and feature requests, and guidance on how to develop [stdlib][stdlib], see the main project [repository][stdlib].

#### Community

[![Chat][chat-image]][chat-url]

---

## License

See [LICENSE][stdlib-license].


## Copyright

Copyright &copy; 2016-2023. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/strided-base.svg
[npm-url]: https://npmjs.org/package/@stdlib/strided-base

[test-image]: https://github.com/stdlib-js/strided-base/actions/workflows/test.yml/badge.svg?branch=v0.1.0
[test-url]: https://github.com/stdlib-js/strided-base/actions/workflows/test.yml?query=branch:v0.1.0

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/strided-base/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/strided-base?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/strided-base.svg
[dependencies-url]: https://david-dm.org/stdlib-js/strided-base/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/strided-base/tree/deno
[umd-url]: https://github.com/stdlib-js/strided-base/tree/umd
[esm-url]: https://github.com/stdlib-js/strided-base/tree/esm
[branches-url]: https://github.com/stdlib-js/strided-base/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/strided-base/main/LICENSE

<!-- <toc-links> -->

[@stdlib/strided/base/binary-addon-dispatch]: https://github.com/stdlib-js/strided-base-binary-addon-dispatch/tree/deno

[@stdlib/strided/base/binary-dtype-signatures]: https://github.com/stdlib-js/strided-base-binary-dtype-signatures/tree/deno

[@stdlib/strided/base/binary-signature-callbacks]: https://github.com/stdlib-js/strided-base-binary-signature-callbacks/tree/deno

[@stdlib/strided/base/binary]: https://github.com/stdlib-js/strided-base-binary/tree/deno

[@stdlib/strided/base/cmap]: https://github.com/stdlib-js/strided-base-cmap/tree/deno

[@stdlib/strided/base/dmap]: https://github.com/stdlib-js/strided-base-dmap/tree/deno

[@stdlib/strided/base/dmap2]: https://github.com/stdlib-js/strided-base-dmap2/tree/deno

[@stdlib/strided/base/dmskmap]: https://github.com/stdlib-js/strided-base-dmskmap/tree/deno

[@stdlib/strided/base/dmskmap2]: https://github.com/stdlib-js/strided-base-dmskmap2/tree/deno

[@stdlib/strided/base/dtype-enum2str]: https://github.com/stdlib-js/strided-base-dtype-enum2str/tree/deno

[@stdlib/strided/base/dtype-resolve-enum]: https://github.com/stdlib-js/strided-base-dtype-resolve-enum/tree/deno

[@stdlib/strided/base/dtype-resolve-str]: https://github.com/stdlib-js/strided-base-dtype-resolve-str/tree/deno

[@stdlib/strided/base/dtype-str2enum]: https://github.com/stdlib-js/strided-base-dtype-str2enum/tree/deno

[@stdlib/strided/base/map-by]: https://github.com/stdlib-js/strided-base-map-by/tree/deno

[@stdlib/strided/base/map-by2]: https://github.com/stdlib-js/strided-base-map-by2/tree/deno

[@stdlib/strided/base/max-view-buffer-index]: https://github.com/stdlib-js/strided-base-max-view-buffer-index/tree/deno

[@stdlib/strided/base/meta-data-props]: https://github.com/stdlib-js/strided-base-meta-data-props/tree/deno

[@stdlib/strided/base/min-view-buffer-index]: https://github.com/stdlib-js/strided-base-min-view-buffer-index/tree/deno

[@stdlib/strided/base/mskunary-addon-dispatch]: https://github.com/stdlib-js/strided-base-mskunary-addon-dispatch/tree/deno

[@stdlib/strided/base/mskunary-dtype-signatures]: https://github.com/stdlib-js/strided-base-mskunary-dtype-signatures/tree/deno

[@stdlib/strided/base/mskunary-signature-callbacks]: https://github.com/stdlib-js/strided-base-mskunary-signature-callbacks/tree/deno

[@stdlib/strided/base/mskunary]: https://github.com/stdlib-js/strided-base-mskunary/tree/deno

[@stdlib/strided/base/nullary-addon-dispatch]: https://github.com/stdlib-js/strided-base-nullary-addon-dispatch/tree/deno

[@stdlib/strided/base/nullary]: https://github.com/stdlib-js/strided-base-nullary/tree/deno

[@stdlib/strided/base/offset-view]: https://github.com/stdlib-js/strided-base-offset-view/tree/deno

[@stdlib/strided/base/quaternary]: https://github.com/stdlib-js/strided-base-quaternary/tree/deno

[@stdlib/strided/base/quinary]: https://github.com/stdlib-js/strided-base-quinary/tree/deno

[@stdlib/strided/base/reinterpret-complex128]: https://github.com/stdlib-js/strided-base-reinterpret-complex128/tree/deno

[@stdlib/strided/base/reinterpret-complex64]: https://github.com/stdlib-js/strided-base-reinterpret-complex64/tree/deno

[@stdlib/strided/base/smap]: https://github.com/stdlib-js/strided-base-smap/tree/deno

[@stdlib/strided/base/smap2]: https://github.com/stdlib-js/strided-base-smap2/tree/deno

[@stdlib/strided/base/smskmap]: https://github.com/stdlib-js/strided-base-smskmap/tree/deno

[@stdlib/strided/base/smskmap2]: https://github.com/stdlib-js/strided-base-smskmap2/tree/deno

[@stdlib/strided/base/ternary]: https://github.com/stdlib-js/strided-base-ternary/tree/deno

[@stdlib/strided/base/unary-addon-dispatch]: https://github.com/stdlib-js/strided-base-unary-addon-dispatch/tree/deno

[@stdlib/strided/base/unary-by]: https://github.com/stdlib-js/strided-base-unary-by/tree/deno

[@stdlib/strided/base/unary-dtype-signatures]: https://github.com/stdlib-js/strided-base-unary-dtype-signatures/tree/deno

[@stdlib/strided/base/unary-signature-callbacks]: https://github.com/stdlib-js/strided-base-unary-signature-callbacks/tree/deno

[@stdlib/strided/base/unary]: https://github.com/stdlib-js/strided-base-unary/tree/deno

[@stdlib/strided/base/zmap]: https://github.com/stdlib-js/strided-base-zmap/tree/deno

<!-- </toc-links> -->

</section>

<!-- /.links -->
