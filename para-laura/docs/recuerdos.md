# Recuerdos

## Gracias a ti, estos pequeños detalles que no tienen sentido para otros, cobran vida en mi corazón. Es tu presencia, tu esencia, tu forma única de ser, y todo lo que eres lo que les otorga significado. Por eso, quiero que conozcas esas pequeñas cosas a las que tu presencia siempre les añadira algo especial.

<div class="slider">
    <div class="slides">
        <div class="slide">
            <img src="https://upload.wikimedia.org/wikipedia/commons/d/db/Tipos_de_verde.png" alt="El color verde">
        </div>
        <div class="slide">
            <img src="https://st4.depositphotos.com/1004592/23885/i/450/depositphotos_238852992-stock-photo-black-cats-front-white-background.jpg" alt="Los gatos negros">
        </div>
        <div class="slide">
            <img src="https://external-preview.redd.it/the-fiona-apple-song-about-discovering-the-meaning-of-life-v0-E6zOBgmXXE8Nj2Q82Qh9q9gzpNFV0mmstpHh1Zd1zuo.jpg?width=1080&crop=smart&auto=webp&s=5e3a76ae790ee7a65fb5dc85be9f3d056b33f292" alt="Fiona Apple">
        </div>
        <div class="slide">
            <img src="https://www.upb.edu.co/es/imagenes/imgtipod-blgleyendosinseparador-megustarialeer-1464204951973.jpg" alt="Libros">
        </div>
        <div class="slide">
            <img src="https://entresemillas.com/2302-medium_default/margaritas-semillas.jpg" alt="Las margaritas">
        </div>
        <div class="slide">
            <img src="https://img.asmedia.epimg.net/resizer/v2/5UYNUG7L6RC7TLHJ34GQEZDZ2A.jpg?auth=05359ed706ff086cd592859cfe8c14b5cb942196a1ecb892ab11f1838e7d66a9&width=1472&height=1104&smart=true" alt="La luna">
        </div>
        <div class="slide">
            <img src="https://www.maybelline.es/-/media/project/loreal/brand-sites/mny/emea/iberic/tips-and-trends/productos-basicos-de-maquillaje/productos-basicos-de-maquillaje_0.jpg?la=es-es&h=349&w=624&rev=50d56cb1cf11407882d815e667fc3bbc&hash=2B10585742F38F4577E56E6F0BD5AEAE" alt="El maquillaje">
        </div>
        <div class="slide">
            <img src="https://preview.redd.it/9e65va69cpc81.jpg?auto=webp&s=302c893651cc5d3e7d9cafababb3ac628d7d8f4b" alt="Silent Hill 3">
        </div>
        <div class="slide">
            <img src="https://www.cocacolaep.com/assets/Spain/Blog-Rojo-y-en-Botella/2023/AGOSTO/Experiencia-cliente/Servicio-perfecto.jpg" alt="Lo bien que cocinas">
        </div>
        <div class="slide">
            <img src="https://c.files.bbci.co.uk/E97C/production/_128027795_gettyimages-636379014.jpg" alt="El amor">
        </div>
        <div class="slide">
            <img src="https://www.universozelda.com/wp-content/uploads/2016/09/bca91decdd77c338b080f7965acc1c96.jpg" alt="El Zelda">
        </div>
        <div class="slide">
            <img src="https://cdn.shopify.com/s/files/1/0883/5334/1730/files/Ramona-Flowers-Haircut-2022.jpg" alt="Ramona Flowers">
        </div>
        <div class="slide">
            <img src="https://yaabil.com/wp-content/uploads/2024/06/8-1024x683.jpg" alt="Velas">
        </div>
        <div class="slide">
            <img src="https://i.etsystatic.com/25542258/r/il/05d0f7/5281825317/il_fullxfull.5281825317_38z0.jpg" alt="Las obras de junji ito">
        </div>
        <div class="slide">
            <img src="https://static8.depositphotos.com/1454655/1006/v/450/depositphotos_10069299-stock-illustration-tribal-element-design.jpg" alt="Los trivales">
        </div>
        <div class="slide">
            <img src="https://img2.rtve.es/i/?w=1600&i=1336037570491.jpg" alt="Atardeceres en la playa">
        </div>
    </div>
    <div class="nav-buttons">
        <button class="nav-button" onclick="prevSlide()">❮</button>
        <button class="nav-button" onclick="nextSlide()">❯</button>
    </div>
</div>

## Por si no lo entiendes muy bien, son como cosas que veo y me recuerdan a ti, o que tienen tu esencia, no se como explicarlo bien, pero espero que me entiendas.

<style>
    body {
        font-family: Arial, sans-serif;
        background-color: #f9f9f9;
        margin: 20px;
        color: #333;
        display: flex;
        justify-content: center; /* Centrar contenido en la página */
    }
    .slider {
        position: relative;
        max-width: 600px;
        margin: auto;
        overflow: hidden;
        border-radius: 10px;
    }
    .slides {
        display: flex;
        transition: transform 0.5s ease;
        align-items: center; /* Centrar verticalmente las imágenes */
    }
    .slide {
        min-width: 100%;
        display: flex; /* Flexbox para centrar la imagen */
        justify-content: center; /* Centrar horizontalmente la imagen */
        box-sizing: border-box;
    }
    img {
        max-width: 100%; /* Hacer que la imagen no se desborde */
        height: auto; /* Mantener la proporción de aspecto */
        border-radius: 10px;
    }
    .nav-buttons {
        position: absolute;
        top: 50%;
        width: 100%;
        display: flex;
        justify-content: space-between;
        transform: translateY(-50%);
    }
    .nav-button {
        background-color: rgba(255, 255, 255, 0.8);
        border: none;
        padding: 10px;
        cursor: pointer;
        border-radius: 5px;
        transition: background-color 0.3s;
    }
    .nav-button:hover {
        background-color: rgba(255, 255, 255, 1);
    }
</style>

<script>
    let currentSlide = 0;

    function showSlide(index) {
        const slides = document.querySelector('.slides');
        const totalSlides = document.querySelectorAll('.slide').length;

        if (index >= totalSlides) {
            currentSlide = 0;
        } else if (index < 0) {
            currentSlide = totalSlides - 1;
        } else {
            currentSlide = index;
        }

        slides.style.transform = 'translateX(' + (-currentSlide * 100) + '%)';
    }

    function nextSlide() {
        showSlide(currentSlide + 1);
    }

    function prevSlide() {
        showSlide(currentSlide - 1);
    }
</script>   

