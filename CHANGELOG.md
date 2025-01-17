## [3.0.0](https://github.com/alanshaw/it-pushable/compare/v2.0.2...v3.0.0) (2022-06-10)


### ⚠ BREAKING CHANGES

* `Uint8Array`s are expected by default, pass `objectMode: true` to push any other data types. If using TypeScript, use generics to define the data type.

### Features

* add readableLength property ([#27](https://github.com/alanshaw/it-pushable/issues/27)) ([f45aee3](https://github.com/alanshaw/it-pushable/commit/f45aee36e72e754b8a27dda48d3051c470aaa8e5))


### Trivial Changes

* fix flaky test ([#28](https://github.com/alanshaw/it-pushable/issues/28)) ([8c3dcc1](https://github.com/alanshaw/it-pushable/commit/8c3dcc1f8e64f2877317a835bb03545f7fa2dd53))

### [2.0.2](https://github.com/alanshaw/it-pushable/compare/v2.0.1...v2.0.2) (2022-06-08)


### Bug Fixes

* update aegir ([#24](https://github.com/alanshaw/it-pushable/issues/24)) ([9c1a478](https://github.com/alanshaw/it-pushable/commit/9c1a4783a536d90bcede5d29cc2d66d2a0d5321a))


### Trivial Changes

* update publish command ([#25](https://github.com/alanshaw/it-pushable/issues/25)) ([b82173f](https://github.com/alanshaw/it-pushable/commit/b82173f3c7d07581e1ece3ed3026ccbbf6c57056))

### [2.0.1](https://github.com/alanshaw/it-pushable/compare/v2.0.0...v2.0.1) (2022-01-13)


### Trivial Changes

* fix readme example ([#13](https://github.com/alanshaw/it-pushable/issues/13)) ([d4d7282](https://github.com/alanshaw/it-pushable/commit/d4d728275ba97977fd2004be749a57bbb74aebca))

## [2.0.0](https://github.com/alanshaw/it-pushable/compare/v1.4.2...v2.0.0) (2022-01-13)


### ⚠ BREAKING CHANGES

* switch to named exports, ESM only

### Features

* convert to typescript ([#12](https://github.com/alanshaw/it-pushable/issues/12)) ([49e0805](https://github.com/alanshaw/it-pushable/commit/49e080564a410a5f3475dfaa389ad8f0f1d8582c))
