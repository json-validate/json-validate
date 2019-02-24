# json-validate

**JSON Validate** is a portable way to describe the format of JSON data (or data
which is semantically similar to JSON, such as parts of YAML). You can use JSON
Validate to:

* Generate code from a JSON Validate schema,
* Generate UIs, such as HTML forms or documentation, or
* Generate validators which ensure data is up-to-spec.

JSON Validate is meant to be extremely simple, so that you can easily build your
own tooling on top of it. If you're familiar with any of these projects:

* [React `PropTypes`](https://reactjs.org/docs/typechecking-with-proptypes.html)
* [TypeScript](https://www.typescriptlang.org/index.html)
* [RELAX NG](https://relaxng.org/)

Then you'll find JSON Validate familiar. It's just a minimal schema language,
but for JSON or JSON-like data.

This repository contains:

* A formal specification of JSON Validate,
* A formal test suite that implementations can use to make sure they're
  following the spec correctly, and
* An informal guide on how implementors can create a JSON Validate
  implementation of their own.
