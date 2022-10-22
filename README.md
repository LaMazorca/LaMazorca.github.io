# LaMazorca.github.io
Practica del modulo del HTLM - Launch X LATAM

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Planetaco</title>
</head>
<body>
    <header>
        <h1>Planetaco desde el 2022</h1>
    </header>
    <section>
            <img src="../Images/Planetaco.png" alt="logo planetacos"/>
        <h2>Menú</h2>
            <h3>Tacos grandes</h3>
            <p>Todos incluyen nopales y cebollas</p>
                <ul>
                    <li>Bisteck ..................... $30</li>
                    <li>Chorizo ..................... $30</li>
                    <li>Chuleta ..................... $30</li>
                    <li>Pastor ..................... $30</li>
                    <li>Campechanos ..................... $30</li>
                </ul>
            <h3>Tacos pequeños</h3>
            <p>Con cilantro y cebolla</p>
                <ul>
                    <li>Bisteck ..................... $15</li>
                    <li>Chorizo ..................... $15</li>
                    <li>Chuleta ..................... $15</li>
                    <li>Pastor ..................... $15</li>
                    <li>Campechanos ..................... $15</li>
                </ul>
            <h3>Especiales</h3>
            <p>Haz tu combo por refresco por $10 más</p>
                <dl>
                    <dt>Planeta Venus ..................... $40</dt>
                    <dd>- Tortilla de maíz con pollo asado</dd>
                    <dt>Planeta Marte ..................... $40</dt>
                    <dd>- Tortilla de harina con carne de res y queso</dd>
                    <dt>Plutón ..................... $40</dt>
                    <dd>- Tortilla de maíz con chuleta</dd>
                    <dt>Planeta Tierra ..................... $40</dt>
                    <dd>- Tortilla de maíz con pastor</dd>
                </dl>
    </section>
<hr>
    <section>
        <h2>Ubicación</h2>
            <h3>Sucursales</h3>
                <table>
                    <tr>
                        <th>Ubicación</th>
                        <th>Dirección</th>
                        <th>Horarios</th>
                    </tr>
                    <tr>
                        <td>Centro</td>
                        <td><a href="https://goo.gl/maps/NrkKwg9GoKwMAZgk7" target="_blank">Calle 86A 644, Los Reyes</a></td>
                        <td>L - D 24H</td>
                    </tr>
                    <tr>
                        <td>Sur</td>
                        <td><a href="https://goo.gl/maps/jFuL6NCEet2rCQXJ8" target="_blank">Calle 50 x 133 y, C. 135 940, Cinco Colonias</a></td>
                        <td>L - D 5pm - 3am</td>
                    </tr>
                    <tr>
                        <td>Norte</td>
                        <td><a href="https://goo.gl/maps/Z6TmsHcrs9ZH6NUH9" target="_blank">C. 7 359, Xcumpich</a></td>
                        <td>M - D 5pm - 3am</td>
                    </tr>
                </table>
    </section>
<hr>
    <section>
        <h2>Pedidos</h2>
            <h3>Haz tu pedido aquí</h3>
                <form action="" method="post">
                    <p>¿De qué taquería quieres?</p>
                        <select>
                            <option value="norte">Norte</option>
                            <option value="centro" selected>Centro</option>
                            <option value="sur">Sur</option>
                        </select>
                    <p>¿De qué tacos quieres?</p>
                        <input type="checkbox" id="bisteck" name="bisteck" value="bisteck">
                        <label for="bisteck">Bisteck</label>
                        <br>
                        <input type="number" id="bisteckNumber" name="bisteckNumber" placeholder="¿Cuántos?">
                        <br>
                        <input type="checkbox" id="chorizo" name="chorizo" value="chorizo">
                        <label for="chorizo">Chorizo</label>
                        <br>
                        <input type="number" id="chorizoNumber" name="chorizoNumber" placeholder="¿Cuántos?">
                        <br> 
                        <input type="checkbox" id="chuleta" name="chuleta" value="chuleta">
                        <label for="chuleta">Chuleta</label>
                        <br>
                        <input type="number" id="chuletaNumber" name="chuletaNumber" placeholder="¿Cuántos?">
                        <br>  
                        <input type="checkbox" id="pastor" name="pastor" value="pastor">
                        <label for="pastor">Pastor</label>
                        <br>
                        <input type="number" id="pastorNumber" name="pastorNumber" placeholder="¿Cuántos?">
                        <br>
                        <input type="checkbox" id="campechanos" name="campechanos" value="campechanos">
                        <label for="campechanos">Campechanos</label>
                        <br>
                        <input type="number" id="campechanosNumber" name="campechanosNumber" placeholder="¿Cuántos?">
                        <br>
                    <p>Dirección del pedido</p>
                        <label for="nombre">Nombre:</label>
                        <br><br>
                        <input type="text" id="nombre" name="nombre" placeholder="¿Cómo te llamas?">
                        <br><br>
                        <label for="nombre">Telefono:</label>
                        <br><br>
                        <input type="tel" id="telefono" name="telefono" placeholder="Número de telefono" maxlength="10">
                        <br><br>
                        <label for="nombre">Dirección:</label>
                        <br><br>
                        <input type="text" id="direccion" name="direccion" placeholder="Dirección">
                        <br><br>
                    <button type="submit">Enviar pedido</button>
                        <br><br>
            </form>
    </section>
</body>
</html>
