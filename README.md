# alurabok

<body>
    <header class="cabeçalho">
        <span class="cabeçalho__menu-hamburguer"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks">
        <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos"></a>
        <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras"></a>
        <a href="#"><img src="img/Usuario.svg" alt="Meu perfil"></a>
    </header>
</body>

.cabeçalho__menu-hamburguer {
    width: 24px;
    height: 24px;
    display: inline-block;
    background-image: url("../img/Menu.svg");
    background-repeat: no-repeat;
    background-position: center;
}

<header class="cabeçalho">
    <div class="container">
        <span class="cabeçalho__menu-hamburguer container__imagem"></span>
        <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem">
    </div>
    <div class="container">
        <a href="#"><img src="img/Favoritos.svg" alt="Meus favoritos" class="container__imagem"></a>
        <a href="#"><img src="img/Compras.svg" alt="Carrinho de compras" class="container__imagem"></a>
        <a href="#"><img src="img/Usuario.svg" alt="Meu perfil" class="container__imagem"></a>
    </div>
</header>

<div class="container">
  <input type="checkbox" id="menu" class="container__botao" />
  <label for="menu">
    <span class="cabeçalho__menu-hamburguer container__imagem"></span>
  </label>
  <img src="img/Logo.svg" alt="Logo da AluraBooks" class="container__imagem" />
</div>

<label for="menu">
  <span class="cabeçalho__menu-hamburguer container__imagem"></span>
</label>

<ul class="lista-menu">
</ul>


<ul class="lista-menu">
  <li class="lista-menu__titulo">Categorias</li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Programação</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Front-end</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Infraestrutura</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Business</a>
  </li>
  <li class="lista-menu__item">
    <a href="#" class="lista-menu__link">Design & UX</a>
  </li>
</ul>

.cabecalho {
  background-color: var(--branco);
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: relative;
}

:root {
  --cor-de-fundo: #ebecee;
  --branco: #ffffff;
  --laranja: #eb9b00;
  --azul-degrade: linear-gradient(97.54deg, #002f52 35.49%, #326589 165.37%);
}

.lista-menu__link {
  background: var(--azul-degrade);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  text-transform: uppercase;
}
