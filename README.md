# RPG Class Selector

Este é um projeto web simples que exibe uma seleção aleatória de classes de RPG como cartas interativas.

## Funcionalidades

-   Exibe 15 cartas de classe selecionadas aleatoriamente.
-   As chances de cada raridade de classe aparecer são ponderadas (Comum, Rara, Épica, Lendária, Única).
-   As cartas flutuam lentamente na tela.
-   Ao clicar em uma carta, ela vira para revelar o nome e a descrição da classe.
-   Todas as outras cartas desaparecem gradualmente com um efeito de desvanecimento lento.

## Tecnologias Utilizadas

-   HTML5
-   CSS3
-   JavaScript

## Como Usar

1.  Clone este repositório para o seu computador.
2.  Abra o arquivo `class_selector.html` em qualquer navegador web moderno.

Não é necessário servidor web nem instalação de dependências.

## Personalização

-   Você pode modificar a lista de classes, descrições e raridades diretamente no script JavaScript dentro do arquivo `class_selector.html`.
-   Os pesos das raridades na função `selectRandomClasses` podem ser ajustados para alterar as chances de cada raridade aparecer.
-   O número de cartas exibidas (atualmente 15) pode ser alterado na chamada da função `selectRandomClasses` na função `initializeCards`.
-   As cores e estilos das cartas podem ser modificados no bloco `<style>` do arquivo `class_selector.html`.
