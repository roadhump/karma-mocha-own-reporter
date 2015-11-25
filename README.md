
# Karma Mocha Own Reporter

Karma plugin to make possibble to use [Mocha]() own reporters (including diff output).

You should use [karma-mocha]() plugin and any decent assertion library ([expect.js](), [chai](), etc).

## Configuration

`karma.conf.js`

```js
{
    reporters: ["mocha-own"],

    mochaOwnReporter: {
        reporter: 'spec'
    }
}
```
