# Case de Aluguel de casas

- Foi disponibilizado por um cliente, um dataset contento algumas casas e apartamentos para alugar na Europa, e foi solicitado uma ánalise dos dados para verificar o melhor apartamento para alugar, de acordo com algumas premissas:

  - O valor do aluguel deve ser menor que 4000 euros.
  - A casa deve aceitar animais de estimação.
  - A casa deve possuir entre 2 e 3 quartos.
  - E de acordo com o cliente, apartamentos localizados em andares superiores são mais valorizados ao decorrer do tempo, sendo assim preferidos caso o mesmo faça a compra do imóvel.

  # A resolução do problema

  - Primeiramente foram feitos alguns estudos sobre o dataset, para verificar quais informações são relevantes para o problema, e quais não.
  - Após isso, foi feito uma estruturação dos dados, renomeando as colunas de forma padrão e mudando o tipo de dados para que possa ser utilizado.
  - Em seguida, foram feitos alguns filtros para pegar apenas as casas/apartamentos de acordo com a necessidade do cliente.
  - Após os filtros, foi agrupado feito um agrupamento da média dos preços por cidade e verificado que os valores mais baixos estão na cidade de Porto.
  - Com a cidade definida, foi feito um agrupamento por andar, para verificar a média dos preços de acordo com o andar do imóvel.
  - Analisando o agrupamento anterior, chegamos a conclusão de que o os apartamento com maior custo benefício para o cliente, são os que estão localizados no 16 andar, o que nos retornou 2 opções para o cliente.
