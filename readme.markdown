# eslint-config-lennon

> my personal eslint preferences

## rules

> some rules are just silly, some rules makes sense.

### `for-direction`

in general, you should use `for-of` loops in the first place, but the good old
`for` loop can come handy as well.

don't go into infinite loops, so enable this one.

### `getter-return`

_TODO_

### `no-async-promise-executor`

you're creating a promise, because you want to wrap something that's not
`async`. use a regular function then, this one is turned on.

### `no-await-in-loop`

it's perfectly fine to `await` in loop, so this one is turned off.

### `no-compare-neg-zero`

you don't want to compare with `-0`.

### `no-cond-assign`

`if (foo = bar)` is usually a mistake, so this one is turned on.

### `no-console`

use a logging library, or add an exception to those _exceptional_ place where
you're using `console` methods.

### `no-constant-condition`

it's usually some workaround to trigger something.

### `no-control-regex`


