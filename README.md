# entregable-uno-de-fundamentos-de-program.-web

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EcoMarket</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="estilos.css">
</head>
<body>
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#">EcoMarket</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav mr-auto">
                    <li class="nav-item active">
                        <a class="nav-link" href="#">Inicio <span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Productos</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contacto</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="jumbotron">
            <h1 class="display-4">EcoMarket</h1>
            <p class="lead">Bienvenido a nuestro sitio web de compras sostenibles</p>
            <hr class="my-4">
            <p>Descubre nuestros productos ecológicos y sostenibles</p>
            <p class="lead">
                <a class="btn btn-primary btn-lg" href="#" role="button">Explorar productos</a>
            </p>
        </section>
        <section class="container">
            <h2>Productos destacados</h2>
            <div class="row">
                <div class="col-md-4">
                    <div class="card">
                        <img src="img/producto1.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Producto 1</h5>
                            <p class="card-text">quieres mas informacion sobre nuestros productos visitanos en youtbe en nuestro sitio web FRANDA ECOMARKET te esperamos 1</p>
                            <a href="#" class="btn btn-primary">Ver detalles</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img/producto2.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Producto 2</h5>
                            <p class="card-text"> quieres mas informacion sobre nuestros productos visitanos en youtbe en nuestro sitio web FRANDA ECOMARKET te esperamos2</p>
                            <a href="#" class="btn btn-primary">Ver detalles</a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card">
                        <img src="img/producto3.jpg" class="card-img-top" alt="...">
                        <div class="card-body">
                            <h5 class="card-title">Producto 3</h5>
                            <p class="card-text"> quieres mas informacion sobre nuestros productos visitanos en youtbe en nuestro sitio web FRANDA ECOMARKET te esperamos3</p>
                            <a href="#" class="btn btn-primary">Ver detalles</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
    </main>
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    <script src="script.js"></script>
</body>
</html>

(java script)
document.querySelectorAll('.btn-primary').forEach(btn => {
  btn.addEventListener('click', () => {

    
      window.location.href = 'product-detail.html';
  });
});

(css estilos )
body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
}

.jumbotron {
  background-color: #ffc107;
  color: #fff;
  padding: 100px 25px;
}

.jumbotron h1 {
  font-size: 48px;
  font-weight: bold;
  margin-bottom: 20px;
}

.jumbotron p {
  font-size: 18px;
  margin-bottom: 30px;
}

.card {
  margin-bottom: 20px;
}

.card-img-top {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-top-left-radius: 10px;
  border-top-right-radius: 10px;
}

.card-body {
  padding: 20px;
}

.card-title {
  font-size: 18px;
  font-weight: bold;
  margin-bottom: 10px;
}

.card-text {
  font-size: 14px;
  margin-bottom: 20px;
}

.btn-primary {
  background-color: #ffc107;
  border-color: #ffc107;
  color: #fff;
}

.btn-primary:hover {
  background-color: #ff9900;
  border-color: #ff9900;
}
