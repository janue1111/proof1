<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Escuela Bíblica Kids - Réplica</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" />
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
     <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="" />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&amp;family=Montserrat:wght@800&amp;display=swap" rel="stylesheet" />
</head>
<body class="bg-gray-100 text-gray-800">

    <div class="bg-purple-600 text-white text-sm text-center py-2 px-4">
        <span class="bg-yellow-400 text-black font-bold text-xs py-0.5 px-2 rounded mr-2">NUEVO</span>
        <span>Anunciadas nuevas fechas para Talleres 2025:</span>
        <a href="#" class="underline hover:text-yellow-300 ml-1">Descubre si es para ti →</a>
    </div>

    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-3 flex justify-between items-center">
            <div class="text-2xl text-gray-900 tracking-tight" style="font-family: 'Montserrat', sans-serif; font-weight: 800;">
                <a href="#">EscuelaBíblicaKids</a>
            </div>
            <div class="hidden md:flex space-x-8 items-center">
                <a href="#" class="text-gray-500 hover:text-purple-600 text-sm transition duration-300">Inicio</a>
                <a href="#quienes-somos" class="text-gray-500 hover:text-purple-600 text-sm transition duration-300">Quiénes Somos</a>
                <a href="#recursos" class="text-gray-500 hover:text-purple-600 text-sm transition duration-300">Recursos</a>
                <a href="#testimonios" class="text-gray-500 hover:text-purple-600 text-sm transition duration-300">Testimonios</a>
                <a href="#" class="text-gray-500 hover:text-purple-600 text-sm transition duration-300">Donar</a>
            </div>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-gray-600 focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </nav>
        <div id="mobile-menu" class="md:hidden hidden bg-white py-2 border-t border-gray-200">
            <a href="#" class="block px-6 py-2 text-gray-500 hover:bg-gray-100 hover:text-purple-600 text-sm">Inicio</a>
            <a href="#quienes-somos" class="block px-6 py-2 text-gray-500 hover:bg-gray-100 hover:text-purple-600 text-sm">Quiénes Somos</a>
            <a href="#recursos" class="block px-6 py-2 text-gray-500 hover:bg-gray-100 hover:text-purple-600 text-sm">Recursos</a>
            <a href="#testimonios" class="block px-6 py-2 text-gray-500 hover:bg-gray-100 hover:text-purple-600 text-sm">Testimonios</a>
            <a href="#" class="block px-6 py-2 text-gray-500 hover:bg-gray-100 hover:text-purple-600 text-sm">Donar</a>
        </div>
    </header>

    <section class="bg-white py-20 text-center">
         <div class="container mx-auto px-6">
            <h1 class="text-4xl md:text-6xl mb-4 leading-tight text-gray-900" style="font-family: 'Montserrat', sans-serif; font-weight: 800;">
                Enseñando la Palabra de Dios a los <span class="text-purple-600">Niños</span>
            </h1>
            <p class="text-lg md:text-xl mb-8 max-w-2xl mx-auto text-gray-600">
                Recursos bíblicos creativos y prácticos para iglesias, padres y maestros.
            </p>
            <a href="https://google.com" target="_blank" rel="noopener noreferrer"
               class="bg-purple-600 hover:bg-purple-700 text-white font-semibold py-3 px-8 rounded-lg text-lg transition duration-300 inline-block">
                ¡QUIERO ACCESO AHORA!
            </a>
        </div>
    </section>

    <section id="quienes-somos" class="py-16 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-8 text-gray-800">Quiénes Somos</h2>
            <div class="flex flex-col md:flex-row items-center justify-center gap-12">
                <div class="md:w-1/2">
                     <img
                        src="https://placehold.co/600x400/e2e8f0/334155?text=Imagen+Equipo"
                        alt="Equipo"
                        class="rounded-lg shadow-lg mx-auto"
                        onerror="this.onerror=null; this.src='https://placehold.co/600x400/cccccc/ffffff?text=Error+Imagen'"
                     />
                </div>
                <div class="md:w-1/2 text-left">
                    <p class="text-lg mb-4">Somos un ministerio apasionado por equipar a la iglesia y a las familias para discipular a la próxima generación. Creemos que la Biblia es la Palabra de Dios y tiene el poder de transformar vidas.</p>
                    <p class="text-lg">Ofrecemos materiales didácticos, capacitación y acompañamiento para que la enseñanza bíblica sea efectiva, relevante y divertida para los niños.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="recursos" class="py-16 bg-blue-50">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-12 text-gray-800">Nuestros Recursos</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-lg transform hover:scale-105 transition duration-300">
                     <img
                        src="https://placehold.co/400x300/a5f3fc/0891b2?text=Recurso+1"
                        alt="Recurso 1"
                        class="rounded-md mb-4 w-full h-48 object-cover"
                        onerror="this.onerror=null; this.src='https://placehold.co/400x300/cccccc/ffffff?text=Error+Imagen'"
                     />
                    <h3 class="text-xl font-semibold mb-2 text-blue-700">Lecciones Bíblicas</h3>
                    <p class="text-gray-600 mb-4">Series completas de lecciones para escuela dominical o grupos pequeños.</p>
                    <a href="#" class="text-blue-600 hover:underline font-medium">Ver más</a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg transform hover:scale-105 transition duration-300">
                     <img
                        src="https://placehold.co/400x300/fecaca/991b1b?text=Recurso+2"
                        alt="Recurso 2"
                        class="rounded-md mb-4 w-full h-48 object-cover"
                        onerror="this.onerror=null; this.src='https://placehold.co/400x300/cccccc/ffffff?text=Error+Imagen'"
                     />
                    <h3 class="text-xl font-semibold mb-2 text-red-700">Manualidades y Actividades</h3>
                    <p class="text-gray-600 mb-4">Ideas creativas para reforzar el aprendizaje bíblico de forma práctica.</p>
                    <a href="#" class="text-red-600 hover:underline font-medium">Ver más</a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg transform hover:scale-105 transition duration-300">
                     <img
                        src="https://placehold.co/400x300/bbf7d0/15803d?text=Recurso+3"
                        alt="Recurso 3"
                        class="rounded-md mb-4 w-full h-48 object-cover"
                        onerror="this.onerror=null; this.src='https://placehold.co/400x300/cccccc/ffffff?text=Error+Imagen'"
                     />
                    <h3 class="text-xl font-semibold mb-2 text-green-700">Capacitación para Maestros</h3>
                    <p class="text-gray-600 mb-4">Talleres y cursos para equipar a líderes y voluntarios del ministerio infantil.</p>
                    <a href="#" class="text-green-600 hover:underline font-medium">Ver más</a>
                </div>
            </div>
        </div>
    </section>

    <section id="testimonios" class="py-16 bg-white">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-3xl font-bold mb-12 text-gray-800">Testimonios</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-6 rounded-lg shadow-md flex flex-col">
                    <img src="https://placehold.co/150x200/e0e0e0/999999?text=Testimonio+1" alt="Testimonio 1" class="mx-auto mb-4 rounded w-32 h-40 object-cover" onerror="this.onerror=null; this.src='https://placehold.co/150x200/cccccc/ffffff?text=Error'" />
                    <h3 class="text-lg font-semibold text-gray-800 mb-2 text-center">Título Testimonio 1</h3>
                    <p class="text-sm text-gray-600 text-center">Descripción breve del testimonio o comentario inspirador sobre cómo los recursos han sido de bendición.</p>
                </div>
                 <div class="bg-gray-50 p-6 rounded-lg shadow-md flex flex-col">
                    <img src="https://placehold.co/150x200/d0d0d0/999999?text=Testimonio+2" alt="Testimonio 2" class="mx-auto mb-4 rounded w-32 h-40 object-cover" onerror="this.onerror=null; this.src='https://placehold.co/150x200/cccccc/ffffff?text=Error'" />
                    <h3 class="text-lg font-semibold text-gray-800 mb-2 text-center">Título Testimonio 2</h3>
                    <p class="text-sm text-gray-600 text-center">Otro ejemplo de texto que describe la experiencia positiva de alguien usando los materiales o participando.</p>
                </div>
                 <div class="bg-gray-50 p-6 rounded-lg shadow-md flex flex-col">
                    <img src="https://placehold.co/150x200/c0c0c0/999999?text=Testimonio+3" alt="Testimonio 3" class="mx-auto mb-4 rounded w-32 h-40 object-cover" onerror="this.onerror=null; this.src='https://placehold.co/150x200/cccccc/ffffff?text=Error'" />
                    <h3 class="text-lg font-semibold text-gray-800 mb-2 text-center">Título Testimonio 3</h3>
                    <p class="text-sm text-gray-600 text-center">Un tercer testimonio que resalta diferentes beneficios o aspectos del ministerio, completando la sección.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="nueva-seccion" class="py-16 bg-white">
        <div class="container mx-auto px-6">
             <div class="grid grid-cols-1 gap-8 max-w-lg mx-auto">
                 <div class="text-center mb-8">
                     <a href="https://google.com" target="_blank" rel="noopener noreferrer"
                        class="bg-purple-600 hover:bg-purple-700 text-white font-semibold py-3 px-8 rounded-lg text-lg transition duration-300 inline-block">
                         ¡QUIERO ACCESO AHORA!
                     </a>
                 </div>
                 <div class="bg-gray-100 rounded-lg shadow-md flex items-center justify-center h-72 p-6">
                     <p class="text-gray-500 text-xl font-semibold">Marcador 1</p>
                 </div>
                 <div class="bg-gray-100 rounded-lg shadow-md flex items-center justify-center h-72 p-6">
                     <p class="text-gray-500 text-xl font-semibold">Marcador 2</p>
                 </div>
             </div>
        </div>
    </section>

    <section id="garantia" class="py-16 bg-gray-100">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 items-center">
                <div class="md:col-span-1">
                    <img src="https://i.imgur.com/XmelnjE.png" alt="Sello de Garantía 100%" class="mx-auto w-48 h-auto md:w-full max-w-[250px]" onerror="this.onerror=null; this.src='https://placehold.co/200/cccccc/ffffff?text=Garantia'" />
                </div>
                <div class="md:col-span-2 text-center md:text-left">
                    <h3 class="text-2xl lg:text-3xl font-bold text-gray-800 mb-2">Tu Inversión 100% Segura: Garantía de 7 Días</h3>
                    <p class="text-lg text-gray-600 mb-4">Es muy sencillo y fácil...</p>
                    <p class="text-gray-700 mb-4">Tendrás acceso al material completo, y si en 7 días ves que el contenido no es para ti, o no era lo que esperabas, te devolvemos el 100% de la inversión. Nuestro objetivo es aportar valor real a la educación de nuestros niños.</p>
                    <p class="text-gray-800 font-semibold mb-4">Plataforma online 100% segura</p>
                    <p class="text-gray-700">Podrás acceder a los contenidos para siempre. Acceso de por vida para ti. El material estará disponible las 24 horas del día, para que puedas acceder las veces que quieras y donde prefieras, ya sea en tu móvil, tablet u ordenador.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="acceso" class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8 md:gap-12 items-center">
                <div>
                    <img src="https://placehold.co/300x400/e2e8f0/334155?text=Kit+Principal" alt="Kit Escuela Bíblica Kids" class="mx-auto rounded-lg shadow-md w-auto max-w-xs" onerror="this.onerror=null; this.src='https://placehold.co/300x400/cccccc/ffffff?text=Kit'" />
                </div>
                <div>
                    <p class="text-sm text-gray-500 uppercase tracking-wider mb-1">Recapitulemos</p>
                    <h2 class="text-2xl md:text-3xl font-bold text-purple-600 mb-6">TODO A LO QUE TENDRÁS ACCESO:</h2>
                    <ul class="space-y-3 text-gray-700">
                        <li class="flex items-start">
                            <span class="text-purple-600 mr-2 mt-1">✔</span>
                            <span>Kit Completo Escuela Bíblica <span class="font-semibold">(Valor $29.90)</span></span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-purple-600 mr-2 mt-1">✔</span>
                            <span>Bonus: Dinámicas Divertidas <span class="font-semibold">(Valor $17.00)</span></span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-purple-600 mr-2 mt-1">✔</span>
                            <span>Bonus: Historias Bíblicas Ilustradas <span class="font-semibold">(Valor $9.90)</span></span>
                        </li>
                        <li class="flex items-start">
                            <span class="text-purple-600 mr-2 mt-1">✔</span>
                            <span>Bonus: Actividades Lúdicas <span class="font-semibold">(Valor $9.90)</span></span>
                        </li>
                         <li class="flex items-start">
                            <span class="text-purple-600 mr-2 mt-1">✔</span>
                            <span>Bonus: Guía de Alfabetización <span class="font-semibold">(Valor $14.90)</span></span>
                        </li>
                    </ul>
                    <p class="mt-6 text-gray-600 font-medium">¡Todo esto por separado costaría más de <span class="font-bold">$80 dólares</span>!</p>
                </div>
            </div>
        </div>
    </section>


    <footer class="bg-gray-800 text-white py-10">
        <div class="container mx-auto px-6 text-center">
            <div class="mb-4">
                <a href="#" class="text-gray-400 hover:text-white mx-2 text-xl"><i class="fab fa-facebook-f"></i></a>
                <a href="#" class="text-gray-400 hover:text-white mx-2 text-xl"><i class="fab fa-instagram"></i></a>
                <a href="#" class="text-gray-400 hover:text-white mx-2 text-xl"><i class="fab fa-youtube"></i></a>
            </div>
            <p class="text-gray-400 text-sm">&copy; 2025 Escuela Bíblica Kids (Réplica). Todos los derechos reservados.</p>
            <p class="text-gray-400 text-sm mt-1">Diseño inspirado en escuelabiblicakids.com</p>
        </div>
    </footer>

    <script>
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');

        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        const mobileLinks = mobileMenu.querySelectorAll('a');
        mobileLinks.forEach(link => {
            link.addEventListener('click', () => {
                 if (!link.href.includes('#') || link.pathname !== window.location.pathname) {
                    return;
                 }
                 if (link.getAttribute('href') === '#' || link.href.endsWith('#')) {
                    if (!mobileMenu.classList.contains('hidden')) {
                         if (link.getAttribute('href') === '#') {
                             mobileMenu.classList.add('hidden');
                         }
                    }
                    return;
                 }

                mobileMenu.classList.add('hidden');
            });
        });
    </script>

</body>
</html>
