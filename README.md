
# Bootcamp Data Science Alura 2021 - Módulo 3
# Previsão dos casos de COVID-19 no Brasil: <br/> Uma análise preditiva no município com maior índice de casos por habitante

<img src="https://images.unsplash.com/flagged/photo-1584036561584-b03c19da874c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1332&q=80" height="600" width="1000"></a>  
Photo by <a href="https://unsplash.com/@fusion_medical_animation">
Fusion Medical Animation</a> on <a href="https://images.unsplash.com/flagged/photo-1584036561584-b03c19da874c?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1332&q=80">Unsplash</a>
  


Elaborado por Francico Foz

<a href="https://img.shields.io/badge/author-gustavolq-blue.svg)](https://www.linkedin.com/in/francisco-tadeu-foz/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a>  

---

## Introdução

Olá! 

Neste repositório você encontrará o meu projeto do módulo 3 do Bootcamp Data Science 2021 da [Alura](https://www.alura.com.br/).

Durante todo o Bootcamp irei mergulhar no oceano da Ciência de Dados a partir de dados reais da área da saúde em 6 módulos.



## Projeto 

Durante o terceiro módulo do bootcamp Data Science 2021 da Alura, podemos estudar séries temporais e conhecer a biblioteca [Facebook Prophet](https://facebook.github.io/prophet/). 

Neste projeto utilizarei das técnicas estudadas para análisar os dados dos boletins epidemiológicos da COVID-19 no Brasil extraídos do [Brasil.io](https://brasil.io/dataset/covid19/) (última atualização: 17 de dezembro de 2021, acesso em 18 de dezembro de 2021).

Você pode encontrar o dataset baixado por mim neste [link](https://drive.google.com/file/d/1cosY6p83n_88hJv9I51oQjcS_I1z0Utw/view?usp=sharing).

---




## Projeto

Esta análise pretende explorar os dados dos casos de COVID-19 dos estados e municípios no Brasil, no período de entre 2020-2021. Realizar uma análise preditiva dos casos, no município que tiver o maior número de casos acumulados por habitante.

Para se delimitar o estudo, buscarei entender qual foi o **estado com maior quantidade de casos por habitante** e dentre este estado qual foi o **município com maior quantidade de casos por habitante**.

A partir deste cenário realizarei os estudos de previsão no município utilizando o **Facebook Prophet**.


Responderei os seguintes questionamentos:

*    Qual foi o estado com maior índice de casos de COVID-19 por habitante?
*    Qual foi o município com maior índice de casos de COVID-19 por habitante?
*    Dentre o estado encontrado, qual foi o município com maior índice de casos de COVID-19 por habitante? 
*    Quais são os números previstos para os próximos 30 dias no município selecionado? 


O projeto foi dividido em três notebooks: 
*    [Parte 1: Manipulação de dados](https://colab.research.google.com/drive/1SALaMotX8eYA671Spf_PEw3ixuIdsxIU?usp=sharing)
*    [Parte 2: Previsão de dados](https://colab.research.google.com/drive/1Y_V5SWMYd-kBGIl6WbmoQn1zs2A5-9BL?usp=sharing)
*    [Parte 3: Visualização de dados](https://colab.research.google.com/drive/1JZMt5n9xstbO9OuRSQfCfFS_ILNqOlzU?usp=sharing)


### **Considerações finais:**

O projeto pode responder os questionamentos iniciais propostos, através da exploração e visualização dos dados.

O estado com o maior índice de casos por habitante desde o início da pandemia (atualmente) é **Roraima**.

Mas nenhum dos 10 municípios com maior índice por habitante são deste estado, mas sim de Goiás, Amazonas, Rio Grande do Norte, Pará, Rio Grande do Sul, Paraná e Santa Catarina.

Dentre o estado de **Roraima** o município com o maior índice de casos por habitante foi o de **Boa Vista**, capital do estado.

Com o auxílio da biblioteca do Facebook Prophet, podemos ovservar que será de 0 o número de novos casos de Covid-19 no município, no próximo mês. 
Entretanto, devemos entender que a ferramenta tomou como base os últimos dados para realizar a previsão e informações incertas como a nova variante [Omicron](https://www.who.int/news/item/28-11-2021-update-on-omicron) não foram colocadas dentro da previsão.

Com o aumento da cobertura vacinal da população, podemos ter uma previsão de menores quantidade de casos. 

Mas é importante lembrarmos que a pandemia não acabou e devemos continuar nos prevenindo ao máximo com todas as medidas de segurança para que não haja novos casos.
