# Tp-integrador-front-end
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="images/codo.png" type="image/x-icon">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-KK94CHFLLe+nY2dmCWGMq91rCGa5gtU4mk92HdvYe+M/SXH301p5ILy+dN9+nJOZ" crossorigin="anonymous">
    <title>Codo a codo 4.0</title>
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-md bg-body-tertiary px-5 py-2 fixed-top" data-bs-theme="dark">
            <div class="container-fluid">
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarToggler"
                    aria-controls="navbar-toggler" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarToggler">
                    <a class="navbar-brand" href="index.html">
                        <img id="logo-pagina" src="images/codo.png" width="100" alt="Logo de la pagina">
                        <span class="nombre-logo">Conf Bs As</span>
                    </a>
                    <ul class="navbar-nav d-flex justify-content-center align-items-e">
                        <li class="nav-item cursor-pointer">
                            <a class="nav-link active" aria-current="page" href="#">La conferencia</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Los oradores</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">El lugar y la fecha</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Conviértete en orador</a>    
                        </li>
                        <li class="nav-item">
                            <a class="nav-link link-verde" href="HTML/ticket.html">Comprar tickets</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header> 
    <div id="carouselExample" class="carousel slide card-superpuesta" data-bs-ride="carousel">
        <div class="carousel-inner">
            <div class="carousel-item active">
                <img src="images/foto 1.jpg" class="d-block w-100" alt="foto 1">
            </div>
            <div class="carousel-item">
                <img src="images/hawaii2.jpg" class="d-block w-100" alt="hawaii2">
            </div>
            <div class="carousel-item">
                <img src="images/hawaii3.jpg" class="d-block w-100" alt="hawaii3">
            </div>
        </div>
        <div class="d-flex">
            <div class="card-img-overlay d-flex flex-column justify-content-center text-end">
                <h5 class="card-title1">Conf Bs As</h5>
                <p class="card-text1">
                Bs As llega por primera vez a la Argentina. Un evento para compartir con
                nuestra comunidad el conocimiento y experiencia de los expertos que 
                están creando el futuro de Internet.Ven a conocer a miembros del
                evento, a otros estudiantes de Codo a Codo y los oradores primer
                nivel que tenemos para ti. 
                Te esperamos!
                </p>
                <div>
                    <button type="button" class="btn btn-outline-light">Quiero ser orador</button>
                    <button type="button" class="btn btn-success" onclick="location.href='HTML/ticket.html'">
                        Comprar tickets
                    </button>
                </div>
            </div>
        </div>
    </div>    
    <div class="titulo-oradores">
        <div>CONOCE A LOS</div> 
        <H4>ORADORES</H4>
    </div>
    <section>
    <div class="container-oradores">
        <div class="row">
            <div class="card-oradores col-lg-4">
                <div class="card">
                    <img src="images/steve.jpg" class="card-img-top" alt="Steve Jobs">
                    <div class="card-body">
                        <div class="badges-contenedor">
                        <span class="badge text-bg-warning">JavaScript</span>
                        <span class="badge text-bg-info">React</span>
                        </div>
                        <h5 class="card-title">Steve Jobs</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, alias, provident magni neque ullam esse explicabo est similique soluta dolorem totam at magnam obcaecati, facilis excepturi. Possimus quasi suscipit a!</p>
                    </div>
                </div>
            </div> 
            <div class="card-oradores col-lg-4">
                <div class="card">
                <img src="images/bill.jpg" class="card-img-top" alt="Bill Gates">
                    <div class="card-body">
                        <div class="badges-contenedor">
                            <span class="badge text-bg-warning">JavaScript</span>
                            <span class="badge text-bg-info">React</span>
                        </div>
                        <h5 class="card-title">Bill Gates</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, alias, provident magni neque ullam esse explicabo est similique soluta dolorem totam at magnam obcaecati, facilis excepturi. Possimus quasi suscipit a!</p>
                    </div>
                </div>
            </div>  
            <div class="card-oradores col-lg-4">
                <div class="card">
                <img src="images/ba1.jpeg" class="card-img-top" alt="Ada Lovelace">
                    <div class="card-body">
                        <div class="badges-contenedor">
                            <span class="badge text-bg-secondary">JavaScript</span>
                            <span class="badge text-bg-danger">React</span>
                        </div>
                        <h5 class="card-title">Ada Lovelace</h5>
                        <p class="card-text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, alias, provident magni neque ullam esse explicabo est similique soluta dolorem totam at magnam obcaecati, facilis excepturi. Possimus quasi suscipit a!</p>
                    </div>
                </div>
            </div>  
        </div>    
    </div>
    </section>
    <div class="card-honolulu">
        <div class="row g-0">
            <div class="col-lg-6 d-flex">
                <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="images/honolulu.jpg" class="d-block w-100" alt="Honolulu">
                        </div>
                        <div class="carousel-item">
                            <img src="images/hawaii.jpg" class="d-block w-100" alt="Buenos Aires">
                        </div>
                        <div class="carousel-item">
                            <img src="images/hawaii2.jpg" class="d-block w-100" alt="Buenos Aires">
                        </div>
                        <div class="carousel-item">
                            <img src="images/hawaii3.jpg" class="d-block w-100" alt="Buenos Aires">
                        </div>
                    </div>
                </div>
            </div>
            <div class="col-lg-6 d-flex p-4 bg-dark honolulu-text">
                <div>
                    <h5>Bs As - Octubre</h5>
                    <p>
                    Buenos Aires es la provincia y localidad mas grande del estado de Argentina, en los Estados Unidos Honolulu
                    es la mas sureña de entre las principales ciudades estadounidenses. Aunque el nombre de Honolulu se refiere al 
                    área urbana en la costa sureste de la isla de Oahu, la ciudad y el condado de honolulu han formado una ciudad-
                    condado consolidada que cubre toda la ciudad (aproximadamente 600 km2 de superficie).
                    </p>
                    <button type="button" class="btn btn-outline-light">Conocé más</button>    
                </div>
            </div>
        </div>
    </div>
    <div class="convocatoria-oradores">
        <div class="div-orador">CONVIÉRTETE EN ORADOR</div> 
        <H4>ORADOR</H4>
        <div class="text-convocatoria">Anotate como orador para dar una <u class="subrayado">charla ignite</u>. Cuéntanos de
            qué quieres hablar!</div>
    </div>
          </li>
    </ul>
</div>
</div>
</nav>
</header>

<main>

    <!doctype html>
<html lang="es">

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Comprar tickets</title>
    <link rel="stylesheet" href="./styles/style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
</head>

<body>

    <main>

        <!-- TICKETS -->
        <section class="container pt-section">
            <div class="row justify-content-center">
                <div class="col-lg-8 col-xl-7">

                    <!-- DESCUENTO -->
                    <div class="row row-cols-1 row-cols-md-3 text-center">
                        <div class="col">
                            <div class="card mb-4 rounded-3 shadow-sm border-primary">
                                <div class="card-header py-3 text-white bg-primary border-primary">
                                    <h4 class="my-0 fw-normal">Estudiante</h4>
                                </div>
                                <div class="card-body">
                                    <p>Tienen un descuento</p>
                                    <h3 class="card-title pricing-card-title">80%</h3>
                                    <small class="fw-light text-muted mt-3">* Presentar documentación</small>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card mb-4 rounded-3 shadow-sm border-info">
                                <div class="card-header py-3 text-white bg-info border-info">
                                    <h4 class="my-0 fw-normal">Trainee</h4>
                                </div>
                                <div class="card-body">
                                    <p>Tienen un descuento</p>
                                    <h3 class="card-title pricing-card-title">50%</h3>
                                    <small class="fw-light text-muted mt-3">* Presentar documentación</small>
                                </div>
                            </div>
                        </div>
                        <div class="col">
                            <div class="card mb-4 rounded-3 shadow-sm border-warning">
                                <div class="card-header py-3 text-white bg-warning border-warning">
                                    <h4 class="my-0 fw-normal">Junior</h4>
                                </div>
                                <div class="card-body">
                                    <p>Tienen un descuento</p>
                                    <h3 class="card-title pricing-card-title">15%</h3>
                                    <small class="fw-light text-muted mt-3">* Presentar documentación</small>
                                </div>
                            </div>
                        </div>
                    </div>

                    <h2 class="titulo-gral">Venta <span>Valor de ticket $200</span></h2>

                    <!-- FORMULARIO TICKETS -->
                    <form class="ticketsForm" action="">
                        <div class="row gx-2">
                            <div class="col-md mb-3">
                                <input type="text" class="form-control" placeholder="Nombre" aria-label="Nombre"
                                    id="nombre" required>
                            </div>
                            <div class="col-md mb-3">
                                <input type="text" class="form-control" placeholder="Apellido" aria-label="Apellido"
                                    id="apellido" required>
                            </div>
                        </div>
                        <div class="row">
                            <div class="col mb-3">
                                <input type="email" class="form-control" placeholder="Email" aria-label="Email"
                                    id="email" required>
                            </div>
                        </div>
                        <div class="row gx-2">
                            <div class="col-md mb-3">
                                <label for="cantidad" class="form-label">Cantidad</label>
                                <input type="number" class="cantidad form-control" placeholder="Cantidad" aria-label="Cantidad" min="1" required>
                            </div>
                            <div class="col-md mb-3">
                                <label for="categoria" class="form-label">Categoría</label>
                                <select class="categoria form-select" aria-label="Categoría">
                                    <option selected value="general">Entrada General</option>
                                    <option value="estudiante">Estudiante</option>
                                    <option value="trainee">Trainee</option>
                                    <option value="junior">Junior</option>
                                </select>
                            </div>
                        </div>
                        <div class="alert alert-primary mt-2 mb-4">
                            <output class="total">
                                <span id="total" class="align-middle">Total a pagar:</span>
                            </output>
                        </div>
                        <div class="row gx-2">
                            <div class="col-md mb-3">
                                <button type="reset" class="w-100 btn btn-success btn-form" id="borrar" name="Borrar">Borrar</button>
                            </div>
                            <div class="col-md mb-3">
                                <button type="button" id="resumen" class="w-100 btn btn-success btn-form" name="Resumen">Resumen</button>
                            </div>
                        </div>
                        </div>
                    </form>
<footer>
        <div class="footer-lista justify-content-center align-items-center">
            <a class="nav-link footer-link text-center" href="#">Preguntas<br>Frecuentes</a>
            <a class="nav-link footer-link text-center" href="#">Contáctanos</a>
            <a class="nav-link footer-link text-center" href="#">Prensa</a>
            <a class="nav-link footer-link text-center" href="#">Conferencia</a>                        
            <a class="nav-link footer-link text-center" href="#">Términos y <br> Condiciones</a>
            <a class="nav-link footer-link text-center" href="#">Privacidad</a>
            <a class="nav-link footer-link text-center" href="#">Estudiantes</a>
        </div> 
    </footer>   
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ENjdO4Dr2bkBIFxQpeoTz1HIcje39Wm4jDKdf19U8gI4ddQ3GYNS7NTKfAdVQSZe" crossorigin="anonymous"></script>
    integrity="sha384-u1OknCvxWvY5kfmNBILK2hRnQC3Pr17a+RTT6rIHI7NnikvbZlHgTPOOmMi466C8"
    crossorigin="anonymous"></script>
    <script src="script.js"></script>
</body>
</html>
