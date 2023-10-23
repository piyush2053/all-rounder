<p align="center">
  <a href="https://www.linkedin.com/in/beingpiyushpatel/"><img src="https://i.ibb.co/dBSY4Md/logo1.png" alt="Versa-Blend"></a>
</p>

# Versa Blend

Versa Blend is a Node.js package available on the npm registry, designed to simplify the development process for programmers. With Versa Blend, developers gain access to a wide array of tools, functions, and methods, allowing them to streamline their coding efforts and reduce the need for custom logic. This package is particularly useful for those working with Express.js, general JavaScript operations, and XML document manipulations.


# Installation

```bash
npm install -g versa-blend # or using yarn: yarn global add versa-blend
```

And Versa blend will be installed globally to your system path.

You can also install Versa blend  as a development dependency:

```bash
npm install --save-dev versa-blend  # or using yarn: yarn add versa-blend -D
```

# How to Use

`xmlString`

This function parses an XML string and returns a Promise that resolves to the parsed JavaScript object.

### Usage

```javascript
xml2js('<root><item>Hello</item></root>')
  .then(result => {
    console.log(result); // Parsed XML object
  })
  .catch(error => {
    console.error(error);
  });
```



Here's a brief example for `excel to pdf`:

```markdown
`excel2pdf(excelFilePath, pdfFilePath)`
```

This function converts an Excel file to a PDF.

### Usage

```javascript
excel2pdf('input.xlsx', 'output.pdf')
  .then(() => {
    console.log('Conversion completed successfully.');
  })
  .catch(error => {
    console.error(error);
  });
  ```
