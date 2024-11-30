# Introdução Microsserviços Com Kafka

<p>Projeto utilizando microsserviços e Kafka com objetivo de aprender e praticar a construção de microsserviços e a criação da comunicação assíncrona entre eles utilizando recursos do Kafka, como tópicos, produtores e consumidores</p>

## Exemplo
<p>Neste Exemplo, são criados 2 microsserviços, um de venda que produz uma mensagem que é enviada para um tópico no Kafka, e outro microsserviço que consome essa informação da venda diretamente do tópico do Kafka</p>

## Serviço Produtor - Venda
<p>Serviço responsável por gerar uma venda e salvar as informações no tópico</p>
<img src="https://github.com/CarlosVinicios99/Introducao-Microsservicos-Com-Kafka/blob/main/producer.jpeg?raw=true">

## Serviço Consumidor - Estoque
<p>Serviço responsável por receber informações da venda e exibir os dados</p>
<img src="https://github.com/CarlosVinicios99/Introducao-Microsservicos-Com-Kafka/blob/main/consumer.jpeg?raw=true">

## Estrutura do Cluster 
<p>Estrutura do cluster do kafka e a disposição dos producers, consumers e dos tópicos com as mensagens recebidas</p>
<img src="https://github.com/CarlosVinicios99/Introducao-Microsservicos-Com-Kafka/blob/main/cluster.jpeg?raw=true">
