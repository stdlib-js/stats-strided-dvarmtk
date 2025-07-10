# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-07-10)

<section class="features">

### Features

-   [`d0172ab`](https://github.com/stdlib-js/stdlib/commit/d0172abf7e4b3fb3c879ea1453a98cdf65600574) - add `stats/strided/dvarmtk`

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`21f2041`](https://github.com/stdlib-js/stdlib/commit/21f2041ea274e9160eb878c2535ff4c8545982c8): switch order of `mean` and `correction` parameters

    -   To migrate, users should swap `mean` and `correction` arguments.
        This change ensures that the `*varm*` function signatures follow
        similar conventions as found in binary APIs, such as those for
        computing the covariance, where the `mean` parameter immediately
        precedes the array argument.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`97af938`](https://github.com/stdlib-js/stdlib/commit/97af9381daa44746086d0110fcbc31c3b8572e7c) - **docs:** fix signature and parameter order _(by Athan Reines)_
-   [`21f2041`](https://github.com/stdlib-js/stdlib/commit/21f2041ea274e9160eb878c2535ff4c8545982c8) - **refactor:** reorder parameters _(by Athan Reines)_
-   [`ab75e22`](https://github.com/stdlib-js/stdlib/commit/ab75e229c58f150da20f42d7f2448e63d1939401) - **refactor:** update paths _(by Gururaj Gurram)_
-   [`d0172ab`](https://github.com/stdlib-js/stdlib/commit/d0172abf7e4b3fb3c879ea1453a98cdf65600574) - **feat:** add `stats/strided/dvarmtk` _(by Aayush Khanna)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Aayush Khanna
-   Athan Reines
-   Gururaj Gurram

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

