# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-06-01)

<section class="features">

### Features

-   [`6afa527`](https://github.com/stdlib-js/stdlib/commit/6afa5271c97c6b90710a4fb15d34bf04e8ae71b4) - add `scale` to namespace
-   [`7475c9d`](https://github.com/stdlib-js/stdlib/commit/7475c9dfd5461211d8071b7073b8958300dd5838) - add `complex/float32/base/scale` [(#7156)](https://github.com/stdlib-js/stdlib/pull/7156)
-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7) - update `complex/float32/base/identity` to accept stdlib complex numbers [(#6235)](https://github.com/stdlib-js/stdlib/pull/6235)
-   [`31343c9`](https://github.com/stdlib-js/stdlib/commit/31343c901e94328361327c4d7054a71052599916) - add `complex/float32/base/identity`
-   [`3a62008`](https://github.com/stdlib-js/stdlib/commit/3a620083a7978286cc05db9231ecbee4d0478e1a) - add `complex/float32/base/sub`
-   [`4866c10`](https://github.com/stdlib-js/stdlib/commit/4866c103418bc09e2c11a3f0238ac6941e830eca) - add `complex/float32/base/neg`
-   [`ae8e7b9`](https://github.com/stdlib-js/stdlib/commit/ae8e7b9f2140d1a5b98e8bc03fb909df3171d410) - update namespace TypeScript declarations [(#5254)](https://github.com/stdlib-js/stdlib/pull/5254)
-   [`d7154e2`](https://github.com/stdlib-js/stdlib/commit/d7154e2c7756ce51a9bbbf38848960ea988d4ea6) - add `strided` and `assign` APIs to `complex/float32/base/mul` [(#5205)](https://github.com/stdlib-js/stdlib/pull/5205)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7): use stdlib C complex64 dtype

    -   To migrate, users should provide a value having the type `stdlib_complex64_t`, rather than a built-in C99 single-precision complex dtype. This dtype is available via the package `@stdlib/complex-float32/ctor`.

-   [`ae8e7b9`](https://github.com/stdlib-js/stdlib/commit/ae8e7b9f2140d1a5b98e8bc03fb909df3171d410): remove `dmaxabs`

    -   To migrate, users should access `dmaxabs` via the `stats/strided` namespace.

</section>

<!-- /.breaking-changes -->

<section class="issues">

### Closed Issues

A total of 2 issues were closed in this release:

[#5203](https://github.com/stdlib-js/stdlib/issues/5203), [#6698](https://github.com/stdlib-js/stdlib/issues/6698)

</section>

<!-- /.issues -->

<section class="commits">

### Commits

<details>

-   [`6afa527`](https://github.com/stdlib-js/stdlib/commit/6afa5271c97c6b90710a4fb15d34bf04e8ae71b4) - **feat:** add `scale` to namespace _(by Athan Reines)_
-   [`7475c9d`](https://github.com/stdlib-js/stdlib/commit/7475c9dfd5461211d8071b7073b8958300dd5838) - **feat:** add `complex/float32/base/scale` [(#7156)](https://github.com/stdlib-js/stdlib/pull/7156) _(by Shabareesh Shetty, Athan Reines)_
-   [`c3320f1`](https://github.com/stdlib-js/stdlib/commit/c3320f1da27e449679eecd2f19f865ae60f72aa5) - **docs:** update namespace table of contents [(#6764)](https://github.com/stdlib-js/stdlib/pull/6764) _(by stdlib-bot)_
-   [`93a9aa2`](https://github.com/stdlib-js/stdlib/commit/93a9aa2f18ce81d06fdaf04c136ed48851eb11f0) - **chore:** fix JavaScript lint errors [(#6699)](https://github.com/stdlib-js/stdlib/pull/6699) _(by SAHIL KUMAR, Philipp Burckhardt)_
-   [`a1e230f`](https://github.com/stdlib-js/stdlib/commit/a1e230f29297caa89880e9c194c615a0400fb7bc) - **chore:** clean up cppcheck-suppress comments _(by Karan Anand)_
-   [`8ab1153`](https://github.com/stdlib-js/stdlib/commit/8ab1153533c1dcbe7eb1ce05590843dbeffa67e7) - **feat:** update `complex/float32/base/identity` to accept stdlib complex numbers [(#6235)](https://github.com/stdlib-js/stdlib/pull/6235) _(by Gururaj Gurram)_
-   [`31343c9`](https://github.com/stdlib-js/stdlib/commit/31343c901e94328361327c4d7054a71052599916) - **feat:** add `complex/float32/base/identity` _(by Gururaj Gurram)_
-   [`89ecfe0`](https://github.com/stdlib-js/stdlib/commit/89ecfe0212aef0448017f8e404a3862fda851170) - **refactor:** update paths _(by Gururaj Gurram)_
-   [`3a62008`](https://github.com/stdlib-js/stdlib/commit/3a620083a7978286cc05db9231ecbee4d0478e1a) - **feat:** add `complex/float32/base/sub` _(by Gururaj Gurram)_
-   [`4866c10`](https://github.com/stdlib-js/stdlib/commit/4866c103418bc09e2c11a3f0238ac6941e830eca) - **feat:** add `complex/float32/base/neg` _(by Gururaj Gurram)_
-   [`ae8e7b9`](https://github.com/stdlib-js/stdlib/commit/ae8e7b9f2140d1a5b98e8bc03fb909df3171d410) - **feat:** update namespace TypeScript declarations [(#5254)](https://github.com/stdlib-js/stdlib/pull/5254) _(by stdlib-bot)_
-   [`d7154e2`](https://github.com/stdlib-js/stdlib/commit/d7154e2c7756ce51a9bbbf38848960ea988d4ea6) - **feat:** add `strided` and `assign` APIs to `complex/float32/base/mul` [(#5205)](https://github.com/stdlib-js/stdlib/pull/5205) _(by Shabareesh Shetty, Athan Reines, stdlib-bot)_
-   [`40308a8`](https://github.com/stdlib-js/stdlib/commit/40308a8953dd480537d4c4359cc6e09f679e3ec1) - **build:** update configurations _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 6 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gururaj Gurram
-   Karan Anand
-   Philipp Burckhardt
-   SAHIL KUMAR
-   Shabareesh Shetty

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

<section class="release" id="v0.1.1">

## 0.1.1 (2024-07-28)

No changes reported for this release.

</section>

<!-- /.release -->

<section class="release" id="v0.1.0">

## 0.1.0 (2024-07-28)

<section class="features">

### Features

-   [`bd258a3`](https://github.com/stdlib-js/stdlib/commit/bd258a3c2803d841658c7465505966149845a6fb) - update namespace TypeScript declarations [(#2628)](https://github.com/stdlib-js/stdlib/pull/2628)
-   [`ea241a3`](https://github.com/stdlib-js/stdlib/commit/ea241a32e7bbd7f346ff993d932adbd1857108e1) - add `assert` to namespace
-   [`69eecad`](https://github.com/stdlib-js/stdlib/commit/69eecadd785a9ba5732e2d136b8755cad6341fd0) - add `complex/float32/base/assert` namespace
-   [`21604d0`](https://github.com/stdlib-js/stdlib/commit/21604d0a1efaa60b3e2f477d36cdcb967312904d) - add `complex/float32/base` namespace
-   [`d6bba38`](https://github.com/stdlib-js/stdlib/commit/d6bba3883b442a2338fb2dbc6a97c6fe6b69edd5) - add `complex/float32/base/mul`
-   [`10ef39d`](https://github.com/stdlib-js/stdlib/commit/10ef39d7b94513bf84f70eef5a673725f155e3d5) - add `complex/float32/base/add`
-   [`77517fe`](https://github.com/stdlib-js/stdlib/commit/77517fea863cd0df1defa56ae9619bcd4f73b1b7) - add `complex/float32/base/assert/is-not-equal`
-   [`53ff701`](https://github.com/stdlib-js/stdlib/commit/53ff701453daab8775e560a20384b37522e48c54) - add `complex/float32/base/assert/is-equal`
-   [`6e0db34`](https://github.com/stdlib-js/stdlib/commit/6e0db34815925043c2b92c2e984a6c7f064bce3f) - add `complex/float32/base/assert/is-same-value-zero`
-   [`5ee47a5`](https://github.com/stdlib-js/stdlib/commit/5ee47a5cb81f9ed1694606d1cba77a542e8cc0b2) - add `complex/float32/assert/is-same-value`

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`bd258a3`](https://github.com/stdlib-js/stdlib/commit/bd258a3c2803d841658c7465505966149845a6fb): update namespace declarations

    -   To migrate, users should see the guidance found in the relevant commits for namespace refactoring. See issue #2260.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`2777e4b`](https://github.com/stdlib-js/stdlib/commit/2777e4be161869d09406e3b17947d24c64b47af2) - **bench:** resolve lint errors in benchmarks _(by Athan Reines)_
-   [`a304cd8`](https://github.com/stdlib-js/stdlib/commit/a304cd8eba1aefe44f74a0273bd4c08345ee92f4) - **docs:** update namespace table of contents [(#2648)](https://github.com/stdlib-js/stdlib/pull/2648) _(by stdlib-bot, Athan Reines)_
-   [`9dc29b4`](https://github.com/stdlib-js/stdlib/commit/9dc29b4d2e6eb5ba0b2625c3bfe9f50034a3ed99) - **docs:** add sub-namespace sections and update namespace table of contents _(by Philipp Burckhardt)_
-   [`bd258a3`](https://github.com/stdlib-js/stdlib/commit/bd258a3c2803d841658c7465505966149845a6fb) - **feat:** update namespace TypeScript declarations [(#2628)](https://github.com/stdlib-js/stdlib/pull/2628) _(by stdlib-bot, Athan Reines)_
-   [`ea241a3`](https://github.com/stdlib-js/stdlib/commit/ea241a32e7bbd7f346ff993d932adbd1857108e1) - **feat:** add `assert` to namespace _(by Athan Reines)_
-   [`69eecad`](https://github.com/stdlib-js/stdlib/commit/69eecadd785a9ba5732e2d136b8755cad6341fd0) - **feat:** add `complex/float32/base/assert` namespace _(by Athan Reines)_
-   [`21604d0`](https://github.com/stdlib-js/stdlib/commit/21604d0a1efaa60b3e2f477d36cdcb967312904d) - **feat:** add `complex/float32/base` namespace _(by Athan Reines)_
-   [`e3a3679`](https://github.com/stdlib-js/stdlib/commit/e3a3679f1e733cf02ce47cdc4bd0137bd37bef41) - **refactor:** update paths _(by Athan Reines)_
-   [`ddd4403`](https://github.com/stdlib-js/stdlib/commit/ddd44032f9d8a6d318c80e3b239ff72280ffc599) - **refactor:** update paths _(by Athan Reines)_
-   [`d6bba38`](https://github.com/stdlib-js/stdlib/commit/d6bba3883b442a2338fb2dbc6a97c6fe6b69edd5) - **feat:** add `complex/float32/base/mul` _(by Athan Reines)_
-   [`0406147`](https://github.com/stdlib-js/stdlib/commit/04061476d1036e1b8b786736b1ba1653eddff1ef) - **refactor:** update paths _(by Athan Reines)_
-   [`10ef39d`](https://github.com/stdlib-js/stdlib/commit/10ef39d7b94513bf84f70eef5a673725f155e3d5) - **feat:** add `complex/float32/base/add` _(by Athan Reines)_
-   [`ad760a9`](https://github.com/stdlib-js/stdlib/commit/ad760a922086631226d8f759a0d467c707fbc0fb) - **refactor:** update paths _(by Athan Reines)_
-   [`77517fe`](https://github.com/stdlib-js/stdlib/commit/77517fea863cd0df1defa56ae9619bcd4f73b1b7) - **feat:** add `complex/float32/base/assert/is-not-equal` _(by Athan Reines)_
-   [`53ff701`](https://github.com/stdlib-js/stdlib/commit/53ff701453daab8775e560a20384b37522e48c54) - **feat:** add `complex/float32/base/assert/is-equal` _(by Athan Reines)_
-   [`6e0db34`](https://github.com/stdlib-js/stdlib/commit/6e0db34815925043c2b92c2e984a6c7f064bce3f) - **feat:** add `complex/float32/base/assert/is-same-value-zero` _(by Athan Reines)_
-   [`5ee47a5`](https://github.com/stdlib-js/stdlib/commit/5ee47a5cb81f9ed1694606d1cba77a542e8cc0b2) - **feat:** add `complex/float32/assert/is-same-value` _(by Athan Reines)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 2 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Philipp Burckhardt

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

