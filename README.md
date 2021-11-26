<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto PET SHOP</title>
    <link rel="stylesheet" href="projeto.css/site.css">

</head>
<body>

    <header>
        <h1>
            <img src="img/logo-mari-e-gabi-petshop.svg" alt="logo
            Petshop Mari e Gabi">
        </h1>
    </header>

    <nav>
        <ul>
            <li><a href="#sobre">Sobre </a></li>
            <li><a href="#produto">Produto </a></li>
            <li><a href="#serviços">Serviço </a></li>
            <li id="itemContato"><a href="#contato">Contato </a></li>
        </ul>
    </nav>
    <section class="fundo-verde">
        <div class="container flex-conteiner">
            <div class="col">
                <h3>SOBRE NÓS</h3><br>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis sint sed veniam alias odio itaque 
                    doloremque vitae quia quas similique, assumenda laborum, quibusdam omnis labore in cupiditate quo, 
                    facilis placeat!
                    </p>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti maiores sed sit, deserunt quibusdam neque 
                    illo veritatis eius voluptates officia exercitationem fugiat eligendi sint. Similique velit dolor tempore 
                    numquam dolorum.</p>
            </div>
            <div class="col"><img src="img/img-sobre.jpg" alt="imagem com cachorrinho"></div>
        </div>
    </section>
    <section>
        <div class="container">
            <h2 class="texto-centralizado">Produtos</h2>
            <p class="texto-centralizado">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus maxime 
                est nam voluptate praesentium. Odit maiores delectus voluptas. Rem ex laboriosam recusandae animi veniam
                eum deleniti sed nihil amet ipsam!</p>
        </div>
        <div class="flex-conteiner">
            <article class="produto">
                <figure>
                    <img src="img/produto-1.jpg" alt="imagem-p1">
                </figure>
                <h3>Pet produto #1</h3>
                <p>R$ 150,00</p>
                <a href="" class="btn-patinha"><img src="img/patinha-preta.png" alt="">Comprar</a>
            </article>
            <article class="produto">
                <figure>
                    <img src="img/produto-2.jpg" alt="imagem-p2">
                </figure>
                <h3>Pet produto #1</h3>
                <p>R$XXXX</p>
                <a href="" class="btn-patinha"><img src="img/patinha-preta.png" alt="">Comprar</a>
            </article>
            <article class="produto">
                <figure>
                    <img src="img/produto-3.jpg" alt="imagem-p3">
                </figure>
                <h3>Pet produto #1</h3>
                <p>R$XXXX</p>
                <a href="" class="btn-patinha"><img src="img/patinha-preta.png" alt="">Comprar</a>
            </article>
        </div>
    </section>
    <section class="fundo-verde">
        <div class="container flex-conteiner">
            <div class="col">
                <h3>Serviços</h3><br>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Perferendis sint sed veniam alias odio itaque 
                    doloremque vitae quia quas similique, assumenda laborum, quibusdam omnis labore in cupiditate quo, 
                    facilis placeat!
                    </p>
                <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Deleniti maiores sed sit, deserunt quibusdam neque 
                    illo veritatis eius voluptates officia exercitationem fugiat eligendi sint. Similique velit dolor tempore 
                    numquam dolorum.</p>
            </div>
            <div class="col">
                <img src="img/img-galeria-1.jpg" alt="imagem com cachorrinho">
                <img src="img/img-galeria-2.jpg" alt="imagem com cachorrinho">
                <img src="img/img-galeria-3.jpg" alt="imagem com cachorrinho">
                <img src="img/img-galeria-4.jpg" alt="imagem com cachorrinho">
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="texto-centralizado">
                <h2>Contatos</h2><br><br>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Nobis nemo voluptatem rem incidunt eveniet fugiat 
                    sit dolor ut inventore aliquid odit necessitatibus officia quisquam, perferendis, temporibus et laboriosam 
                    repellendus excepturi.</p>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fugit porro dolorum, distinctio sit quaerat 
                    similique magnam accusantium quis! Nemo, in doloremque! Tempora, possimus facilis excepturi ullam temporibus 
                    vitae doloremque esse.</p>
            </div>
            <div class="flex-conteiner">
                <div class="col">
                    <form action="">
                        <label for="nome"><strong>Nome:</strong></label><br>
                        <input type="text" id="nome" placeholder="Insira o seu nome completo"><br>
                        <label for="email"><strong>E-mail:</strong> </label><br>
                        <input type="email" id="email" placeholder="exemplo@teste.com"><br>
                        <label for="telefone"><strong>Telefone:</strong></label><br>
                        <input type="tel" id="telefone" placeholder="(00) 0 0000-0000"><br>
                        <label for="assunto"><strong>Assunto:</strong></label><br>
                        <input type="text" id="assunto" placeholder="Insira o seu assunto de mensagem"><br>
                        <label for="msg"><strong>Mensagem:</strong></label><br>
                        <textarea name="msg" id="msg" cols="30" rows="10" placeholder="Insira sua mensagem"></textarea>
                    </form>
                </div>
                <div class="col">

                </div>
            </div>
        </div>
    </section>

    
</body>
</html>
