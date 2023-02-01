<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CV Stanley Crowley</title>
    <!-- incorporacion de estilos: bootstrap + estilos -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" type="text/css" href="css/estilos.css" />
    <link rel="icon" type="image/x-icon" href="./img/favicon.ico">

    <!-- paleta de colores 
    #546FF4
    #8954F4
    #54C0F4
     -->
</head>
<body>
    <nav class="navbar sticky-top navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Curriculum Vitae</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#datos_contacto">Datos de Contacto</a>
                </li>
                
                <li class="nav-item">
                    <a class="nav-link" href="#button_collapse_formacion">Formación</a>
                </li>

                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#button_collapse_habilidades">Habilidades</a>
                </li>
            
                <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#button_collapse_experiencia_detallada">Experiencia</a>
                </li>
            </ul>
            </div>
        </div>
    </nav>

    <!-- Datos principales -->    
    <div id="datos_contacto" class="container-fluid text-center">
        <div class="row">
            <div class = "col-md-5 d-flex align-items-center justify-content-center" >
                <img src="https://randomuser.me/api/portraits/women/73.jpg" alt="Foto de Perfil de Caterina Stanley" id="foto_perfil" >
            </div>
            
            <div class = "col-12 col-md-7">
                <h1 id="titulo_contacto">Datos de Contacto</h1>
                <ul id="lista_datos_contacto">
                    <li>Nombre y Apellido: Caterina Anne Stanley Crowley</li>
                    <li>Fecha de Nacimiento: 15/08/1990</li>
                    <li>Domicilio: Av. Crovara 3500, La Tablada, Provincia de Buenos Aires</li>
                    <li>Teléfono de contacto: +54-911-4799-9974</li>
                </ul>
            </div>
           
        </div>
    </div>


    <!-- Formacion -->
    <div>
        <div class="d-grid gap-2">
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapse_formacion" aria-expanded="false" aria-controls="collapse_formacion" id="button_collapse_formacion" >
                <h1>Formación</h1>
            </button>
        </div>
    
        <div class="collapse" id="collapse_formacion">
            <div id="formacion" class="container-fluid text-center">
                <div class="row">
                    <div class = "col-6"><h2>Secundaria</h2>
                        <h3>Art Oriented High School Degree</h3>
                        <ul class="lista_formacion">
                            <li>Saint Ann's School</li>
                            <li>Año de graduación: 2007</li>
                            <li>Domicilio: Pierrepoint St. 129, Brooklyn, New York, Estados Unidos</li>
                            <li><a href="http://www.saintannsny.org/" target="_blank">Contacto</a> </li>
                        </ul>
                    </div>
                    <div class = "col-6"><h2>Universitario</h2>
                        <h3>Licenciatura en Diseño Industrial</h3>
                        <ul class="lista_formacion">
                            <li>Universidad Argentina de la Empresa</li>
                            <li>Año de graduación: 2011</li>
                            <li>Domicilio: Lima 775, CABA, Argentina</li>
                            <li><a href="https://www.uade.edu.ar/" target="_blank">Contacto</a> </li>
                        </ul>
                    </div>
                </div>

                <div class="row">
                    <div class = "col-6"><h2>Posgrado</h2>             
                        <h3>Especialización en Branding y Marketing</h3>
                        <ul class="lista_formacion">
                            <li>Universidad Argentina de la Empresa</li>
                            <li>Año de graduación: 2011</li>
                            <li>Domicilio: Lima 775, CABA, Argentina</li>
                            <li><a href="https://www.uade.edu.ar/" target="_blank">Contacto</a> </li>
                        </ul>
                    </div>
                    
                    <div class = "col-6"><h2>Cursos</h2>
                        <h3>Workshop in cultural products from Argentina</h3>
                        <ul class="lista_formacion">
                            <li>University of California - Los Angeles</li>
                            <li>Julio 2019</li>
                            <li>Los Angeles, California, Estados Unidos</li>
                            <li><a href="https://www.ucla.edu/" target="_blank">Contacto</a> </li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- Habilidades -->
    <div>
        <div class="d-grid gap-2">
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapse_habilidades" aria-expanded="false" aria-controls="collapse_habilidades" id="button_collapse_habilidades">
                <h1>Habilidades</h1>
            </button>
        </div>

        <div class="collapse" id="collapse_habilidades">
            <div id="habilidades" class="container-fluid text-center">
                <div class="row">
                    <div class = "col-md-2"></div>
                    <div class = "col-6 col-md-4">
                        <h2>Software</h2>
                        <ul id="lista_soft">
                            <li>AutoCAD: avanzado</li>
                            <li>SolidEdge: avanzado</li>
                            <li>Blender: avanzado</li>
                            <li>Office y Google Suite: avanzado</li>
                        </ul>
                    </div>
                    <div class = "col-6 col-md-4">
                        <h2>Idiomas</h2>
                        <ul id="lista_lang">
                            <li>Inglés: nativo</li>
                            <li>Español: nativo</li>
                            <li>Aleman: intermedio</li>
                            <li>Portugués: fluido</li>
                        </ul>
                    </div>
                    <div class = "col-md-2"></div>
                </div>
            </div>
        </div>
    </div>

    <!-- Experiencia -->
    <div>
        <div class="d-grid gap-2">
            <button class="btn btn-primary" type="button" data-bs-toggle="collapse" data-bs-target="#collapse_experiencia" aria-expanded="false" aria-controls="collapse_experiencia" id="button_collapse_experiencia_detallada">
                <h1>Experiencia</h1>
            </button>
        </div>

        <div class="collapse" id="collapse_experiencia">
            <div id="experiencia_detallada" class="container-fluid text-center">
                <div id="exp_BnD" class="row">
                    <h2 id="h2_BnD">Black and Decker</h2>
                    <h3>Latin America and Caribbean branch</h3>
                    <p class="desde_hasta">Marzo 2019 - Actualidad</p>
                    <p>Expertise en desarrollo de martillos. Encargada de desarrollo de martillos automáticos y pionera en línea Tools for Everyone. Achievement Award in HSE Compliance, consultoria interna en medidas de seguridad</p>
                </div>
                <div id="exp_stanley" class="row">
                    <h2>Stanley</h2>
                    <h3>South America Outdoor division</h3>
                    <p class="desde_hasta">Julio 2016 - Enero 2019</p>
                    <p>Encargada de innovation deployment y branding para línea de mates y bombillas Stanley®.</p>
                </div>
            </div>
        </div>
    </div>

    <script src="js/funciones.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>
    
</body>
</html>
