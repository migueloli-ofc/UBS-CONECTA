<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UBS CONECTA</title>
    <link rel="shortcut icon" href="UBSCONECTA.png.png" type="image/x-icon">
  <link rel="https://migueloli-ofc.github.io/UBS-CONECTA/projeto.html">
  <link rel="https://migueloli-ofc.github.io/UBS-CONECTA/unidades.html">
  <link rel="https://migueloli-ofc.github.io/UBS-CONECTA/duvidas.html">
  <link rel="https://migueloli-ofc.github.io/UBS-CONECTA/ficha.html">
    <style>
        body{
            background-image: url(Fundokkkk.png);
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            background-position: bottom;
            margin: 0;
            
        }
        .cabecalho{
            background-color: #f9172b;
            width: 100%;
            height: 50px;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #caf0f8;
            font-size: 17px;
            font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        .sub-links{
            display: flex;
            justify-content: center;
            align-items: center;
            margin-left: 35%;
            background-color: transparent;
            width: 450px;
            height: 30px;
        }
        .botao-ubs, .duvidas, .ficha, .sobre-nos{
            width: 80px;
            height: 25px;
            margin-right: 5px;
            color: white;
            background-color: transparent;
            border: 2px solid transparent;
            cursor: pointer;
            font-size: 14px;
        }
        .sobre-nos, .botao-ubs{
            width: 80px;
        }
        .ficha{
            width: 130px;
        }
        .botao-ubs:hover, .duvidas:hover, .ficha:hover, .sobre-nos:hover{
            background-color: rgba(255,255,255,0.9);
            border: 2px solid transparent;
            border-bottom: 2px solid #008000;
            border-top: 2px solid #023e8a;
            color: black;
        }
        .corpo{
            margin-right: 50px;
            margin-left: 50px;
            margin-bottom: 10px;
            color: #343a40;
            text-align: center;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 20px;
        }
        b{
            color: green;
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif
        }
        b:hover{
            color: #f9172b;
        }
        #ft1{
            margin-right: 165px;
        }
        #ft2{
            margin-left: 95px;
        }
        #ft1, #ft2{
            border-radius: 20px;
            width: 480px;
            height: 300px;
        }
        #ft1:hover,#ft2:hover{
            transform: scale(1.1);
            transition: 0.2s;
        }
        .bem-vindo:hover{
            color: #008000;
        }
        .informacoes1{
            background-color: white;
            border-radius: 15px;
            display: flex;
            padding: 10px;
            justify-content:flex-end;
            align-items:center;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 25px;
            text-align:justify;
            color: #343a40;
        }
        .informacoes1:hover{
            background-color: rgba(255,255,255,0.8);
        }
        #logo1{
            width: 300px;
            height: 300px;
        }
        .logo{
            margin-left: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        #negrito1{
            color: #f9172b;
        }
        #negrito2{
            color: #023e8a;
        }
        .linha1{
            margin-left: 35px;
            height: 200px;
            border: 1px solid #fafa00;
            box-shadow: 10px 5px 5px black;
        }
        .linha-horizontal{
            width: 90%;
            margin-top: 30px;
            margin-left: auto;
            border: 1px solid transparent;
            background-color: red;
            border-radius: 50px;
            height: 1px;
        }
        .informacoes2{
            background-color: white;
            border-radius: 15px;
            display: flex;
            padding: 10px;
            justify-content:flex-end;
            align-items:center;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 25px;
            text-align:justify;
            color: #343a40;
        }
        .informacoes2:hover{
            background-color: rgba(255,255,255,0.8);
        }
        .imagem{
            margin-right: 50px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        #logo2{
            margin: 20px;
            width: 300px;
            height: 300px;
            border-radius: 15px;
        }
        #logo1:hover, #logo2:hover{
            transform: scale(0.9);
            transition: 0.3s;
        }
        .linha2{
            margin-right: 30px;
            height: 270px;
            border: 1px solid #023e8a;
            box-shadow: 10px 5px 5px black;
        }
        ol{
            margin: 15px;
            text-align:left;
            background-color: #023e8a;
            color: white;
            border-radius: 15px;
            padding: 5px 5px 5px 50px;
        }
        .informacoes3{
            background-color: white;
            border-radius: 15px;
            display: flex;
            padding: 10px;
            justify-content:flex-end;
            align-items:center;
            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 25px;
            text-align:justify;
            color: #343a40;
        }
        .informacoes3:hover{
            background-color: rgba(255,255,255,0.8);
        }
        .linha3{
            margin-left: 35px;
            height: 200px;
            border: 1px solid #008000;
            box-shadow: 10px 5px 5px black;
        }
        .texto1{
            font-family: cursive;
            font-size: 27px;
            text-shadow: 10px 10px 15px black;
        }
        footer{
            padding: 3px;
            height: 80px;
            background-color: black;
            color: #fafa00;
            text-align: center;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 25px;
        }
        .botao-home{
            background-color: transparent;
            border: none;
            width: 70px;
            height: 70px;
            cursor: pointer;
            margin-top: 50px;
        }
        .botao-home:hover, .botao-ficha:hover,.botao-ficha1:hover{
            transform: scale(1.3);
            transition: 0.2s;
        }
        .botao-ficha{
            background-color: #f9172b;
            border: 2px solid #343a40;
            width: 150px;
            height: 30px;
            cursor: pointer;
            font-size: 17px;
            color: white;
            float: right;
        }
        .botao-ficha1{
            background-color: #f9172b;
            border: 2px solid #343a40;
            width: 150px;
            height: 30px;
            cursor: pointer;
            font-size: 17px;
            color: white;
            float: left;
        }
    </style>
</head>
<body>
    <div class="cabecalho">
        <img src="Logo UBSCONECTA1 - Canva.png" width="100px" height="100px" alt="logo-ubs-conecta">
        <h1>UBS CONECTA</h1>
        <div class="sub-links">
        <button onclick="abrirHome('projeto.html')" class="sobre-nos">Início</button>
        <button onclick="abrirUbs('unidades.html')" class="botao-ubs" >UBS's</button>
        <button onclick="abrirContatos('duvidas.html')" class="duvidas">Dúvidas?</button>
        <button onclick="abrirFicha('ficha.html')" class="ficha">Faça já sua ficha</button>
            <script>
                function abrirHome(sobre){
                    window.location.href = sobre;
                }
                function abrirUbs(ubs){
                    window.location.href = ubs;
                }
                function abrirContatos(duvidas){
                    window.location.href = duvidas;
                }
                function abrirFicha(ficha){
                    window.location.href = ficha;
                }
            </script>
    </div>
    </div>

    <div class="corpo">
        <h1 class="bem-vindo">Sistema de criação de fichas de atendimento. <br> <b>UBS CONECTA</b> ajudando quem mais precisa!</h1>
        <br><br>
        <div class="fotos">
            <img src="https://www.shutterstock.com/image-photo/perfect-white-toothy-smile-after-600nw-2570358635.jpg" id="ft1" alt="foto-dentista" title="Dentista no consultório" >
            <img src="https://d2ks5cytjcldab.cloudfront.net/conteudo/363-48a9348b1f00b8c7c5130f19ecc24dde.jpg" id="ft2" alt="foto-medico" title="Médico sorrindo" >
        </div>
        <br><br>
        <div class="informacoes1">
            <div class="texto">
                 <p id="inf1">O site <b>UBS CONECTA</b> foi criado para solucionar um dos maiores desafios das Unidades Básicas de Saúde: os <b id="negrito1">atrasos</b> e <b id="negrito1">dificuldades na criação das Fichas de Atendimento</b>.
                 Pensando em facilitar a rotina dos pacientes e melhorar o fluxo de atendimento, desenvolvemos uma plataforma moderna, simples e totalmente acessível.</p>
            </div><hr class="linha1">
            <div class="logo">
                <img src="UBSCONECTA.png.png" title="Logomarca UBS CONECTA" id="logo1" >
            </div>
        </div>
        
            <hr class="linha-horizontal">
            <br>
            <div class="informacoes2">
            <div class="imagem">
                <img src="Imagem-celular1.png" title="Celular com a logo UBS CONECTA" id="logo2">
            </div><hr class="linha2" heigth="200px" width="0px">
            <div class="texto">
                <p id="inf1">Com o <b>UBS CONECTA</b>, sua ficha pode ser feita de casa, pelo celular ou computador.
                Nada de perder tempo indo até a UBS só para descobrir que sua consulta não será naquele dia.
                <b id="negrito2">Você</b> se organiza melhor, e a <b id="negrito2">UBS</b> também!

               <br>Nosso sistema foi desenvolvido para todos os cidadãos e profissionais.
                    </p>
                <ol type="I">
                    <li>Pacientes ganham agilidade.</li>
                    <li>Profissionais têm acesso ampliado e trabalham com mais eficiência.</li>
                    <li>Todos saem beneficiados.</li>
                </ol>
                </div>
            </div>
            <hr class="linha-horizontal">
            <br>
            <div class="informacoes3">
            <div class="texto">
                 <p id="inf1">O <b>UBS CONECTA</b> reforça o compromisso com a melhoria contínua da <b id="negrito1">saúde pública</b>, oferecendo uma ferramenta que promove <b id="negrito2">agilidade</b>, <b id="negrito2">transparência</b> e <b id="negrito2">acessibilidade</b> contribuindo para um serviço mais organizado e de melhor qualidade.</p>
            </div><hr class="linha3">
            <div class="logo">
                <img src="Conexão1.png" title="Simbolo de conexão" id="logo1" >
            </div>
        </div>
        <hr class="linha-horizontal">
        <div class="texto1">
            <h3>UBS Conecta - conectando pessoas, saúde e tecnologia em um só lugar.</h3>
        </div>
                <button onclick="abrirFicha('ficha.html')" class="botao-ficha1">Faça já sua ficha</button>
                <button onclick="abrirUbs('projeto.html')" class="botao-home" ><img src="seta-para-cima (2).png" width="60px" height="60px"></button>
                <button onclick="abrirFicha('ficha.html')" class="botao-ficha">Faça já sua ficha</button>
        </div>
    <footer>
        <h5>Feito por Miguel Oliveira e Letícia Moura - Todos os direitos reservados - 2025</h5>
    </footer>
</body>
</html>
