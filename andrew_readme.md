# Documentation for Andrew's Contribution

## Project summary

> In this document I will be discussing how I contributed to the project

> Below is my overall code for the topnav

```css
.topNav {
    background: #D35E17;
    height: 7.5vh;
    width: 100%;
    text-align: center;
    justify-content: space-around;
}

.topNav button {
    height: 7.5vh;
    font-family: Genty;
    font-size: 20px;
    width: 19vw;
    color: rgb(255, 255, 255);
    background: #D35E17;
    transition: .3s;
    z-index: -2;
    cursor: pointer;
    outline: none;
    border: none;
    box-sizing: border-box;
    border-radius: 5px;
}

.topNav button:hover {
    background: #edab82;
    color: grey;
    height: 8vh;
    border-radius: 5px;
}
```
```html
<div class="topNav">
    <button href="#" onclick="coffeeAlert()" id="blackCof">Black</button>
    <button href="#" onclick="coffeeAlert()" id="espressoCof">Espresso</button>
    <button href="#" onclick="coffeeAlert()" id="mochaCof">Mocha</button>
    <button href="#" onclick="coffeeAlert()" id="latteCof">Latte</button>
    <button href="#" onclick="coffeeAlert()" id="frapCof">Frappucino</button>
  </div>
  ```

> With the nav bar, I mainly focused on giving it a visually appealing aspect while still keeping some simple functionality. 

> With that in in mind, giving the nav bar just some simple buttons that would redirect you to the certain type of coffee you may be looking for. Giving the nav bar a hover effect to "notify" the user that the button is ready to be pressed and also just to give it some visual pezaz.

```html
<div class="topNav">
    <button href="#" onclick="coffeeAlert()" id="blackCof">Black</button>
    <button href="#" onclick="coffeeAlert()" id="espressoCof">Espresso</button>
    <button href="#" onclick="coffeeAlert()" id="mochaCof">Mocha</button>
    <button href="#" onclick="coffeeAlert()" id="latteCof">Latte</button>
    <button href="#" onclick="coffeeAlert()" id="frapCof">Frappucino</button>
  </div>
```
```css
.topNav button:hover {
    background: #edab82;
    color: grey;
    height: 8vh;
    border-radius: 5px;
}
```

## With the help of levi, we were able to save time but also missed out on a good function. Adding a popup that notifies the user that the coffee is currently out of order was able to help with user convenience.

![Alt text](<coffee maching broke.PNG>)


# With styling the rest of the website, I tried to incorporate the color pallete given to us.

![Alt text](<coffee pallete.PNG>)


>In order to also give the website that little info tab at the bottom I went and added a gradient to the background

```css
body {
    background: linear-gradient(180deg, #F4E9DD 0%, #F4E9DD 89%, #D35E17 89%, #D35E17 100%);
    margin: 0;
}
```