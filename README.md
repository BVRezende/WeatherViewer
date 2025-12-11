# WeatherViewer
Aplication for class Prog III

WeatherViewer App — Versão Adaptada

Este projeto é uma releitura moderna do WeatherViewer App (Capítulo 7 do livro Android for Programmers), agora ajustado para consumir uma API REST personalizada hospedada na AWS.

Informações do Aluno

Nome: Bruno Vinicius Rezende

Instituição: UEMG — Unidade Passos

Curso: Sistemas de Informação

Disciplina: Programação III

Semestre: 2025/02


Sobre o Projeto

O app permite consultar a previsão do tempo para os próximos 7 dias de qualquer cidade. Ele serve como base para estudo de conceitos essenciais no desenvolvimento Android, tais como:

 Networking

Consumo de Web Service REST (JSON) usando HttpUrlConnection.

 Multithreading

Execução de tarefas em background com AsyncTask, garantindo uma interface fluida.

 JSON Parsing

Manipulação de objetos complexos via JSONObject e JSONArray.

 Interface e Experiência do Usuário

ListView com ArrayAdapter customizado e padrão ViewHolder.

Tratamento de erros detalhado (ex.: cidade inexistente × falta de conexão).

Indicadores visuais como ProgressBar.

Componentes Material Design: TextInputLayout, FloatingActionButton.

Personalização da barra de status.

 Como Executar o Projeto (Com Segurança)

Para seguir a boa prática indicada em "Software Engineering Observation 7.1", a chave da API não está incluída no repositório.
Para rodar o app, faça o seguinte:

Clone o repositório.

Abra o projeto no Android Studio.

Na raiz do projeto, crie (ou edite) o arquivo local.properties.

Adicione a linha:

WEATHER_API_KEY=AgentWeather2024_a8f3b9c1d7e2f5g6h4i9j0k1l2m3n4o5p6;

 Alternativa

Caso prefira configurar diretamente no código, no arquivo MainActivity.java substitua:

private final String API_KEY = BuildConfig.API_KEY;


por:

private final String API_KEY = "AgentWeather2024_a8f3b9c1d7e2f5g6h4i9j0k1l2m3n4o5p6";
