# Documentação Enem Auto Correction

Inicialmente, serão fornecidos detalhes fundamentais sobre o corpus utilizado, o Essay-
BR, que abrange uma ampla variedade de documentos argumentativos coletados ao longo
de vários anos e anotados com notas relativas às competências da redação do ENEM. Esses
detalhes incluem o número de redações, competências avaliadas e a faixa de notas finais. A
análise do conjunto de dados destacará padrões de distribuição, evidenciando a frequência
de notas e a concentração em determinados intervalos.

Em seguida, serão apresentadas as especificações do modelo adotado, treinamento e
resultados obtidos, tanto para modelos de classificação quanto para regressão. A abordagem
de treinamento, a quebra do conjunto de dados e a escolha de hiperparâmetros serão
discutidas em detalhes. Além disso, a interface web desenvolvida para a aplicação prática
dos modelos será descrita, destacando sua funcionalidade e integração com os modelos de
correção automática.

## Enem Corpus

O Corpus Essay-BR contém 4570 documentos argumentativos e 86 tópicos. As re-
dações foram coletadas de Dezembro de 2015 até Abril de 2020. Os tópicos incluem:
questões políticas, atividades culturais, covid-19, movimentos populares dentre outros.
Todos os documentos estão anotados com notas relativas as 5 competências da Redação
do ENEM.

Cada redação do nosso Corpus possui: Título, texto da redação, 5 notas relativas a
avaliação de cada competência e nota final.


