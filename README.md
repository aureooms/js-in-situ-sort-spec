:notebook_with_decorative_cover: [@aureooms/js-in-situ-sort-spec](https://make-github-pseudonymous-again.github.io/js-in-situ-sort-spec)
==

In-place sorting specification for JavaScript.
See [docs](https://make-github-pseudonymous-again.github.io/js-in-situ-sort-spec).
Parent is [@aureooms/js-sort](https://github.com/make-github-pseudonymous-again/js-sort).

```js
import ava from 'ava';
import * as spec from '@aureooms/js-in-situ-sort-spec';

spec.test(
    ava, // Any testing library exhibiting the same interface as `ava`.
    [
        [
            'mock', // Name of the implementation.
            (compare, a, i, j) => spec.mock(compare, a, i, j), // Sorting implementation.
        ]
    ],
    {
        length: [24, 1000], // Array lengths to test.
        array: [Int8Array], // Array types to test.
    }
);
```

[![License](https://img.shields.io/github/license/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://raw.githubusercontent.com/make-github-pseudonymous-again/js-in-situ-sort-spec/master/LICENSE)
[![Version](https://img.shields.io/npm/v/@aureooms/js-in-situ-sort-spec.svg)](https://www.npmjs.org/package/@aureooms/js-in-situ-sort-spec)
[![Build](https://img.shields.io/travis/make-github-pseudonymous-again/js-in-situ-sort-spec/master.svg)](https://travis-ci.org/make-github-pseudonymous-again/js-in-situ-sort-spec/branches)
[![Dependencies](https://img.shields.io/david/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://david-dm.org/make-github-pseudonymous-again/js-in-situ-sort-spec)
[![Dev dependencies](https://img.shields.io/david/dev/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://david-dm.org/make-github-pseudonymous-again/js-in-situ-sort-spec?type=dev)
[![GitHub issues](https://img.shields.io/github/issues/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://github.com/make-github-pseudonymous-again/js-in-situ-sort-spec/issues)
[![Downloads](https://img.shields.io/npm/dm/@aureooms/js-in-situ-sort-spec.svg)](https://www.npmjs.org/package/@aureooms/js-in-situ-sort-spec)

[![Code issues](https://img.shields.io/codeclimate/issues/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://codeclimate.com/github/make-github-pseudonymous-again/js-in-situ-sort-spec/issues)
[![Code maintainability](https://img.shields.io/codeclimate/maintainability/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://codeclimate.com/github/make-github-pseudonymous-again/js-in-situ-sort-spec/trends/churn)
[![Code coverage (cov)](https://img.shields.io/codecov/c/gh/make-github-pseudonymous-again/js-in-situ-sort-spec/master.svg)](https://codecov.io/gh/make-github-pseudonymous-again/js-in-situ-sort-spec)
[![Code technical debt](https://img.shields.io/codeclimate/tech-debt/make-github-pseudonymous-again/js-in-situ-sort-spec.svg)](https://codeclimate.com/github/make-github-pseudonymous-again/js-in-situ-sort-spec/trends/technical_debt)
[![Documentation](https://make-github-pseudonymous-again.github.io/js-in-situ-sort-spec/badge.svg)](https://make-github-pseudonymous-again.github.io/js-in-situ-sort-spec/source.html)
[![Package size](https://img.shields.io/bundlephobia/minzip/@aureooms/js-in-situ-sort-spec)](https://bundlephobia.com/result?p=@aureooms/js-in-situ-sort-spec)
