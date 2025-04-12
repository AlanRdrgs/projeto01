<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario</title>
    <style>
          body {
            margin: 0;
            height: 400px;
            font-family: Arial, sans-serif;
        }

        .topo {
            color: white;
            background-color: #b61c1c;
            padding: 18px;
            text-align: center;
        }

        nav {
            background-color: #ffccbb;
            color: rgb(5, 5, 5);
            text-align: center;
            padding: 5px;
        }

        nav a {
            padding-left: 10px;
            text-decoration: none;
            color: black;
        }

        nav a:hover {
            color: #b61c1c;
            font-weight: bold;
        }

        footer {
            padding: 10px;
            background-color: #b61c1c;
            text-align: center;
            color: white;
            margin-top: 75px;
           
            
        }

        .foot {
            color: white;
            
            text-decoration: none;
        }

        .foot:hover {
            text-decoration: underline;
        }

        .card{
            width: 300px;
            border-radius: 20px;
            border: 1px solid rgb(238, 234, 234);
            text-align: justify;
            padding: 80px;
            margin: 0%;
            background-color: white;
            transition: transform 0.5s ease;
            transform:  background-color 0.5 ease;
            box-shadow: 2px 2px 5px rgb(96, 93, 93);
         
        }

        .container {
            display: flex;
            justify-content: center;
            height: 100%;
            align-items: center;
            padding: 50px;

        }
        .card h2{
            text-align: center;
            color: green;
        }
        #email{
            width: 300px;
            margin: 10px;
             border-radius:3px;
        }
        #senha{
            width: 300px;
            margin: 10px;
             border-radius:3px;
        }

        button{
            margin: 10px;
            width: 300px;
            text-align: center;
            background-color: green;
            color: white;
            border-radius:3px;
        
        }
        label{
            margin: 10px;
        }

        main {
            height:100%;
            padding: 0%;
        }
        input{
            border-radius: 1%;
            
        }
        form{
            margin-bottom: 10;
        }
       
       
        
    </style>
</head>

<body>
    <header>
        <div class="topo">
            <h1>Restaurante Sabor Brasil</h1>
            <p>O verdadeiro sabor da nossa terra</p>
        </div>
        <nav>
            <a href="index.html">Início</a>
            <a href="pratos.html">Pratos</a>
            <a href="bebidas.html">Bebidas</a>
            <a href="cadatro.html">Cadastro</a>
            <a href="login.html">Login</a>
        </nav>
    </header>

    <main>


        <section class="container">

            <section class="card">
                <h2>Login</h2>  <br>

                <form action="">
                    <label for="email">E-mail: </label><br>
                    <input type="email" id="email" name="email" required="required" placeholder="exemplo@mail.com"><br>
    
                    <label for="senha">Senha: </label><br>
                    <input type="password" id="senha" name="senha"><br>
    
                    <button input type="submit"> Enviar </button>
    
                </form>
                

            </section>
        </section>

            </form>
        </div>
    </main>







    <footer>
        <p>Restaurante Sabor Brasil | Todos os direitos reservados</p>

        <div class="redes"><a href="" class="foot">Facebook</a> | <a href="" class="foot">Instagram</a> | <a href=""
                class="foot">Whatsapp</a></div>
    </footer>
</body>

</html>