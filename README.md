# De Pátria para Pátria

## Visão geral

- Descrição
- Tecnologias e Técnicas
- GitHub Pages

### Descrição

O projeto mostra as cidades de origem de alguns funcionários do Practicum, com imagens ilustrativas de cada uma dessas cidades, acompanhada de uma breve descrição sobre o local. O principal desafio deste projeto foi a implementação de um design responsivo/adaptativo junto de um aninhamento por grade. Logo, todos os elementos devem ser exibidos corretamente em tamanhos de tela populares, em conformidade com o que é apresentado no Figma.

### Tecnologias e Técnicas

#### Figma

Depois de três projetos desafiadores ao longo desta caminhada, pela primeira vez o Figma entra em cena, apresentando uma amostra do resultado final do website nas três resoluções apresentadas, juntamente com a aparência quando alguns elementos estiverem no estado hover.

#### TinyPNG

Prezando por um layout, além de responsivo, leve, foi pensado na otimização das imagens exportadas do Figma. Assim, pode-se garantir que a página terá mais facilidade no carregamento.

#### Valores relativos

Uma das principais técnicas usadas para tornar blocos responsivos, foi o uso de valores relativos, como: "%", "rem" e valores decimais para a altura de linha, e propriedades, como: max-width e max-height.

#### Grid Layout

Neste projeto, o layout de grade ganha espaço, dominando grande parte do aninhamento de blocos e elementos, sendo o desafio principal a ser trabalhado dentro do projeto.

#### Flexbox

Para complementar o aninhamento de blocos e elementos, dessa vez, o flexbox foi usado apenas para os "blocos secundários", que estão dentro de outros blocos.

#### Consulta de Mídia

Pela primeira vez, foi implementado o uso da consulta de mídia para a construção do layout correspondente à resolução de tela apresentada no projeto. Neste projeto, foram usados três pontos de interrupção: um ponto médio entre 320-768px, 768-1280px e por fim de 1280px-superior.

#### Fontes Externas

Conforme requerido pelo projeto, neste projeto foi usado a fonte 'Inter', que foi exportada através de @font-face.

#### Metodologia BEM

Mais do que construir o que poderá ser visto na tela, no projeto é pensado também na organização do projeto como um todo, isso se dando na separação do código em diferentes arquivos .css, armazenados em diferentes diretórios: blocks (contém toda a estilização dos blocos separados em vários arquivos .css correspondente a cada um deles.), images (contém todas as imagens do projeto), pages (contém index.css que conecta todos os blocos.css), e por fim vendor (contém materiais externos para o projeto, como fontes e normalize.css)

### GitHub Pages

Acredito que depois de ter um breve resumo do que se trata o projeto, e das técnicas/tecnologias usadas para a sua construção, nada será mais esclarecedor do vendo com os próprios olhos o resultado final do website. Você poderá conferir através do link: https://elionayhaddad.github.io/web_project_3_ptbr/
