# JavaScript TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error and its solution.  The error occurs when attempting to access a property of a variable that is currently undefined.

## Bug
The `foo` function attempts to access the `length` property of `x`. If `x` is `undefined`, this will result in a `TypeError`.

## Solution
The solution involves checking if `x` is `undefined` before accessing `x.length`.  This prevents the `TypeError` by ensuring the `length` property is only accessed when `x` is a valid array or object.