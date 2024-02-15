<!--

@license Apache-2.0

Copyright (c) 2018 The Stdlib Authors.

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

# Binomial

[![NPM version][npm-image]][npm-url] [![Build Status][test-image]][test-url] [![Coverage Status][coverage-image]][coverage-url] <!-- [![dependencies][dependencies-image]][dependencies-url] -->

> Binomial distribution.



<section class="usage">

## Usage

To use in Observable,

```javascript
binomial = require( 'https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-binomial@umd/browser.js' )
```

To vendor stdlib functionality and avoid installing dependency trees for Node.js, you can use the UMD server build:

```javascript
var binomial = require( 'path/to/vendor/umd/stats-base-dists-binomial/index.js' )
```

To include the bundle in a webpage,

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-binomial@umd/browser.js"></script>
```

If no recognized module system is present, access bundle contents via the global scope:

```html
<script type="text/javascript">
(function () {
    window.binomial;
})();
</script>
```

#### binomial

Binomial distribution.

```javascript
var dist = binomial;
// returns {...}
```

The namespace contains the following distribution functions:

<!-- <toc pattern="*+(cdf|pmf|mgf|quantile)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`cdf( x, n, p )`][@stdlib/stats/base/dists/binomial/cdf]</span><span class="delimiter">: </span><span class="description">binomial distribution cumulative distribution function.</span>
-   <span class="signature">[`logpmf( x, n, p )`][@stdlib/stats/base/dists/binomial/logpmf]</span><span class="delimiter">: </span><span class="description">evaluate the natural logarithm of the probability mass function (PMF) for a binomial distribution.</span>
-   <span class="signature">[`mgf( t, n, p )`][@stdlib/stats/base/dists/binomial/mgf]</span><span class="delimiter">: </span><span class="description">binomial distribution moment-generating function (MGF).</span>
-   <span class="signature">[`pmf( x, n, p )`][@stdlib/stats/base/dists/binomial/pmf]</span><span class="delimiter">: </span><span class="description">binomial distribution probability mass function (PMF).</span>
-   <span class="signature">[`quantile( r, n, p )`][@stdlib/stats/base/dists/binomial/quantile]</span><span class="delimiter">: </span><span class="description">binomial distribution quantile function.</span>

</div>

<!-- </toc> -->

The namespace contains the following functions for calculating distribution properties:

<!-- <toc pattern="*+(entropy|kurtosis|mean|median|mode|skewness|stdev|variance)*"> -->

<div class="namespace-toc">

-   <span class="signature">[`entropy( n, p )`][@stdlib/stats/base/dists/binomial/entropy]</span><span class="delimiter">: </span><span class="description">binomial distribution entropy.</span>
-   <span class="signature">[`kurtosis( n, p )`][@stdlib/stats/base/dists/binomial/kurtosis]</span><span class="delimiter">: </span><span class="description">binomial distribution excess kurtosis.</span>
-   <span class="signature">[`mean( n, p )`][@stdlib/stats/base/dists/binomial/mean]</span><span class="delimiter">: </span><span class="description">binomial distribution expected value.</span>
-   <span class="signature">[`median( n, p )`][@stdlib/stats/base/dists/binomial/median]</span><span class="delimiter">: </span><span class="description">binomial distribution median.</span>
-   <span class="signature">[`mode( n, p )`][@stdlib/stats/base/dists/binomial/mode]</span><span class="delimiter">: </span><span class="description">binomial distribution mode.</span>
-   <span class="signature">[`skewness( n, p )`][@stdlib/stats/base/dists/binomial/skewness]</span><span class="delimiter">: </span><span class="description">binomial distribution skewness.</span>
-   <span class="signature">[`stdev( n, p )`][@stdlib/stats/base/dists/binomial/stdev]</span><span class="delimiter">: </span><span class="description">binomial distribution standard deviation.</span>
-   <span class="signature">[`variance( n, p )`][@stdlib/stats/base/dists/binomial/variance]</span><span class="delimiter">: </span><span class="description">binomial distribution variance.</span>

</div>

<!-- </toc> -->

The namespace contains a constructor function for creating a [binomial][binomial-distribution] distribution object.

<!-- <toc pattern="*ctor*"> -->

<div class="namespace-toc">

-   <span class="signature">[`Binomial( [n, p] )`][@stdlib/stats/base/dists/binomial/ctor]</span><span class="delimiter">: </span><span class="description">binomial distribution constructor.</span>

</div>

<!-- </toc> -->

```javascript
var Binomial = require( '@stdlib/stats-base-dists-binomial' ).Binomial;
var dist = new Binomial( 10, 0.4 );

var mu = dist.mean;
// returns 4
```

</section>

<!-- /.usage -->

<section class="examples">

## Examples

<!-- TODO: better examples -->

<!-- eslint no-undef: "error" -->

```html
<!DOCTYPE html>
<html lang="en">
<body>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/utils-keys@umd/browser.js"></script>
<script type="text/javascript" src="https://cdn.jsdelivr.net/gh/stdlib-js/stats-base-dists-binomial@umd/browser.js"></script>
<script type="text/javascript">
(function () {

console.log( objectKeys( binomial ) );

})();
</script>
</body>
</html>
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

Copyright &copy; 2016-2024. The Stdlib [Authors][stdlib-authors].

</section>

<!-- /.stdlib -->

<!-- Section for all links. Make sure to keep an empty line after the `section` element and another before the `/section` close. -->

<section class="links">

[npm-image]: http://img.shields.io/npm/v/@stdlib/stats-base-dists-binomial.svg
[npm-url]: https://npmjs.org/package/@stdlib/stats-base-dists-binomial

[test-image]: https://github.com/stdlib-js/stats-base-dists-binomial/actions/workflows/test.yml/badge.svg?branch=v0.2.0
[test-url]: https://github.com/stdlib-js/stats-base-dists-binomial/actions/workflows/test.yml?query=branch:v0.2.0

[coverage-image]: https://img.shields.io/codecov/c/github/stdlib-js/stats-base-dists-binomial/main.svg
[coverage-url]: https://codecov.io/github/stdlib-js/stats-base-dists-binomial?branch=main

<!--

[dependencies-image]: https://img.shields.io/david/stdlib-js/stats-base-dists-binomial.svg
[dependencies-url]: https://david-dm.org/stdlib-js/stats-base-dists-binomial/main

-->

[chat-image]: https://img.shields.io/gitter/room/stdlib-js/stdlib.svg
[chat-url]: https://app.gitter.im/#/room/#stdlib-js_stdlib:gitter.im

[stdlib]: https://github.com/stdlib-js/stdlib

[stdlib-authors]: https://github.com/stdlib-js/stdlib/graphs/contributors

[umd]: https://github.com/umdjs/umd
[es-module]: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules

[deno-url]: https://github.com/stdlib-js/stats-base-dists-binomial/tree/deno
[deno-readme]: https://github.com/stdlib-js/stats-base-dists-binomial/blob/deno/README.md
[umd-url]: https://github.com/stdlib-js/stats-base-dists-binomial/tree/umd
[umd-readme]: https://github.com/stdlib-js/stats-base-dists-binomial/blob/umd/README.md
[esm-url]: https://github.com/stdlib-js/stats-base-dists-binomial/tree/esm
[esm-readme]: https://github.com/stdlib-js/stats-base-dists-binomial/blob/esm/README.md
[branches-url]: https://github.com/stdlib-js/stats-base-dists-binomial/blob/main/branches.md

[stdlib-license]: https://raw.githubusercontent.com/stdlib-js/stats-base-dists-binomial/main/LICENSE

[binomial-distribution]: https://en.wikipedia.org/wiki/Binomial_distribution

<!-- <toc-links> -->

[@stdlib/stats/base/dists/binomial/ctor]: https://github.com/stdlib-js/stats-base-dists-binomial-ctor/tree/umd

[@stdlib/stats/base/dists/binomial/entropy]: https://github.com/stdlib-js/stats-base-dists-binomial-entropy/tree/umd

[@stdlib/stats/base/dists/binomial/kurtosis]: https://github.com/stdlib-js/stats-base-dists-binomial-kurtosis/tree/umd

[@stdlib/stats/base/dists/binomial/mean]: https://github.com/stdlib-js/stats-base-dists-binomial-mean/tree/umd

[@stdlib/stats/base/dists/binomial/median]: https://github.com/stdlib-js/stats-base-dists-binomial-median/tree/umd

[@stdlib/stats/base/dists/binomial/mode]: https://github.com/stdlib-js/stats-base-dists-binomial-mode/tree/umd

[@stdlib/stats/base/dists/binomial/skewness]: https://github.com/stdlib-js/stats-base-dists-binomial-skewness/tree/umd

[@stdlib/stats/base/dists/binomial/stdev]: https://github.com/stdlib-js/stats-base-dists-binomial-stdev/tree/umd

[@stdlib/stats/base/dists/binomial/variance]: https://github.com/stdlib-js/stats-base-dists-binomial-variance/tree/umd

[@stdlib/stats/base/dists/binomial/cdf]: https://github.com/stdlib-js/stats-base-dists-binomial-cdf/tree/umd

[@stdlib/stats/base/dists/binomial/logpmf]: https://github.com/stdlib-js/stats-base-dists-binomial-logpmf/tree/umd

[@stdlib/stats/base/dists/binomial/mgf]: https://github.com/stdlib-js/stats-base-dists-binomial-mgf/tree/umd

[@stdlib/stats/base/dists/binomial/pmf]: https://github.com/stdlib-js/stats-base-dists-binomial-pmf/tree/umd

[@stdlib/stats/base/dists/binomial/quantile]: https://github.com/stdlib-js/stats-base-dists-binomial-quantile/tree/umd

<!-- </toc-links> -->

</section>

<!-- /.links -->
