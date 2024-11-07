<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Empleos Seguros para Adolescentes</title>
    <style>
        /* Estilos básicos */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f5;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 10px;
            background-color: #fff;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.2);
        }
        h1, h2 {
            color: #333;
        }
        .job-item, .advice-item {
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            cursor: pointer;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #45a049;
        }
        #job-form, #interest-form-section {
            display: flex;
            flex-direction: column;
        }
        .hidden {
            display: none;
        }
    </style>
</head>
<body>

    <header>
        <h1>Empleos Seguros para Adolescentes</h1>
    </header>

    <!-- Formulario para publicar empleo -->
    <section id="publish-job">
        <h2>Publicar un Empleo</h2>
        <form id="job-form">
            <label for="job-type">Tipo de Empleo:</label>
            <select id="job-type" required>
                <option value="">Seleccionar...</option>
                <option value="Cuidado de Mascotas">Cuidado de Mascotas</option>
                <option value="Cuidado de Niños">Cuidado de Niños</option>
                <option value="Tutoría Académica">Tutoría Académica</option>
                <option value="Cafetería o Restaurante">Cafetería o Restaurante</option>
                <option value="Asistente de Tienda">Asistente de Tienda</option>
                <option value="Asistente de Eventos">Asistente de Eventos</option>
                <option value="Marketing Digital">Marketing Digital</option>
                <option value="Jardinería">Jardinería</option>
                <option value="Repartidor">Repartidor</option>
                <option value="Freelance en Habilidades Digitales">Freelance en Habilidades Digitales</option>
                <option value="Llenado de Planillas Deportivas">Llenado de Planillas Deportivas</option>
                <option value="Limpieza">Limpieza</option>
                <option value="Editores de app">Editores de app</option>
            </select>
            <label for="employer-name">Nombre del Empleador:</label>
            <input type="text" id="employer-name" required>
            <label for="employer-address">Dirección:</label>
            <input type="text" id="employer-address" required>
            <label for="employer-phone">Teléfono:</label>
            <input type="text" id="employer-phone" required>
            <button type="button" onclick="publishJob()">Publicar Empleo</button>
        </form>
    </section>

    <!-- Lista de empleos publicados -->
    <section id="job-list">
        <h2>Lista de Empleos</h2>
        <div id="job-container"></div>
    </section>

    <!-- Detalles del empleo y formulario de interés -->
    <section id="interest-form-section" class="hidden">
        <h2>Interesado en el Empleo</h2>
        <p id="job-description"></p>
        <label for="teen-name">Nombre:</label>
        <input type="text" id="teen-name" required>
        <label for="teen-phone">Teléfono:</label>
        <input type="text" id="teen-phone" required>
        <button type="button" onclick="confirmInterest()">Enviar Interés</button>
    </section>

    <!-- Consejos para cada empleo -->
    <section id="advice-section">
        <h2>Consejos para realizar los trabajos</h2>
        <div id="advice-list"></div>
    </section>

    <script>
        const jobs = [];
        const jobContainer = document.getElementById("job-container");
        const interestFormSection = document.getElementById("interest-form-section");
        const jobDescription = document.getElementById("job-description");
        let selectedJobIndex = null;

        const adviceData = {
            "Cuidado de Mascotas": "Recuerda ser amable y cuidar de las mascotas con paciencia.",
            "Cuidado de Niños": "Mantente atento y ofrece un entorno seguro para los niños.",
            "Tutoría Académica": "Prepara los temas de antemano y explica con claridad.",
            "Cafetería o Restaurante": "Sé puntual y atiende a los clientes con cortesía.",
            "Asistente de Tienda": "Organiza bien los productos y atiende con una sonrisa.",
            "Asistente de Eventos": "Sé proactivo y ayuda en la organización del evento.",
            "Marketing Digital": "Estudia sobre redes sociales y aprende herramientas básicas de diseño.",
            "Jardinería": "Utiliza las herramientas con precaución y sigue instrucciones.",
            "Repartidor": "Sigue las rutas indicadas y maneja con seguridad.",
            "Freelance en Habilidades Digitales": "Crea un portafolio de tus habilidades.",
            "Llenado de Planillas Deportivas": "Asegúrate de tener la información correcta.",
            "Limpieza": "Trabaja de manera ordenada y sigue un plan para no olvidar áreas."
            "Editor de app": "Cuidado con los datos y plataformas que vas a manejar."
        };

        function publishJob() {
            const jobType = document.getElementById("job-type").value;
            const employerName = document.getElementById("employer-name").value;
            const employerAddress = document.getElementById("employer-address").value;
            const employerPhone = document.getElementById("employer-phone").value;

            if (!jobType || !employerName || !employerAddress || !employerPhone) {
                alert("Todos los campos son obligatorios.");
                return;
            }

            const job = {
                title: jobType,
                description: ${jobType} ofrecido por ${employerName}. Ubicación: ${employerAddress}, Teléfono: ${employerPhone},
                reserved: false
            };

            jobs.push(job);
            renderJobs();
        }

        function renderJobs() {
            jobContainer.innerHTML = "";
            jobs.forEach((job, index) => {
                if (!job.reserved) {
                    const jobItem = document.createElement("div");
                    jobItem.classList.add("job-item");
                    jobItem.textContent = job.title;
                    jobItem.onclick = () => showJobDetails(index);
                    jobContainer.appendChild(jobItem);
                }
            });
        }

        function showJobDetails(index) {
            selectedJobIndex = index;
            const job = jobs[index];
            jobDescription.textContent = job.description;
            interestFormSection.classList.remove("hidden");
        }

        function confirmInterest() {
            const teenName = document.getElementById("teen-name").value;
            const teenPhone = document.getElementById("teen-phone").value;

            if (!teenName || !teenPhone) {
                alert("Por favor, completa todos los campos.");
                return;
            }

            jobs[selectedJobIndex].reserved = true;
            renderJobs();
            interestFormSection.classList.add("hidden");
            alert("Has mostrado interés en este empleo y ahora está reservado para ti.");
        }

        function renderAdvice() {
            const adviceList = document.getElementById("advice-list");
            adviceList.innerHTML = "";
            Object.keys(adviceData).forEach(jobType => {
                const adviceItem = document.createElement("div");
                adviceItem.classList.add("advice-item");
                adviceItem.textContent = ${jobType}: ${adviceData[jobType]};
                adviceList.appendChild(adviceItem);
            });
        }

        renderJobs();
        renderAdvice();
    </script>
</body>
</html>