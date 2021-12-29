# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :

### CSS Layout:
```
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-image: url("/static/img/bgi.jpg");
  background-color: black;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px rgb(207,103,24);
}

.banner {
  display: block;
  width: 100%;
  height: 100%;
  text-align: center;
  font-size: 65px;
  background-image: url("/static/img/banner1.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 150px;
  color: #C7C85E;
  font-family:serif;
  font-weight: bolder;
}

.banner img {
  float:left;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #f0ba0a;
  text-align: center;
  font-weight: bolder;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}

.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: #16d1ae;
}

.menuitem a {
  text-decoration: none;
  color: #9c1018;
}

.content {
  display: block;
  width: 100%;
  background-color: #ebdb07;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: #ebdb07;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
  font-size: 20px;
}
.gamecont {
  text-align: center;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 215px;
  height: 235px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
  font-weight: bolder;
  text-align: right;
  font-size: x-large;
}
.productitem .itemprice {
  display: block;
  font-weight: bold;
  text-align: right;
  font-size: large;
}
.buy {
  text-align: center;
  font-size: 20px;
  color: rgb(10, 19, 151);
}
.pay {
  text-align: center;
  font-size: 100px;
  color: rgb(243, 0, 0);
  font-family:Fantasy,copperplate;


}
.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #f0ba0a;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  font-weight: bolder;
  color: #9c1018;
}
.people img {
  width: 100%;
  height: 100%;
  display: block;
}
.people {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}
.people .pimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100%;
  margin-bottom: 5px;
}
.people .pname {
  display: block;
  font-size: 30px;
}
.people .pprice {
  display: block;
  font-size: 20px;
}
.people img {
  width: 100%;
  height: 100%;
  display: block;
}

```

### HOME PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Games</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us,</h1>
          <img src="./img/g4l.jpeg" alt="Building" />
          <div class="contenttext">
            At Gamer 4 Life, we believe in the power of gamers to make great changes in  
            the world with their unbelievable iq and knowlegdge. We sell original games for all types of platforms. For nintendo to ps5 we sell more than lakhs of games. Our products focus on
             make your favourite game work for you perfectly, and not the other way
            around.
            <br />
            Our games are always updated up to date and once bought you will receive regular updates on time perfectly. We don't compromise on the quality of the product.
            Games are made easily availble for everyone with our regular discounts. Our products cost less compared to other websites. We even sell specific games for completely free for special occasion(Watch out for those!!!).
            <br>
            So what are you waiting for...... grab your <a href="/static/products.html">games now!!</a> <br><br><br>
            <ul>
              <li>Available <b>4</b> everyone, no discrimination</li>
              <li>Premium quality products <b>4</b> reasonable price</li>
              <li>24/7 customer service <b>4</b> 365 days</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

### PRODUCT PAGE:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Trending Games:</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                    <a href="/static/gta5.html">
                  <img src="/static/img/gta5.jpg" alt="product image">
                  </div>
                  <div class="itemname">Grand Theft Auto 5</div>
                  <div class="itemprice">Price: Rs.1,999 </div></a>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                    <a href="/static/cyberpunk.html">
                  <img src="/static/img/cyber.jpg"  alt="product image">
                  </div>
                  <div class="itemname">Cyberpunk 2077</div>
                  <div class="itemprice">Price: Rs.2,999</div></a>
                </div>
                  <div class="productitem"> 
                    <div class="itemimage">
                      <a href="/static/dyinglight2.html">
                    <img src="/static/img/light.jpg"  alt="product image">
                    </div>
                    <div class="itemname">Dying Light 2</div>
                    <div class="itemprice">Price: Rs.3,099</div></a>
                    </div>
                    <div class="productitem"> 
                      <div class="itemimage">
                        <a href="/static/pubg.html">
                      <img src="/static/img/pubg.jpg"  alt="product image">
                      </div>
                      <div class="itemname">PUBG</div>
                      <div class="itemprice">Price: Rs.999</div></a>                    
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                  <a href="/static/revillage.html">
                <img src="/static/img/revillage.png"  alt="product image">
                </div>
                <div class="itemname">Resident evil Village</div>
                <div class="itemprice">Price: Rs.3,499</div></a>                    
        </div>
        <div class="productitem"> 
          <div class="itemimage">
            <a href="/static/godofwar.html">
          <img src="/static/img/godofwar.jfif"  alt="product image">
          </div>
          <div class="itemname">The God of War</div>
          <div class="itemprice">Price: Rs.3,599</div></a>                    
  </div>
  <div class="productitem"> 
    <div class="itemimage">
      <a href="/static/farcry6.html">
    <img src="/static/img/farcry6.jpg"  alt="product image">
    </div>
    <div class="itemname">Farcry 6</div>
    <div class="itemprice">Price: Rs.3,199</div></a>                    
</div>
<div class="productitem"> 
  <div class="itemimage">
    <a href="/static/assassinscreed.html">
  <img src="/static/img/creed.jfif"  alt="product image">
  </div>
  <div class="itemname">AC Odyssey</div>
  <div class="itemprice">Price: Rs.2,099</div></a>                    
</div>
<div class="productitem"> 
  <div class="itemimage">
    <a href="/static/lastofus.html">
  <img src="/static/img/lou2.png"  alt="product image">
  </div>
  <div class="itemname">The Last Of Us 2</div>
  <div class="itemprice">Price: Rs.2,499</div></a>                     
</div>
<div class="productitem"> 
  <div class="itemimage">
    <a href="/static/tombraider.html">
  <img src="/static/img/TombRaider2013.jpg"  alt="product image">
  </div>
  <div class="itemname">Tomb Raider 2013</div>
  <div class="itemprice">Price: Rs.899</div></a>                    
</div>
          <div class="productitem"> 
            <div class="itemimage">
              <a href="/static/forzahorizon.html">
            <img src="/static/img/forzahorizon5.jpg"  alt="product image">
            </div>
            <div class="itemname">Forza Horizon 5</div>
            <div class="itemprice">Price: Rs.3,399</div></a>                    
          </div> 
          <div class="productitem"> 
            <div class="itemimage">
              <a href="/static/daysgone.html">
            <img src="/static/img/daysgone.jpg"  alt="product image">
            </div>
            <div class="itemname">Days Gone</div>
            <div class="itemprice">Price: Rs.2,399</div></a>                    
          </div>           
      </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 1:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="gta5.mp4" />
        </video>
        <div class="contenttext">
        Grand Theft Auto V is an action-adventure game played from either a third-person or first-person perspective. Players complete missions-linear scenarios with set objectives-to progress through the story. Outside of the missions, players may freely roam the open world.
        <br>
        The game is played from either a third-person or first-person perspective, and its world is navigated on foot and by vehicle. Players control the three lead protagonists throughout single-player and switch among them, both during and outside missions. The story is centred on the heist sequences, and many missions involve shooting and driving gameplay. A "wanted" system governs the aggression of law enforcement response to players who commit crimes. Grand Theft Auto Online, the game's online multiplayer mode, lets up to 30 players engage in a variety of different cooperative and competitive game modes.
        <br>
        Extensively marketed and widely anticipated, the game broke industry sales records and became the fastest-selling entertainment product in history, earning $800 million in its first day and $1 billion in its first three days. It received widespread critical acclaim, with praise directed at its multiple protagonist design, open world, presentation and gameplay. However, it caused controversies related to its depiction of violence and women. Considered one of seventh and eighth generation console gaming's most significant titles and among the best video games ever made, it won year-end accolades including Game of the Year awards from several gaming publications. It is the second best-selling video game of all time with over 155 million copies shipped, and as of April 2018, one of the most financially successful entertainment products of all time, with about $6 billion in worldwide revenue.
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.1,999 only!</div> </a></div> 
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 2:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="cyberpunk.mp4" />
        </video>
        <div class="contenttext">
        Cyberpunk 2077 is an open-world, action-adventure story set in Night City, a megalopolis obsessed with power, glamour and body modification. ... You can customize your character's cyberware, skillset and playstyle, and explore a vast city where the choices you make shape the story and the world around you.
        <br>
        The game was developed using the REDengine 4 by a team of around 500 people, exceeding the number that worked on the studio's previous game The Witcher 3: Wild Hunt (2015). CD Projekt launched a new division in Wrocław, Poland, and partnered with Digital Scapes, Nvidia, QLOC, and Jali Research to aid the production. Cyberpunk creator Mike Pondsmith was a consultant, and actor Keanu Reeves has a starring role. The original score was led by Marcin Przybyłowicz, featuring the contributions of several licensed artists.
        <br>
        After years of anticipation, CD Projekt released Cyberpunk 2077 for PlayStation 4, Stadia, Windows, and Xbox One on 10 December 2020, with PlayStation 5 and Xbox Series X/S versions planned to follow in the first quarter of 2022. It received praise from critics for its narrative, setting, and graphics, although some of its gameplay elements received mixed responses, while its themes and representation of transgender characters received some criticism. It was also widely criticized for bugs, particularly in the console versions, which suffered from performance problems; Sony removed it from the PlayStation Store from December 2020 to June 2021 while CD Projekt rectified some of the problems. CD Projekt became subject to investigations and class-action lawsuits for their perceived attempts at downplaying the severity of the technical problems before release
        <br>
        
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.2,999 only!</div></a></div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 3:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="light.mp4" />
        </video>
        <div class="contenttext">
        Dying Light 2 Stay Human is an action role-playing survival horror video game, featuring a zombie apocalyptic-themed open world. Set 20 years after Dying Light, starring a new protagonist named Aiden Caldwell (voiced by Jonah Scott), who is equipped with various parkour skills.

        <br>
        Players can perform actions such as climbing ledges, sliding, leaping off from edges, and wall running to quickly navigate the city. It was confirmed that there are over 3000 parkour animations to give a more fluid free running experience. Tools such as a grappling hook and a paraglider also aid traversal in the city. Aiden can also use the undead to break his fall. The game is mostly melee-based with the majority of fighting using melee weapons. The melee weapons have a limited lifespan and will degrade as the player uses them in combat. Long-range weapons such as crossbows, shotguns, and spears can be used as well. Weapons can be upgraded with different blueprints and components which can be found by breaking down weapons for craft parts. Aiden can also utilize superhuman skills due to the infection. New zombies have been added. Like the first game, the zombies are slow when exposed to sunlight, but they become more aggressive and hostile at night.
        <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.3,099 only!</div></a> </div>           
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 4:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="pubg.mp4" />
        </video>
        <div class="contenttext">
        PUBG: Battlegrounds (or PUBG, previously known as PlayerUnknown's Battlegrounds) is an online multiplayer battle royale game developed and published by PUBG Corporation, a subsidiary of Bluehole. The game is based on previous mods that were created by Brendan "PlayerUnknown" Greene for other games, inspired by the 2000 Japanese film Battle Royale, and expanded into a standalone game under Greene's creative direction. In the game, up to one hundred players parachute onto an island and scavenge for weapons and equipment to kill others while avoiding getting killed themselves. The available safe area of the game's map decreases in size over time, directing surviving players into tighter areas to force encounters. The last player or team standing wins the round.
        <br>
        PUBG was first released for Microsoft Windows via Steam's early access beta program in March 2017, with a full release in December 2017. The game was also released by Microsoft Studios for the Xbox One via its Xbox Game Preview program that same month, and officially released in September 2018. PUBG Mobile, a free-to-play mobile game version for Android and iOS, was released in 2018, in addition to a port for the PlayStation 4. A version for the Stadia streaming platform was released in April 2020. PUBG is one of the best-selling, highest-grossing and most-played video games of all time. The original PUBG: Battlegrounds has sold over 70 million copies on personal computers and game consoles as of 2020, while the more successful PUGB Mobile version has accumulated 1 billion downloads as of March 2021 and grossed over $6.2 billion on mobile devices as of August 2021. The main game will transition to a free to play model starting in January 2022.
        <br>
        PUBG received positive reviews from critics, who found that while the game had some technical flaws, it presented new types of gameplay that could be easily approached by players of any skill level and was highly replayable. The game was attributed to popularizing the battle royale genre, with a number of unofficial Chinese clones also being produced following its success. The game also received several Game of the Year nominations, among other accolades. PUBG Corporation has run several small tournaments and introduced in-game tools to help with broadcasting the game to spectators, as they wish for it to become a popular esport. PUBG Mobile has been banned in some countries for allegedly being harmful and addictive to younger players.
        <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.900 only!</div> </a></div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 5:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="revillage.mp4" />
        </video>
        <div class="contenttext">
        Resident Evil Village[a] is a 2021 survival horror game developed and published by Capcom. It is the sequel to Resident Evil 7: Biohazard (2017). Players control Ethan Winters, who is searching for his kidnapped daughter after a fateful encounter with Chris Redfield, and finds himself in a village filled with mutant creatures. While Village maintains the Resident Evil series' survival horror elements, the game adopts a more action-oriented gameplay style compared to its predecessor.
        <br>
        The game was announced at the PlayStation 5 reveal event in June 2020 and was released on May 7, 2021, for Microsoft Windows, PlayStation 4, PlayStation 5, Stadia, Xbox One, and Xbox Series X/S. Resident Evil Village received generally favorable reviews, being praised for its gameplay, setting, and variety, although it received criticism for its puzzles, boss fights and performance issues on the Microsoft Windows version. The game's increased focus on action over its predecessor received more mixed opinions.
        <br>
       
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.3,499 only!</div></a> </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 6:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="godofwar.mp4" />
        </video>
        <div class="contenttext">
        In God of War, players control Kratos, a Spartan warrior who is sent by the Greek gods to kill Ares, the god of war. As the story progresses, Kratos is revealed to be Ares' former servant, who had been tricked into killing his own family and is haunted by terrible nightmares. Armed with the Blades of Chaos, a weapon made out of two daggers attached to chains, Kratos rumbles through ancient Athens and other locations on a murderous quest to terminate the rogue god. Action in God of War is viewed from the third person, and advanced movements such as running, jumping, climbing, and swimming are similar to those in the Tomb Raider series, another adventure-game series with strong platform-game characteristics. Some of Kratos's foes can be killed only by combinations of magic and physical attacks, making combat more reliant on skill. Greek mythology powers the story, so players encounter a myriad of Minotaurs and Hydras.
        <br>
        God of War's popularity prompted the development of a number of direct sequels and several spin-offs. God of War II (2007) for the PlayStation 2 also earned favourable critical response and generated excellent sales, and God of War III (2010) concluded the story of Kratos's revenge in spectacular fashion.
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.3,599 only!</div> </a>  </div>     
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 7:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="farcry6.mp4" />
        </video>
        <div class="contenttext">
        Far Cry 6 is a 2021 action-adventure first-person shooter game developed by Ubisoft Toronto and published by Ubisoft. It is the sixth main installment in the Far Cry series and the successor to 2018's Far Cry 5. The game was released on October 7, 2021, for Microsoft Windows, PlayStation 4, PlayStation 5, Xbox One, Xbox Series X/S, Stadia, and Amazon Luna. Set on the fictional Caribbean island of Yara, ruled as a dictatorship by "El Presidente" Antón Castillo (portrayed by Giancarlo Esposito) who is raising his son Diego (Anthony Gonzalez) to follow in his rule, players take on the role of guerilla fighter Dani Rojas (voiced by either Nisa Gunduz or Sean Rey), attempting to topple Castillo and his regime.
        <br>
        The game received a generally mixed reception, with critics praising its small improvements to the series gameplay formula and performances, but criticizing its lack of innovation and aging design.
        <br>
        The player has the ability to construct and upgrade guerrilla bases called "Camp Facilities", which provide useful resources and in-game bonuses to increase the skillset of the character, specialize perks in hunting animals, unlock fast travel locations throughout Yara, enlist new recruits and manage their equipment, or launch friendly NPC operations. The game's version of Far Cry 5's "Fangs for Hire" companion system returns, called "Amigos", which features recruitable animals with a variety of abilities and perks tasked to assist the player in combat and exploration.
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.3,199 only!</div>  </a></div>      
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 8:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="creedodyssey.mp4" />
        </video>
        <div class="contenttext">
        Assassin's Creed Odyssey is a 2018 action role-playing video game developed by Ubisoft Quebec and published by Ubisoft. It is the eleventh major installment in the Assassin's Creed series and the successor to 2017's Assassin's Creed Origins. Like its predecessor, the game features a large open world, and adopts many elements from the role-playing genre, putting more emphasis on combat and exploration than stealth. Naval combat from previous games in the series also plays a prominent role in Odyssey. The game's plot is set in a fictional history of real-world events, and tells a mythological history of the Peloponnesian War between Athens and Sparta from 431 to 422 BC. Players control a male or female mercenary who fights on both sides of the war as they attempt to find their family and eliminate a mysterious organization known as the Cult of Kosmos. Odyssey also continues the story arc of Layla Hassan, a major character introduced in Origins, who interface with the mercenary's memories as part of her efforts to locate a powerful artifact on behalf of the Assassin Brotherhood.
        <br>
        Development of the game commenced shortly following the release of Assassin's Creed Syndicate (2015). Following the footsteps of Origins, Odyssey facilitated the transition of Assassin's Creed into a series of action role-playing games by introducing player choices. Compared with other games in the series, Odyssey has a larger focus on mythology, in this case Greek mythology, and a smaller focus on the on the conflict between the Assassins and Templars, which are the central narrative element present in most mainline Assassin's Creed game. Throughout the game's development, the team was inspired by other contemporary RPG titles including The Witcher 3: Wild Hunt, The Elder Scrolls V: Skyrim and Fallout. The music of the game was composed by The Flight.
        <br>
        Odyssey was released worldwide for Microsoft Windows, PlayStation 4, Xbox One on October 5, 2018. It received generally positive reviews from critics, with praise for its gameplay, graphics, characters, role-playing elements and world design, but was criticised for its pacing, feeling too ambitious, and the inclusion of microtransactions. Odyssey was a favorable commercial success, selling over 10 million copies worldwide by March 2020. Ubisoft supported the game extensively following its launch, releasing two paid expansions and a Discovery Tour, which includes a series of guided tours that allow players to explore the world of Classical Greece for educational purposes. Odyssey was followed in November 2020 by Assassin's Creed Valhalla, which takes place in medieval England and Norway during the Viking expansion across Europe
        <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.2,099 only!</div> </a></div>       
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 9:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="lastofus2.mp4" />
        </video>
        <div class="contenttext">
        The Last of Us Part II is a 2020 action-adventure game developed by Naughty Dog and published by Sony Interactive Entertainment for the PlayStation 4. Set five years after The Last of Us (2013), the game focuses on two playable characters in a post-apocalyptic United States whose lives intertwine: Ellie, who sets out for revenge after suffering a tragedy, and Abby, a soldier who becomes involved in a conflict between her militia and a religious cult. The game is played from the third-person perspective and allows the player to fight human enemies and cannibalistic zombie-like creatures with firearms, improvised weapons, and stealth.
        <br>
        Development of The Last of Us Part II began in 2014, soon after the release of The Last of Us Remastered. Neil Druckmann returned as creative director, co-writing the story with Halley Gross. The game's themes of revenge and retribution were inspired by Druckmann's experiences growing up in Israel. Ashley Johnson reprises her role as Ellie, while Laura Bailey was cast as Abby. Their performances included the simultaneous recording of motion and voice. The developers pushed the technical capabilities of the PlayStation 4 during development. Gustavo Santaolalla returned to compose and perform the score. Development reportedly included a crunch schedule of 12-hour workdays.
        <br>
        Following some delays, partly due to the COVID-19 pandemic, The Last of Us Part II was released on June 19, 2020. It received critical acclaim, with praise for its gameplay, audio design, score, performances, characters, and visual fidelity, though its narrative and themes divided critics. It was the subject of review bombing on Metacritic, with some player criticism directed at particular scenes, chapters, and characters; discourse surrounding the game was observed to have become adversarial. Part II is one of the best-selling PlayStation 4 games and the fastest-selling PlayStation 4 exclusive, with over four million units sold in its release weekend. It holds the record for most Game of the Year awards, and received multiple other accolades from awards shows and gaming publications.
        <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.2,499 only!</div> </a> </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 10:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="tombraider.mp4" />
        </video>
        <div class="contenttext">
        Tomb Raider is a 2013 action-adventure video game developed by Crystal Dynamics and published by Square Enix's European subsidiary. It is the tenth title in the Tomb Raider franchise, and operates as a reboot that reconstructs the origins of Lara Croft.[4][5] Tomb Raider was first released on 5 March 2013 for Microsoft Windows, PlayStation 3 and Xbox 360. Gameplay elements focus more on survival, although exploration is used within the game when exploring the island and various optional tombs. It is also the first game in the main series to have multiplayer, the first game in the series to be published by Square Enix, after the latter's acquisition of Eidos Interactive in 2009, and the first game in the series to be given a "Mature" rating from the ESRB.
        <br>
        Crystal Dynamics began development of Tomb Raider soon after the release of Tomb Raider: Underworld in 2008. Rather than a sequel, the team decided to completely reboot the series, re-establishing the origins of Lara Croft for the second time, as they did with Tomb Raider: Legend. Tomb Raider is set on Yamatai, an island from which Lara, who is untested and not yet the battle-hardened explorer she is in other titles in the series, must save her friends and escape while being hunted down by a malevolent cult. Camilla Luddington was announced to voice and perform as Lara Croft in 2010, replacing Keeley Hawes.
        <br>
        Widely anticipated, the game suffered a delayed release from late 2012 to March 2013. Upon release, Tomb Raider received critical acclaim, with critics praising the graphics, gameplay, Luddington's performance as Lara, and Lara's characterization and development, although the addition of a multiplayer mode was not well received and some reviewers directed criticism towards the game's ludonarrative dissonance. Tomb Raider went on to sell more than 14.5 million copies as of October 2021, making it the best-selling Tomb Raider title to date. A remastered version, Tomb Raider: Definitive Edition, was released worldwide in January 2014 for PlayStation 4 and Xbox One containing all features and DLC. A sequel, Rise of the Tomb Raider, was released in November 2015 and a third and final instalment, Shadow of the Tomb Raider, was released in September 2018.
        <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.899 only!</div></a>  </div>    
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 11:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="forzahorizon5.mp4" />
        </video>
        <div class="contenttext">
        Forza Horizon 5 is a 2021 racing video game developed by Playground Games and published by Xbox Game Studios. It is the fifth Forza Horizon title and twelfth main instalment in the Forza series. The game is set in a fictionalised representation of Mexico. It was released on 9 November 2021[a] for Microsoft Windows, Xbox One, and Xbox Series X/S.
        <br>
        The game received critical acclaim and became a huge commercial success upon release; it launched to over ten million players in its first week of full availability, the biggest-ever launch for an Xbox Game Studios title. The game was nominated for three jury-voted awards at The Game Awards 2021, winning all three of its nominations and tying with It Takes Two for most wins, and was also nominated for the public-voted Players' Voice award, which went to fellow Xbox Game Studios title Halo Infinite.
        <br>
        Forza Horizon 5 is a racing video game set in an open world environment based in a fictional representation of Mexico. The game has the largest map in the entire Forza Horizon series, being 50% larger than Forza Horizon 4 while also having the highest point in the Horizon series. The map was described by creative director Mike Brown as one of the most diverse Forza Horizon maps the team has built. The map contains an active caldera volcano, jungles and beaches, ancient Mayan temples, and towns and cities such as Guanajuato. Players can explore the open world freely, though they can also compete in multiplayer races and complete the campaign mode. Both the cars featured in the game and the player character can be extensively customised. Players are able to create custom liveries and tunes for cars, and perform engine swaps, drivetrain swaps, or install body kits on certain vehicles. The game is the first in the franchise to support ray tracing on cars (although this is only available in ForzaVista).
        <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.3,399 only!</div> </a>  </div>   
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Product 12:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
          <input type="button" value="Back to Games" onclick="history.back()">
         </form>    
        <video  width=100% height=360px autoplay>
          <source src="daysgone.mp4" />
        </video>
        <div class="contenttext">
        Days Gone is a 2019 action-adventure video game developed by Bend Studio and published by Sony Interactive Entertainment. The game is set in post-apocalyptic Oregon two years after the start of a pandemic. Former outlaw-turned-drifter Deacon St. John discovers his wife Sarah may still be alive and goes on a quest to find her. Days Gone is played from a third-person perspective in which the player can explore an open world environment. Players can use firearms, melee weapons and improvised weapons, and can use stealth to defend themselves against hostile humans and cannibalistic creatures known as freakers. A major game mechanic is Deacon's motorcycle, which is used as the player character's main mode of transportation and mobile inventory.
       <br>
       Days Gone was Bend Studio's first open-world project, its first original property since Syphon Filter (1999), and its first development project for home consoles after spending decades working on spinoff games for handheld consoles. The game's development took approximately six years; Bend Studio expanded nearly three-fold to support it. Major sources of inspiration for Days Gone were World War Z, The Walking Dead and Sons of Anarchy. The game was officially unveiled at E3 2016; its release was originally planned for 2018 but was delayed several times.
       <br>
       The game was released in April 2019 for PlayStation 4 and in May 2021 for Windows. Upon release, it received mixed to positive reviews from critics, who praised the graphics, the artificial intelligence of the enemies and Sam Witwer's performance as Deacon but criticized the story, mission design, and several technical issues. It was often regarded as one of the weaker Sony first-party games that were released during the PlayStation 4 generation. Days Gone was a commercial success; it sold more copies than all of Bend Studio's previous games combined and became the 19th-best-selling game of 2019 in the US. In 2021, it was reported that the development team had unsuccessfully pitched a sequel to Sony.
       <br>
        <a href="/static/buy.html"><div class="buy">Buy Now</a><br>Rs.2,399 only!</div></a></div>     
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

##### Buying Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
            <input type="button" value="Back to Description" onclick="history.back()">
           </form>
        
        <div class="pay"> Congrats!!<br>Your Device has been successfully hacked by us.....
        <br><img src="img/laug.PNG" ./>
      </div>                
      </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

### People Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
          <h1>Our Team:</h1><br><br>
          <div class="productitems">
            <div class="people"> 
              <a href="/static/peopleinf.html">
                <div class="pimage">
                <img src="/static/img/p1.png" alt="product image">
                </div>
                <b><div class="pname">Task Master</div>
                <div class="pprice">Website Owner</div></a>
            </div></b>
            <div class="people"> 
              <a href="/static/peopleinf.html">
                <div class="pimage">
                <img src="/static/img/p2.png"  alt="product image">
                </div>
                <b><div class="pname">Bill Gates</div>
                <div class="pprice">Finance manager</div></a>
            </div></b>
            <div class="people"> 
              <a href="/static/peopleinf.html">
              <div class="pimage">
              <img src="/static/img/p3.png"  alt="product image">
              </div>
              <b><div class="pname">Samantha </div>
              <div class="pprice">HR</div></a>
            </div></b>
            <div class="people"> 
              <a href="/static/peopleinf.html">
              <div class="pimage">
              <img src="/static/img/p4.png" alt="product image">
              </div><b>
              <div class="pname">Otis Milburn</div>
              <div class="pprice">Marketing Manager</div></a>
          </div></b>
          <div class="people"> 
            <a href="/static/peopleinf.html">
            <div class="pimage">
            <img src="/static/img/p5.png"  alt="product image">
            </div><b>
            <div class="pname">Robert Downey Jr.</div>
            <div class="pprice">Backend Team Leader</div></a>
        </div></b>  
        <div class="people"> 
          <a href="/static/peopleinf.html">
          <div class="pimage">
          <img src="/static/img/p6.png"  alt="product image">
          </div><b>
          <div class="pname">Emma Watson</div>
          <div class="pprice">Operation Manager</div></a>
      </div></b>
          </div>
        </div>
            
      </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### All People Info:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
            <input type="button" value="Back to People" onclick="history.back()">
           </form>
        
        <div class="pay"> Staying anonymous!!<br>
            Currently no information available.
      </div>                
      </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

### Contact Us:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>
  <body>
    <div class="container">
        <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Games</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>Contact Us:</h1><br><br>
          <h1>Address:</h1>
          <div class="contenttext"><b>
           6966 Ocean Beach<br>
           Grove Street,<br>
           Los Santos-151486,<br>
           USA<br></b>
          </div><br>
          <h1>Phone:</h1>
          <div class="contenttext"><b>
              1.Taskmaster-9985878451<br><br>
              2.Bill Gates-8571586517<br><br>
              3.Samantha-9840502522</b>
          </div>
          <h1>E-Mail:</h1><br>
          <a href="/static/email.html">
          <div class="contenttext"><b>
              www.g4l.com</b></a>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Gamer 4 Life, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

#### Email Page:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>GAMER 4 LIFE</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/logomn.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">4 LIFE</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Games</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <form>
            <input type="button" value="Back to Contact" onclick="history.back()">
           </form>
        
        <div class="pay"> Thanks for installing ILOVEYOU virus!!<br>
            Stay tuned on your gmail for more updates.
      </div>                
      </div>
      <div class="footer">
        Copyright &#169; 2021 GAMER 4 LIFE, Developed by NITHISHKUMAR.
      </div>
    </div>
  </body>
</html>
```

## OUTPUT:

### Home Page:

![output](./images/home.PNG)

### Product Page:
![](./images/product1half.JPG)
![](./images/product2half.JPG)

#### Product 1:
![](./images/product1.png)

#### Product 2:
![](./images/product2.png)

#### Product 3:
![](./images/product3.png)

#### Product 4:
![](./images/product4.png)

#### Product 5:
![](./images/product5.png)

#### Product 6:
![](./images/product6.png)

#### Product 7:
![](./images/product7.png)

#### Product 8:
![](./images/product8.png)

#### Product 9:
![](./images/product9.png)

#### Product 10:
![](./images/product10.png)

#### Product 11:
![](./images/product11.png)

#### Product 12:
![](./images/product12.png)

##### Buying Page:
![](./images/productbuyingpage.png)

### People:
![](./images/people.png)

#### People Info:
![](./images/peopleinfo.png)

### Contact Us:
![](./images/contactus.png)

#### Email Page:
![](./images/contactusemail.png)

## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
