# Sección Secreta

<div id="secretContent" style="display: none;">
    <h2>Contenido Secreto</h2>
    <p>Este es el contenido que solo se puede ver si tienes la clave correcta.</p>
</div>

<div id="passwordContainer">
    <p> HOLA LAURA, para acceder al apartado secreto uuuhuhh ejejje, tendrás que buscar pistas por toda la página jeejje y así podrás descrifrar la clave jejejej buen suerte <p>
    <label for="password">Introduce la clave para acceder al contenido secreto:</label>
    <input type="password" id="password" />
    <button onclick="togglePasswordVisibility()">👁️</button>
    <button onclick="checkPassword()">Acceder</button>
    <p id="message" style="color: red;"></p>
</div>

<script>
    function checkPassword() {
        const password = document.getElementById('password').value;
        const secretContent = document.getElementById('secretContent');
        const message = document.getElementById('message');
        const passwordContainer = document.getElementById('passwordContainer');
        
        // Cambia "tu_clave_secreta" por la clave que deseas usar
        if (password === "caca en mis pantalones") {
            secretContent.style.display = 'block'; // Mostrar contenido secreto
            message.innerText = ''; // Limpiar mensaje
            passwordContainer.style.display = 'none'; // Ocultar el contenedor de la contraseña
        } else {
            message.innerText = 'Clave incorrecta. Inténtalo de nuevo.';
            secretContent.style.display = 'none'; // Ocultar contenido secreto
        }
    }

    function togglePasswordVisibility() {
        const passwordInput = document.getElementById('password');
        const type = passwordInput.getAttribute('type') === 'password' ? 'text' : 'password';
        passwordInput.setAttribute('type', type);
    }
</script>
