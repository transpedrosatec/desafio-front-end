# Desafio Front-end Transpedrosa
Primeiramente, obrigado pelo seu interesse em trabalhar na equipe de tecnologia e inovação na frente de desenvolvimento! Abaixo você encontrará todos as informações necessárias para iniciar o seu teste.

## Avisos iniciais
- Leia com atenção todo o documento antes de começar;
- Tente seguir o máximo possível das instruções do teste;
- Crie um repositório público em seu GitHub pessoal para a entrega do teste e faça todos seus commits por lá;
- Você poderá consultar fontes externas como Stackoverflow, Documentações oficiais, Google ou outros projetos pessoais para a realização do teste;
- Fique a vontade para tirar qualquer dúvida com os recrutadores.

## Projeto: Relatório de Sobra e Falta
O desafio consiste em desenvolver um sistema para disponibilizar e preencher o relatório de sobra e falta que os motoristas devem completar em todas as suas operações de descarga. No processo, o motorista carrega seu caminhão com combustível em uma base e entrega o produto no posto de gasolina conforme sua rota pré-determinada. Durante a transferência do combustível, o motorista deve anotar, de acordo com o pedido da rota, se a quantidade de produto que chegou ao cliente foi maior, menor ou exatamente o esperado. Por exemplo, se o pedido foi de 10 mil litros e o motorista descarregou apenas 9.975, isso quer dizer que houve uma falta de 25 litros do produto. Do mesmo modo, se houve uma descarga de 10.010 litros, houve uma sobra de 10 litros.  
Além de registrar as sobras e faltas, o motorista também deve armazenar os comprovantes das descargas realizadas. Portanto, a aplicação deve incluir uma interface que permita ao motorista preencher o relatório de forma clara e intuitiva, onde ele possa visualizar facilmente as informações de sobra e falta. Além disso, deve ser possível fazer o upload e a recuperação dos comprovantes de maneira simplificada, garantindo que todos os dados sejam acessíveis e organizados.

### Requisitos do projeto
A seguir estão algums requisitos que são importantes para o funcionamento do projeto:
- Os motoristas deve informar, para a descarga, os seguintes campos: `Cliente`, `Posto`, `Data e hora da descarga`, `Litragem do pedido`, `Litragem descarregada` e as `Evidências` que a descarga foi realizada.
- Apenas as evidências não serão campos obrigatórios para o preenchimento do formulário;
- A data e hora não devem ser calculadas automáticamente pelo sistema pois o motorista não necessáriamente estará preenchendo o relatório exatamente no momento da descarga;
- As evidências podem ser arquivos de imagens ou documentos pdf, sendo possível anexar, no máximo, 3 evidências para cada descarga;
- Deve ser possível editar um relatório após seu preenchimento, inclusive seus arquivos de evidência devem ser editáveis;
- Deve ser possível excluir um relatório;
- É necessário que seja visível, de forma clara, todas as descargas que o motorista realizou e ainda não anexou evidências;
- A visualização deve ser clara, também, de quais descargas foram feitas com sobra, com falta, bem como a quantidade de cada uma;
- O layout deve ser responsivo pois os motoristas preencherão os formulários em sua grande maioria pelo celular, portanto deve-se aplicar o conceito de `mobile first` ao projeto.

### Requisitos técnicos
Para a elaboração e desenvolvimento do projeto, você poderá escolher o framework javascript de front-end de sua preferência. Serão apreciados os projetos que forem desenvolvidos com as seguintes stacks:
- Vue.js
- Typescript
- Tailwind

## Avaliação
Como o projeto não conta com um layout pré-estabelecido em uma ferramenta como o Figma, sua criatividade e habilidade em desenvolver interfaces serão aspectos importantes da nossa avaliação. Não se preocupe se não conseguir atender a todos os requisitos do projeto perfeitamente; a avaliação não será rigorosa nesse sentido. Durante a entrevista, você terá a oportunidade de explicar suas escolhas de design e desenvolvimento, bem como discutir questões de tempo e disponibilidade e detalhar o que pode ter ficado faltando.  
Os critérios da avaliação seguirão os seguintes tópicos:

### Habilidades básicas de criação de projetos front-end:
- Uso do Git;
- Capacidade analítica;
- Organização.

### Habilidades de interface (UI)
- Consistência visual;
- Uso adequado de cores e fontes;
- Responsividade;
- Protótipo de telas.

### Habilidades de experiência (UX)
- Facilidade de uso;
- Navegação intuitiva;
- Fluxos bem definidos;
- Minimização de cliques;
- Feedback claro e útil ao usuário (mensagens de erro, sucessos, etc.);
- Pré-validação de dados;
- Utilização do Local Storage para salvamento dos dados.

### Desempenho
- Uso eficiente de recursos;
- Tamanho e otimização dos assets;
- Lazy Loading.

### Qualidade
- Proteção contra vulnerabilidades comuns (ex.: XSS, CSRF);
- Ferramentas de linting e formatação

### Código e Arquitetura
- Boa estrutura de pastas;
- Codigo limpo e organizado;
- Nomes descritivos;
- Funções curtas;
- Boa divisão de responsabilidades;
- Princípios SOLID;

### Boas práticas
- Cumprimento das convenções e nomenclaturas do framework escolhido (caso esteja construindo em Vue, opte por utilizar a [Composition API](https://vuejs.org/guide/introduction.html#composition-api) e atente-se ao [style-guide](https://vuejs.org/style-guide/) e ao [eslint oficial](https://eslint.vuejs.org/) do framework);
- Evite a manipulação direta da DOM;
- Código modularizado;
- Documentação escrita.

### Diferenciais
- Bom uso de Typescript;
- Mock de back-end com [fake-server](https://github.com/typicode/json-server) e uso do [axios](https://axios-http.com/ptbr/docs/intro);
- Cobertura de testes unitários e testes de integração;
