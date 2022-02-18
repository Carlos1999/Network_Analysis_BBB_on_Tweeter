# :blue_book: Estudo da Rede dos Tweets sobre o BBB22  



## :mag: Introdução 

 Para a realização do presente estudo, foram analisados alguns dados provenientes da API do Twitter. Tal API pode ser acessada através da página do Twitter Developer. Após passar por alguns processos de segurança submetidos pelo próprio Twitter o acesso à API é liberado para que você possa ter acesso alguns a dados (Com algumas limitações de quantidade) disponibilizados pela rede social.<br><br>No que diz respeito a esse trabalho, os dados coletados foram utilizados para a criação de uma rede. Para isso, utilizamos como tema para a realização da pesquisa a hashtag BBB22 (Referente ao reality show Big Brother Brasil 2022).<br><br>Com base nos resultados dessa pesquisa, um grafo (rede) foi criado para analisar os usuários que tweetam sobre a hashtag BBB22 bem como as menções feitas nessas postagens.<br><br>No contexto da rede criada, cada usuário corresponde a um nó na rede e cada menção que um usuário faz a outro corresponde a uma aresta (link) entre o nó referente ao usuário que mencionou e o nó correspondente ao usuário mencionado. A rede modelada se caracteriza como dirigida.



 Desse modo foi gerado o grafo utilizando uma parte do dataset (Com apenas 500 usuários) fornecido com o objetivo de realizar análises sobre a disposição da rede através de grandezas conhecidas, criando gráficos e exibindo os nós com valores mais importantes.



 No que diz respeito ao ranqueamento dos nós (Node Ranking) as métricas estudadas foram: Degree centrality, Betweenness Centrality e EigenVector centrality.



 Além disso, foram feitas uma análise bivariada (PDF e CDF) , uma análise multivariada e uma análise da decomposição da rede.



## :hammer_and_wrench: As principais tecnologias utilizadas foram:

- Python;
- Google colaboratory;
- Networkx;
- Gephi.



## :large_blue_diamond: Passo a passo para reprodução

Caso queira reproduzir por conta o notebook é necessário: 

- Criar uma conta de desenvolvedor do Twitter para ter acesso a API, isso é feito a partir desse [link](https://developer.twitter.com/en/apply-for-access).
- Executar as células do notebook na ordem.



## :man_technologist: Autores do Projeto

* Carlos Vinícius dos Santos ([@Carlos1999](https://github.com/carlos1999))

* Hugo Felipe dos Santos ([@hugofsantos](https://github.com/hugofsantos))

  

## :question: Sobre o Projeto

Projeto criado para a disciplina de Análise de Redes (IMD1155), ministrada pelo professor [@ivanovitchm](https://github.com/ivanovitchm), do **Instituto Metrópole Digital - UFRN**, curso de Bacharelado em Tecnologia da Informação.
