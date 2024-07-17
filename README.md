## 🏦 RISCO RELATIVO 💸 ##


## Caso

No atual cenário financeiro, a diminuição das taxas de juros tem gerado um notável aumento na demanda por crédito no banco "Super Caja". No entanto, essa crescente demanda tem sobrecarregado a equipe de análise de crédito, que atualmente está imersa em um processo manual ineficiente e demorado para avaliar as inúmeras solicitações de empréstimo.

## Objetivo

Realizar a automatização do processo de análise por meio de técnicas avançadas de análise de dados. O objetivo principal é melhorar a eficiência e a precisão na avaliação do risco de crédito, permitindo ao banco tomar decisões informadas sobre a concessão de crédito e reduzir o risco de empréstimos não reembolsáveis. Esta proposta também destaca a integração de uma métrica existente de pagamentos em atraso, fortalecendo assim a capacidade do modelo.

## Análise Geral

Este conjunto de dados contém dados sobre empréstimos concedidos a um grupo de clientes do banco. Os dados estão divididos em 4 tabelas, a primeira com dados do usuário/cliente, a segunda com dados do tipo empréstimo, a terceira com o comportamento de pagamento desses empréstimos, e a quarta com a informação dos clientes já identificados como inadimplentes.

O conjunto de dados está disponível para download neste link conjunto de dados. Observe que é um arquivo compactado, você terá que descompactá-lo para acessar os arquivos com as tabelas.

## Hipóteses 

# ⁉️ 1 - Os mais jovens correm um risco maior de não pagamento:

Hipótese  Confirmada!  Ao lado podemos ver que pessoas com idade entre 21 e 41 e entre 41 e 52 anos possuem um perfil de mal pagador, confirmando a hipótese de que quanto mais jovem maior é o risco de inadimplência.

# ⁉️  2 - Pessoas com mais empréstimos ativos correm maior risco de serem maus pagadores.

Hipótese Refutada! Pessoas classificadas como maus pagadores são aquelas com uma quantidade de empréstimos ativos entre 1 e 8.

# ⁉️  3 - Pessoas que atrasam seus pagamentos por mais de 90 dias correm maior risco de serem maus pagadores.

Hipótese  Confirmada!  Segundo a análise de risco relativo, pessoas que atrasam seus pagamentos por mais de 90 dias tendem a ser maus pagadores.

## Conclusões

Esses insights destacam a complexidade das relações entre os diferentes fatores financeiros e comportamentais dos clientes, sugerindo a necessidade de estratégias personalizadas para cada segmento, visando melhor gestão e mitigação de riscos.

Estas análises fornecem insights valiosos para o Banco Super Caja, permitindo que a instituição:

Aprimore suas estratégias de gerenciamento de risco. 
Desenvolvam abordagens personalizadas no relacionamento com diferentes perfis de clientes.
Implemente medidas preventivas para reduzir a inadimplência.
Otimize seus processos de concessão de crédito.

Em suma, este analise se apresenta como uma ferramenta poderosa para a tomada de decisões baseadas em dados, possibilitando uma melhor gestão do negócio e mitigação de riscos financeiros para o Banco Super Caja.

## Melhorias Futuras

Seria valioso incluir na base de dados informações como o estado civil, o nível de escolaridade e os salários dos clientes nos últimos três meses. Esses dados permitiriam verificar se há variações nos salários a cada mês. 

Além disso, manter a base de dados atualizada continuamente é fundamental para aprofundar a análise e desenvolver modelos de Machine Learning mais eficazes.


## Ferramentas
- Big Query: importei a base de dados em csv.
- Loker Studio: criar dashboard e visualizações.


## Linguagens
- SQL no BigQuery

## Links úteis 
(1) Dashboard - 💻[Loker Studio](https://lookerstudio.google.com/s/g5315WZJAiU) </br>

(2) BigQuery - 💻[Big Query](https://lookerstudio.google.com/s/g5315WZJAiU) </br>

(3) BaseDeDados - ✳️[Google Sheets](https://drive.google.com/file/d/1jCm5ValysL41zP85jd1KmsDM5wW9y4S9/view?usp=drive_link)</br>

(4) Ficha Técnica - ✳️[Google Docs](https://docs.google.com/document/d/1LARSIPmOrSMls7yDqgu6NSeD8BoYyKN5H0VBq-uPHCQ/edit?usp=sharing)</br> 


## 🤝 Colaboradora
Carolyne Oliveira: 
[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/carolyne-oliveira-5ba98a29b/)
</br>
