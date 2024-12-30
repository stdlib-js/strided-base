# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2024-12-30)

<section class="packages">

### Packages

<section class="package" id="strided-base-unreleased">

#### [@stdlib/strided/base](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base)

<details>

<section class="features">

##### Features

-   [`8b1548f`](https://github.com/stdlib-js/stdlib/commit/8b1548fb45c1ff131f5edac20cb984344a2d28ec) - update namespace TypeScript declarations [(#3190)](https://github.com/stdlib-js/stdlib/pull/3190)
-   [`1b3cf97`](https://github.com/stdlib-js/stdlib/commit/1b3cf97bd73b4f48b413f68fe5f4377489cd44c8) - add `strided2object` to namespace
-   [`dea5a9b`](https://github.com/stdlib-js/stdlib/commit/dea5a9bf9264c43b6e62af90c39f038b5d4f249d) - add `readDataView` to namespace
-   [`66edaac`](https://github.com/stdlib-js/stdlib/commit/66edaac1799b998fa00c14e6bc0f31db79ad18d4) - add `writeDataView` to namespace

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`8b1548f`](https://github.com/stdlib-js/stdlib/commit/8b1548fb45c1ff131f5edac20cb984344a2d28ec): update namespace declarations

    -   To migrate, users should consult the corresponding packages containing the respective implementations to determine what is breaking. The primary breakages come from the `blas/*` namespace, where we recently refactored how top-level BLAS APIs operate on input arguments.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-max-view-buffer-index-unreleased">

#### [@stdlib/strided/base/max-view-buffer-index](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/max-view-buffer-index)

<details>

<section class="features">

##### Features

-   [`33bda21`](https://github.com/stdlib-js/stdlib/commit/33bda211ab94674737e60da4113c7d5f15661934) - add C API

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-min-view-buffer-index-unreleased">

#### [@stdlib/strided/base/min-view-buffer-index](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/min-view-buffer-index)

<details>

<section class="features">

##### Features

-   [`50795c2`](https://github.com/stdlib-js/stdlib/commit/50795c21034e39baf48e77ef50358af6f52ceb96) - add C API

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`2ca8d8f`](https://github.com/stdlib-js/stdlib/commit/2ca8d8f5f7b6db6f38c3149e0d524db6d9e80b59) - update declaration

</section>

<!-- /.bug-fixes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-read--unreleased">

#### [@stdlib/strided/base/read-](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/read-)

<details>

<section class="features">

##### Features

-   [`1584e8c`](https://github.com/stdlib-js/stdlib/commit/1584e8c0a7f196580a5d9a0fa4c64a1c06102218) - add `strided/base/read-dataview`

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-strided2object-unreleased">

#### [@stdlib/strided/base/strided2object](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/strided2object)

<details>

<section class="features">

##### Features

-   [`c442b93`](https://github.com/stdlib-js/stdlib/commit/c442b93d2ed3af2a2f50402b4b0dc87e9090f596) - add `blas/base/drotm-wasm` [(#3021)](https://github.com/stdlib-js/stdlib/pull/3021)
-   [`6f6df5d`](https://github.com/stdlib-js/stdlib/commit/6f6df5d539a8035cb3af7b1ceec0ead1ee943bee) - add `strided/base/strided2object`

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-write--unreleased">

#### [@stdlib/strided/base/write-](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/write-)

<details>

<section class="features">

##### Features

-   [`dd143b9`](https://github.com/stdlib-js/stdlib/commit/dd143b98c8207e4cab846d9c9a5c0162fb10ee5a) - add `strided/base/write-dataview`

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

</section>

<!-- /.packages -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`8b1548f`](https://github.com/stdlib-js/stdlib/commit/8b1548fb45c1ff131f5edac20cb984344a2d28ec): update namespace declarations

    -   To migrate, users should consult the corresponding packages containing the respective implementations to determine what is breaking. The primary breakages come from the `blas/*` namespace, where we recently refactored how top-level BLAS APIs operate on input arguments.

</section>

<!-- /.breaking-changes -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Aman Bhansali
-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

<section class="commits">

### Commits

<details>

-   [`7d6450c`](https://github.com/stdlib-js/stdlib/commit/7d6450c671dd91fffbec536a216a76f9e094dad0) - **docs:** update related packages sections [(#4186)](https://github.com/stdlib-js/stdlib/pull/4186) _(by stdlib-bot)_
-   [`62364f6`](https://github.com/stdlib-js/stdlib/commit/62364f62ea823a3b52c2ad25660ecd80c71f8f36) - **style:** fix C comment alignment _(by Philipp Burckhardt)_
-   [`8684eb4`](https://github.com/stdlib-js/stdlib/commit/8684eb429498a239bff9bdd72f443dd1cd981552) - **docs:** update related packages sections [(#4114)](https://github.com/stdlib-js/stdlib/pull/4114) _(by stdlib-bot, Athan Reines)_
-   [`5cb36ef`](https://github.com/stdlib-js/stdlib/commit/5cb36ef4c6f8158585ac88867a8dec21ed3fa372) - **docs:** update related packages sections [(#3890)](https://github.com/stdlib-js/stdlib/pull/3890) _(by stdlib-bot)_
-   [`1c56b73`](https://github.com/stdlib-js/stdlib/commit/1c56b737ec018cc818cebf19e5c7947fa684e126) - **docs:** update related packages sections [(#3380)](https://github.com/stdlib-js/stdlib/pull/3380) _(by stdlib-bot)_
-   [`b6a2b0b`](https://github.com/stdlib-js/stdlib/commit/b6a2b0b27dc8cc1e9fc02d9679a3ce468cf49b9d) - **docs:** update namespace table of contents [(#3192)](https://github.com/stdlib-js/stdlib/pull/3192) _(by stdlib-bot, Philipp Burckhardt)_
-   [`8b1548f`](https://github.com/stdlib-js/stdlib/commit/8b1548fb45c1ff131f5edac20cb984344a2d28ec) - **feat:** update namespace TypeScript declarations [(#3190)](https://github.com/stdlib-js/stdlib/pull/3190) _(by stdlib-bot, Philipp Burckhardt)_
-   [`c442b93`](https://github.com/stdlib-js/stdlib/commit/c442b93d2ed3af2a2f50402b4b0dc87e9090f596) - **feat:** add `blas/base/drotm-wasm` [(#3021)](https://github.com/stdlib-js/stdlib/pull/3021) _(by Aman Bhansali, Athan Reines)_
-   [`2c4e5d8`](https://github.com/stdlib-js/stdlib/commit/2c4e5d824e0c5dc8fd536bf79ff565cee100ce46) - **build:** disable additional lint rule in TS tests _(by Philipp Burckhardt)_
-   [`abf0407`](https://github.com/stdlib-js/stdlib/commit/abf040787f6598438b0100a729a8331b7f80f62f) - **chore:** resolve lint errors in TS files _(by Philipp Burckhardt)_
-   [`ff9fa81`](https://github.com/stdlib-js/stdlib/commit/ff9fa81f917d539f1a11fba5580e1744991a8a11) - **docs:** fix TSDoc lint errors _(by Philipp Burckhardt)_
-   [`6e9f42e`](https://github.com/stdlib-js/stdlib/commit/6e9f42e4c912485d9896eaa16c88b70fd3688e97) - **docs:** harmonize list formatting in repl.txt and ensure starting newline _(by Philipp Burckhardt)_
-   [`0c2eafb`](https://github.com/stdlib-js/stdlib/commit/0c2eafb772442a6b2ec4be78490c19f0a70d6235) - **docs:** fix copy and remove extraneous newline _(by Athan Reines)_
-   [`f387603`](https://github.com/stdlib-js/stdlib/commit/f387603e739f88a38af3263ce6ff675ad903ee8c) - **docs:** consistently use declarative instead of imperative sentences outside of intros _(by Philipp Burckhardt)_
-   [`1b3cf97`](https://github.com/stdlib-js/stdlib/commit/1b3cf97bd73b4f48b413f68fe5f4377489cd44c8) - **feat:** add `strided2object` to namespace _(by Athan Reines)_
-   [`6f6df5d`](https://github.com/stdlib-js/stdlib/commit/6f6df5d539a8035cb3af7b1ceec0ead1ee943bee) - **feat:** add `strided/base/strided2object` _(by Athan Reines)_
-   [`6485a76`](https://github.com/stdlib-js/stdlib/commit/6485a7699b2176a95159769a6e461a09185f7721) - **docs:** update examples _(by Athan Reines)_
-   [`dea5a9b`](https://github.com/stdlib-js/stdlib/commit/dea5a9bf9264c43b6e62af90c39f038b5d4f249d) - **feat:** add `readDataView` to namespace _(by Athan Reines)_
-   [`1584e8c`](https://github.com/stdlib-js/stdlib/commit/1584e8c0a7f196580a5d9a0fa4c64a1c06102218) - **feat:** add `strided/base/read-dataview` _(by Athan Reines)_
-   [`6ca3c57`](https://github.com/stdlib-js/stdlib/commit/6ca3c5745b7c01e973da3d3c4e62d549e53afb9f) - **docs:** fix copy _(by Athan Reines)_
-   [`029dfd6`](https://github.com/stdlib-js/stdlib/commit/029dfd67172ab20604f843cdbc5f8106c881ae0c) - **docs:** fix examples _(by Athan Reines)_
-   [`66edaac`](https://github.com/stdlib-js/stdlib/commit/66edaac1799b998fa00c14e6bc0f31db79ad18d4) - **feat:** add `writeDataView` to namespace _(by Athan Reines)_
-   [`dd143b9`](https://github.com/stdlib-js/stdlib/commit/dd143b98c8207e4cab846d9c9a5c0162fb10ee5a) - **feat:** add `strided/base/write-dataview` _(by Athan Reines)_
-   [`33bda21`](https://github.com/stdlib-js/stdlib/commit/33bda211ab94674737e60da4113c7d5f15661934) - **feat:** add C API _(by Athan Reines)_
-   [`2ca8d8f`](https://github.com/stdlib-js/stdlib/commit/2ca8d8f5f7b6db6f38c3149e0d524db6d9e80b59) - **fix:** update declaration _(by Athan Reines)_
-   [`50795c2`](https://github.com/stdlib-js/stdlib/commit/50795c21034e39baf48e77ef50358af6f52ceb96) - **feat:** add C API _(by Athan Reines)_
-   [`fba5621`](https://github.com/stdlib-js/stdlib/commit/fba562144708136533371a0a765bfd834f756601) - **refactor:** annotate parameters as constants and fix docs _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

</section>

<!-- /.release -->

<section class="release" id="v0.3.0">

## 0.3.0 (2024-07-29)

<section class="packages">

### Packages

<section class="package" id="strided-base-v0.3.0">

#### [@stdlib/strided/base](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base)

<details>

<section class="features">

##### Features

-   [`082d2e9`](https://github.com/stdlib-js/stdlib/commit/082d2e98bb97b40f3ae8bbb1965728fe58747df1) - add boolean dtype support to `strided/base/binary-addon-dispatch` [(#2526)](https://github.com/stdlib-js/stdlib/pull/2526)
-   [`599f5e4`](https://github.com/stdlib-js/stdlib/commit/599f5e4435bf9ae550a80162851521095b2410fc) - add boolean dtype support to `strided/base/binary` [(#2525)](https://github.com/stdlib-js/stdlib/pull/2525)
-   [`ccaf9fe`](https://github.com/stdlib-js/stdlib/commit/ccaf9fe07622dcbb1816e8678a8de685c075b4e6) - update namespace TypeScript declarations [(#2490)](https://github.com/stdlib-js/stdlib/pull/2490)
-   [`cc63b8b`](https://github.com/stdlib-js/stdlib/commit/cc63b8b462d786b370c07c7c68aad6a4b491c900) - add `reinterpretBoolean` to namespace
-   [`adba03d`](https://github.com/stdlib-js/stdlib/commit/adba03dafef68163b55f1578802dc7ba87fbceb8) - add `stride2offset` to namespace

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - update include paths

</section>

<!-- /.bug-fixes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dtype-resolve-str-v0.3.0">

#### [@stdlib/strided/base/dtype-resolve-str](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dtype-resolve-str)

<details>

<section class="bug-fixes">

##### Bug Fixes

-   [`a96a408`](https://github.com/stdlib-js/stdlib/commit/a96a408fec1b83def148098dc9cf8a233e071526) - accommodate enum values equal to `0`

</section>

<!-- /.bug-fixes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-mskunary-v0.3.0">

#### [@stdlib/strided/base/mskunary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/mskunary)

<details>

<section class="features">

##### Features

-   [`dc36936`](https://github.com/stdlib-js/stdlib/commit/dc369364ee617f8f62b40d951a0f0d34f795da6e) - add boolean dtype support to `strided/base/mskunary` [(#2520)](https://github.com/stdlib-js/stdlib/pull/2520)

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - update include paths

</section>

<!-- /.bug-fixes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-mskunary-addon-dispatch-v0.3.0">

#### [@stdlib/strided/base/mskunary-addon-dispatch](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/mskunary-addon-dispatch)

<details>

<section class="features">

##### Features

-   [`f5ee96c`](https://github.com/stdlib-js/stdlib/commit/f5ee96c41495ce92c5d75ed0a2934ae9f92cf46c) - add boolean dtype support to `strided/base/mskunary-addon-dispatch` [(#2523)](https://github.com/stdlib-js/stdlib/pull/2523)

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-nullary-v0.3.0">

#### [@stdlib/strided/base/nullary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/nullary)

<details>

<section class="features">

##### Features

-   [`4d3d36e`](https://github.com/stdlib-js/stdlib/commit/4d3d36e8b492c8df66a1fdbdb71ff7093d95aa9a) - add boolean dtype support to `strided/base/nullary` [(#2513)](https://github.com/stdlib-js/stdlib/pull/2513)

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - update include paths

</section>

<!-- /.bug-fixes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-nullary-addon-dispatch-v0.3.0">

#### [@stdlib/strided/base/nullary-addon-dispatch](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/nullary-addon-dispatch)

<details>

<section class="features">

##### Features

-   [`8831e32`](https://github.com/stdlib-js/stdlib/commit/8831e321bcf7a46141f66a9756f67dcc8d277ccc) - add boolean dtype support to `strided/base/nullary-addon-dispatch` [(#2521)](https://github.com/stdlib-js/stdlib/pull/2521)

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-reinterpret-boolean-v0.3.0">

#### [@stdlib/strided/base/reinterpret-boolean](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/reinterpret-boolean)

<details>

<section class="features">

##### Features

-   [`1d52f5a`](https://github.com/stdlib-js/stdlib/commit/1d52f5a23cae38bee1ffa324459c4c7eb3c91a06) - add `strided/base/reinterpret-boolean` [(#2297)](https://github.com/stdlib-js/stdlib/pull/2297)

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-stride2offset-v0.3.0">

#### [@stdlib/strided/base/stride2offset](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/stride2offset)

<details>

<section class="features">

##### Features

-   [`cb53df7`](https://github.com/stdlib-js/stdlib/commit/cb53df70e2afc7c11aabf3846db305424d012150) - add `strided/base/stride2offset`

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-v0.3.0">

#### [@stdlib/strided/base/unary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary)

<details>

<section class="features">

##### Features

-   [`441d61c`](https://github.com/stdlib-js/stdlib/commit/441d61c7abef39ebb7bd9b2ce99a2300aa27cbfd) - add boolean dtype support to `strided/base/unary` [(#2519)](https://github.com/stdlib-js/stdlib/pull/2519)

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - update include paths

</section>

<!-- /.bug-fixes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-addon-dispatch-v0.3.0">

#### [@stdlib/strided/base/unary-addon-dispatch](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary-addon-dispatch)

<details>

<section class="features">

##### Features

-   [`867c4e2`](https://github.com/stdlib-js/stdlib/commit/867c4e221e2320d37c0f99dd47e19ab523c56c56) - add boolean dtype support to `strided/base/unary-addon-dispatch` [(#2522)](https://github.com/stdlib-js/stdlib/pull/2522)

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

</section>

<!-- /.packages -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Jaysukh Makvana
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

<section class="commits">

### Commits

<details>

-   [`2777e4b`](https://github.com/stdlib-js/stdlib/commit/2777e4be161869d09406e3b17947d24c64b47af2) - **bench:** resolve lint errors in benchmarks _(by Athan Reines)_
-   [`0406147`](https://github.com/stdlib-js/stdlib/commit/04061476d1036e1b8b786736b1ba1653eddff1ef) - **refactor:** update paths _(by Athan Reines)_
-   [`b9703b5`](https://github.com/stdlib-js/stdlib/commit/b9703b569dc2f0a67e604e388a0d188b08138b48) - **refactor:** update paths _(by Athan Reines)_
-   [`32bbcb3`](https://github.com/stdlib-js/stdlib/commit/32bbcb3b3dae1f028fd18166ee7875a93d44d0ee) - **refactor:** update paths _(by Athan Reines)_
-   [`8d4c46b`](https://github.com/stdlib-js/stdlib/commit/8d4c46b10ca912401e0ff0caa37a17cd3c443c2f) - **refactor:** update paths _(by Athan Reines)_
-   [`ed9c0a5`](https://github.com/stdlib-js/stdlib/commit/ed9c0a5e55ff09af3dd6af8c38615480e2c1828e) - **refactor:** update paths _(by Athan Reines)_
-   [`18b3c79`](https://github.com/stdlib-js/stdlib/commit/18b3c79c5035c7082618b7379cd6576e64393a96) - **refactor:** update paths _(by Athan Reines)_
-   [`d04dcbd`](https://github.com/stdlib-js/stdlib/commit/d04dcbd6dc3b0bf4a89bd3947d317fa5ff15bb38) - **docs:** remove private annotations in C comments _(by Philipp Burckhardt)_
-   [`1f39c86`](https://github.com/stdlib-js/stdlib/commit/1f39c864924bf3d3cf4b5d8d39010e634416b66d) - **docs:** fix example _(by Athan Reines)_
-   [`4708d70`](https://github.com/stdlib-js/stdlib/commit/4708d704db87214af36a82e77072e3aade8c29fd) - **docs:** update namespace table of contents [(#2532)](https://github.com/stdlib-js/stdlib/pull/2532) _(by stdlib-bot, Philipp Burckhardt)_
-   [`7b973eb`](https://github.com/stdlib-js/stdlib/commit/7b973eb5ce98a21ce6cb62021f9cb3090d7d5524) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`aeb7b51`](https://github.com/stdlib-js/stdlib/commit/aeb7b514c9b48c1ddbfb84dfd269b65838ec38c8) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`6249bfd`](https://github.com/stdlib-js/stdlib/commit/6249bfd06ccb8fcd57117473bed9e6f63f203fb9) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`320429f`](https://github.com/stdlib-js/stdlib/commit/320429f06d6e0c4b4007e232facd40be18e8dfa1) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`4436cd1`](https://github.com/stdlib-js/stdlib/commit/4436cd18548a94684e37bbb070d4d0c02d501e13) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`6d1214c`](https://github.com/stdlib-js/stdlib/commit/6d1214c3924e1ce46da96eec67443405fb2cdda6) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`fbe7514`](https://github.com/stdlib-js/stdlib/commit/fbe7514000293f76032de91b4c5f55621d16176f) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`07f85a1`](https://github.com/stdlib-js/stdlib/commit/07f85a1a76b4c043770509482d223a0895d65ae4) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`3656b32`](https://github.com/stdlib-js/stdlib/commit/3656b32bde500f96319833f3d4f80bfc18099ff1) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`bb1d8a0`](https://github.com/stdlib-js/stdlib/commit/bb1d8a06bb865dbac2fb8c9a6e69a5c9c46e1a05) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`cfcce81`](https://github.com/stdlib-js/stdlib/commit/cfcce813757c18dd4e58eb612d594efbba3023e3) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`e47b1be`](https://github.com/stdlib-js/stdlib/commit/e47b1be3a80eb9a7ab1fa9f421a133a580ce4366) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`95cf265`](https://github.com/stdlib-js/stdlib/commit/95cf2652a5c8938b7b682e562d29c0540f3f33ba) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`0d4ef60`](https://github.com/stdlib-js/stdlib/commit/0d4ef609d7df182136e5421b5340d92c466afb7c) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`741144c`](https://github.com/stdlib-js/stdlib/commit/741144c09dec958375c7d6e16e46cc08707e7506) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`1600510`](https://github.com/stdlib-js/stdlib/commit/1600510d9214b9a33dc4dffa26762c78a1fa88e2) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`223ff4e`](https://github.com/stdlib-js/stdlib/commit/223ff4e67a753e7707d9aac41d01905c17c434ed) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`abffdf1`](https://github.com/stdlib-js/stdlib/commit/abffdf1ac7615c960b4b496dfb7936f6f243d6d4) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`341533b`](https://github.com/stdlib-js/stdlib/commit/341533b52c5ed1a389655f411fb897376b7c72ca) - **refactor:** use utility to resolve offset _(by Athan Reines)_
-   [`9bd72c5`](https://github.com/stdlib-js/stdlib/commit/9bd72c5900e083c88b4b0525359a627d25839ba0) - **refactor:** use utility to resolve stride _(by Athan Reines)_
-   [`c1da2d5`](https://github.com/stdlib-js/stdlib/commit/c1da2d5a424afe0fe98ed5b91c119850d1f0b6f0) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`64592e5`](https://github.com/stdlib-js/stdlib/commit/64592e5433563c9b028393e16757ffd8efcc2f0a) - **refactor:** reduce code duplication _(by Athan Reines)_
-   [`082d2e9`](https://github.com/stdlib-js/stdlib/commit/082d2e98bb97b40f3ae8bbb1965728fe58747df1) - **feat:** add boolean dtype support to `strided/base/binary-addon-dispatch` [(#2526)](https://github.com/stdlib-js/stdlib/pull/2526) _(by Jaysukh Makvana)_
-   [`599f5e4`](https://github.com/stdlib-js/stdlib/commit/599f5e4435bf9ae550a80162851521095b2410fc) - **feat:** add boolean dtype support to `strided/base/binary` [(#2525)](https://github.com/stdlib-js/stdlib/pull/2525) _(by Jaysukh Makvana, Athan Reines)_
-   [`dc36936`](https://github.com/stdlib-js/stdlib/commit/dc369364ee617f8f62b40d951a0f0d34f795da6e) - **feat:** add boolean dtype support to `strided/base/mskunary` [(#2520)](https://github.com/stdlib-js/stdlib/pull/2520) _(by Jaysukh Makvana)_
-   [`441d61c`](https://github.com/stdlib-js/stdlib/commit/441d61c7abef39ebb7bd9b2ce99a2300aa27cbfd) - **feat:** add boolean dtype support to `strided/base/unary` [(#2519)](https://github.com/stdlib-js/stdlib/pull/2519) _(by Jaysukh Makvana)_
-   [`f5ee96c`](https://github.com/stdlib-js/stdlib/commit/f5ee96c41495ce92c5d75ed0a2934ae9f92cf46c) - **feat:** add boolean dtype support to `strided/base/mskunary-addon-dispatch` [(#2523)](https://github.com/stdlib-js/stdlib/pull/2523) _(by Jaysukh Makvana)_
-   [`867c4e2`](https://github.com/stdlib-js/stdlib/commit/867c4e221e2320d37c0f99dd47e19ab523c56c56) - **feat:** add boolean dtype support to `strided/base/unary-addon-dispatch` [(#2522)](https://github.com/stdlib-js/stdlib/pull/2522) _(by Jaysukh Makvana)_
-   [`8831e32`](https://github.com/stdlib-js/stdlib/commit/8831e321bcf7a46141f66a9756f67dcc8d277ccc) - **feat:** add boolean dtype support to `strided/base/nullary-addon-dispatch` [(#2521)](https://github.com/stdlib-js/stdlib/pull/2521) _(by Jaysukh Makvana)_
-   [`4d3d36e`](https://github.com/stdlib-js/stdlib/commit/4d3d36e8b492c8df66a1fdbdb71ff7093d95aa9a) - **feat:** add boolean dtype support to `strided/base/nullary` [(#2513)](https://github.com/stdlib-js/stdlib/pull/2513) _(by Jaysukh Makvana, Athan Reines)_
-   [`ccaf9fe`](https://github.com/stdlib-js/stdlib/commit/ccaf9fe07622dcbb1816e8678a8de685c075b4e6) - **feat:** update namespace TypeScript declarations [(#2490)](https://github.com/stdlib-js/stdlib/pull/2490) _(by stdlib-bot, Athan Reines)_
-   [`cc63b8b`](https://github.com/stdlib-js/stdlib/commit/cc63b8b462d786b370c07c7c68aad6a4b491c900) - **feat:** add `reinterpretBoolean` to namespace _(by Athan Reines)_
-   [`adba03d`](https://github.com/stdlib-js/stdlib/commit/adba03dafef68163b55f1578802dc7ba87fbceb8) - **feat:** add `stride2offset` to namespace _(by Athan Reines)_
-   [`11ad206`](https://github.com/stdlib-js/stdlib/commit/11ad206dbf92e0a1827ccdf5aa8f4c58bf82ed2a) - **bench:** fix function name _(by Athan Reines)_
-   [`cb53df7`](https://github.com/stdlib-js/stdlib/commit/cb53df70e2afc7c11aabf3846db305424d012150) - **feat:** add `strided/base/stride2offset` _(by Athan Reines)_
-   [`a96a408`](https://github.com/stdlib-js/stdlib/commit/a96a408fec1b83def148098dc9cf8a233e071526) - **fix:** accommodate enum values equal to `0` _(by Athan Reines)_
-   [`1d52f5a`](https://github.com/stdlib-js/stdlib/commit/1d52f5a23cae38bee1ffa324459c4c7eb3c91a06) - **feat:** add `strided/base/reinterpret-boolean` [(#2297)](https://github.com/stdlib-js/stdlib/pull/2297) _(by Jaysukh Makvana, Athan Reines)_
-   [`cf3f92e`](https://github.com/stdlib-js/stdlib/commit/cf3f92eddd20ec1a4106c8a34f7d7705a9a99dbc) - **fix:** update include paths _(by Athan Reines)_
-   [`75d4f83`](https://github.com/stdlib-js/stdlib/commit/75d4f83cb85610d23a04dc21a03f8075f6d3665f) - **refactor:** update require and include paths _(by Athan Reines)_
-   [`ec98887`](https://github.com/stdlib-js/stdlib/commit/ec9888724c28aa7218d88ff62b91b71c0089c559) - **docs:** update related packages sections [(#2241)](https://github.com/stdlib-js/stdlib/pull/2241) _(by stdlib-bot)_

</details>

</section>

<!-- /.commits -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.1">

## 0.2.1 (2024-02-25)

<section class="packages">

### Packages

<section class="package" id="strided-base-v0.2.1">

#### [@stdlib/strided/base](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base)

<details>

<section class="features">

##### Features

-   [`0adcae5`](https://github.com/stdlib-js/stdlib/commit/0adcae51386086e2ef5fb5d78402389cff776deb) - update namespace TypeScript declarations [(#1340)](https://github.com/stdlib-js/stdlib/pull/1340)

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`0adcae5`](https://github.com/stdlib-js/stdlib/commit/0adcae51386086e2ef5fb5d78402389cff776deb): rename exported aliases

    -   To migrate, users should consult the relevant namespace documentation and associated commits in order to determine which aliases have been renamed.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

</section>

<!-- /.packages -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`0adcae5`](https://github.com/stdlib-js/stdlib/commit/0adcae51386086e2ef5fb5d78402389cff776deb): rename exported aliases

    -   To migrate, users should consult the relevant namespace documentation and associated commits in order to determine which aliases have been renamed.

</section>

<!-- /.breaking-changes -->

<section class="contributors">

### Contributors

A total of 1 person contributed to this release. Thank you to this contributor:

-   Athan Reines

</section>

<!-- /.contributors -->

<section class="commits">

### Commits

<details>

-   [`39b8176`](https://github.com/stdlib-js/stdlib/commit/39b81766b9d8a5e89ba4a26e5ea07f6413b46973) - **docs:** update namespace table of contents [(#1341)](https://github.com/stdlib-js/stdlib/pull/1341) _(by stdlib-bot, Athan Reines)_
-   [`0adcae5`](https://github.com/stdlib-js/stdlib/commit/0adcae51386086e2ef5fb5d78402389cff776deb) - **feat:** update namespace TypeScript declarations [(#1340)](https://github.com/stdlib-js/stdlib/pull/1340) _(by stdlib-bot, Athan Reines)_

</details>

</section>

<!-- /.commits -->

</section>

<!-- /.release -->

<section class="release" id="v0.2.0">

## 0.2.0 (2024-02-14)

<section class="packages">

### Packages

<section class="package" id="strided-base-v0.2.0">

#### [@stdlib/strided/base](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base)

<details>

<section class="features">

##### Features

-   [`862cd8f`](https://github.com/stdlib-js/stdlib/commit/862cd8fb848fb40521acfb563e40242b8a3762a6) - add `reinterpretComplex` to namespace
-   [`783804d`](https://github.com/stdlib-js/stdlib/commit/783804dbc9b3899c5227c5593e0ca1e8a6a9f195) - update namespace TypeScript declarations [(#1170)](https://github.com/stdlib-js/stdlib/pull/1170)

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-reinterpret-complex-v0.2.0">

#### [@stdlib/strided/base/reinterpret-complex](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/reinterpret-complex)

<details>

<section class="features">

##### Features

-   [`8f40030`](https://github.com/stdlib-js/stdlib/commit/8f4003046fead850c53b405d2c1f0ee6584459f0) - add `strided/base/reinterpret-complex`

</section>

<!-- /.features -->

</details>

</section>

<!-- /.package -->

</section>

<!-- /.packages -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

<section class="commits">

### Commits

<details>

-   [`862cd8f`](https://github.com/stdlib-js/stdlib/commit/862cd8fb848fb40521acfb563e40242b8a3762a6) - **feat:** add `reinterpretComplex` to namespace _(by Athan Reines)_
-   [`8f40030`](https://github.com/stdlib-js/stdlib/commit/8f4003046fead850c53b405d2c1f0ee6584459f0) - **feat:** add `strided/base/reinterpret-complex` _(by Athan Reines)_
-   [`dea49e0`](https://github.com/stdlib-js/stdlib/commit/dea49e03ab5571233e3da26835a6a6d3256d5737) - **docs:** use single quotes in require calls instead of backticks _(by Philipp Burckhardt)_
-   [`783804d`](https://github.com/stdlib-js/stdlib/commit/783804dbc9b3899c5227c5593e0ca1e8a6a9f195) - **feat:** update namespace TypeScript declarations [(#1170)](https://github.com/stdlib-js/stdlib/pull/1170) _(by stdlib-bot, Athan Reines)_
-   [`d1b801d`](https://github.com/stdlib-js/stdlib/commit/d1b801d5986af48ab59e426fd47e7fecdb16c286) - **refactor:** use stdlib package to sum five numbers _(by Athan Reines)_
-   [`19b9334`](https://github.com/stdlib-js/stdlib/commit/19b9334c6c4f02e012bc2b5ba9569035ef80daa9) - **refactor:** use stdlib package to sum four numbers _(by Athan Reines)_
-   [`d3f4b2f`](https://github.com/stdlib-js/stdlib/commit/d3f4b2f050facb36cfeb62192746fdfe305a21c7) - **refactor:** use stdlib package to sum three numbers _(by Athan Reines)_
-   [`9502ed2`](https://github.com/stdlib-js/stdlib/commit/9502ed27e2853e312c556a48bdd7775095e66709) - **build:** replace tslint directive with eslint equivalent _(by Philipp Burckhardt)_
-   [`46d049b`](https://github.com/stdlib-js/stdlib/commit/46d049b5d38f9ef6e426d6a517ac8925c94d7642) - **build:** replace tslint directive _(by Philipp Burckhardt)_
-   [`7db5611`](https://github.com/stdlib-js/stdlib/commit/7db56115b014aa41e4a3458629286ae3bd99c4e7) - **docs:** update links and fix headings _(by Athan Reines)_
-   [`d73bbf4`](https://github.com/stdlib-js/stdlib/commit/d73bbf43d222f935085f8ecf7526e5f57835f74e) - **build:** replace lint directives _(by Philipp Burckhardt)_
-   [`f9c75ce`](https://github.com/stdlib-js/stdlib/commit/f9c75ce726ed4e5fade8622315bb98094dad8561) - **build:** remove tslint directives _(by Philipp Burckhardt)_

</details>

</section>

<!-- /.commits -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2023-09-24)

<section class="packages">

### Packages

<section class="package" id="strided-base-v0.1.0">

#### [@stdlib/strided/base](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`b544a52`](https://github.com/stdlib-js/stdlib/commit/b544a5272fdd3eaff7ff3bd23963400232641e7b) - update import path for `Collection` type definition and refactor to use generics
-   [`32a2827`](https://github.com/stdlib-js/stdlib/commit/32a282799ffd272d2a0554e81755a14923564e51) - update import paths for complex type defs
-   [`0a81f83`](https://github.com/stdlib-js/stdlib/commit/0a81f837f2eb6e7c0fec6bf5d25066f6c11095a9) - resolve C lint errors

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-cmap-v0.1.0">

#### [@stdlib/strided/base/cmap](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/cmap)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`32a2827`](https://github.com/stdlib-js/stdlib/commit/32a282799ffd272d2a0554e81755a14923564e51) - update import paths for complex type defs

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dmap-v0.1.0">

#### [@stdlib/strided/base/dmap](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dmap)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dmap2-v0.1.0">

#### [@stdlib/strided/base/dmap2](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dmap2)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dmskmap-v0.1.0">

#### [@stdlib/strided/base/dmskmap](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dmskmap)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dmskmap2-v0.1.0">

#### [@stdlib/strided/base/dmskmap2](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dmskmap2)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dtype-enum2str-v0.1.0">

#### [@stdlib/strided/base/dtype-enum2str](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dtype-enum2str)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dtype-resolve-enum-v0.1.0">

#### [@stdlib/strided/base/dtype-resolve-enum](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dtype-resolve-enum)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dtype-resolve-str-v0.1.0">

#### [@stdlib/strided/base/dtype-resolve-str](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dtype-resolve-str)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-dtype-str2enum-v0.1.0">

#### [@stdlib/strided/base/dtype-str2enum](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/dtype-str2enum)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-function-object-v0.1.0">

#### [@stdlib/strided/base/function-object](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/function-object)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-map-by-v0.1.0">

#### [@stdlib/strided/base/map-by](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/map-by)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`e2a2a33`](https://github.com/stdlib-js/stdlib/commit/e2a2a338451784fc2c22d944a4106efa473cbb17) - update import path for `Collection` type definition and use generics

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-map-by2-v0.1.0">

#### [@stdlib/strided/base/map-by2](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/map-by2)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`cff1be6`](https://github.com/stdlib-js/stdlib/commit/cff1be61f870c55caa4ffffb8d2dfe6c93ded927) - update import path for `Collection` type definition and refactor to use generics

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-max-view-buffer-index-v0.1.0">

#### [@stdlib/strided/base/max-view-buffer-index](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/max-view-buffer-index)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-meta--v0.1.0">

#### [@stdlib/strided/base/meta-](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/meta-)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-min-view-buffer-index-v0.1.0">

#### [@stdlib/strided/base/min-view-buffer-index](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/min-view-buffer-index)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-mskunary-v0.1.0">

#### [@stdlib/strided/base/mskunary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/mskunary)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`0a81f83`](https://github.com/stdlib-js/stdlib/commit/0a81f837f2eb6e7c0fec6bf5d25066f6c11095a9) - resolve C lint errors

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-mskunary-addon-dispatch-v0.1.0">

#### [@stdlib/strided/base/mskunary-addon-dispatch](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/mskunary-addon-dispatch)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`a51eab8`](https://github.com/stdlib-js/stdlib/commit/a51eab8a37968194e388922e62621bc8c330ff5f) - update import path for `Collection` type definition and refactor to use generics
-   [`9212514`](https://github.com/stdlib-js/stdlib/commit/9212514cd0ba9a681c2ca86ebe2fd3b61f866b64) - set correct package names and descriptions

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-mskunary-dtype-signatures-v0.1.0">

#### [@stdlib/strided/base/mskunary-dtype-signatures](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/mskunary-dtype-signatures)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-mskunary-signature-callbacks-v0.1.0">

#### [@stdlib/strided/base/mskunary-signature-callbacks](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/mskunary-signature-callbacks)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`32a2827`](https://github.com/stdlib-js/stdlib/commit/32a282799ffd272d2a0554e81755a14923564e51) - update import paths for complex type defs

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-nullary-v0.1.0">

#### [@stdlib/strided/base/nullary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/nullary)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`0a81f83`](https://github.com/stdlib-js/stdlib/commit/0a81f837f2eb6e7c0fec6bf5d25066f6c11095a9) - resolve C lint errors

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-nullary-addon-dispatch-v0.1.0">

#### [@stdlib/strided/base/nullary-addon-dispatch](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/nullary-addon-dispatch)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`50bafc3`](https://github.com/stdlib-js/stdlib/commit/50bafc3c54152ff252560823e64958ccfb3035e4) - update import path for `Collection` type definition and refactor to use generics

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-offset-view-v0.1.0">

#### [@stdlib/strided/base/offset-view](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/offset-view)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-quaternary-v0.1.0">

#### [@stdlib/strided/base/quaternary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/quaternary)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-quinary-v0.1.0">

#### [@stdlib/strided/base/quinary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/quinary)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-reinterpret-complex128-v0.1.0">

#### [@stdlib/strided/base/reinterpret-complex128](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/reinterpret-complex128)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-reinterpret-complex64-v0.1.0">

#### [@stdlib/strided/base/reinterpret-complex64](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/reinterpret-complex64)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-smap-v0.1.0">

#### [@stdlib/strided/base/smap](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/smap)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-smap2-v0.1.0">

#### [@stdlib/strided/base/smap2](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/smap2)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-smskmap-v0.1.0">

#### [@stdlib/strided/base/smskmap](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/smskmap)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-smskmap2-v0.1.0">

#### [@stdlib/strided/base/smskmap2](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/smskmap2)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-ternary-v0.1.0">

#### [@stdlib/strided/base/ternary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/ternary)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-v0.1.0">

#### [@stdlib/strided/base/unary](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`0a81f83`](https://github.com/stdlib-js/stdlib/commit/0a81f837f2eb6e7c0fec6bf5d25066f6c11095a9) - resolve C lint errors

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-addon-dispatch-v0.1.0">

#### [@stdlib/strided/base/unary-addon-dispatch](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary-addon-dispatch)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`fb02af2`](https://github.com/stdlib-js/stdlib/commit/fb02af211b127fd621c00b1609741bf012804685) - update import path for `Collection` type definition and refactor to use generics

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-by-v0.1.0">

#### [@stdlib/strided/base/unary-by](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary-by)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`b798cac`](https://github.com/stdlib-js/stdlib/commit/b798cac25d12722bcb8f858f025d916aa9f3d366) - update import path for `Collection` type definition and use generics

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-dtype-signatures-v0.1.0">

#### [@stdlib/strided/base/unary-dtype-signatures](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary-dtype-signatures)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-unary-signature-callbacks-v0.1.0">

#### [@stdlib/strided/base/unary-signature-callbacks](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/unary-signature-callbacks)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`32a2827`](https://github.com/stdlib-js/stdlib/commit/32a282799ffd272d2a0554e81755a14923564e51) - update import paths for complex type defs

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

<section class="package" id="strided-base-zmap-v0.1.0">

#### [@stdlib/strided/base/zmap](https://github.com/stdlib-js/stdlib/tree/develop/lib/node_modules/%40stdlib/strided/base/zmap)

<details>

<section class="features">

##### Features

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - update minimum TypeScript version

</section>

<!-- /.features -->

<section class="bug-fixes">

##### Bug Fixes

-   [`32a2827`](https://github.com/stdlib-js/stdlib/commit/32a282799ffd272d2a0554e81755a14923564e51) - update import paths for complex type defs

</section>

<!-- /.bug-fixes -->

<section class="breaking-changes">

##### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

</details>

</section>

<!-- /.package -->

</section>

<!-- /.packages -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7): update minimum TypeScript version to 4.1

    -   To migrate, users should upgrade their TypeScript version to at least version 4.1.

</section>

<!-- /.breaking-changes -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

<section class="commits">

### Commits

<details>

-   [`cff1be6`](https://github.com/stdlib-js/stdlib/commit/cff1be61f870c55caa4ffffb8d2dfe6c93ded927) - **fix:** update import path for `Collection` type definition and refactor to use generics _(by Athan Reines)_
-   [`a51eab8`](https://github.com/stdlib-js/stdlib/commit/a51eab8a37968194e388922e62621bc8c330ff5f) - **fix:** update import path for `Collection` type definition and refactor to use generics _(by Athan Reines)_
-   [`fb02af2`](https://github.com/stdlib-js/stdlib/commit/fb02af211b127fd621c00b1609741bf012804685) - **fix:** update import path for `Collection` type definition and refactor to use generics _(by Athan Reines)_
-   [`50bafc3`](https://github.com/stdlib-js/stdlib/commit/50bafc3c54152ff252560823e64958ccfb3035e4) - **fix:** update import path for `Collection` type definition and refactor to use generics _(by Athan Reines)_
-   [`b544a52`](https://github.com/stdlib-js/stdlib/commit/b544a5272fdd3eaff7ff3bd23963400232641e7b) - **fix:** update import path for `Collection` type definition and refactor to use generics _(by Athan Reines)_
-   [`b798cac`](https://github.com/stdlib-js/stdlib/commit/b798cac25d12722bcb8f858f025d916aa9f3d366) - **fix:** update import path for `Collection` type definition and use generics _(by Athan Reines)_
-   [`e2a2a33`](https://github.com/stdlib-js/stdlib/commit/e2a2a338451784fc2c22d944a4106efa473cbb17) - **fix:** update import path for `Collection` type definition and use generics _(by Athan Reines)_
-   [`ca91187`](https://github.com/stdlib-js/stdlib/commit/ca9118749c1e8f3ad1f722ef69e3dc602e57b6c7) - **feat:** update minimum TypeScript version _(by Philipp Burckhardt)_
-   [`32a2827`](https://github.com/stdlib-js/stdlib/commit/32a282799ffd272d2a0554e81755a14923564e51) - **fix:** update import paths for complex type defs _(by Athan Reines)_
-   [`9212514`](https://github.com/stdlib-js/stdlib/commit/9212514cd0ba9a681c2ca86ebe2fd3b61f866b64) - **fix:** set correct package names and descriptions _(by Philipp Burckhardt)_
-   [`55866ea`](https://github.com/stdlib-js/stdlib/commit/55866ea8ef1282528b839fd9ce9c43c6a80056f8) - **test:** use strictEqual checks _(by Philipp Burckhardt)_
-   [`0a81f83`](https://github.com/stdlib-js/stdlib/commit/0a81f837f2eb6e7c0fec6bf5d25066f6c11095a9) - **fix:** resolve C lint errors _(by Athan Reines)_
-   [`28e1c84`](https://github.com/stdlib-js/stdlib/commit/28e1c84390d88044883c9ef940a12f38d66ea3ef) - **docs:** resolve C lint errors _(by Athan Reines)_
-   [`cf94561`](https://github.com/stdlib-js/stdlib/commit/cf94561e14fd89fed4c600352f0c638987e4a3c3) - **refactor:** add shebang to script _(by Athan Reines)_
-   [`6341e64`](https://github.com/stdlib-js/stdlib/commit/6341e64d23a90a13ac5505ca92d5e874568a9462) - **docs:** remove comment from example _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

</section>

<!-- /.release -->

<section class="release" id="v0.0.7">

## 0.0.7 (2022-02-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.6">

## 0.0.6 (2021-08-22)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.5">

## 0.0.5 (2021-07-07)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.4">

## 0.0.4 (2021-06-27)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.3">

## 0.0.3 (2021-06-16)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.2">

## 0.0.2 (2021-06-15)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.0.1">

## 0.0.1 (2021-06-14)

No changes reported for this release.

</section>

<!-- /.release -->

