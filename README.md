# Desafio QA

Como entregar estes desafios
Efetuar um fork deste repositório em um gerenciador Git de sua preferência, como Github, Bitbucket etc.
Ao final do teste, enviar o link do repositório para o recrutador.
Fique a vontade para adicionar qualquer tipo de conteúdo que julgue útil ao projeto. Também é permitido alterar/acrescentar um README com instruções de como executá-lo, melhorias de design etc.
Obs.: Não fazer um Pull Request para este projeto!

Com o que devo me preocupar quando for entregar os desafios?
Descreva como utilizar e executar a sua solução;
Descreva o processo de resolução dos desafios;
Descreva a motivação e o porque da utilização de cada tecnologia;
Descreva o que considera interessante sabermos :)
Não se limitar aos requisitos destes desafios. Sinta-se em casa em adicionar mais detalhes a solução.

## Parte 1 - Planejamento de testes
Objetivo: Criar um documento descrevendo os testes a serem realizados no blog da Frente Corretora - https://frentecorretora.com.br/blog/

### Escopo
Os testes deverão cobrir somente a página principal
Incluir na validação tudo o que for relevante para uma validação mínima da página. Exemplos: links para posts, caixas de pesquisa, menus etc.
Os cenários/casos de testes devem armazenados na pasta 1-planejamento, especificados na linguagem Gherkin ou em formato de planilha. No caso de planilha, especificar os testes utilizando obrigatoriamente as seguintes colunas: Dados dos testes, Procedimento e Resultado Esperado

### Parte 2 - Execução dos testes
Objetivo: Executar os testes planejados na Parte 1, evidenciar os testes executados, criar métricas de execução e registro de defeitos.

### Escopo
Armazenar na pasta 2-execução métricas dos testes executados (sumário da execução, total de casos de teste passed, failed etc.)
Armazenar também um registro de defeitos encontrados durante a execução, em formato de planilha.
Os defeitos devem ser descritos de uma maneira que seja de fácil compreensão aos possíveis envolvidos (desenvolvedores, outros QAs, gerentes de projeto etc.). Utilize como referência este post do CartoonTester
Não se esqueça de evidenciar os defeitos encontrados adequadamente!

## Parte 3 - Automação dos testes
Objetivo: Automatizar um cenário/caso de teste do blog da Idwall

### Escopo
Automatizar o seguinte caso de teste:
Cenário: Pesquisar um post no blog da Frente corretora
    Quando acesso o blog da Frente Corretora
    E pesquiso um post informando um título existente
    Então deve exibir o post pesquisado em uma página de resultados
Utilizar o framework de teste de sua preferência (ex. JUnit, MSTest, RSpec, Cucumber, Cypress, TestCafé, Nightwatch etc.)
Armazenar o código da automação na pasta 3-automacao
Criar também um README.md, com as instruções necessárias para executar a automação.
Lembre-se que a máquina de quem efetuará a avaliação nem sempre contém todos os pacotes, programas e afins, necessários para a execução. Portanto, seja bem descritivo!
