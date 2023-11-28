# ![DOM Events Lab - Setup](./assets/hero.png)

## Setup 
Open your Terminal application and navigate to your **`~/code/ga/labs`** directory:

```bash
cd ~/code/ga/labs
```

Make a new directory called **`dom-events-lab`**, then enter this directory:

```bash
mkdir dom-events-lab
cd dom-events-lab
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
  <title>DOM Events Lab</title>
  <script defer src="./app.js"></script>
  <link rel="stylesheet" href="./style.css">
</head>
<body>
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
</body>
</html>
```

### CSS
Add the following code to your CSS stylesheet.

```css
* {
  box-sizing: border-box;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  font-family: system-ui, sans-serif;
}

.display {
  width: 100%;
  height: 50px;
  font-size: 24px;
  padding: 12px;
  display: flex;
  justify-content: flex-end;
  color: white;
  border-radius: 4px;
  background-color: rgb(60, 80, 100);
}

.calculator {
  padding: 24px;
  width: 300px;
  height: 400px;
  gap: 32px;
  display: flex;
  flex-direction: column;
  border-radius: 8px;
  border: 1px solid black;
  background-color: #1f1e1e;
}

.row {
  display: flex;
  justify-content: space-between;
}

.row:last-child::before {
  content: "";
  width: 40px;
  height: 40px;
}

.button {
  padding: 0;
  width: 40px;
  height: 40px;
  cursor: pointer;
  font-size: 24px;
  display: flex;
  align-items: center;
  justify-content: center;
  color: #ffffff;
  background-color: #ff043a;
  border-radius: 4px;
  border: 2px solid rgb(255, 60, 60);
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