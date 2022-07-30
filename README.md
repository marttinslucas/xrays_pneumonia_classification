# Modelo de Classificação de Pneumonia através de raios X
## Introdução:
* Com a recente pandemia provocada pelo surto de COVID-19, foi necessário um esforço do sistema de saúde de cada país em diagnosticas e tratar os sintomas da doença em muitos pacientes ao dia. O estresse provocado no sistema de saúde devido ao grande número de pacientes e consequentemente diagnósticos, podem reduzir a qualidade desses diagnósticos, uma vez que os responsáveis (médicos) estão sobre alta demanda e pressão.
* Uma das doenças causadas pela covid-19 é a Pneumonia, que pode ser vista em exames de Raio-X e se diagnosticada com precisão e antecedência, será vital para o tratamento do paciente.
## Objetivo:
* O objetivo desse estudo é criar um modelo de Deep Learning, que possa diagnosticar Pneumonia através de exames de Raio-X.
* A meta é alcançar uma acurácia do modelo, superior a 90% com maior redução possível dos falsos negativos, uma vez que se tratando da saúde humana, devemos nos atentar aqueles diagnósticos preditos como Normais, mas que na realidade são positivos para Pneumonia. Pois, ao diagnosticar o paciente como normal, sendo esse positivo, as chances de tratamento correto diminuem, podendo pôr em risco a vida do paciente.
* Reiterando, que o objetivo da criação de uma inteligência artificial é o aumento do conhecimento humano, ou seja, ajudar na tomada de decisões de maneira a facilitar os diagnósticos, mas nunca trabalhar sem supervisão.
* `Para o uso real de uma inteligência como a feita neste notebook seria necessário um estudo de possíveis viéses, um maior número de amostras, idades, sexos, para garantir uma maior confiança na rede neural, a fim de reduzir ao máximo todo bias.`
## Dataset:
* O dataset contendo as imagens de Raio-X normais e com pneumonia, foram encontrados em: https://data.mendeley.com/datasets/rscbjbr9sj/2
## Conteúdo:
* Os dados contém imagens de raio-x, classificados previamente dentro de suas respectivas pastas, como normal ou pneumonia.
