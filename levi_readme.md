# Levi Duarte's Project Contribution

> This is Levi Duarte's project contribution. I was tasked with the overall design of the project,
including creating a wireframe to work with and organizing tasks to the rest of the members. 

### Review Contribution

Another member worked on the button the topnav, but the functions listed were my portion worked and details are shown below.
I've created the overall layout and design using Display Grid which required research, but was easy in the end. 
```HTML
    <button href="#" onclick="coffeeAlert()" id="blackCof">Black</button>
    <button href="#" onclick="coffeeAlert()" id="espressoCof">Espresso</button>
    <button href="#" onclick="coffeeAlert()" id="mochaCof">Mocha</button>
    <button href="#" onclick="coffeeAlert()" id="latteCof">Latte</button>
    <button href="#" onclick="coffeeAlert()" id="frapCof">Frappucino</button>


    <div id="Header-Body" class="column-2">
      <div id="Header" class=" col-2-row-1">
        <h1>Welcome to Barcelle Coffee Roastrey</h1>
        <h3>Our Mission: Borcelle Coffee Roastery is positioned to be a unique, nostalgic,
          and health-focused dining experience catering to the growing
          demand for sustainable, plant-based options in a market longing
          for a throwback to the past.</h3>
      </div>

      <div id="Body-Area" class="col-2-row-2">
        <div id="Home-Area" class="body-part">
          <h3>Founding Story</h3>
          <p> Borcelle Coffee Roastery was
            established by a group of coffee
            aficionados and culinary experts
            who shared a passion for quality,
            nostalgia, and wellness. They recognized a growing demand for
            plant-based options and a yearning for a throwback dining
            experience, leading them to create a space where these
            elements harmoniously blend.
          </p>
        </div>
        <div id="Home-Area" class="body-part">
          <h3>Products and Services</h3>
          <p>Borcelle Coffee Roastery offers a
            range of artisanal coffees,
            organic teas, and plant-based
            dining options. These include
            specialty coffee blends, healthy
            snacks, and full meals, all made
            from sustainable, plant-based
            ingredients. The offerings
            combine traditional flavors with
            modern, health-conscious recipes,
            catering to a wide range of palates.</p>
        </div>
        <div id="Home-Area" class="body-part">
          <h3>Mission and Values</h3>
          <p>
            The company's mission is to offer
            a unique dining experience
            that promotes health and sustainability.
            Its vision is to become a haven for
            coffee lovers and health-conscious
            diners, where the past's charm meets
            the future's sustainability.
          </p>
        </div>
        <div id="Home-Area" class="body-part">
          <h3>Eco-Friendly Practices</h3>
          <p>Beyond sustainable sourcing,
            Borcelle Coffee Roastery
            implements environmentally
            friendly practices in its
            operations, like compostable
            packaging and energy-efficient
            appliances. Health and wellness
            are central to their menu design,
            offering nutrient-rich, plant-based
            options.</p>
        </div>
        <div id="Home-Area" class="body-part">
          <h3>Market Positioning and Audience</h3>
          <p>Borcelle Coffee Roastery targets
            health-conscious individuals,
            coffee enthusiasts, and those
            seeking a nostalgic dining
            experience. They position
            themselves as a unique
            establishment, offering a one-of-
            a-kind blend of health, nostalgia,
            and sustainability.</p>
        </div>
        <div id="Home-Area" class="body-part">
          <h3>Future Goals</h3>
          <p>The company aims to become a
            leader in sustainable and health-focused dining.
            They plan to expand their presence, offering
            their unique dining experience to
            a broader audience while continuing to innovate in the
            realms of sustainable and health-conscious food.</p>
        </div>

      </div>
    </div>

```


In this portion, this is the CSS styles for the Side Nav, Body, and Banner. Using CSS Grid system, i've created equal portions that are
square and aligned well.
``` CSS
div#Header {
    padding-left: 30px;
    padding-right: 30px;
    text-align: center;
    letter-spacing: 2px;
}

.row-2 {
    display: grid;
    grid-template-columns: 1fr 2fr;
    grid-gap: 20px;
    margin-top: 2%;
    margin-left: 10%;
    margin-right: 10%;

}

div.column-1 {
    height: 101vh;
    z-index: 1;
    top: 0;
    left: 0;
    transition: 0.5s;
    background-color: white;
    color: #742D00;
}

.col-2-row-1 {
    height: 20vh;
    background-color: #FAAF86;
    color: #742D00;
    border-radius: 10px;
}

.col-2-row-2 {
    border-radius: 10px;
    margin-top: 1%;
    height: 100vh;
    background-color: #742D00;
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-template-rows: 1fr 1fr 1fr;

}

.col-2-row-2 p {
    padding: 1%;
    font-weight: bolder;
}

```

In this portions, here is the alert message for the coffee selection in the top nav. This was a last minute selection since we didn't have a lot of time. The alert is powered by a function and returns when the button in the nav is clicked.

``` JS 
const blackCoffee = document.getElementById("blackCoffee");
const espressoCofee = document.getElementById("espressoCof");
const mochaCoffee = document.getElementById("mochaCof");
const latteCoffee = document.getElementById("latteCof");
const frapCoffee = document.getElementById("frapCof");

function coffeeAlert(){
    alert("SORRY COFFEE MACHINE IS BROKEN...")
}

```

