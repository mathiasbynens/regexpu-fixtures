# regexpu-fixtures [![regexpu-fixtures on npm](https://img.shields.io/npm/v/regexpu-fixtures)](https://www.npmjs.com/package/regexpu-fixtures)

[_regexpu_](https://mths.be/regexpu) is a source code transpiler that enables the use of ES2015 Unicode regular expressions in JavaScript-of-today (ES5).

_regexpu-fixtures_ contains the fixtures used in _regexpu_’s test suite. This might be useful for other regular expression-related tests.

## For maintainers

### How to publish a new release

1. On the `main` branch, bump the version number in `package.json`:

    ```sh
    npm version patch -m 'Release v%s'
    ```

    Instead of `patch`, use `minor` or `major` [as needed](https://semver.org/).

    Note that this produces a Git commit + tag.

1. Push the release commit and tag:

    ```sh
    git push && git push --tags
    ```

    Our CI then automatically publishes the new release to npm.

## Author

| [![twitter/mathias](https://gravatar.com/avatar/24e08a9ea84deb17ae121074d0f17125?s=70)](https://twitter.com/mathias "Follow @mathias on Twitter") |
|---|
| [Mathias Bynens](https://mathiasbynens.be/) |

## License

_regexpu-fixtures_ is available under the [MIT](https://mths.be/mit) license.
