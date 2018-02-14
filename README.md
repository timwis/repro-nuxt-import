# repro-nuxt-import
Demonstrates that importing vue inside the jest context logs the Vue production tip to the console.

## usage
```bash
npm test

 PASS  ./test.js
  ✓ logs vue production tip (1ms)

  console.info node_modules/vue/dist/vue.runtime.common.js:7913
    You are running Vue in development mode.
    Make sure to turn on production mode when deploying for production.
    See more tips at https://vuejs.org/guide/deployment.html

  console.log test.js:4
    done

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        2.429s
Ran all test suites.
```
