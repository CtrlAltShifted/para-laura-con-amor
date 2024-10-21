# Sección Secreta

<div id="secretContent" style="display: none;">
    <h2>Contenido Secreto</h2>
    <p>Este es el contenido que solo se puede ver si tienes la clave correcta.</p>
</div>

<div>
    <p> Este apartado es secreto, para acceder a el tendras que buscar pistas entre los demás documentos para averiguar la clave jeje <p>
    <label for="password">Introduce la clave para acceder al contenido secreto:</label>
    <input type="password" id="password" />
    <button onclick="checkPassword()">Acceder</button>
    <p id="message" style="color: red;"></p>
</div>

<script>
    function checkPassword() {
        const password = document.getElementById('password').value;
        const secretContent = document.getElementById('secretContent');
        const message = document.getElementById('message');
        
        // Cambia "tu_clave_secreta" por la clave que deseas usar
        if (password === "caca") {
            secretContent.style.display = 'block';
            message.innerText = '';
        } else {
            message.innerText = 'Clave incorrecta. Inténtalo de nuevo.';
            secretContent.style.display = 'none';
        }
    }
</script>
