## Step 1
---------------

    <div class="container">
      <!-- Destinations -->
      <div class="row" id="destinations">
        <h2 class="text-center">Destinations</h2>
        <hr>
      </div>
      <!-- Crew -->
      <div class="row" id="crew">
        <h2 class="text-center">Crew</h2>
        <hr>
      </div>
      <!-- About -->
      <div class="row" id="about">
        <h2 class="text-center">About Kessel Runners</h2>
        <hr>
        <p>Kessel Runners is a tourist company made up of retired pilots from the Alliance to Restore the Republic and the New Republic. Rather than sit around and collect a pension, they decided to keep doing what they love, and show others the wonders of the galaxy.</p>
        <p>But really, it's a fictional site for students of the <a href="http://fourathens.com/classes">FourAthens code classes</a>. </p>
      </div>

      <footer>
        <p class="text-center">&copy; Kessel Runners GFFA Tours 2015</p>
      </footer>
    </div>

## Step 2
---------------

    <script>
      $('.carousel').carousel({
        interval: 10000
      })
    </script>

    <div id="destination-carousel" class="carousel slide" data-ride="carousel">
      <!-- Indicators -->
      <ol class="carousel-indicators">
        <li data-target="#destination-carousel" data-slide-to="0" class="active"></li>
        <li data-target="#destination-carousel" data-slide-to="1"></li>
        <li data-target="#destination-carousel" data-slide-to="2"></li>
        <li data-target="#destination-carousel" data-slide-to="3"></li>
        <li data-target="#destination-carousel" data-slide-to="4"></li>
      </ol>

      <!-- Wrapper for slides -->
      <div class="carousel-inner" role="listbox">
        <div class="item active text-center">
          <img src="img/coruscant-1.jpg" alt="img/coruscant-1.jpg">
          <div class="carousel-caption">
            <h2>Capital of the Galaxy</h2>
            <p><a href="#coruscant" class="btn btn-primary btn-lg">Secondary CTA</a>&nbsp;<a class="btn btn-success btn-lg" href="#" role="button">Learn more &raquo;</a></p>
          </div>
        </div>
        <div class="item text-center">
          <img src="img/endor-1.jpg" alt="img/coruscant-1.jpg">
          <div class="carousel-caption">
            <h2>Birthplace of the New Republic</h2>
            <p><a href="#endor" class="btn btn-primary btn-lg">Secondary CTA</a>&nbsp;<a class="btn btn-success btn-lg" href="#" role="button">Learn more &raquo;</a></p>
          </div>
        </div>
        <div class="item text-center">
          <img src="img/bespin-1.jpg" alt="img/coruscant-1.jpg">
          <div class="carousel-caption">
            <h2>Luxury in the clouds</h2>
            <p><a href="#bespin" class="btn btn-primary btn-lg">Secondary CTA</a>&nbsp;<a class="btn btn-success btn-lg" href="#" role="button">Learn more &raquo;</a></p>
          </div>
        </div>
        <div class="item text-center">
          <img src="img/naboo-1.jpg" alt="img/coruscant-1.jpg">
          <div class="carousel-caption">
            <h2>Jewel of the former Empire</h2>
            <p><a href="#naboo" class="btn btn-primary btn-lg">Secondary CTA</a>&nbsp;<a class="btn btn-success btn-lg" href="#" role="button">Learn more &raquo;</a></p>
          </div>
        </div>
        <div class="item text-center">
          <img src="img/corellia-1.jpg" alt="img/coruscant-1.jpg">
          <div class="carousel-caption">
            <h2>Homeworld of Heroes</h2>
            <p><a href="#corellia" class="btn btn-primary btn-lg">Secondary CTA</a>&nbsp;<a class="btn btn-success btn-lg" href="#" role="button">Learn more &raquo;</a></p>
          </div>
        </div>
      </div>

      <!-- Controls -->
      <a class="left carousel-control" href="#destination-carousel" role="button" data-slide="prev">
        <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a class="right carousel-control" href="#destination-carousel" role="button" data-slide="next">
        <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>

## Step 3
---------------

#destinations > .row {
  padding-top: 2em;
}
.navbar-inverse {
  background-image: none;
  background-color: #76b38f;
  border: none;
  border-top: 3px solid #52936d;
  border-bottom: 1px solid #52936d;
  border-radius: 0;
  padding: 1em;
  text-align: center;
}
.navbar ul {
  margin: 0 10px;
  padding: 5px 0;
  display: inline-block;
}

.navbar li {
  white-space: none;
  transition: background .2s;
  position: relative;
  float: left;
  margin: 0;
  padding: 0;
  list-style: none;
}

.navbar a {
  color: #fff;
  text-decoration: none;
  font-size: 1.25em;
}

.navbar a:hover {
  text-decoration: none;
}

.navbar li > a::after {
  content: '|';
  font-family: 'fontello';
  vertical-align: middle;
  font-size: 1.5em;
  margin: 0px 30px;
  color: #f1f1f1 !important;
}

.navbar li:last-child > a::after {
  content: '';
}

    <nav class="navbar navbar-inverse" role="navigation">
      <div class="container">
        <div class="navbar-header">
          <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
        </div>
        <div id="navbar" class="navbar-collapse collapse">
          <!-- This is where our links will go -->
          <ul>
            <li><a href="#">Kessel Runners Home</a></li>
            <li><a href="#destinations">Destinations</a></li>
            <li><a href="#crew">Crew</a></li>
            <li><a href="#about">About</a></li>
          </ul>
        </div><!--/.navbar-collapse -->
      </div>
    </nav>

        <div class="row" id="coruscant">
          <div class="col-md-4">
            <img src="img/coruscant-2.jpg" alt="">
          </div>
        </div>
        <div class="row" id="endor">
          <div class="col-md-4 col-md-offset-1">
            <img src="img/endor-2.jpg" alt="">
          </div>
        </div>
        <div class="row" id="bespin">
          <div class="col-md-4">
            <img src="img/bespin-2.jpg" alt="">
          </div>
        </div>
        <div class="row" id="naboo">
          <div class="col-md-4 col-md-offset-1">
            <img src="img/naboo-2.jpg" alt="">
          </div>
        </div>
        <div class="row" id="corellia">
          <div class="col-md-4">
            <img src="img/corellia-2.jpg" alt="">
          </div>
        </div>

## Step 4
---------------

          <div class="col-md-7 col-md-offset-1">
            <h3>Coruscant</h3>
            <h6>Capital of the Galaxy</h6>
            <hr>
            <p>Coruscant, formerly known as Imperial Center, was named for the planet's resemblence to a Corusca gem as the lights of the planet-wide Galactic City never go out. Even during the Clone Wars, when the capital was under direct attack by the Confederacy of Independent Systems, the lights of Coruscant represented the light of democracy that would never be extinguished.</p>
            <p>With the fall of the Galactic Empire, Coruscant was restored as a key planet in the New Republic. Imperial sympathizers are still known troublemakers, but Triple Zero, as it's known for its galactic coordinates, is a must see no matter what the circumstances.</p>
          </div>

          <div class="col-md-7">
            <h3>Endor</h3>
            <h6>Birthplace of the New Republic</h6>
            <hr>
            <p>On the forest moon of Endor, the Alliance to Restore the Republic found their greatest challenge, and won a decisive victory against the Galactic Empire's Death Star II, the Executor armada, and the Emperor himself. The Alliance fleet, led by Admiral Ackbar, defeated the Empire's most powerful fleet and its most experienced commanders.</p>
            <p>In the years since the Battle of Endor, the forest moon has become a quietly successful tourist location, with the native Ewok populations welcoming travellers looking for a less-pampered adventure. The natural beauty of the forest moon is huge draw, no matter what your political leanings.</p>
          </div>

          <div class="col-md-7 col-md-offset-1">
            <h3>Bespin</h3>
            <h6>Luxury in the clouds</h6>
            <hr>
            <p>Bespin was an immense gas giant located in the vicinity of the Anoat system, in a little-visited sector of the galaxy. Bespin had several moons, and its gaseous mass contained a thin stratum of habitable atmosphere. Its layers were a source of rare Tibanna gas, which was harvested and refined in several mining complexes, including Cloud City, an opulent metropolis suspended in the planet's huge billowing clouds. </p>
            <p>The Ugnaught city of Ugnorgrad also was located over the planet, being ruled by King Ozz in the time after the Battle of Endor. During the Galactic Civil War, Bespin remained unaffiliated, but that did not prevent the Galactic Empire from garrisoning the planet and seizing Cloud City. However, with the Empire's defeat at Endor, the gas giant and its prosperous mining colony ended up recovering their freedom.</p>
          </div>

          <div class="col-md-7">
            <h3>Naboo</h3>
            <h6>Jewel of the former Empire</h6>
            <hr>
            <p>Naboo was a small pastoral world located near the border of the Outer Rim Territories. It was noted for having a porous crust that contained plasmic energy. Its surface comprized a vast array of different landscapes, from rolling plains and grassy hills to swampy lakes. Beside its natural features, Naboo was considered a world of classical beauty due to the aesthetics of its population centers. While most of Naboo's land animals were peaceful, as exemplified by the gentle shaak, the planet's oceans teemed with menacing creatures such as the opee sea killer and the sando aqua monster.</p>
            <p>Following the rise of the Galactic Empire, Naboo hosted one of the new regime's military garrisons. However, when news of Palpatine's death had spread across the galaxy after the Battle of Endor, an outpouring of joy occurred on Naboo, the inhabitants of which considered themselves free at last. Naboo was one of the first planets to be freed by the New Republic. Thane Kyrell and Corona Squadron fought to hold the Empire from retaking the planet, and it's now a major tourist destination.</p>
          </div>

          <div class="col-md-7 col-md-offset-1">
            <h3>Corellia</h3>
            <h6>Homeworld of Heroes</h6>
            <hr>
            <p>Corellia was located in the Core Worlds. It was known for its ace pilots and large starships. Vessels such as the Millennium Falcon and Imperial starships were built on Corellia. At some point in the Imperial era, an organization known as the Corellian Resistance operated on the planet, fighting against the Galactic Empire. One of their members, Miru Nadrinakar, attempted to warn them of an upcoming crackdown.</p>
            <p>It was the homeworld of Han Solo, Wedge Antilles, the Besalisk Gadren, and the bounty hunter Dengar.</p>
          </div>

## Step 5
---------------

<div class="col-md-4 text-center">
  <img src="/img/wedge.jpg" alt="">
  <h3>Wedge Antilles</h3>
  <p>Wedge Antilles was a renowned human male starfighter pilot from Corellia who served in the Alliance to Restore the Republic and the New Republic during their fight against the Galactic Empire. He became a member of the Rebel Alliance during the Galactic Civil War and fought in the Battle of Yavin, where he flew in Red Squadron alongside Luke Skywalker.</p>
</div>
<div class="col-md-4 text-center">
  <img src="/img/mirax.jpg" alt="">
  <h3>Mirax Terrik</h3>
  <p>Wedge and Mirax grew up as close friends, as Mirax's father occasionally used the Antilles Fuel Depot as a waystation during his smuggling activities. When her father was finally apprehended by CorSec and sentenced to five years of hard labor on Kessel, the still underage Mirax took control of his smuggling operation. Under her guidance, the organization maintained its profitability despite turning almost completely legitimate. She's been flying ever since.</p>
</div>
<div class="col-md-4 text-center">
  <img src="/img/janson.jpg" alt="">
  <h3>Wes Janson</h3>
  <p>Wes Janson was a human male pilot native to Taanab who served as a Lieutenant for the Alliance to Restore the Republic during the Galactic Civil War. He served as a gunner for Wedge Antilles at the Battle of Hoth. He was the first member of Rogue Squadron to successfully take down an Imperial walker with the harpoon and tow cable gambit devised by Commander Luke Skywalker. Following the battle, Janson (along with Antilles and Derek Klivian) boarded X-wing starfighters and helped the last Rebel transport, The Bright Hope escape Hoth.</p>
</div>