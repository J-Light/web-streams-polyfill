# Changelog

> **Tags:**
> - 💥 Breaking Change
> - 👓 Spec Compliance
> - 🚀 New Feature
> - 🐛 Bug Fix
> - 📝 Documentation
> - 🏠 Internal
> - 💅 Polish

## Unreleased

## v2.0.3 (2019-04-04)

* 👓 Align with [spec version `6f94580`](https://github.com/whatwg/streams/tree/6f94580f6731d1e017c516af097d47c45aad1f56/) ([#21](https://github.com/MattiasBuelens/web-streams-polyfill/pull/21))
* 🏠 Run web platform tests on ES5 variant ([#19](https://github.com/MattiasBuelens/web-streams-polyfill/pull/19))

## v2.0.2 (2019-03-17)

* 💅 Improve performance of `reader.read()` and `writer.write()` ([#17](https://github.com/MattiasBuelens/web-streams-polyfill/pull/17), [#18](https://github.com/MattiasBuelens/web-streams-polyfill/pull/18))

## v2.0.1 (2019-03-16)

* 🐛 Fix performance issue with large queues ([#15](https://github.com/MattiasBuelens/web-streams-polyfill/pull/15), [#16](https://github.com/MattiasBuelens/web-streams-polyfill/pull/16))

## v2.0.0 (2019-03-10)

* 💥 Ownership change: [@mattiasbuelens/web-streams-polyfill](https://www.npmjs.com/package/@mattiasbuelens/web-streams-polyfill/v/0.3.2) has been republished as [web-streams-polyfill](https://www.npmjs.com/package/web-streams-polyfill).
  For the full list of changes between web-streams-polyfill v1.3.2 and this version, [visit the fork's changelog](https://github.com/MattiasBuelens/web-streams-polyfill/blob/v0.3.2/CHANGELOG.md).

* 💥 CommonJS entry points have been moved to `dist/`:
  * `index.js` ➡ `dist/polyfill.js`
  * `index.es6.js` ➡ `dist/polyfill.es6.js`

  However, we recommend migrating to a [variant sub-package](https://github.com/MattiasBuelens/web-streams-polyfill#usage) instead:
  * `require('web-streams-polyfill/index.js')` ➡ `require('web-streams-polyfill')`
  * `require('web-streams-polyfill/index.es6.js')` ➡ `require('web-streams-polyfill/es6')`

* 👓 Align with [spec version `2c8f35e`](https://github.com/whatwg/streams/tree/2c8f35ed23451ffc9b32ec37b56def4a5349abb1/)

* 🏠 Code moved from [creatorrr/web-streams-polyfill](https://github.com/creatorrr/web-streams-polyfill) to [MattiasBuelens/web-streams-polyfill](https://github.com/MattiasBuelens/web-streams-polyfill)
