<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ejercicio Bootstrap</title>
  <link rel="stylesheet" href="Bootstrap.css">
</head>
<body>
    <div class="container"> <!--container de ancho fijo-->
        <div class="row"> <!-- BS5 Grid Basic -->
            <div class="col-md-6"> <!--Columna mediana-->
                <h1>Bienvenido a mi landing page</h1> <!--Encabezado-->
                <p>Esta es una landing page sencilla creada con Bootstrap 5 Grid.</p>
                <button type="button" class="btn btn-primary">Llamada a la acción</button> <!--boton azul-->
            </div>
            <div class="col-md-6"> <!--Columna mediana-->
                <img src="https://cdn.pixabay.com/photo/2017/07/31/20/06/ball-2560612_640.jpg" class="img-fluid" alt="Imagen principal"> <!--float-start-->
            </div>
        </div>
        <div class="row mt-4"> <!-- BS5 Grid Basic -->
            <div class="col-md-4"> <!--Columna mediana-->
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Característica 1</h5> <!--Encabezado pequeño-->
                        <p class="card-text">Descripción de la característica 1.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4"> <!--Columna mediana-->
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Característica 2</h5> <!--Encabezado pequeño-->
                        <p class="card-text">Descripción de la característica 2.</p>
                    </div>
                </div>
            </div>
            <div class="col-md-4"> <!--Columna mediana-->
                <div class="card">
                    <div class="card-body">
                        <h5 class="card-title">Característica 3</h5> <!--Encabezado pequeño-->
                        <p class="card-text">Descripción de la característica 3.</p>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
