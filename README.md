# siembra-de-arboles
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guía Completa para la Siembra de Árboles</title>
    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Font Awesome para iconos -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        .hero-section {
            background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('https://media.admagazine.com/photos/618a70bfbe961b98e9f09fba/3:2/w_1788,h_1192,c_limit/28669.jpg');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 100px 0;
            margin-bottom: 30px;
        }
        .benefit-card {
            transition: transform 0.3s;
            margin-bottom: 20px;
            height: 100%;
        }
        .benefit-card:hover {
            transform: translateY(-10px);
        }
        .step-icon {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: #28a745;
        }
        .tree-type-card img {
            height: 200px;
            object-fit: cover;
        }
        footer {
            background-color: #343a40;
            color: white;
            padding: 30px 0;
        }
    </style>
</head>
<body>
    <!-- Barra de navegación -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-success sticky-top">
        <div class="container">
            <a class="navbar-brand" href="#">
                <i class="fas fa-tree me-2"></i>Siembra de Árboles
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#importancia">Importancia</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#como-sembrar">Cómo Sembrar</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#tipos-arboles">Tipos de Árboles</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#cuidados">Cuidados</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    <!-- Sección Hero -->
    <section class="hero-section text-center">
        <div class="container">
            <h1 class="display-4 fw-bold">Guía Completa para la Siembra de Árboles</h1>
            <p class="lead">Aprende todo lo necesario para contribuir al medio ambiente sembrando árboles correctamente</p>
            <a href="#como-sembrar" class="btn btn-success btn-lg mt-3">Comenzar</a>
        </div>
    </section>

    <!-- Sección Importancia -->
    <section id="importancia" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">¿Por qué es importante sembrar árboles?</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card benefit-card shadow">
                        <div class="card-body text-center">
                            <i class="fas fa-lungs step-icon"></i>
                            <h4>Producción de Oxígeno</h4>
                            <p>Un árbol maduro puede producir suficiente oxígeno para 10 personas al año. Los árboles absorben CO2 y liberan oxígeno mediante la fotosíntesis.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card benefit-card shadow">
                        <div class="card-body text-center">
                            <i class="fas fa-temperature-low step-icon"></i>
                            <h4>Regulación Climática</h4>
                            <p>Los árboles reducen el efecto de isla de calor urbano, disminuyen la temperatura ambiente y regulan los patrones climáticos locales.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card benefit-card shadow">
                        <div class="card-body text-center">
                            <i class="fas fa-water step-icon"></i>
                            <h4>Conservación del Agua</h4>
                            <p>Los árboles reducen la escorrentía, previenen la erosión del suelo y filtran contaminantes, protegiendo las fuentes de agua.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-4">
                <div class="col-md-6">
                    <div class="card benefit-card shadow">
                        <div class="card-body text-center">
                            <i class="fas fa-paw step-icon"></i>
                            <h4>Hábitat para Fauna</h4>
                            <p>Proporcionan refugio y alimento para numerosas especies de aves, insectos y mamíferos, manteniendo la biodiversidad.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card benefit-card shadow">
                        <div class="card-body text-center">
                            <i class="fas fa-heartbeat step-icon"></i>
                            <h4>Beneficios para la Salud</h4>
                            <p>Reducen el estrés, mejoran la calidad del aire y promueven la actividad física, contribuyendo al bienestar humano.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Cómo Sembrar -->
    <section id="como-sembrar" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Guía Paso a Paso para Sembrar Árboles</h2>
            <div class="row g-4">
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <div class="step-icon"><i class="fas fa-1"></i></div>
                            <h4>Selección del Árbol</h4>
                            <p>Elige especies nativas adaptadas a tu clima y suelo. Considera el espacio disponible cuando el árbol crezca.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <div class="step-icon"><i class="fas fa-2"></i></div>
                            <h4>Época de Siembra</h4>
                            <p>La mejor época es al inicio de la temporada de lluvias o en primavera, cuando las temperaturas son moderadas.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <div class="step-icon"><i class="fas fa-3"></i></div>
                            <h4>Preparación del Terreno</h4>
                            <p>Excava un hoyo 2-3 veces más ancho que el cepellón y de igual profundidad. Afloja la tierra alrededor para facilitar el crecimiento de raíces.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-6 col-lg-3">
                    <div class="card h-100 shadow-sm">
                        <div class="card-body text-center">
                            <div class="step-icon"><i class="fas fa-4"></i></div>
                            <h4>Plantación</h4>
                            <p>Coloca el árbol en el centro del hoyo. Rellena con tierra mezclada con compost. No entierres el tronco más de lo que estaba en el contenedor.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-4">
                <div class="col-md-6">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="text-center mb-4">Herramientas Necesarias</h4>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i>Pala para cavar</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i>Guantes de jardinería</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i>Carretilla para transportar tierra/compost</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i>Regadera o manguera</li>
                                <li class="list-group-item"><i class="fas fa-check-circle text-success me-2"></i>Tutor (para árboles jóvenes)</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="text-center mb-4">Consejos Adicionales</h4>
                            <div class="alert alert-success">
                                <i class="fas fa-lightbulb me-2"></i>Riega abundantemente después de plantar y mantén la tierra húmeda las primeras semanas.
                            </div>
                            <div class="alert alert-info">
                                <i class="fas fa-lightbulb me-2"></i>Aplica una capa de mulch (5-10 cm) alrededor del árbol para retener humedad y controlar malezas.
                            </div>
                            <div class="alert alert-warning">
                                <i class="fas fa-lightbulb me-2"></i>Evita plantar cerca de edificios, tuberías o cables eléctricos (considera el tamaño adulto del árbol).
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Tipos de Árboles -->
    <section id="tipos-arboles" class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Tipos de Árboles Recomendados</h2>
            <div class="row g-4">
                <div class="col-md-4">
                    <div class="card tree-type-card shadow-sm h-100">
                        <img src="https://i.etsystatic.com/26195869/r/il/013f9d/3496404450/il_570xN.3496404450_ran8.jpg" class="card-img-top" alt="Árboles Frutales">
                        <div class="card-body">
                            <h4 class="card-title">Árboles Frutales</h4>
                            <p class="card-text">Proporcionan alimento y belleza. Ejemplos: manzano, naranjo, limonero, mango. Requieren más cuidado pero ofrecen recompensas tangibles.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card tree-type-card shadow-sm h-100">
                        <img src="https://i0.wp.com/elsalvadorinenglish.com/wp-content/uploads/2025/02/maquilishuat-25.png?fit=1170%2C610&ssl=1" class="card-img-top" alt="Árboles Nativos">
                        <div class="card-body">
                            <h4 class="card-title">Árboles Nativos</h4>
                            <p class="card-text">Adaptados al clima y suelo local, requieren menos mantenimiento. Apoyan la biodiversidad local. Investiga cuáles son autóctonos de tu región.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card tree-type-card shadow-sm h-100">
                        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRMJgKRjgSHXatPOW68uLeCklPypF1eweLEuQ&s" class="card-img-top" alt="Árboles de Sombra">
                        <div class="card-body">
                            <h4 class="card-title">Árboles de Sombra</h4>
                            <p class="card-text">Ideales para espacios urbanos y jardines. Ejemplos: roble, arce, fresno. Crecen rápido y proporcionan sombra en verano.</p>
                        </div>
                    </div>
                </div>
            </div>
            <div class="row mt-4">
                <div class="col-md-6">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="text-center mb-4">Árboles para Pequeños Espacios</h4>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><strong>Arce japonés:</strong> Crecimiento lento, hermoso follaje otoñal</li>
                                <li class="list-group-item"><strong>Cerezo ornamental:</strong> Hermosas flores en primavera</li>
                                <li class="list-group-item"><strong>Magnolia stellata:</strong> Florece temprano, tamaño compacto</li>
                                <li class="list-group-item"><strong>Olivo enano:</strong> Resistente a sequía, aspecto mediterráneo</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-md-6">
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4 class="text-center mb-4">Árboles para Grandes Espacios</h4>
                            <ul class="list-group list-group-flush">
                                <li class="list-group-item"><strong>Conacaste:</strong> Majestuoso, crecimiento muy alto</li>
                                <li class="list-group-item"><strong>Roble:</strong> Longevo, gran valor ecológico</li>
                                <li class="list-group-item"><strong>Castaño:</strong> Frutos comestibles, amplia copa</li>
                                <li class="list-group-item"><strong>Pino:</strong> Perenne, resistente, buena para suelos pobres</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección Cuidados -->
    <section id="cuidados" class="py-5 bg-light">
        <div class="container">
            <h2 class="text-center mb-5">Cuidados Posteriores a la Siembra</h2>
            <div class="row">
                <div class="col-lg-6">
                    <div class="card mb-4 shadow-sm">
                        <div class="card-body">
                            <h4><i class="fas fa-tint text-primary me-2"></i> Riego Adecuado</h4>
                            <p>Los árboles recién plantados necesitan riego regular (2-3 veces por semana) durante los primeros 1-2 años. Riega profundamente para fomentar raíces profundas. Reduce la frecuencia pero aumenta la cantidad de agua a medida que el árbol madura.</p>
                            <div class="alert alert-info">
                                <strong>Señales de estrés hídrico:</strong> Hojas marchitas, amarillamiento, caída prematura de hojas.
                            </div>
                        </div>
                    </div>
                    <div class="card mb-4 shadow-sm">
                        <div class="card-body">
                            <h4><i class="fas fa-cut text-danger me-2"></i> Poda Correcta</h4>
                            <p>Poda solo lo necesario los primeros años. Elimina ramas muertas, enfermas o que se crucen. La mejor época para podar es a finales de invierno o principios de primavera para la mayoría de especies.</p>
                            <ul>
                                <li>No elimines más del 25% del follaje en una temporada</li>
                                <li>Usa herramientas limpias y afiladas</li>
                                <li>Corta justo por fuera del collar de la rama</li>
                            </ul>
                        </div>
                    </div>
                </div>
                <div class="col-lg-6">
                    <div class="card mb-4 shadow-sm">
                        <div class="card-body">
                            <h4><i class="fas fa-bug text-warning me-2"></i> Control de Plagas y Enfermedades</h4>
                            <p>Inspecciona regularmente tu árbol para detectar problemas temprano. Identifica correctamente el problema antes de tratar. Prefiere métodos orgánicos y selectivos para no dañar insectos beneficiosos.</p>
                            <table class="table table-bordered">
                                <thead>
                                    <tr>
                                        <th>Problema</th>
                                        <th>Solución</th>
                                    </tr>
                                </thead>
                                <tbody>
                                    <tr>
                                        <td>Áfidos</td>
                                        <td>Jabón insecticida o chorro de agua fuerte</td>
                                    </tr>
                                    <tr>
                                        <td>Orugas</td>
                                        <td>Bacillus thuringiensis (Bt)</td>
                                    </tr>
                                    <tr>
                                        <td>Hongos</td>
                                        <td>Mejorar circulación de aire, fungicidas orgánicos</td>
                                    </tr>
                                </tbody>
                            </table>
                        </div>
                    </div>
                    <div class="card shadow-sm">
                        <div class="card-body">
                            <h4><i class="fas fa-flask text-success me-2"></i> Fertilización</h4>
                            <p>La mayoría de árboles no necesitan fertilizante el primer año. Después, usa fertilizantes orgánicos de liberación lenta en primavera. Evita fertilizar a finales de verano para no estimular crecimiento nuevo antes del invierno.</p>
                            <div class="progress mb-2">
                                <div class="progress-bar bg-success" style="width: 70%">Nitrógeno (70%)</div>
                            </div>
                            <div class="progress mb-2">
                                <div class="progress-bar bg-info" style="width: 20%">Fósforo (20%)</div>
                            </div>
                            <div class="progress">
                                <div class="progress-bar bg-warning" style="width: 10%">Potasio (10%)</div>
                            </div>
                            <p class="mt-2"><small>Proporción típica N-P-K para árboles jóvenes</small></p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Sección de Datos Curiosos -->
    <section class="py-5">
        <div class="container">
            <h2 class="text-center mb-5">Datos Curiosos sobre los Árboles</h2>
            <div class="row">
                <div class="col-md-10 mx-auto">
                    <div class="accordion" id="curiosidadesAccordion">
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#curiosidad1">
                                    <i class="fas fa-leaf me-2 text-success"></i> Los árboles más antiguos del mundo
                                </button>
                            </h2>
                            <div id="curiosidad1" class="accordion-collapse collapse show" data-bs-parent="#curiosidadesAccordion">
                                <div class="accordion-body">
                                    <p>Los pinos bristlecone (Pinus longaeva) en las Montañas Blancas de California son los organismos no clonales más antiguos conocidos. "Matusalén" tiene más de 4,800 años, mientras que un ejemplar sin nombre supera los 5,000 años.</p>
                                    <img src="https://www.shutterstock.com/image-photo/bristlecone-pine-on-slope-mt-600nw-1403166914.jpg" class="img-fluid rounded mb-3" alt="Pino Bristlecone">
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#curiosidad2">
                                    <i class="fas fa-tree me-2 text-success"></i> Comunicación entre árboles
                                </button>
                            </h2>
                            <div id="curiosidad2" class="accordion-collapse collapse" data-bs-parent="#curiosidadesAccordion">
                                <div class="accordion-body">
                                    <p>Los árboles pueden comunicarse y compartir recursos a través de redes de hongos micorrícicos en el suelo, conocida como la "Wood Wide Web". Los árboles madre pueden enviar nutrientes a árboles más jóvenes de su misma especie.</p>
                                </div>
                            </div>
                        </div>
                        <div class="accordion-item">
                            <h2 class="accordion-header">
                                <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#curiosidad3">
                                    <i class="fas fa-cloud me-2 text-success"></i> Impacto en el clima global
                                </button>
                            </h2>
                            <div id="curiosidad3" class="accordion-collapse collapse" data-bs-parent="#curiosidadesAccordion">
                                <div class="accordion-body">
                                    <p>Los bosques del mundo almacenan aproximadamente 400 gigatoneladas de carbono, más del doble que la cantidad actualmente en la atmósfera. Un árbol maduro puede absorber hasta 22 kg de CO2 al año.</p>
                                    <div class="progress">
                                        <div class="progress-bar bg-success" style="width: 40%">Bosques (40%)</div>
                                        <div class="progress-bar bg-info" style="width: 30%">Océanos (30%)</div>
                                        <div class="progress-bar bg-warning" style="width: 20%">Suelos (20%)</div>
                                        <div class="progress-bar bg-danger" style="width: 10%">Otros (10%)</div>
                                    </div>
                                    <p class="mt-2"><small>Distribución de sumideros de carbono naturales</small></p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Llamado a la acción -->
    <section class="py-5 bg-success text-white">
        <div class="container text-center">
            <h2 class="mb-4">¡Empieza a sembrar hoy mismo!</h2>
            <p class="lead mb-4">Cada árbol que plantas es un regalo para las futuras generaciones y un paso hacia un planeta más saludable.</p>
            <div class="d-flex justify-content-center gap-3">
                <a href="#" class="btn btn-light btn-lg">Encuentra especies nativas</a>
                <a href="#" class="btn btn-outline-light btn-lg">Únete a iniciativas locales</a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-4 mb-4 mb-md-0">
                    <h5><i class="fas fa-tree me-2"></i>Siembra de Árboles</h5>
                    <p>Guía completa para contribuir al medio ambiente a través de la siembra responsable de árboles.</p>
                    <div class="social-icons">
                        <a href="#" class="text-white me-2"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="text-white me-2"><i class="fab fa-twitter"></i></a>
                        <a href="#" class="text-white me-2"><i class="fab fa-instagram"></i></a>
                        <a href="#" class="text-white"><i class="fab fa-youtube"></i></a>
                    </div>
                </div>
                <div class="col-md-2 mb-4 mb-md-0">
                    <h5>Enlaces</h5>
                    <ul class="list-unstyled">
                        <li><a href="#importancia" class="text-white">Importancia</a></li>
                        <li><a href="#como-sembrar" class="text-white">Cómo sembrar</a></li>
                        <li><a href="#tipos-arboles" class="text-white">Tipos de árboles</a></li>
                        <li><a href="#cuidados" class="text-white">Cuidados</a></li>
                    </ul>
                </div>
                <div class="col-md-3 mb-4 mb-md-0">
                    <h5>Recursos</h5>
                    <ul class="list-unstyled">
                        <li><a href="#" class="text-white">Guía de especies nativas</a></li>
                        <li><a href="#" class="text-white">Calendario de siembra</a></li>
                        <li><a href="#" class="text-white">Organizaciones ambientales</a></li>
                        <li><a href="#" class="text-white">Talleres de jardinería</a></li>
                    </ul>
                </div>
                <div class="col-md-3">
                    <h5>Contacto</h5>
                    <ul class="list-unstyled">
                        <li><i class="fas fa-envelope me-2"></i> info@siembraarboles.com</li>
                        <li><i class="fas fa-phone me-2"></i> +1 234 567 890</li>
                        <li><i class="fas fa-map-marker-alt me-2"></i> Ciudad Verde, País</li>
                    </ul>
                </div>
            </div>
            <hr class="my-4 bg-light">
            <div class="row">
                <div class="col-md-6 text-center text-md-start">
                    <p class="mb-0">&copy; 2023 Siembra de Árboles. Todos los derechos reservados.</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <p class="mb-0">
                        <a href="#" class="text-white">Política de privacidad</a> | 
                        <a href="#" class="text-white">Términos de servicio</a>
                    </p>
                </div>
            </div>
        </div>
    </footer>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
