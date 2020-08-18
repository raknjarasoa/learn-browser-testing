
### How to use this

1. Firstly, make sure the existing test in this folder runs successfully. Run this command in your terminal:

```sh
npm run howl # checks that qawolf is working
npm start # runs a sample wikipedia test
```

2. First, run this command to CREATE your test:

```sh
node ../../node_modules/qawolf/build/index.js create https://www.wikipedia.org/ yourTestNameHere
```

3. Then, run this command to RUN your test:

```sh
node ../../node_modules/qawolf/build/index.js test yourTestNameHere
```

4. Create new tests on websites other than Wikipedia

### Windows User

If those commands above do not work on Windows, try these:

```sh
yarn howl
yarn start

# Create a test
node ..\\..\\node_modules\\qawolf\\build\\index.js create https://www.wikipedia.org/ yourTestNameHere

# Run your test
node ..\\..\\node_modules\\qawolf\\build\\index.js test yourTestNameHere
```

### See also

[Puppeteer Recorder](https://chrome.google.com/webstore/detail/puppeteer-recorder/djeegiggegleadkkbgopoonhjimgehda?hl=en)