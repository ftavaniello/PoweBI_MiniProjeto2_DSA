# PoweBI_MiniProjeto2_DSA
Repositório contendo o dashboard desenvolvido como segundo Mini Projeto do curso "Microsoft Business Intelligence e DataScience"
#
### Introdução:

- Esse projeto é o segundo mini-projeto oferecido pelo curso de Microsoft Power BI para Business Intelligence e Data Science da plataforma Data Science Academy (DSA). O objetivo principal foi elaborar um dashboard de informações da área comercial de uma empresa, visando analisar a sua performance de vendas. Para que esse trabalho pudesse ser desenvolvido, um arquivo Excel com todos os dados necessários foi fornecido pelo curso e as instruções para criação desse dashboard foram dadas ao longo das aulas. Os dados fornecidos são fictícios, elaborados apenas para motivos de aprendizagem.
#
### Desenvolvimento:
- Antes de iniciar a elaboração do dashboard em si, é importante confirmar se os dados que foram carregados para o Power BI estão consistentes. Para isso, acessamos o Power Query e conferimos o conteúdo desses dados. No caso das informações fornecidas pelo curso da DSA, não houve necessidade de realizar nenhuma mudança antes de começar o projeto.
- As informações fornecidas pelo curso na forma de um arquivo de planilha do Excel.
- Esse dashboard irá contar com um índice para navegação no arquivo e mais quatro relatórios. O primeiro deles é o de "Narrativa Inteligente", seguido por “Principais Influenciadores de Vendas”, “Faixas de Vendas por Categorias e Pontos de Venda” e por fim, “Performance de Vendedores por Região”.
  
- Relatório - Índice:
    - Para esse projeto, optou-se por desenvolver quatro páginas de relatório no Power BI e deixar uma delas como índice, para facilitar a navegação entre essas informações. Para isso, foi inserido um botão de “Navigator de Página”, que permite criar um navegador de acordo com a paginação já existente, ou seja, ele cria um botão para cada uma das páginas, indicando como texto o próprio título dessas páginas. Tendo em vista que esse dashboard foi desenvolvido no PowerBI desktop, não basta apenas clicar no “botão” de determinada página, é necessário selecionar o ctrl junto. Esse índice foi formatado de uma forma que ficasse mais amigável para o usuário do dashboard, apresentando as opções de páginas de forma horizontal.

- Relatório - Narrativa Inteligente:
    - O primeiro gráfico criado foi um gráfico de pizza para avaliar o total do valor de vendas por segmento da loja. Na legenda, foi inserido o segmento das vendas, que são subdivididos em doméstico, corporativo e industrial, e para o valor, foi utilizado a soma dos valores de venda. Para esse caso, foi relevante manter o rótulo do gráfico para facilitar a sua interpretação.
    - Em seguida, foi elaborado um gráfico de total de vendas por fabricante. Para tal, foi escolhido um gráfico de barras e no eixo X foi colocado os fabricantes e no eixo Y o total de vendas.
    - O terceiro gráfico é um gráfico do total de valor de vendas por categoria. Foi escolhido um funil para essa representação, com a “Categoria” no eixo Categoria e a soma do valor de vendas no eixo Valores. Essa visualização é mais comumente utilizada para quando se tem poucas categorias, para facilitar a visualização. É importante manter o rótulo das categorias ao lado e também o rótulo dos dados.
    - O último item presente nesse relatório é o de narrativa inteligente, no qual o próprio Power BI tenta resumir o que ele encontrou nessa página. Esse recurso, pode ser capaz de calcular suas próprias medidas em alguns casos perante as informações fornecidas ali. Além disso, ele pode se alterar caso algum dado em específico seja selecionado em algum dos gráficos presentes na página.

- Relatório - Principais Influenciadores de Vendas
    - Nessa relatório, o objetivo é analisar quais os fatores que mais geram impacto no aumento ou diminuição das vendas. Para isso, o elemento visual escolhido foi o de “Principais Influenciadores”, com o material de análise sendo o campo Valor de Venda, e a explicação se dando por segmento e por categoria.
    - Tendo em vista que essa visualização é muito “grande”, optou-se por deixar apenas uma página para ela, facilitando a visualização e o entendimento do gráfico.
- Relatório - Faixa de Vendas por Categoria e Pontos de Venda
    - O relatório conta com uma visualização por Gráfico de Faixas, contando com Categoria no Eixo X, soma dos valores de venda no Eixo Y e as lojas na legenda. Ele permite interpretar o movimento de vendas de uma mesma loja através de suas categorias disponíveis para venda, ou seja, mostra o aumento ou diminuição nas vendas de uma categoria para a outra em um mesmo ponto de venda. Ao passar o mouse exatamente em um ponto de determinada loja na sua categoria, é possível visualizar seus dados com maior precisão, e se for necessário, ao selecionar a faixa de conecta uma categoria a outra é possível ver os valores de diferença entre elas.
    - Foi retirada a legenda do eixo Y identificando a cor de acordo com ponto de venda para despoluir o visual, dado que as lojas são identificadas de acordo com códigos. Contudo, ao passar o mouse em cima dos pontos disponíveis para cada cor, é possível ver a qual loja ele se refere e o seu total de vendas exato.
    - Um controle deslizante foi adicionado para facilitar a visualização na íntegra das informações ali presentes pois permite uma melhor visualização das faixas devido a expansão de dados que podem não sendo devido ao tamanho do gráfico.

- Relatório - Performance dos Vendedores por Região
    - Essa página conta com um mapa, no qual a localização é com base nos Estados disponíveis no conjunto de dados, a legenda é definida pelos vendedores e o tamanho da bolha é em relação ao total de vendas.
    - Nesse mapa, foi inserido um filtro para exibir apenas os vendedores com mais de 30000 de total de venda. Esse valor foi escolhido a fim de exemplo para o desenvolvimento desse gráfico, mas em um caso de uso real, seria interessante discutir a métrica a ser filtrada com os interessados na visualização de dados, de forma que, para eles, a informação se tornasse mais precisa e relevante.
    - Em relação a formatação, optou-se por manter o estilo do mapa em escala de cinza, para não tirar o foco da informação principal. Nos controles, estão habilitados o zoom automático, os botões de zoom e o botão de laço, para que o usuário tenha a possibilidade de manipular o mapa como desejar.

#
### Conclusão:
- Foi possível elaborar um dashboard no PowerBI com dados da área comercial, com foco na análise de vendas. Apesar de ser um projeto desenvolvido em conjunto com o curso, foi de suma relevância para expandir os meus conhecimentos e usar técnicas que ainda não conhecia, como o recurso de navegação para criar um índice.
