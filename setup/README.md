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

Then, create a **`app.js`**, a **`index.html`**, and a **`style.css`** file. These files will hold your work for this lab:

```bash
touch app.js index.html style.css
```

With the files created, open the contents of the directory in VS Code:

```bash
code .
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
.display {
  color: white;
  background-color: grey;
  border: 1px solid red;
  height: 40px;
  width: 90%;
  border: 1px solid black;
  margin-top: 10px;
  display: flex;
  font-size: 36px;
  justify-content: flex-end;
}

.calculator {
  width: 300px;
  border: 1px solid black;
  height: 400px;
  display: flex;
  flex-direction: column;
  gap: 30px;
  background-color: #1f1e1e;
}

.container {
  display: flex;
  width: 100%;
  justify-content: center;
  align-items: center;
  margin-top: 10vh;
}

.row {
  display: flex;
  justify-content: space-around;
}

.button {
  height: 40px;
  width: 40px;
  border: 1px solid black;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 32px;
  border-radius: 50%;
  padding: 0;
  background-color: #ff043a;
  color: #ffffff;
}
```

### JavaScript
Add the following outline to your JS file.

```js
/*-------------------------------- Constants --------------------------------*/

/*-------------------------------- Variables --------------------------------*/

/*------------------------ Cached Element References ------------------------*/

/*-------------------------------- Functions --------------------------------*/

/*----------------------------- Event Listeners -----------------------------*/
```

- Open the **`index.html`** file in your browser and access the console output in your browser's dev tools to begin work on your JavaScript logic.



