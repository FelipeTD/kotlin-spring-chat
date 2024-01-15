## Spring Boot com Kotlin Coroutines e RSocket para criar um chat

Esse projeto é um fork do projeto original que pode ser encontrado em https://github.com/kotlin-hands-on/kotlin-spring-chat/tree/initial

Ele foi utilizado para estudo do Kotlin com Spring Boot e RSocket para criação de um chat

Ele está dividido em 5 partes sendo elas:

### Parte 1
- Entendimento do projeto inicial, como ele foi feito e o que ele utiliza

### Parte 2
- Adicionando persistência de dados com Spring Data JDBC e H2
- Incluido teste unitários

### Parte 3
- Utilização de extensões para deixar o código mais organizado
- Utilização de markdown para deixar os testes mais organizados

### Parte 4
- Adicionando Spring Webflux com Kotlin Coroutines
- Isso permite que a aplicação seja assincrona e sem bloqueios

### Parte 5
- Adicionando RSocket para streaming de mensagens
- Testes atualizados para testar o streaming
- Deletado classe FakeMessageService pois já temos a implementação
