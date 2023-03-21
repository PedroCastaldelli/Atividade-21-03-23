# Atividade-21-03-23
Site institucional

-------------------------------------------------------------------------------
--html--

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aquatec | Página inicial</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="header">
        <div class="container">
            <h1 class="titulo">Aquatec</h1>
            <ul class="navbar">
                <li><a href="">Início</a></li>
                <li><a href="">Simulador</a></li>
                <li>|</li>
                <li><a href="">Login</a></li>
                <li><a href="">Cadastro</a></li>
            </ul>
        </div>
    </div> 

    <div class="banner">
        <div class="container">
            <p>Preservando <span>hoje</span> para existirem <span>amanhã</span></p>
        </div>
    </div>

    <div class="social">
        <div class="container">
            <div class="boxes">
                <div class="box">
                    <img src="./planet-earth_color.png" alt="">
                    <h4></h4>
                    <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Aliquam asperiores, placeat qui ipsa recusandae, maxime et explicabo laboriosam fugit, ad soluta doloremque est molestias voluptas voluptatum nisi doloribus nesciunt facere?</p>
                </div>
                <div class="box">
                    <img src="./lightbulb_color.png" alt="">
                    <h4></h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Fugit odit placeat voluptate eum totam doloremque debitis pariatur reprehenderit rerum! Voluptatibus repudiandae nemo officiis voluptatum dolorem minima exercitationem obcaecati, laborum repellendus.</p>
                </div>
                <div class="box">
                    <img src="./growth_color.png" alt="">
                    <h4></h4>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo pariatur dolorum, consequuntur eos nam esse labore ullam non harum, voluptates rerum et aperiam! Fuga accusamus minus alias, nisi laudantium dolore.</p>
                </div>
            </div>
        </div>
    </div>
    
</body>
</html>

----------------------------------------------------------------------------------------------------
--css--

body {
    margin: 0;
    padding: 0;
}


/* Header */

.header {
    background-color: black;
    border: 3px solid #32b9cd;
}

.container {
    display: flex;
    width: 80%;
    margin: auto;
}

.header .container {
    display: flex;
    justify-content: space-between;

}

.titulo {
    color: #32b9cd;
    font-weight: 500;
}

.navbar {
    display: flex;
    width: 300px;
    align-items: center;
    list-style: none;
    justify-content: space-between;
}

.navbar li,
.navbar a {
    color: #e3b062;
    background-size: cover;
}


/* Banner */

.banner {
    background-image: url('./bg-jelly-fish-para_outras_pags.png');
}

.banner .container {
    height: 500PX;
    justify-content: center;
    align-items: center;
    color: white;
}

.banner P {
    width: 288px;
    font-size: 2.2rem;
}

.banner span {
    font-weight: 800;
}


/* Missão, visão e valores */


.social {
    background-color: #e5e5e5;
}

.boxes {
    display: flex;
    padding: 50px 0;
    gap: 8px;
}

.box {
    display: flex;
    flex-direction: column;
    align-items: center;

}

.box img {
    width: 170px;
}
