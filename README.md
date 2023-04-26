# Slide
Este é um projeto simples de um slide de imagens criado utilizando `HTML`, `CSS` e `JavaScript`. O slide permite a visualização de várias imagens através de uma navegação por botões ou por movimentos de touch e mouse.

## Instalação
Para utilizar este slide, basta clonar o repositório ou baixar os arquivos necessários em sua máquina.

`git clone https://github.com/seu-usuario/slide-curso-js.git`

## Utilização
Para utilizar o slide, basta abrir o arquivo index.html em um navegador web. Você pode modificar as imagens exibidas e a quantidade de imagens alterando os arquivos de imagem presentes na pasta img. Além disso, também é possível alterar a aparência do slide modificando o arquivo style.css.

Caso deseje utilizar o slide em outro projeto, basta importar a classe Slide presente no arquivo slide.js e instanciá-la, passando como parâmetros o seletor do slide e o seletor do wrapper do slide, como no exemplo abaixo:

`import { Slide } from "./slide.js";`

`const slide = new Slide(".slide", ".slide-wrapper");`

`slide.init();`

## Créditos
Este slide foi desenvolvido durante o curso de JavaScript da Origamid. Visite o slide : https://bhzdev.github.io/slide/.
