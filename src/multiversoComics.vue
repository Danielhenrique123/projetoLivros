<template>

  <!DOCTYPE html>
  <html lang="pt-br">

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="/main.css">


    <title>Muntiverso comics</title>

  </head>

  <body>

    <header class="header">

      <div class="logo">
        <h1>Mutiverso comics</h1>
      </div>

      <div class="pesquisa">
        <input type="text" placeholder="Pesquisar...">

        <a href="#"><i class="fa-solid fa-magnifying-glass"></i></a>

      </div>

      <nav class="navegacao">
        <ul>
          <li title="Termos"><a href="#">Termos</a></li>
          <li title="Equipes"><a href="#">Equipes </a></li>
          <li title="Envios"><a href="#">Envios</a></li>
          <li title="Devoluçoes"><a href="#">Devoluções</a></li>
          <li><a href="/src/assets/carinho/carinho.html"><i
                class="fa-solid fa-cart-shopping"></i></a></li>



          <div class="divisao"> </div>

          <li><a href="#"><i class="fa-solid fa-heart"></i></a></li>

          <div class="divisao"> </div>

          <li><a href="#"><i class="fa-solid fa-user"></i></a></li>
        </ul>

      </nav>

    </header>

    <div class="linha"></div>

    <main>

      <section class="apresentacao">


        <h2>Bem-vindo ao Mutiverso Comics</h2>
        <div>
          <a href="#">Autor da marvel</a>
        </div>


        <h1>Stanley Martin Lieber</h1>

        <p>
          Quem é que não conhece Stan Lee? Certamente um dos maiores nomes dos quadrinhos em todos os tempos, até quem nunca leu um gibi na vida sabe que ele foi, durante décadas, a cara da Marvel Comics. Foi também o criador do Homem-Aranha, Quarteto Fantástico, Homem de Ferro, Demolidor, Hulk, Thor, entre tantos outros.
        </p>
        <div class="botao"><a href="#">Acessar página do autor</a></div>

        <!-- //////// FALTA COLOCAR A IMG ///////-->
      </section>
      <div class="linha3"></div>

      <section class="indicacao">
        <div>
          <nav>
            <ul>
              <li>
                <a href="#"> <i class="fa-solid fa-truck"></i> Frete grátis para SC</a>
              </li>

              <div class="reverce"></div>

              <li>
                <a href="#"><i class="fa-solid fa-star"></i> Livros recomendados</a>
              </li>

              <div class="reverce"></div>

              <li>
                <a href="#"><i class="fa-solid fa-book-open"></i> Mais vendidos <div class="sublinhado"></div></a>

              </li>
            </ul>
          </nav>
        </div>

      </section>

      <div class="linha3"></div>

      <section class="comics">

        <h1>
          Lansamentos novos
        </h1>
        <div class="quadrinhos">

          <nav>

            <ul class="ajuste">

              <li>
                <img src="/public/images/images.jpeg" alt="#" class="invencivel">

                <h3>Invencible</h3>

                <p>Robert Kirkman</p>

                <div>

                     <div>

                  <p>Preço- R$ 15.50</p>

                  <button onclick="adicionarItem('invensivel')"> <i class="fa-solid fa-cart-shopping"></i> Compra
                  </button>
                </div>
                </div>
              </li>



              <li>
                <img src="/public/images/images (1).jpeg" alt="#">
                <h3>Guerra civil</h3>
                <p>Stanley Martin Lieber</p>

                <div>

                  <p>Preço- R$ 15.50</p>

                  <button onclick="adicionarItem('guera civil')"> <i class="fa-solid fa-cart-shopping"></i> Compra
                  </button>
                </div>
              </li>
              <li>
                <img src="/public/images/images (2).jpeg" alt="#">

                <h3>Homem aranha</h3>

                <p>Stanley Martin Lieber</p>

                <div>

                  <p>Preço- R$ 10.00</p>

                  <button onclick="adicionarItem('homen aranha')"> <i class="fa-solid fa-cart-shopping"></i> Compra
                  </button>
                </div>
              </li>
            </Ul>
          </nav>

        </div>
        <div class="quadrinhos">

          <nav>

            <ul class="ajuste">

              <li class="theboys">
                <img src="/public/images/capa-v03.jpg" alt="#" class="invencivel">

                <h3>the boys vol.3</h3>

                <p>Darick Robertson</p>

                <div>

                  <p>Preço- R$ 63.96</p>

                  <button onclick="adicionarItem('the boys')"> <i class="fa-solid fa-cart-shopping"></i> Compra
                  </button>
                </div>
              </li>



              <li class="batman">
                <img src="/public/images/Batman06Rebirth.jpg" alt="#">
                <h3>batman</h3>
                <p>Major Malcolm Wheeler-Nicholson</p>

                <div>

                  <p>Preço- R$ 50.00</p>

                  <button onclick="adicionarItem('batman')"> <i class="fa-solid fa-cart-shopping"></i> Compra
                  </button>
                </div>
              </li>

              <li class="invensivel2">
                <img src="/public/images/unnamed.jpg" alt="#">

                <h3>Invencible vol.3</h3>

                <p>Robert Kirkman</p>

                <div>

                  <p>Preço- R$ 60.00</p>

                  <button onclick="adicionarItem('invencivel 2')"> <i class="fa-solid fa-cart-shopping"></i> Compra
                  </button>
                </div>
              </li>
            </Ul>
          </nav>

        </div>



      </section>
    </main>


    <footer>
      <div class="footer-section">
        <h4>Multiverso comics</h4>
        <p>Conectando valor e fidelidade em um só lugar.</p>
      </div>

      <div class="footer-section">
        <h4>Contatos</h4>
        <ul>
          <li><a href="#"><i class="fa-solid fa-phone"></i></a> (+55) 47 99986-7741</li>
          <li><a href="#"><i class="fa-solid fa-envelope"></i></a> multiversocomics22@gmail.com</li>

        </ul>
      </div>

      <div class="footer-section">
        <h4>Redes Sociais</h4>
        <div class="social-icons">
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-instagram"></i>
          <i class="fab fa-twitter"></i>

        </div>
      </div>
      <div class="linha3"></div>

      <div class="footer-bottom">
        &copy; 2025 Multiverso Comics. Todos os direitos reservados.
      </div>
    </footer>

  </body>

  </html>

</template>
