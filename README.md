<html>
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contador de Visitas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }
        .contador {
            font-size: 2em;
            margin: 20px 0;
        }
    </style>
</head>
<body>
  <h1>
   👋 Hi, I’m @Hferpi 🇪🇸   
  </h1>  
   <h1>Bienvenido a mi página</h1>
    <p>Has visitado esta página:</p>
    <div class="contador" id="contador"></div>
    <p>veces en este navegador.</p>

    <script>
        // Obtenemos el contador desde localStorage
        let contadorVisitas = localStorage.getItem('contadorVisitas');
        
        // Si no existe el contador, lo inicializamos a 0
        if (contadorVisitas === null) {
            contadorVisitas = 0;
        }

        // Incrementamos el contador en 1
        contadorVisitas++;

        // Actualizamos el contador en localStorage
        localStorage.setItem('contadorVisitas', contadorVisitas);

        // Mostramos el valor del contador en la página
        document.getElementById('contador').innerText = contadorVisitas;
    </script>
<div>
  <ul>
<li>- 👀 I’m interested in create something to impact the world</li>

<li> 🌱 I’m currently learning all, my background is zero. In this moment i ' m starting a google course of cybersecurity </li>
<li> 💞️ I’m looking to collaborate on make the world better </li>
<li> 📫 How to reach me hferpi@gmail.com </li>
<li> 😄 Pronouns: 0,1% to 100% 🔁 </li>
  </ul>
</div>

Hi, I m new in this area. I'm coming from learn all I can, I start this week the 26 of February of 2024.


</body>
</html>
