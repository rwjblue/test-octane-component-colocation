# test-octane-component-colocation

Showing "basic" component colocation is working properly.

This repo is:

```
ember new test-octane-component-colocation --yarn
cd test-octane-component-colocation
ember generate component hello
ember generate component-class hello
```

Tweaked the implementation to have _some_ functionality, fixed the test.

```
❯ ember test
DEPRECATION: ember-cli-htmlbars-inline-precompile is no longer needed with ember-cli-htmlbars versions 4.0.0 and higher, please remove it from `/private/tmp/test-octane-component-colocation/package.json`
Environment: test
cleaning up...
Built project successfully. Stored in "/var/folders/mt/yt2qjpl93ls98lrkrs81rzch000pzv/T/tests-dist-2019919-52400-1aa34cu.zvj4".
ok 1 Chrome 77.0 - [94 ms] - Integration | Component | hello: it renders
ok 2 Chrome 77.0 - [1 ms] - ESLint | app: app.js
ok 3 Chrome 77.0 - [0 ms] - ESLint | app: components/hello.js
ok 4 Chrome 77.0 - [0 ms] - ESLint | app: resolver.js
ok 5 Chrome 77.0 - [0 ms] - ESLint | app: router.js
ok 6 Chrome 77.0 - [0 ms] - TemplateLint: test-octane-component-colocation/templates/application.hbs
ok 7 Chrome 77.0 - [1 ms] - ESLint | tests: integration/components/hello-test.js
ok 8 Chrome 77.0 - [0 ms] - ESLint | tests: test-helper.js
ok 9 Chrome 77.0 - [0 ms] - ember-qunit: Ember.onerror validation: Ember.onerror is functioning properly

1..9
# tests 9
# pass  9
# skip  0
# fail  0

# ok
```
