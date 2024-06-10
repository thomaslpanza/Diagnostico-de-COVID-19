# Diagnostico-de-COVID-19
## Desenvolvimento de um modelo de diagnóstico de pacientes com COVID-19

Foi criado um modelo de diagnóstico de pacientes para a COVID-19, utilizando como base de dados o histórico médico, idade, sexo e condição atual (entubado, internado em UTI).

Após a organização da base de dados, é feita uma exploração inicial com análises prévias da base de dados.

Em seguida, foram criados 3 modelos diferentes utilizando diferentes ferramentas. Utilizando as métricas de avaliação para cada modelo, foi definido o modelo criado através do XG Boost para ser otimizado.
Tentou-se fazer sua otimização pelo Random Search, mas houve uma grande demanda computacional. Com isso, foram utilizadas técnicas de over e under-sampling, além da SMOTE para balancear melhor os dados e se conseguir uma melhora do modelo.
