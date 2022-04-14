## Preconditions:
1. Install Node.js 14 (Has to be lower than 16 so WDIO Sync mode will work) - https://nodejs.org/en/blog/release/v14.17.3/
2. Install Java - https://www.java.com/en/download/
3. Install VSCode - https://code.visualstudio.com/download
4. Install VSCode extensions - Copy Relative Path Posix, ESLint

## Installing NPM packages:
1. Open the project with VSCode
2. Open the terminal
3. Run the command - npm install

** In case you DO NOT have the latest version of Google Chrome installed on your computer, run the following command:
  npm i chromedriver <chromeVersion> (for example - npm i chromedriver@96.0.0)

## Running the test:
- Option 1 - On the left side of VSCode explorer, there is a play/debug button, under the NPM Scripts. Clicking on either will execute the test
- Option 2 - In the VSCode terminal, run the following command - npx wdio ./test/config/wdio.local.conf.js

## References & Tips for the test itself:
- WDIO (Web Driver IO) using Synchronous (sync) Mode API- https://webdriver.io/docs/api
- WDIO Selectors - https://webdriver.io/docs/selectors/#chain-selectors
- WDIO Elements - https://webdriver.io/docs/api/element/$$/
