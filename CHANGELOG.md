# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2026-03-23)

<section class="commits">

### Commits

<details>

-   [`675c404`](https://github.com/stdlib-js/stdlib/commit/675c404341e210a6ff4d37477bbc3f79e927fd8d) - **bench:** refactor to use string interpolation in `stats/base/dists/binomial` [(#10176)](https://github.com/stdlib-js/stdlib/pull/10176) _(by Vishal Gaikwad)_
-   [`4756e95`](https://github.com/stdlib-js/stdlib/commit/4756e952607ba75dc0013d2b8e226e7d3db000d9) - **docs:** use \"probability mass function\" instead of \"probability density function\" for PMF methods _(by Philipp Burckhardt)_
-   [`0ca797b`](https://github.com/stdlib-js/stdlib/commit/0ca797b5558b96111256a7446eafe101761b240b) - **bench:** use float literals for `uniform` range arguments _(by Philipp Burckhardt)_
-   [`f38e8a7`](https://github.com/stdlib-js/stdlib/commit/f38e8a7b433e0e9888eb57c83f4374073089ad85) - **docs:** clean-up parameters in Julia fixtures scripts _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Philipp Burckhardt
-   Vishal Gaikwad

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.3.1">

## 0.3.1 (2026-02-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.3.0">

## 0.3.0 (2026-01-31)

<section class="features">

### Features

-   [`797e534`](https://github.com/stdlib-js/stdlib/commit/797e53461faa68130f467a325f4996892e62a05a) - add C implementation for `stats/base/dists/binomial/pmf` [(#4359)](https://github.com/stdlib-js/stdlib/pull/4359)
-   [`394df9c`](https://github.com/stdlib-js/stdlib/commit/394df9cbfe1e319625331814813bfffb5113d8d6) - add C implementation for `stats/base/dists/binomial/entropy` [(#4016)](https://github.com/stdlib-js/stdlib/pull/4016)
-   [`b74cf16`](https://github.com/stdlib-js/stdlib/commit/b74cf1670fd9f0bde46fd02d2e432c94bbebf6c6) - add C implementation for `stats/base/dists/binomial/mgf` [(#4414)](https://github.com/stdlib-js/stdlib/pull/4414)
-   [`9b455b1`](https://github.com/stdlib-js/stdlib/commit/9b455b15cb301af9ecc7eff8960e223a3a7d1b24) - add C implementation for `stats/base/dists/binomial/median` [(#3950)](https://github.com/stdlib-js/stdlib/pull/3950)
-   [`e05da28`](https://github.com/stdlib-js/stdlib/commit/e05da283a2493c635c06ab0f19e4aefbcc9e2540) - add C implementation for `stats/base/dists/binomial/stdev` [(#4408)](https://github.com/stdlib-js/stdlib/pull/4408)
-   [`d465523`](https://github.com/stdlib-js/stdlib/commit/d465523f1465201c42ca8491ecf14c6bde261031) - add C implementation for `stats/base/dists/binomial/kurtosis` [(#4411)](https://github.com/stdlib-js/stdlib/pull/4411)
-   [`9805877`](https://github.com/stdlib-js/stdlib/commit/9805877a4645bd964574b02d6bf4ce8d36f97f7b) - add C implementation for `stats/base/dists/binomial/skewness` [(#4410)](https://github.com/stdlib-js/stdlib/pull/4410)
-   [`95dd2ff`](https://github.com/stdlib-js/stdlib/commit/95dd2ffb02ddeb98f100d73cdb017264905dd3a4) - add C implementation for `stats/base/dists/binomial/mean` [(#3681)](https://github.com/stdlib-js/stdlib/pull/3681)
-   [`3283517`](https://github.com/stdlib-js/stdlib/commit/32835176f21ecd14cbf81a51699d49533ff63fe6) - add C implementation for `stats/base/dists/binomial/variance` [(#3929)](https://github.com/stdlib-js/stdlib/pull/3929)
-   [`8447e7a`](https://github.com/stdlib-js/stdlib/commit/8447e7a2a28a2f5cdca879dea9a6ebe56783b82f) - add C implementation for `stats/base/dists/binomial/mode` [(#3947)](https://github.com/stdlib-js/stdlib/pull/3947)

</section>

<!-- /.features -->

<section class="reverts">

### Reverts

-   [`932f042`](https://github.com/stdlib-js/stdlib/commit/932f0422195ffa4db9efaca5e060881716aae006) - chore: add src to directories

</section>

<!-- /.reverts -->

<section class="issues">

### Closed Issues

A total of 15 issues were closed in this release:

[#3466](https://github.com/stdlib-js/stdlib/issues/3466), [#3467](https://github.com/stdlib-js/stdlib/issues/3467), [#3469](https://github.com/stdlib-js/stdlib/issues/3469), [#3470](https://github.com/stdlib-js/stdlib/issues/3470), [#3471](https://github.com/stdlib-js/stdlib/issues/3471), [#3472](https://github.com/stdlib-js/stdlib/issues/3472), [#3473](https://github.com/stdlib-js/stdlib/issues/3473), [#3475](https://github.com/stdlib-js/stdlib/issues/3475), [#3476](https://github.com/stdlib-js/stdlib/issues/3476), [#3477](https://github.com/stdlib-js/stdlib/issues/3477), [#5125](https://github.com/stdlib-js/stdlib/issues/5125), [#5149](https://github.com/stdlib-js/stdlib/issues/5149), [#5303](https://github.com/stdlib-js/stdlib/issues/5303), [#5305](https://github.com/stdlib-js/stdlib/issues/5305), [#7758](https://github.com/stdlib-js/stdlib/issues/7758)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`932f042`](https://github.com/stdlib-js/stdlib/commit/932f0422195ffa4db9efaca5e060881716aae006) - **revert:** chore: add src to directories _(by Philipp Burckhardt)_
-   [`3b896f1`](https://github.com/stdlib-js/stdlib/commit/3b896f19550d799ea5a61d386974f6ce1f341eaa) - **chore:** add src to directories _(by Philipp Burckhardt)_
-   [`2cabe18`](https://github.com/stdlib-js/stdlib/commit/2cabe1887e6a502a306b70580fb5d038da0917f3) - **docs:** fix return values in TSDoc return annotation comments _(by Philipp Burckhardt)_
-   [`14fbe2a`](https://github.com/stdlib-js/stdlib/commit/14fbe2a5ced542c4183b6cae8a5d369462a6023a) - **docs:** clean-up TypeScript declarations example code _(by Philipp Burckhardt)_
-   [`e2efe32`](https://github.com/stdlib-js/stdlib/commit/e2efe32914d0d9dae5da34e6f7e7bf7655430710) - **chore:** rename exported variable in d.ts file to match name used in example code _(by Philipp Burckhardt)_
-   [`e678757`](https://github.com/stdlib-js/stdlib/commit/e678757c9a62631a907278ec13a5d7b27c0f1e15) - **docs:** fix return annotation values _(by Philipp Burckhardt)_
-   [`7add020`](https://github.com/stdlib-js/stdlib/commit/7add0201c13e56a0381926ccfd4073c84eaf2ed4) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`fc438e0`](https://github.com/stdlib-js/stdlib/commit/fc438e0edbad0689d6923d6f3edb959b96597662) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`07f7c05`](https://github.com/stdlib-js/stdlib/commit/07f7c0522c73e6ad9505e1d45035ae439344200d) - **test:** use standardized assertion messages and fix lint errors _(by Philipp Burckhardt)_
-   [`9c21fd2`](https://github.com/stdlib-js/stdlib/commit/9c21fd20ef8b8a6a88abb96d80ea6d8e4c5434eb) - **test:** use .strictEqual() instead of .equal() _(by Philipp Burckhardt)_
-   [`b6ca4b7`](https://github.com/stdlib-js/stdlib/commit/b6ca4b794ee6a139616ef2115e7ba38bdede2f85) - **docs:** fix capitalization [(#7763)](https://github.com/stdlib-js/stdlib/pull/7763) _(by Abhishek G, Athan Reines)_
-   [`797e534`](https://github.com/stdlib-js/stdlib/commit/797e53461faa68130f467a325f4996892e62a05a) - **feat:** add C implementation for `stats/base/dists/binomial/pmf` [(#4359)](https://github.com/stdlib-js/stdlib/pull/4359) _(by Abhijit Raut, Philipp Burckhardt, stdlib-bot)_
-   [`394df9c`](https://github.com/stdlib-js/stdlib/commit/394df9cbfe1e319625331814813bfffb5113d8d6) - **feat:** add C implementation for `stats/base/dists/binomial/entropy` [(#4016)](https://github.com/stdlib-js/stdlib/pull/4016) _(by Divyansh Seth, Philipp Burckhardt, stdlib-bot)_
-   [`b74cf16`](https://github.com/stdlib-js/stdlib/commit/b74cf1670fd9f0bde46fd02d2e432c94bbebf6c6) - **feat:** add C implementation for `stats/base/dists/binomial/mgf` [(#4414)](https://github.com/stdlib-js/stdlib/pull/4414) _(by Prashant Kumar Yadav, Philipp Burckhardt, stdlib-bot)_
-   [`c1df69c`](https://github.com/stdlib-js/stdlib/commit/c1df69ccf92f1ce80f08883226dd4252644f0324) - **docs:** replace manual `for` loop in examples [(#6848)](https://github.com/stdlib-js/stdlib/pull/6848) _(by Harsh Yadav, Athan Reines)_
-   [`a5e0667`](https://github.com/stdlib-js/stdlib/commit/a5e0667c308881e101549d77c6d8573e3b632c67) - **docs:** replace manual `for` loop in examples [(#6849)](https://github.com/stdlib-js/stdlib/pull/6849) _(by Harsh Yadav, Athan Reines)_
-   [`7279e43`](https://github.com/stdlib-js/stdlib/commit/7279e433dc1936056560624b5892eea8d9350ef1) - **bench:** update random value generation [(#6853)](https://github.com/stdlib-js/stdlib/pull/6853) _(by Harsh Yadav)_
-   [`c1acd4b`](https://github.com/stdlib-js/stdlib/commit/c1acd4bf3ed08b40d6d4e93ee245f03c9eef8472) - **bench:** update random value generation [(#6858)](https://github.com/stdlib-js/stdlib/pull/6858) _(by Harsh Yadav, Athan Reines)_
-   [`e658ffd`](https://github.com/stdlib-js/stdlib/commit/e658ffd3c46b5cb1ba33c0be61e55bf6995237ca) - **bench:** update random value generation [(#6856)](https://github.com/stdlib-js/stdlib/pull/6856) _(by Harsh Yadav)_
-   [`22c4c3e`](https://github.com/stdlib-js/stdlib/commit/22c4c3e5ffc0356aabf7b740b8e201e9ee427901) - **bench:** update random value generation [(#6857)](https://github.com/stdlib-js/stdlib/pull/6857) _(by Harsh Yadav)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`6670680`](https://github.com/stdlib-js/stdlib/commit/6670680a8981818c8e3774da4bf2a8c7dedb4715) - **chore:** address commit comments and use discrete uniform PRNG [(#5313)](https://github.com/stdlib-js/stdlib/pull/5313) _(by Rishav Tarway)_
-   [`7c6d2b7`](https://github.com/stdlib-js/stdlib/commit/7c6d2b7038784f61acad0b3f0f9680df91a34411) - **docs:** update examples for `stdlib/base/dists/binomial/stdev` [(#5311)](https://github.com/stdlib-js/stdlib/pull/5311) _(by Rishav Tarway)_
-   [`7fc07a2`](https://github.com/stdlib-js/stdlib/commit/7fc07a2122bb9e862ae7e2237dd48096051199dd) - **docs:** fix missing section tags in various READMEs [(#5322)](https://github.com/stdlib-js/stdlib/pull/5322) _(by Saurabh Singh)_
-   [`f7988d3`](https://github.com/stdlib-js/stdlib/commit/f7988d3c02e0eff3bd9bd7523b5dc975bb98dc0e) - **bench:** fix `isnan` checks in `stats/base/dists` [(#5296)](https://github.com/stdlib-js/stdlib/pull/5296) _(by Karan Anand)_
-   [`a51a6b7`](https://github.com/stdlib-js/stdlib/commit/a51a6b7ae837114b7d9fa0854d31d03afe1e1111) - **chore:** explicitly cast and change tolerance _(by Philipp Burckhardt)_
-   [`9b455b1`](https://github.com/stdlib-js/stdlib/commit/9b455b15cb301af9ecc7eff8960e223a3a7d1b24) - **feat:** add C implementation for `stats/base/dists/binomial/median` [(#3950)](https://github.com/stdlib-js/stdlib/pull/3950) _(by Prashant Kumar Yadav, Philipp Burckhardt)_
-   [`e05da28`](https://github.com/stdlib-js/stdlib/commit/e05da283a2493c635c06ab0f19e4aefbcc9e2540) - **feat:** add C implementation for `stats/base/dists/binomial/stdev` [(#4408)](https://github.com/stdlib-js/stdlib/pull/4408) _(by Prashant Kumar Yadav, Philipp Burckhardt, stdlib-bot)_
-   [`d465523`](https://github.com/stdlib-js/stdlib/commit/d465523f1465201c42ca8491ecf14c6bde261031) - **feat:** add C implementation for `stats/base/dists/binomial/kurtosis` [(#4411)](https://github.com/stdlib-js/stdlib/pull/4411) _(by Prashant Kumar Yadav, Philipp Burckhardt, stdlib-bot)_
-   [`c45b0ba`](https://github.com/stdlib-js/stdlib/commit/c45b0ba1e520ffe95e231d4e634cbcc26dfd5242) - **chore:** address commit comments [(#5219)](https://github.com/stdlib-js/stdlib/pull/5219) _(by Saurabh Singh)_
-   [`10b7eff`](https://github.com/stdlib-js/stdlib/commit/10b7eff89e06862772f7c5ba751171f8def32848) - **bench:** refactor number generation [(#5198)](https://github.com/stdlib-js/stdlib/pull/5198) _(by Harsh Yadav)_
-   [`d53a818`](https://github.com/stdlib-js/stdlib/commit/d53a8184c029c3df7c45a7a1a2da9ff90b4f883e) - **docs:** fix errors in the structure of READMEs in `stats/base/*` [(#5138)](https://github.com/stdlib-js/stdlib/pull/5138) _(by Aayush Khanna)_
-   [`9805877`](https://github.com/stdlib-js/stdlib/commit/9805877a4645bd964574b02d6bf4ce8d36f97f7b) - **feat:** add C implementation for `stats/base/dists/binomial/skewness` [(#4410)](https://github.com/stdlib-js/stdlib/pull/4410) _(by Prashant Kumar Yadav, Philipp Burckhardt)_
-   [`95dd2ff`](https://github.com/stdlib-js/stdlib/commit/95dd2ffb02ddeb98f100d73cdb017264905dd3a4) - **feat:** add C implementation for `stats/base/dists/binomial/mean` [(#3681)](https://github.com/stdlib-js/stdlib/pull/3681) _(by Prashant Kumar Yadav, Philipp Burckhardt)_
-   [`af55f0d`](https://github.com/stdlib-js/stdlib/commit/af55f0d6d6b4d06c36f46357740ea89a4639ab5b) - **bench:** refactor random number generation in `stats/base/dists/binomial` [(#4841)](https://github.com/stdlib-js/stdlib/pull/4841) _(by Karan Anand)_
-   [`f75a0ce`](https://github.com/stdlib-js/stdlib/commit/f75a0cef6a3112b166dba04c13bada9763cec350) - **chore:** use excess kurtosis consistently _(by Philipp Burckhardt)_
-   [`3283517`](https://github.com/stdlib-js/stdlib/commit/32835176f21ecd14cbf81a51699d49533ff63fe6) - **feat:** add C implementation for `stats/base/dists/binomial/variance` [(#3929)](https://github.com/stdlib-js/stdlib/pull/3929) _(by Prashant Kumar Yadav, Athan Reines, Philipp Burckhardt)_
-   [`8447e7a`](https://github.com/stdlib-js/stdlib/commit/8447e7a2a28a2f5cdca879dea9a6ebe56783b82f) - **feat:** add C implementation for `stats/base/dists/binomial/mode` [(#3947)](https://github.com/stdlib-js/stdlib/pull/3947) _(by Prashant Kumar Yadav, Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 11 people contributed to this release. Thank you to the following contributors:

-   Aayush Khanna
-   Abhijit Raut
-   Abhishek G
-   Athan Reines
-   Divyansh Seth
-   Harsh Yadav
-   Karan Anand
-   Philipp Burckhardt
-   Prashant Kumar Yadav
-   Rishav Tarway
-   Saurabh Singh

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.2">

## 0.2.2 (2024-07-28)

<section class="commits">

### Commits

<details>

-   [`ac73b91`](https://github.com/stdlib-js/stdlib/commit/ac73b9195cf4f4e087dca2df535ac49831e1aa07) - **docs:** satisfy spellchecker _(by Philipp Burckhardt)_
-   [`41d41e9`](https://github.com/stdlib-js/stdlib/commit/41d41e959b4eaad3c631e6898e3144a4015a5458) - **test:** include trailing newlines in Julia-generated JSON fixtures _(by Philipp Burckhardt)_
-   [`9ed7d0e`](https://github.com/stdlib-js/stdlib/commit/9ed7d0e7d57edb5ad0dfb65c944bed87d475cbf3) - **chore:** add missing trailing newlines _(by Philipp Burckhardt)_
-   [`8b0d39d`](https://github.com/stdlib-js/stdlib/commit/8b0d39d2047d445437c597ce5e5962241f0c9056) - **docs:** improve README examples of `stats/base/dists/binomial` namespace _(by Nishant Shinde, Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Nishant Shinde
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-24)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="commits">

### Commits

<details>

-   [`9502ed2`](https://github.com/stdlib-js/stdlib/commit/9502ed27e2853e312c556a48bdd7775095e66709) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_
-   [`d73bbf4`](https://github.com/stdlib-js/stdlib/commit/d73bbf43d222f935085f8ecf7526e5f57835f74e) - **build:** replace lint directives _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-24)

<section class="features">

### Features

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`81ca3ab`](https://github.com/stdlib-js/stdlib/commit/81ca3ab33585150e98a402b3e6d57beb1ec36864) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`d5fa8e8`](https://github.com/stdlib-js/stdlib/commit/d5fa8e8a6267a837a25a7027e9fe3e847bc2d1c5) - **test:** use strictEqual checks _(by Philipp Burckhardt)_
-   [`ce7e336`](https://github.com/stdlib-js/stdlib/commit/ce7e3367c0f9477773fe76dd0eca64dc6ad33c02) - **docs:** update equations _(by Philipp Burckhardt)_
-   [`37f032d`](https://github.com/stdlib-js/stdlib/commit/37f032d4a571f667ea99f6f52f60b5d736c627f3) - **docs:** render equations via math code blocks _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2022-07-08)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-27)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

