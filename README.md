# Spreadsheet matcher app - Programa comparador de planilhas 


  ![screen-layout](https://github.com/Julia-slvbrg/spreadsheet-matcher/assets/114543081/27c5e8a0-2275-47c3-945d-a71dff20caa8)

This application is a spreadsheet matcher designed specifically for lay judges that work in Belo Horizonte - Brazil. Its purpose is to facilitate their management of processes that have already been cleared by the court.

Users can select two .xlsx files for comparison, and the app will then create a new Excel file with two spreadsheets: one containing data present in both spreadsheets, and the other containing data exclusive to the second input file.

OBS1: The development of this program has no connection with TJMG, it was carried out at the request of some people.
OBS2: Since this app was made to fit a demand and was sold to the interested parties, the code is not open.

## Index
- <a href="#functionalities">Application functionalities</a>
- <a href="#layout">Layout</a>
- <a href="#demonstration">Demonstration</a>
- <a href="#run">How to run the application</a>
- <a href="#tecnologies-used">Tecnologies used</a>
- <a href="#developer">Developer</a>
- <a href="#next-steps">Next steps</a>

## Application functionalities
 - [x]  Load .xlsx files in the inputs
 - [x]  Compare the files
 - [x]  Create a new Excel file with the result data

## Layout
App screen

![layout](https://github.com/Julia-slvbrg/spreadsheet-matcher/assets/114543081/e2f0be3e-d687-4a45-b5e0-b300a9f6e9ba)


## Demonstration


https://github.com/Julia-slvbrg/spreadsheet-matcher/assets/114543081/6a0d0857-b1eb-4fd5-908b-163c341f8b95



https://github.com/Julia-slvbrg/spreadsheet-matcher/assets/114543081/581d4428-ecf2-4836-ac9e-2f0c3aa6d7c3



## How to run the application
```bash
# Clone this repository
$ git clone repolink

# Acess the app folder on your terminal
$ cd spreadsheet-matcher

# Install the dependencies
$ npm install

# Run the app 
$ npm start
```

## Tecnologies used
1. [Electron](https://www.electronjs.org/)
2. Javascript
3. Node.js
4. HTML
5. CSS
6. [Toastify JS](https://apvarun.github.io/toastify-js/)
7. [read-excel-file](https://www.npmjs.com/package/read-excel-file)
8. [exceljs](https://www.npmjs.com/package/exceljs)

## Developer
[LinkedIn](https://www.linkedin.com/in/julia-silva-borges/)

## Next steps
 - [ ] Add a header to the second result spreadsheet
