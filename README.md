# Modelo de Classificação de Pneumonia através de Raios X

## Introdução

Com a recente pandemia provocada pelo surto de COVID-19, foi necessário um esforço do sistema de saúde de cada país em diagnosticar e tratar os sintomas da doença em muitos pacientes por dia. O estresse provocado no sistema de saúde devido ao grande número de pacientes e, consequentemente, diagnósticos, pode reduzir a qualidade desses diagnósticos, uma vez que os responsáveis (médicos) estão sob alta demanda e pressão.

Uma das doenças causadas pelo COVID-19 é a Pneumonia, que pode ser visualizada em exames de Raio-X e, se diagnosticada com precisão e antecedência, será vital para o tratamento do paciente.

## Objetivo

O objetivo deste estudo é criar um modelo de Deep Learning capaz de diagnosticar Pneumonia através de exames de Raio-X.

A meta é alcançar uma acurácia do modelo superior a 90%, com a redução máxima possível dos falsos negativos. Uma vez que, tratando-se da saúde humana, devemos nos atentar aos diagnósticos preditos como Normais, mas que na realidade são positivos para Pneumonia. Pois, ao diagnosticar o paciente como normal, sendo este positivo, as chances de tratamento correto diminuem, podendo pôr em risco a vida do paciente.

Reitera-se que o objetivo da criação de uma inteligência artificial é o aumento do conhecimento humano, ou seja, ajudar na tomada de decisões de maneira a facilitar os diagnósticos, mas nunca trabalhar sem supervisão.

Para o uso real de uma inteligência como a feita neste notebook, seria necessário um estudo de possíveis viéses, um maior número de amostras, idades, sexos, para garantir uma maior confiança na rede neural, a fim de reduzir ao máximo todo bias.

## Dataset

O dataset contendo as imagens de Raio-X normais e com pneumonia foi encontrado em: [Dataset de Raio-X](https://data.mendeley.com/datasets/rscbjbr9sj/2)

## Conteúdo

Os dados contêm imagens de raio-x, classificadas previamente dentro de suas respectivas pastas, como normal ou pneumonia.
