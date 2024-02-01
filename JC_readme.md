# Documentation for JC's Contribution

> Here's some info about my contribution
> I was in charge of the navbar that you see on the side of the page.
```html
<div id="sidenav" class="column-1">
      <nav>

        <button id="home" onclick="">
          <div class="container">
            <div class="image">
              <img src="assets/homeIcon.png" alt="Home">
            </div>
            <div class="text">
              Home
            </div>
          </div>
        </button>

        <button id="info" onclick="">
          <div class="container">
            <div class="image">
              <img src="assets/infoIcon.png" alt="About">
            </div>
            <div class="text" id="nav-about">
              About
            </div>
          </div>
        </button>

        <button id="support" onclick="">
          <div class="container">
            <div class="image">
              <img src="assets/supportIcon.png" alt="Services">
            </div>
            <div class="text">
              Services
            </div>
          </div>
        </button>

        <button id="contact" onclick="">
          <div class="container">
            <div class="image">
              <img src="assets/phoneIcon.png" alt="Contact">
            </div>
            <div class="text">
              Contact
            </div>
          </div>
        </button>

        <button id="menu" onclick="">
          <div class="container">
            <div class="image">
              <img src="assets/menuIcon.png" alt="Menu">
            </div>
            <div class="text">Menu</div>
          </div>
        </button>
      </nav>
    </div>
```
```css
div#sidenav {
    margin:0;
    padding:0;
    height:100%;
    width:100%;
    z-index:1;
    top:0;
    left:0;
    background-color:#F2AE1C;
    transition:0.5s;
    overflow:auto;
    border-radius: 10px;
}

#sidenav button {
    /* padding: 8px 8px 8px 32px; */
    padding:60.9px;
    text-decoration: none;
    display:block;
    transition:0.3s;
    color:#F4E9DD;
  background-color: #F2AE1C;
  outline: none;
    text-shadow:2px 2px black;
}

#sidenav button:hover {
    background-color:#D35E17;
    color:#742D00;
}

.container {
    display: grid;
    align-items: center; 
    grid-template-columns: 1fr 1fr 1fr;
    column-gap: 5px;
   }
   
   img {
     max-width: 100%;
     max-height: 100%;
   }
```
> images are a bit small

```css
   .text {
     font-size: 50px;
     font-family: 'Lilita One', sans-serif;
   }
```

