<html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JASTI MKT - Marketing y Programación</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body { font-family: 'Times New Roman', serif; background-color: #F5F1E3; color: #2C3E50; }
        .header { background-color: #154734; color: #F5F1E3; }
        .button { background-color: #B29762; color: white; }
        .button:hover { background-color: #8C7853; }
    </style>
</head>
<body>
     <header class="header p-5 text-center text-3xl font-bold">
        JASTI MKT - Marketing y Programación
    </header>
    
    <nav class="bg-gray-200 p-4 text-center">
        <a href="#servicios" class="mx-4 text-green-900">Servicios</a>
        <a href="#nosotros" class="mx-4 text-green-900">Nosotros</a>
        <a href="#contacto" class="mx-4 text-green-900">Contacto</a>
    </nav>

    <section id="galeria" class="p-10">
        <h2 class="text-xl font-bold text-center mb-4">MKT</h2>
        <div class="grid md:grid-cols-3 gap-6">
            <img src="C:\Users\braya\OneDrive\Escritorio\jpg pagina web\mkt 2.jpg" alt="Proyecto 3D 1" class="w-full rounded-lg shadow-md">
            <img src="C:\Users\braya\OneDrive\Escritorio\jpg pagina web\mkt 3 pr.jpg" alt="Proyecto 3D 2" class="w-full rounded-lg shadow-md">
            <img src="C:\Users\braya\OneDrive\Escritorio\jpg pagina web\mkt1.jpg" alt="Proyecto 3D 3" class="w-full rounded-lg shadow-md">
        </div>
    </section>

    <section id="servicios" class="p-10">
        <h2 class="text-xl font-bold text-center mb-4">Nuestros Servicios</h2>
        <div class="grid md:grid-cols-2 gap-6">
            <div class="bg-white p-6 rounded-lg shadow-md flex flex-col items-center">
                <img src="https://th.bing.com/th/id/OIP.Gea-_JbROQPne_Et6RYqcQHaE8?w=567&h=378&rs=1&pid=ImgDetMain" alt="Marketing Digital" class="w-48 h-48 mb-4 rounded">
                <h3 class="text-lg font-semibold">Marketing Digital</h3>
                <p class="text-center">SEO, publicidad en redes sociales, email marketing y estrategias de contenido.</p>
            </div>
            <div class="bg-white p-6 rounded-lg shadow-md flex flex-col items-center">
                <img src="https://www.herzing.edu/sites/default/files/styles/fp_960_480/public/2020-09/how-to-become-software-engineer.jpg.webp?itok=uuamJN8l" alt="Desarrollo Web" class="w-48 h-48 mb-4 rounded">
                <h3 class="text-lg font-semibold">Desarrollo Web</h3>
                <p class="text-center">Creación de páginas web modernas, diseño responsivo y optimización de velocidad.</p>
            </div>
        </div>
    
    <section id="nosotros" class="bg-gray-200 p-10">
        <h2 class="text-xl font-bold text-center mb-4">Sobre Nosotros</h2>
        <p class="text-center">Somos un equipo apasionado por la tecnología y el marketing, ofreciendo soluciones efectivas para negocios.</p>
        <div class="flex justify-center mt-4">
            <img src="https://via.placeholder.com/500" alt="Equipo JASTI MKT" class="rounded shadow-md">
        </div>
    </section>

    <section id="contacto" class="p-10">
        <h2 class="text-xl font-bold text-center mb-4">Contacto</h2>
        <form class="max-w-lg mx-auto bg-white p-6 rounded-lg shadow-md">
            <label class="block mb-2">Nombre:</label>
            <input type="text" class="w-full p-2 border rounded mb-4" placeholder="Tu nombre">
            
            <label class="block mb-2">Correo Electrónico:</label>
            <input type="email" class="w-full p-2 border rounded mb-4" placeholder="tucorreo@ejemplo.com">
            
            <label class="block mb-2">Mensaje:</label>
            <textarea class="w-full p-2 border rounded mb-4" rows="4" placeholder="Tu mensaje"></textarea>
            
            <button type="submit" class="w-full button p-2 rounded">Enviar</button>
        </form>
    </section>

    <div class="fixed bottom-4 right-4">
        <a href="https://wa.me/573224413532" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp" class="w-16 h-16">
        </a>
    </div>
</body>
</html>
