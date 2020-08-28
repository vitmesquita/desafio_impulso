# Desafio Impulso
Repositório destinado a resolução do desafio de estágio em Modelagem e Análise de Dados da ImpulsoGov
## Como comparar municípios?
#### (a) Como você selecionaria municípios para comparação? Descreva quais caracaterísticas você selecionaria para definir municípios semelhantes. 
Visando selecionar municípios semelhantes para comparação da situação em relação a COVID-19, filtraria primeiro os municipios que sejam semelhantes em questão de população e população dependente do SUS. Após esse filtro necessário para evitar comparações que não fazem sentido (como comparar grandes metrópoles com cidades pequenas ou cidades mais ricas com mais pobres), entendo que as principais questões a serem elucidadas para um gestor são: "Como está nosso aparato hospitalar?" e "Como nossa população está reagindo?". Nesse sentido, entendo que faça sentido a separação das cidades filtradas em dois grupos:
##### (1) Cidades semelhantes no fator população
Cidades onde a população se comporta de forma semelhante a cidade do gestor. Selecionando cidades onde os fatores "nível de quarentena" e "ritmo de contágio (rt)" são semelhantes.
##### (2) Cidades semelhantes no fator saúde
Cidades onde o aparato hospitalar se comporta de forma semelhante a cidade do gestor. Selecionando cidades onde os fatores "notificação" e "região do SUS" são semelhantes

#### (b) Descreva 2 (duas) análises ou visualizações que você montaria para comparar a situação entre esses municípios.
Para responder as questões que descrevi como principais a serem elucidadas a um gestor público, não acredito que faça sentido comparar respostas do aparato hospitalar em cidades onde a população tem um grau de cuidado diferente da do gestor em questão. Analogamente, não acredito que faça sentido comparar a reação da população em cidades onde os números hospitalares não sejam semelhantes.
Dessa forma, uma vez selecionados os grupos de municípios semelhantes nos aspectos citados, montaria uma análise personalizada para cada grupo de forma que:
##### (1) Cidades semelhantes no fator população
Nas cidades onde a população se comporta de forma semelhante a do gestor, compararia os aspectos: taxa de mortalidade, número de leitos, ventiladores e número de casos
##### (2) Cidades semelhantes no fator saúde
Nas cidades onde o aparato hospitalar se comporta de forma semelhante a do gestor, compararia os aspectos: nível de quarentena e ritmo de contágio 
