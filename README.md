Vinheria Agnello

#Projeto
A Vinheria Agnello é uma vinheria familiar localizada em SP, que oferece uma seleção exclusiva de vinhos artesanais e importados.  
O projeto tem como objetivo apresentar a história, os produtos e as unidades da vinheria, além de facilitar o contato e reservas online.
Este site foi desenvolvido como parte de um estudo/prática em HTML, CSS e organização de front-end.

#Estrutura do Projeto
O site é composto pelas seguintes páginas:
- index.html = Página inicial com destaque para a Vinheria.  
- sobre_nos.html = História da vinheria e valores da marca.  
- produtos.html = Catálogo de vinhos com imagens, descrições e preços.  
- contato.html = Formulário de contato e informações de atendimento.  
- unidades.html = Lista de unidades da Vinheria com endereço, telefone e botão para reservar mesa.  

#Estrutura de diretórios:
cp-front-main/
│──scr
│   │── assets
│   |   |── Imagens
│   │
│   │── css
│   │   │──animation
│   │   │   |──contato.css
│   │   │   |──produtos.css
│   │   │   |──sobrenos.css
│   │   │   |──unidades.css
│   │   │
│   │   │──style
│   │   │   │──uni_contato.css
│   │   │   │──uni_produtos.css
│   │   │   │──uni_sobrenos.css
│   │   │   │──uni_unidades.css
│   │   │
│   │   |──style.css
│   │
│   │──pages
│       │── sobre_nos.html
│       │── produtos.html
│       │── contato.html
│       │── unidades.html
│      
│── index.html
│── README.md

Efeitos Visuais

O projeto utiliza diversos recursos visuais para enriquecer a experiência do usuário:

Pseudo-classes
:hover em .caixa-conteudo, .vinicola-img, .btn-reserva, .botao-cta para aplicar transformações e efeitos de destaque ao passar o mouse.
:hover article para revelar conteúdo adicional com transição suave.

Pseudo-elementos
::before e ::after em .caixa-conteudo para criar camadas visuais com gradientes e bordas animadas que aparecem ao interagir com o conteúdo.

Animações
@keyframes ondasVinho: animação aplicada ao fundo .fundo-animado, simulando ondas suaves com rotação e variação de opacidade, criando um efeito elegante e contínuo.

Esses efeitos foram aplicados com transições suaves, transformações visuais e camadas sobrepostas.

Integrantes:
- Yuri Fukamachi — RM: 567314  
- Kenzo Mimura — RM: 568158  
- Michel Benchimol — RM: 567345

O site está disponível no GitHub:
https://yurifukamachi07-beep.github.io/cp-2front/