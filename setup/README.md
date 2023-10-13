# JavaScript DOM Calculator Lab - Setup

![Hero image](./assets/hero.png)
tktk Hunter - we need to replace this stock hero image with one that includes "JavaScript DOM Calculator Lab - Setup"

## Setup 

Open your Terminal application and navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

Make a new directory called **`js-dom-calculator-lab`**, then enter this directory:

```bash
mkdir js-dom-calculator-lab
cd js-dom-calculator-lab
```

Then, create an **`script.js`**, an **`index.html`**, and a **`style.css`** file. These files will hold your work for this lab:

```bash
touch script.js index.html style.css
```

With the files created, open the contents of the directory in VS Code:

```bash
code .
```

Open the **`index.html`** file and add HTML boilerplate. Then make use of the **`script.js`** file by adding this line inside the `<head>` tag:

```html
<script defer src="./script.js"></script>
<link href="./style.css" rel="stylesheet" />
```

### HTML
Add the following to your **`index.html`** file.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DOM Calculator</title>
  <script defer src="./app.js"></script>
  <link rel="stylesheet" href="./style.css">
</head>
<body>
  <div class="container">
    <div class="calculator">
      <div class="row">
        <div class="display"></div>
      </div>
      <div class="row">
        <div class="button">7</div>
        <div class="button">8</div>
        <div class="button">9</div>
        <div class="button">/</div>
      </div>
      <div class="row">
        <div class="button">4</div>
        <div class="button">5</div>
        <div class="button">6</div>
        <div class="button">*</div>
      </div>
      <div class="row">
        <div class="button">1</div>
        <div class="button">2</div>
        <div class="button">3</div>
        <div class="button">-</div>
      </div>
      <div class="row">
        <div class="button">0</div>
        <div class="button">C</div>
        <div class="button equals">=</div>
      </div>
    </div>
  </div>
</body>
</html>
```
### CSS
Add the following code to your CSS stylesheet.

```css
/* tktk add css */
```

### JavaScript
Add the following outline to your JS file.

```js
/*-------------------------------- Constants --------------------------------*/

/*-------------------------------- Variables --------------------------------*/

/*------------------------ Cached Element References ------------------------*/

/*----------------------------- Event Listeners -----------------------------*/

/*-------------------------------- Functions --------------------------------*/
```


- Open the **`index.html`** file in your browser and access the console output in your browser's dev tools to begin work on your JavaScript logic.



