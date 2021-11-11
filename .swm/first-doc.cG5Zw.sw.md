---
id: cG5Zw
name: First Doc
file_version: 1.0.2
app_version: 0.6.5-4
file_blobs:
  tests/module2.spec.js: 2e15ac3b08ba76bdd586dd735427a18973f44ffe
---

Here is how we setup our tests

<br/>

This first test checks to make sure the index file exists.
<!-- NOTE-swimm-snippet: the lines below link your snippet to Swimm -->
### 📄 tests/module2.spec.js
```javascript
⬜ 6      const { checkFileExists } = require('../utils');
⬜ 7      
⬜ 8      describe('Module 2', () => {
🟩 9        it("you should have a file named 'index.js' in the src directory @entry", () => {
🟩 10         let indexFile = fs.existsSync(path.join(process.cwd(), 'src/index.js'));
🟩 11         expect(indexFile).to.not.equal(
🟩 12           false,
🟩 13           'It seems you have not created the `index.js` file in `src/`.',
🟩 14         );
🟩 15       });
⬜ 16       it('should have an exported function named `fetchMovies` @declare-fetchmovies', () => {
⬜ 17         if (checkFileExists('index')) {
⬜ 18           let indexFile = fs.readFileSync(
```

<br/>

This file was generated by Swimm. [Click here to view it in the app](https://app.swimm.io/repos/Z2l0aHViJTNBJTNBamF2YXNjcmlwdC1wcm9taXNlcy1hc3luYy1hd2FpdCUzQSUzQWFhcm9uZnJhbmNvLXhicw==/docs/cG5Zw).