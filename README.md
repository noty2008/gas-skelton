# GAS Skelton
Skeleton code for writing Google Apps Script in TypeScript.
## caution
Please install clasp globally.
```
$ npm i -g clasp
```
## Usage
* 1.Open the script editor from a spreadsheet, document, etc. 
    Or, create a stand-alone project.
* 2.Allow the use of Apps Script from the API.
* 3.```$ npm install```.
* 4.Copy ```.clasp.default.json``` to ```.clasp.json```
* 5.Rewrite scriptId in ```.clasp.json``` to the script ID of your script.
* 6.Edit TypeScript source under the ```src```.
* 7.```npm start``` will compile the TypeScript source and upload the compiled source.
## Directory
```
.
├── .clasp.default.json - Here is an example of .clasp.json configuration. Please copy it to .clasp.json and use it.
├── .clasp.json - You can specify where to upload your project and which directory to upload it to.
├── .gitignore - A set of files that Git ignores is specified. 
├── README.md - This file.
├── appsscript.json - The manifest file.
├── lib - Directory containing the files to be uploaded. 
├── node_modules  - Libraries used by Node.js. 
├── package-lock.json - The detailed versions of Node.js's dependent libraries are specified. 
├── package.json - Package file of Node.js. 
├── src - The directory where the TypeScript source is placed.
└── tsconfig.json - TypeScript compilation settings.
```
