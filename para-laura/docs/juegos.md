# Videojuegos

## Te he preparado un juegito en el que tendrás que adivinar por la portada borrosa qué juego es...Hay en total 20 juegiños. Ten en cuenta que son juegos que los dos conocemos... Hay 4 categorías: 
1. Juegos que me gusta transmitirte 
2. Juegos que me gusta que TÚ me transmitas 
3. Juegos que quiero que juegues y me transmitas 
4. Juegos que me gusta jugar contigo. 
Ahora que sabes las categorías... ¡Que empiece el juego!

<div id="game-container">
  <!-- Juego 1 -->
  <div class="game" id="game1">
    <img src="https://i.3djuegos.com/juegos/5184/silent_hill_3/fotos/ficha/silent_hill_3-1697794.jpg" alt="Juego 1" class="blurry-img" id="img1">
    <div class="controls">
      <select id="select1">
        <option value="">Selecciona un juego</option>
        <option value="Silent Hill 3">Silent Hill 3</option>
        <option value="Elden Ring">Elden Ring</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Outlast">Outlast</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Silent Hill 2">Silent Hill 2</option>
        <option value="Crow Country">Crow Country</option>
        <option value="PowerWash Simulator">PowerWash Simulator</option>
        <option value="Demonologist">Demonologist</option>
      </select>
      <button onclick="checkAnswer(1, 'Silent Hill 3', 'Silent Hill 3 es un juego que me encanta verte jugar, me encanta que resolvamos las cosas juntos. Es un juego que te hace ser un chico muy interesante jeje')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 2 -->
  <div class="game" id="game2" style="display: none;">
    <img src="https://cdn.hobbyconsolas.com/sites/navi.axelspringer.es/public/media/image/2017/04/outlast-trinity-caratula.jpg?tf=1200x" alt="Juego 2" class="blurry-img" id="img2">
    <div class="controls">
      <select id="select2">
        <option value="">Selecciona un juego</option>
        <option value="Elden Ring">Elden Ring</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Outlast">Outlast</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Silent Hill 2">Silent Hill 2</option>
        <option value="Crow Country">Crow Country</option>
        <option value="PowerWash Simulator">PowerWash Simulator</option>
        <option value="Demonologist">Demonologist</option>
      </select>
      <button onclick="checkAnswer(2, 'Outlast', 'La saga de Outlast es un saga que me encantaría que jugasemos juntos de forma física, tenemos que organizar una cita para jugar juntitos está triología (que tengo comprada) que da susto y así si nos asustamos podemos abrazarnos y besarnos uwu.')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 3 -->
  <div class="game" id="game3" style="display: none;">
    <img src="https://fyre.cdn.sewest.net/powerwash-simulator/6295daf05c77740019a6eca2/packshot-image-ySbPs05fF.jpg?quality=85&width=3840" alt="Juego 3" class="blurry-img" id="img3">
    <div class="controls">
      <select id="select3">
        <option value="">Selecciona un juego</option>
        <option value="Elden Ring">Elden Ring</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Silent Hill 2">Silent Hill 2</option>
        <option value="Crow Country">Crow Country</option>
        <option value="PowerWash Simulator">PowerWash Simulator</option>
        <option value="Demonologist">Demonologist</option>
      </select>
      <button onclick="checkAnswer(3, 'PowerWash Simulator', 'Me encantó jugar contigo este juego, tan tranquilito... mientras hablabamos de chill... Deberíamos volver a jugarlo juntitos :3')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 4 -->
  <div class="game" id="game4" style="display: none;">
    <img src="https://static-cdn.jtvnw.net/ttv-boxart/1286840579_IGDB-272x380.jpg" alt="Juego 4" class="blurry-img" id="img4">
    <div class="controls">
      <select id="select4">
        <option value="">Selecciona un juego</option>
        <option value="Elden Ring">Elden Ring</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Silent Hill 2">Silent Hill 2</option>
        <option value="Crow Country">Crow Country</option>
        <option value="Demonologist">Demonologist</option>
      </select>
      <button onclick="checkAnswer(4, 'Demonologist', 'Que bien me lo pase jugando a este juego contigo, los susto que nos dabamos jajajjdjadjad. Aunque el juego fuese mierdecilla, me lo pase muy bien contigo...')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 5 -->
  <div class="game" id="game5" style="display: none;">
    <img src="https://uvejuegos.com/img/caratulas/62850/1_pc.jpg" alt="Juego 5" class="blurry-img" id="img5">
    <div class="controls">
      <select id="select5">
        <option value="">Selecciona un juego</option>
        <option value="Elden Ring">Elden Ring</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Silent Hill 2">Silent Hill 2</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(5, 'Elden Ring', 'Me encanta transmitirte Elden Ring, aunque se que aveces tu te aburras, a mi me encanta sentirme observado por ti, y enseñarte armas y que tu le des opiniones, y que me animes cuando estoy contra un boss...')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 6 -->
  <div class="game" id="game6" style="display: none;">
    <img src="https://tierraadentro.fondodeculturaeconomica.com/wp-content/uploads/2022/02/9891_IGDB-272x380.jpeg" alt="Juego 6" class="blurry-img" id="img6">
    <div class="controls">
      <select id="select6">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Silent Hill 2">Silent Hill 2</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(6, 'Silent Hill 2', 'ME ENCANTO TRANSMITIRTE EL SILENT HILL 2 Y QUE JUGASEMOS JUNTITOS Y TENGO MUCHAS GANAS DE COMPRAR EL REMASTERED Y JUGARLO JUNTITOS OTRA VEZ!!!')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 7 -->
  <div class="game" id="game7" style="display: none;">
    <img src="https://spainaudiovisualhub.mineco.gob.es/content/dam/seteleco-hub-audiovisual/resources/images/videojuegos/02_gris.jpg" alt="Juego 7" class="blurry-img" id="img7">
    <div class="controls">
      <select id="select7">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Gris">Gris</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(7, 'Gris', 'Quiero que juguemos a este juego juntos físicamente, es un juego corto pero se ve que es muy bonito, y me recuerda a ti, así que hay que organizar cita para jugar juntos!')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 8 -->
  <div class="game" id="game8" style="display: none;">
    <img src="https://assetsio.gnwcdn.com/co20x5.jpg?width=1200&height=1200&fit=bounds&quality=70&format=jpg&auto=webp" alt="Juego 8" class="blurry-img" id="img8">
    <div class="controls">
      <select id="select8">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="The Forest">The Forest</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(8, 'The Forest', 'Recuerdo que The Forest fue uno de los primeros juegos que te empeze a transmitir, y me encanto que tu me pidieras que te transmitiera y que te encanta el juego, tengo pensado comprarte The Forest, o haber si rebajan el The Forest 2 y así lo jugamos juntitos que me hace mucha ilusión')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 9 -->
  <div class="game" id="game9" style="display: none;">
    <img src="https://i.pinimg.com/236x/a8/ac/cf/a8accf7cba6517e4f8c253a7ee867afb.jpg" alt="Juego 9" class="blurry-img" id="img9">
    <div class="controls">
      <select id="select9">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="Minecraft">Minecraft</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(9, 'Minecraft', 'Me encanta jugar minecraft contigo, se que soy muy tonto y por mi culpa aveces te hago sentir mal al jugar, pero voy a cambiar y así conseguiremos jugar minecraft juntitos como novios hermosos')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 10 -->
  <div class="game" id="game10" style="display: none;">
    <img src="https://s3.gamescribe.io/high/fbf71ce4-a5e1-580a-64c9-bb93637414e1.jpg" alt="Juego 10" class="blurry-img" id="img10">
    <div class="controls">
      <select id="select10">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>
        <option value="Supermarket Together">Supermarket Together</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(10, 'Supermarket Together', 'Me encanto jugar contigo a este juegito, fue muy gracioso y divertido jejejej, está chulo manejar un supermercado juntitos :3')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 11 -->
  <div class="game" id="game11" style="display: none;">
    <img src="https://data.xxlgamer.com/products/3843/0YH1fBjgmuKXYL-big.jpg" alt="Juego 11" class="blurry-img" id="img11">
    <div class="controls">
      <select id="select11">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Stardew Valley">Stardew Valley</option>on>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(11, 'Stardew Valley', 'Es un juegiño que me encanta transmitirte, que tu me transmitas y que jueguemos juntoz... aunque hayamos tenido nuestras peleitas mientras jugabamos, yo me lo pasaba muy bien contigo :3333')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 12 -->
  <div class="game" id="game12" style="display: none;">
    <img src="https://www.selecta-vision.com/wp-content/uploads/2024/07/617359-blasphemous-xbox-one-front-cover_3.jpg" alt="Juego 12" class="blurry-img" id="img12">
    <div class="controls">
      <select id="select12">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Blasphemous">Blasphemous</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(12, 'Blasphemous', 'Me lo pase tan bien transmitiendote este juegardo, te amo mucho y gracias por ver mis transmisiones :3')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 13 -->
  <div class="game" id="game13" style="display: none;">
    <img src="https://assetsio.gnwcdn.com/co2ekt.jpg?width=1200&height=1200&fit=bounds&quality=70&format=jpg&auto=webp" alt="Juego 13" class="blurry-img" id="img13">
    <div class="controls">
      <select id="select13">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Fortnite">Fortnite</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(13, 'Fortnite', 'Un juego que aunque yo sea muy competitivo... disfruto mucho jugando contigo, siempre tenemos nuestras peleitas pero yo me lo paso re que te bien contigo :3')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 14 -->
  <div class="game" id="game14" style="display: none;">
    <img src="https://cdn.ozone.bg/media/catalog/product/cache/1/image/400x498/a4e40ebdc3e371adff845072e1c73f37/d/a/58fe916c01e167a42b7dda85c6f6535f/dark-souls-trilogy-compendium-25th-anniversary-edition-30.jpg" alt="Juego 14" class="blurry-img" id="img14">
    <div class="controls">
      <select id="select14">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Dark Souls">Dark Souls</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(14, 'Dark Souls', 'Es una saga que disfruto mucho cuando estas conmigo en llamada viendome jugar, me encanta tu compañia y sobretodo en uno de mis juegiños favs, te amooooo')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 15 -->
  <div class="game" id="game15" style="display: none;">
    <img src="https://pics.filmaffinity.com/Hollow_Knight-986585901-large.jpg" alt="Juego 15" class="blurry-img" id="img15">
    <div class="controls">
      <select id="select15">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Hollow Knight">Hollow Knight</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(15, 'Hollow Knight', 'Juegito que disfrutamos juntos, me encantó transmitirte y que me vieses, tenemos que repetirlo y jugarlo hasta el final jeje')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 16 -->
  <div class="game" id="game16" style="display: none;">
    <img src="https://farm6.staticflickr.com/5498/14323170106_20d240b59b_o.png" alt="Juego 16" class="blurry-img" id="img16">
    <div class="controls">
      <select id="select16">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="The Sims 4">The Sims 4</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(16, 'The Sims 4', 'JUEGARDO QUE ME ENCANTA QUE ME TRANSMITAS, ERES TAN PRO QE SE ME CAE LA POLLA AL SUELO CUANDO ME ENSEÑAS LOS PERSONAJES QUE CREAR O LAS CASAS QUE TE CURRAS, muy chulo jeje')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 17 -->
  <div class="game" id="game17" style="display: none;">
    <img src="https://i.3djuegos.com/juegos/17586/phasmophobia/fotos/ficha/phasmophobia-5275630.webp" alt="Juego 17" class="blurry-img" id="img17">
    <div class="controls">
      <select id="select17">
        <option value="">Selecciona un juego</option>
        <option value="Papa's Freezeria">Papa's Freezeria</option>
        <option value="Phasmophobia">Phasmophobia</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(17, 'Phasmophobia', 'Juegazo de terror que hemos disfrutado muchísimo juntos, deseando que salga en oferta y comprarnoslo y jugar cuando queramos y pasar miedo juntitos jejejej, que risas me echaba contigo tontorron uwu')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 18 -->
  <div class="game" id="game18" style="display: none;">
    <img src="https://howlongtobeat.com/games/126295_Papas_Freezeria.jpg" alt="Juego 18" class="blurry-img" id="img18">
    <div class="controls">
      <select id="select18">
        <option value="">Selecciona un juego</option>
        <option value="Papas Freezeria">Papa's Freezeria</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(18, 'Papas Freezeria', 'Juegito que nos compartimos el uno con el otro y que nos poniamos bien competitivos haber quien tenia más días hechos ehejejej')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 19 -->
  <div class="game" id="game19" style="display: none;">
    <img src="https://i.3djuegos.com/juegos/18541/resident_evil_4_remake/fotos/ficha/resident_evil_4_remake-5789986.jpg" alt="Juego 19" class="blurry-img" id="img19">
    <div class="controls">
      <select id="select19">
        <option value="">Selecciona un juego</option>
        <option value="Resident Evil">Resident Evil</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(19, 'Resident Evil', 'Buah resident evil es una saga que quiero que jueguemos juntitos, en persona o yo transmitiendote, es un juego que seguro te gustaría un montón')">Adivinar</button>
    </div>
  </div>

  <!-- Juego 20 -->
  <div class="game" id="game20" style="display: none;">
    <img src="https://i.3djuegos.com/juegos/19709/crow_country/fotos/ficha/crow_country-5889371.webp" alt="Juego 20" class="blurry-img" id="img20">
    <div class="controls">
      <select id="select20">
        <option value="">Selecciona un juego</option>
        <option value="Crow Country">Crow Country</option>
      </select>
      <button onclick="checkAnswer(20, 'Crow Country', 'Es un juego que tengo tantas ganas de comprartelo y que me lo transmitas, esque es tan tu el juegito, es estilo silent hill + resident evil, es muy chulo y quiero vertelo juegar jeje')">Adivinar</button>
    </div>
  </div>

  <!-- Flecha para continuar al siguiente juego -->
  <div id="next-btn" style="display: none; cursor: pointer; margin-top: 20px;">
    <span style="font-size: 24px;">➡️</span>
  </div>

  <!-- Botón para reiniciar el juego -->
  <div id="restart-btn" style="display: none; margin-top: 20px;">
    <button onclick="restartGame()">Reiniciar Juego</button>
  </div>
</div>

<style>
  #game-container {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  
  .game {
    margin: 20px;
    text-align: center;
  }
  
  .blurry-img {
    width: 300px;
    height: auto;
    filter: blur(10px);
    transition: filter 0.5s ease;
  }

  .controls {
    margin-top: 10px; /* Espaciado entre la imagen y los controles */
    padding: 10px; /* Padding para mejorar el aspecto visual */
  }

  select {
    margin-right: 10px; /* Espaciado entre el select y el botón */
    padding: 5px;
  }

  button {
    padding: 5px 10px;
  }
</style>

<script>
  let currentGame = 1;

  function checkAnswer(gameNumber, correctAnswer, description) {
    const select = document.getElementById(`select${gameNumber}`);
    const img = document.getElementById(`img${gameNumber}`);
    const userAnswer = select.value;

    if (userAnswer === correctAnswer) {
      img.style.filter = 'blur(0)';
      alert('¡Correcto! ' + description);
      document.getElementById('next-btn').style.display = 'block'; // Mostrar flecha para continuar
      document.getElementById('restart-btn').style.display = 'block'; // Mostrar botón de reiniciar
    } else {
      alert('Incorrecto. Intenta de nuevo.');
    }
  }

  document.getElementById('next-btn').onclick = function() {
    const currentGameDiv = document.getElementById(`game${currentGame}`);
    currentGameDiv.style.display = 'none'; // Ocultar el juego actual
    currentGame++; // Pasar al siguiente juego

    if (currentGame <= 20) { // Cambia el número total de juegos aquí si agregas más
      const nextGameDiv = document.getElementById(`game${currentGame}`);
      nextGameDiv.style.display = 'block'; // Mostrar el siguiente juego
      document.getElementById('next-btn').style.display = 'none'; // Ocultar flecha al cambiar de juego
      document.getElementById('restart-btn').style.display = 'none'; // Ocultar botón de reiniciar al cambiar de juego
    } else {
      alert('¡Has completado todos los juegos!');
      currentGame = 1; // Reiniciar para poder volver a jugar
    }
  };

  function restartGame() {
    const currentGameDiv = document.getElementById(`game${currentGame}`);
    currentGameDiv.style.display = 'none'; // Ocultar el juego actual
    currentGame = 1; // Reiniciar el juego al primer juego
    document.getElementById('game1').style.display = 'block'; // Mostrar el primer juego
    document.getElementById('next-btn').style.display = 'none'; // Ocultar flecha al reiniciar
    document.getElementById('restart-btn').style.display = 'none'; // Ocultar botón de reiniciar al reiniciar
  }
</script>
