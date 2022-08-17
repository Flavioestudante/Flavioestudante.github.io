# Flavioestudante.github.io
Curriculo Jornada Dev
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum</title>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Hubballi&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/1c7eb9d53f.js" crossorigin="anonymous"></script>
    <style>
        #header {
            background-color: steelblue;
            margin-top: 50px;
            margin-bottom: 50px;
            font-family: 'Hubballi', cursive;
        }
        #nameAndTitle {
            background-color: white;
            width: 450px;
            margin: 0 auto;
            text-align: center;
        }
        #nameAndTitle h1, h2 {
            margin: 0;
        }
        h1, h2, h3 {
            text-transform: uppercase;
        }
        #contact{
            list-style-type: none;
        }
        #contact i {
            width: 30px;
            color: steelblue;
        }
        #container {
            display: grid;
            grid-template-columns: 30% auto;
            grid-column-gap: 20px;
        }
        #sidebbar, content  {
            display: flex;
            flex-direction: column;
            row-gap: 20px;
        }
        .card h3 {
            font-family: 'Hubballi', cursive; 
        }
        .card {
           font-family: Montserrat;
           border: 1px solid rgb(164, 170, 175);
           border-radius: 15px;
           padding: 20px;
        }
    </style>
</head>
<body>
   <div id="header">
        <div id="nameAndTitle">
            <h1>Flavio Rodrigues de Sousa</h1>
            <h2>Operador de Produção</h2>
        </div>
   </div>
   <div id="container">
        <div id="sidebar">
            <div class="card">
                <h3>Contato</h3>
                <ul id="contact">
                    <li><i class="fa-solid fa-envelope"></i> flavio-rodrigues77@hotmail.com</li>
                    <li><i class="fa-solid fa-phone"></i> (83) 99600-0938</li>
                    <li><i class="fa-solid fa-location-dot"></i> Campina Grande, PB</li>
                </ul>
            </div>
            <div class="card">
                <h3>Skills</h3>
                <ul>
                    <li>html</li>
                    <li>css</li>
                    <li>javascript</li>
                </ul>
            </div>
            <div class="card">
                <h3>Formação Acadêmica</h3>
                <ul>
                    <li>Introdução a HTML e CSS - 5 Horas </li>
                    <li>Python Hashtag - Cursando</li>
                    <li>Power BI Hashtag - Cursando</li>
                </ul>
            </div>
            <div class="card">
                <h3>Links</h3>
                <ul>
                    <li><a target="_blank" href="https://www.linkedin.com/in/fl%C3%A1vio-rodrigues-945a66233/">Linkedin</a></li>
                    <li><a target="_blank" href="https://www.facebook.com/flaviorodriguesdesousa">Facebook</a></li>
                </ul>
            </div>
        </div>
        <div id="content">
            <div class="card">
                <h3>Sobre Mim</h3>
                <p>
                    Olá, me chamo Flávio tenho 35 anos, sou de Aurora-CE mas atualmente moro na cidade Brejo Santo-CE,
                     estou embusca de novas oportunidades
                    atualmente estou estudando Python, excel e Power BI pela Hashtag.
                </p>
            </div>
            <div class="card">
                <h3>Experiência Profissionais</h3>
                <p>
                    <b>Alpargatas S.A - Mai/21 a Ago/22</b><br>
                    Misturar resíduo para fabricação das palmilhas
                    <ul>
                        <li>Operador de Mistura</li>
                    </ul>
                </p>
                <p>
                    <b>Tess LTDA - Set/19 a Mai/21</b><br>
                    Montagem de calçados, Separação de Pedidos
                    <ul>
                        <li>Operador de Produção</li>
                        <li>Separação para conferência</li>
                    </ul>
                </p>
                <p>
                    <b>International Paper - Abr/13 a Fev/19</b><br>
                    Operador de Máquinas, Cobre férias de operadores
                    <ul>
                        <li>Operador de Produção 1</li>
                        <li>Separação de pedidos</li>
                    </ul>
                </p>
            </div>
        </div>
   </div>
</body>
</html>
