# Películas y Series

## Las Películas y Series que He Disfrutado Contigo

En esta sección, quiero compartir contigo una lista de películas y series que han dejado una huella especial en mi corazón, gracias a los momentos que hemos pasado juntos, mi amor precioso. Cada uno de estos títulos me recuerda a ti y a las risas, las lágrimas y la complicidad que hemos compartido mientras los veíamos. Espero que revivas esos recuerdos cada vez que las veas.

Desliza por las películas y series con los botones. Pulsa los botones para ver algo especial jeje.

<div class="card-container">
    <div class="card" id="card1">
        <img src="https://i.pinimg.com/736x/b2/6d/5d/b26d5dae367051a955c8f63bea09fb14.jpg" alt="Título 1">
    </div>
    <div class="card" id="card2">
        <img src="https://pbs.twimg.com/media/GDVRHlbWgAARVjS.jpg:large" alt="Título 2">
    </div>
    <div class="card" id="card3">
        <img src="https://i.pinimg.com/736x/65/9b/fa/659bfa81800eccfed26deb744cff265b.jpg" alt="Título 3">
    </div>
    <div class="card" id="card4">
        <img src="https://graffica.info/wp-content/uploads/2017/05/cartel-mother-aronofsky.jpg" alt="Título 4">
    </div>
    <div class="card" id="card5">
        <img src="https://preview.redd.it/cwn6bznkxdu61.jpg?auto=webp&s=66facf2b9bf206bf8c3581b5777f6522c74e2be5" alt="Título 5">
    </div>
    <div class="card" id="card6">
        <img src="https://m.media-amazon.com/images/I/819nOOq5HFL.jpg" alt="Título 6">
    </div>
    <div class="card" id="card7">
        <img src="https://musicart.xboxlive.com/7/022c1100-0000-0000-0000-000000000002/504/image.jpg?w=1920&h=1080" alt="Título 7">
    </div>
    <div class="card" id="card8">
        <img src="https://es.web.img2.acsta.net/medias/nmedia/18/89/70/21/20062737.jpg" alt="Título 8">
    </div>
    <div class="card" id="card9">
        <img src="https://m.media-amazon.com/images/I/81lBjoX3JgL.jpg" alt="Título 9">
    </div>
    <div class="card" id="card10">
        <img src="https://m.media-amazon.com/images/I/81Y0vBkhs3L.jpg" alt="Título 10">
    </div>
    <div class="card" id="card11">
        <img src="https://i.blogs.es/40eca9/scott-pilgrim-teaser-poster/450_1000.jpg" alt="Título 11">
    </div>
    <div class="card" id="card12">
        <img src="https://i.pinimg.com/236x/ae/9c/15/ae9c156411aa5e8a46cb0c1afadf5e48.jpg" alt="Título 12">
    </div>
    <div class="card" id="card13">
        <img src="https://m.media-amazon.com/images/M/MV5BY2Q3MDFiZGQtMjc4NS00MDJiLWFmYjgtNmI0MTQwMzUyOWNmXkEyXkFqcGc@._V1_.jpg" alt="Título 13">
    </div>
    <div class="card" id="card14">
        <img src="https://pics.filmaffinity.com/7_vairgenes-857681604-large.jpg" alt="Título 14">
    </div>
     <div class="card" id="card15">
        <img src="https://i.pinimg.com/originals/2b/cc/52/2bcc521f4292e0b582b26c52407d1235.png" alt="Título 15">
    </div>

</div>

<div class="buttons">
    <button class="btn" id="prevBtn">◀️ Anterior</button>
    <button class="btn" id="nextBtn">Siguiente ▶️</button>
</div>

<!-- Contenedor para las descripciones fuera de las tarjetas -->
<div id="descriptionContainer" style="text-align: center; margin-top: 20px;">
    <p id="movieDescription">Selecciona una película/serie para ver la descripción.</p>
</div>

<!-- Botón de información fuera de las tarjetas -->
<div class="infoButtons" style="text-align: center; margin-top: 20px;">
    <button class="infoBtn" data-index="0">🔍 The Notebook</button>
    <button class="infoBtn" data-index="1">🔍 One Day</button>
    <button class="infoBtn" data-index="2">🔍 Arcane</button>
    <button class="infoBtn" data-index="3">🔍 Mother!</button>
    <button class="infoBtn" data-index="4">🔍 Saga SAW</button>
    <button class="infoBtn" data-index="5">🔍 Everything everywhere all at once</button>
    <button class="infoBtn" data-index="6">🔍 How High</button>
    <button class="infoBtn" data-index="7">🔍 Orgullo y prejuicio</button> 
    <button class="infoBtn" data-index="8">🔍 Mamma mia</button> 
    <button class="infoBtn" data-index="9">🔍 Jennifers Body</button>
    <button class="infoBtn" data-index="10">🔍 Scott Pilgrim vs. the World</button>
    <button class="infoBtn" data-index="11">🔍 Saga The conjuring</button>
    <button class="infoBtn" data-index="12">🔍 The house that Jack built</button>
    <button class="infoBtn" data-index="13">🔍 7 virgenes</button>
    <button class="infoBtn" data-index="14">🔍 Saga AHS</button>
</div>

<style>
    .card-container {
        width: 300px; /* Ancho del contenedor */
        height: 400px; /* Altura del contenedor */
        overflow: hidden;
        position: relative;
        margin: 20px auto;
        transition: transform 0.5s ease; /* Suaviza la transición del contenedor */
    }

    .card {
        background: white;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        position: absolute;
        width: 100%;
        height: 100%;
        transition: transform 0.5s ease; /* Suaviza la transición de las tarjetas */
        display: flex;
        justify-content: center; /* Centra el contenido */
        align-items: center; /* Centra el contenido */
    }

    .card img {
        width: 100%;
        height: 100%; /* Ocupa el 100% de la altura del contenedor */
        object-fit: cover; /* Asegura que la imagen cubra el contenedor sin distorsionarse */
        border-radius: 10px; /* Bordes redondeados */
    }

    .buttons {
        text-align: center;
        margin-top: 20px;
    }

    .btn {
        background-color: #ff4081;
        color: white;
        border: none;
        padding: 10px 20px;
        border-radius: 5px;
        cursor: pointer;
        margin: 0 10px;
    }

    .btn:hover {
        background-color: #e91e63;
    }

    .infoButtons {
        display: flex;
        justify-content: center;
        margin-top: 20px;
        flex-wrap: wrap; /* Permite que los botones se muevan a la siguiente línea si es necesario */
    }

    .infoBtn {
        background-color: #4caf50;
        color: white;
        border: none;
        padding: 5px 10px;
        border-radius: 5px;
        cursor: pointer;
        margin: 0 5px;
    }

    .infoBtn:hover {
        background-color: #45a049;
    }
</style>

<script>
    const cards = document.querySelectorAll('.card');
    const infoButtons = document.querySelectorAll('.infoBtn');
    let currentIndex = 0;

    // Descripciones de las películas
    const descriptions = [
        "The Notebook: Me encantó ver esta película juntos, fue tan bonita y emotiva. Siempre la recordaré gracias a ti.",
        "One Day: Me encanto que me dieras a conocer esta serie, fue increíble verla juntos.",
        "Arcane: Siempre estaré eternamente agradecido de que accederías a ver Arcane conmigo, me encanta poder compartir contigo una serie tan preciosa.",
        "Mother!: Gracias por enseñarme está maravilla de película, y por aceptar verla conmigo una vez más, te amo.",
        "Saga SAW: ME FLIPÓ ver la saga entera de SAW contigo, siempre recordaré esos momentos de tensión que pasamos juntos.",
        "Everything everywhere all at once: Descripción de la película 5 que me encanta ver contigo.",
        "How High: Una de las primeras película que vimos juntos, la tengo muy marcada.",
        "Orgullo y prejuicio: Me pediste que le diera una oportunidad para verla contigo, me encanto Laura, y siento que si estuviesemos en el mismo tiempo que ellos, seríamos ellos.",
        "Mamma mia: GRACIAS por ver Mamma mia conmigo, se que no te gustó mucho, pero a mi me encanto poder verla contigo juntitos en tu casa.",
        "Jennifers Body: Aish está película me encanto verla contigo, gracias por recomendarla.",
        "Scott Pilgrim vs. the World: La película que más me recuerda a nosotros, somos ellos literal, te amo.",
        "Saga The conjuring: La mejor saga de terror que nos hemos metido por el culo juntos, la tengo tan relacionada contigo miamor.",
        "The house that jack built: Una película muy buena que vimos juntos, me encanto y siempre la recordare como algo que hicimos juntos.",
        "7 virgenes: Siento que si fuesemos dos chavales de calle seríamos ellos, mejores amigos hasta la muerte.",
        "Saga AHS: Es una saga que me recuerda tanto a ti Laura, me flipo ver 3 temporadas contigo, me encanto mucho de verdad.",
    ];

    function showCard(index) {
        cards.forEach((card, i) => {
            card.style.transform = `translateY(${(i - index) * 100}%)`;
        });
        // Reiniciar la descripción al seleccionar una nueva tarjeta
        document.getElementById("movieDescription").innerText = "Selecciona una película para ver la descripción.";
    }

    showCard(currentIndex);

    // Mostrar la descripción al hacer clic en el botón de información
    infoButtons.forEach((button) => {
        button.addEventListener('click', () => {
            const index = button.getAttribute("data-index");
            document.getElementById("movieDescription").innerText = descriptions[index];
        });
    });

    document.getElementById('nextBtn').addEventListener('click', () => {
        currentIndex = Math.min(currentIndex + 1, cards.length - 1);
        showCard(currentIndex);
    });

    document.getElementById('prevBtn').addEventListener('click', () => {
        currentIndex = Math.max(currentIndex - 1, 0);
        showCard(currentIndex);
    });
</script>

## Aclaración 

Obviamente, habrá muchas más películas y series que hemos visto juntos y que me han marcado mucho, pero para mí, esas son las que más destacan en el fondo de mi corazón, seguramente me habré saltado alguna, pero bueno, siempre está el Letterbox donde están bien guardaditas las películas que hemos visto juntos :3 
