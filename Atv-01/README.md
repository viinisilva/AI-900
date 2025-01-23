<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="60px" src="https://hermes.dio.me/lab_projects/badges/87d332d0-5198-4a2f-b159-38c8c2976954.png"></a>
    <span> Trabalhando com Machine Learning</span>
</h1>

## Criando modelo de previsão - Passo a passo

O passo a passo para ser seguido, é disponibilizado pela própria microsoft, através do link:

https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/01-machine-learning.html
<h1>Testes Utilizando o Laboratório</h1>
<img src="https://github.com/viinisilva/AI-900/blob/main/Atv-01/1.jpg">
<img src="https://github.com/viinisilva/AI-900/blob/main/Atv-01/2.jpg">
<img src="https://github.com/viinisilva/AI-900/blob/main/Atv-01/3.jpg">
<img src="https://github.com/viinisilva/AI-900/blob/main/Atv-01/4.png">

Para o teste, utilizei o json abaixo:

``` JASON

   {
  "input_data": {
    "columns": [
      "day",
      "mnth",
      "year",
      "season",
      "holiday",
      "weekday",
      "workingday",
      "weathersit",
      "temp",
      "atemp",
      "hum",
      "windspeed"
    ],
    "index": [0],
    "data": [[1,1,2022,2,0,1,1,2,0.3,0.3,0.3,0.3]]
  }
 }


A previsão gerada foi:

{1 item
"Results": 354.2802801444516
}


