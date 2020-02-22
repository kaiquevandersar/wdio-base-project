Automated test project.
<br /><br />
Framework used: [WebdriverIO](https://webdriver.io/ "WebdriverIO")<br />
Language: Node.js
<br /><br />
Requirements to run the tests:
- Node.js and npm installed
`node -v`
`npm -v`
- Chrome installed
<br /><br />
Tutorial for execution:
1. Make sure you have Node.js, npm and chrome installed.
2. Clone the project.
3. After cloning, inside the project folder, execute the command<br />
 `npm install`<br />
4. After downloading the dependencies, the project is ready to be executed using the command:<br />
`npm run <suite>`<br />
suites available:<br />
 `npm run regressionDialogflow`<br />
 `npm run regressionQnaMaker`<br />
 `npm run regressionWatson`<br />
 `npm run regressionLuis`<br />
 `npm run regressionClever`<br />
 `npm run regressionLogin`<br />
<br /><br />
After the tests, if you want to see the result through the [Allure](http://allure.qatools.ru/ "Allure"), just run the command `npm run allure` at the root of the project.

