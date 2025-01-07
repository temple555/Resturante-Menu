# Resturante-Menu
Project Final
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Restaurante Delicias</title>
</head>
<body>
    <header>
        <img id="header-img" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRyru3VnAEo1A-r30AoI65pSHOBd0FLujhkCg&s" alt="Imagen del Restaurante Delicias">
        <h1>Restaurante Delicias</h1>
        <nav>
            <ul>
                <li><a href="#menu">Menú</a></li>
                <li><a href="#order-form">Realizar su pedido</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="menu">
            <h2>Menú</h2>
            <article>
                <img src="https://assets.unileversolutions.com/recipes-v2/218401.jpg" width="210" alt="Hamburguesa Clásica">
                <h3>Hamburguesa Clásica</h3>
                <p>Jugosa carne de res, lechuga fresca, tomate maduro y nuestra salsa secreta en un pan artesanal. <i>Precio: $10.99</i></p>
            </article>
            <article>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTY7RbPLpeQGEKr-JMLB6L9kRdCTMtUbFJfJw&s" width="210" alt="Pizza Margarita">
                <h3>Pizza Margarita</h3>
                <p>Masa fina y crujiente, salsa de tomate natural, mozzarella fresca y albahaca. <i>Precio: $12.50</i></p>
            </article>
            <article>
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZhyMOeehqrCdQu8bbtXAQ5mjfKLNC5qOkEg&s" width="210" alt="Ensalada César">
                <h3>Ensalada César</h3>
                <p>Lechuga romana, crutones, queso parmesano y nuestro aderezo César casero. <i>Precio: $8.99</i></p>
            </article>
        </section>
        <section id="order-form">
            <h2>Realizar su pedido</h2>
            <form action="#" method="post">
            <div>
        <label for="qty-hamburguesa">Hamburguesa Clásica (Cantidad):</label>
            <input type="number" id="qty-hamburguesa" name="qty-hamburguesa" min="0" value="0">
                </div>
                <div>
                    <label for="qty-pizza">Pizza Margarita (Cantidad):</label>
                    <input type="number" id="qty-pizza" name="qty-pizza" min="0" value="0">
                </div>
                <div>
                    <label for="qty-ensalada">Ensalada César (Cantidad):</label>
                    <input type="number" id="qty-ensalada" name="qty-ensalada" min="0" value="0">
                </div>
                <div>
                    <p>Guarniciones:</p>
                    <label for="papas">
                        <input type="radio" id="papas" name="side" value="papas"> Papas Fritas
                    </label>
                    <br>
                    <label for="aros">
                        <input type="radio" id="aros" name="side" value="aros"> Aros de Cebolla
                    </label>
                </div>
                <div>
                    <p>Extras:</p>
                    <label for="queso">
                        <input type="checkbox" id="queso" name="extra-queso" value="queso"> Queso Extra
                    </label>
                    <br>
                    <label for="tocino">
                        <input type="checkbox" id="tocino" name="extra-tocino" value="tocino"> Tocino
                    </label>
                </div>
                <div>
                    <label for="special-requests">Solicitudes Especiales (Hamburguesa):</label>
                    <textarea id="special-requests" name="special-requests" rows="4" cols="50"></textarea>
                </div>
                <div>
                    <input type="submit" value="Go To Checkout">
                </div>
            </form>
        </section>
    </main>
    <footer>
        <p>Hecho con amor por Jonathan Nuñez</p>
    </footer>
</body>
</html>
