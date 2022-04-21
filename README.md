# House-Rocket-Company
Análise Exploratória de dados, com o objetivo de indicar os imóveis que devem ser comprados e o melhor momento para sua venda.

# House Rocket - House Sales in King County, USA

# Questão de Negócio

Como poderia uma empresa que trabalha com a compra e venda de imóveis se beneficiar com a análise de dados? É o que veremos neste projeto.

Para ilustrar como é a análise de dados pode beneficiar um negócio, vamos simular um ambiente de negócio onde uma empresa, entítulada de House Rocket, realiza a compra e venda de imóveis por meio de uma plataforma digital.

Com um portfólio concentrado em King County (EUA), os stakeholders precisam saber:

Quais imóveis a House Rocket deveria comprar e por qual preço?

Uma vez comprado, qual melhor momento para vender os imóveis e por qual preço?

Para responder aos stakeholders, será feita uma análise exploratória dos dados, tentando identificar os melhores imóveis na ótima de compra e venda da empresa, visando alavancar seus lucros.

# Premissas de Negócio

Como premissa de negócio, iremos utilizar duas:

Se no portfólio tiverem casas (ID's) duplicados, será mantido o ID com a data mais recente.
Será excluído do portfólio as casas onde os preços de vendas sejam outliers.
No campo 'Conditions', vamos considerar a escala crescente quanto maior melhor.

# Planejamento da Solução

Afim de utilizar a maior capacidade dos dados, será feito:

Descrição dos dados
Feature Engineering
Preparação dos dados
Análise Exploratória de dados
Criação do produto de dados
Como principais insights de negócio

Não há uma diferença substância do preço dos imóveis mais antigos, comparados com os mais novos.
Imóveis que tem características 'Waterfront' são 40% mais caros em comparação aqueles que não tem essa característica.
Imóveis onde há porão são 15% mais caros que os que não tem. Essa característica pode ser aproveitada na compra dos imóveis onde não há porão, os reformando (construindo porão), para uma posterior venda com um valor maior.

# Resultados Financeiros para o negócio

Após análise do portfólio da House Rocket, partindo do planejamento descrito no início deste documento, foi possível mapear os imóveis mais propensos para compra e posterior venda. No resultado proposto, a House Rocket deverá desembolsar um total de $ 4.381.264.877,00 na aquisição de 11.690 imóveis, de um total de 21.436, disponíveis no portfólio.

Na venda dos imóveis foi possível indicar para a empresa qual o melhor período para venda. A resultado proposto se deu por meio da análise do comportamento dos preços pela área e pelas estações do ano, indicando qual o melhor período para venda.

Seguindo a recomendação da análise, a empresa poderá ter uma receita nas vendas de $$5.639.229.496,94. As vendas podem trazer um lucro de $ 1.257.965.619,94 (28,71%) dos desembolsados na compra dos imóveis.

# Conclusão

Após análise dos resultados, percebe-se um ganho substância no uso potencial dos dados por meio de sua exploração. Devido o resultado, resume-se que o objetivo inicial deste projeto foi alcançado, dando oportunidade para os próximos passos para sua evolução.

# Próximos passos

Como próximos passos, pretende-se:

Aprimorar a forma de calculo percentual para incrementar o valor de venda;
Montar o modelo em produção, para que os interessados façam visualizações mais personalizadas em suas análises.
