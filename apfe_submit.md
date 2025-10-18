# BD: Trabalho Prático APFE

**Grupo**: P3G12
- Francisco Santos, MEC: 126255
- Keegan Azevedo, MEC: 110160

## Introdução / Introduction
O nosso projeto consiste no desenvolvimento de uma base de dados que permitirá acompanhar as temporadas da Liga Portugal. A aplicação disponibilizará informações sobre equipas, jogadores, resultados e classificações, bem como a merch das maiores equipas. 
O principal objetivo é centralizar dados da Liga Portugal, atuais e históricos, numa única plataforma organizada e acessível.

## ​Análise de Requisitos / Requirements

### Objetivo geral

Criar uma base de dados para armazenar e consultar dados da Liga Portugal, incluindo temporadas, equipas, jogadores e jogos.

### Requesitos funcionais
- Permitir visualizar a classificação geral de uma temporada.
- Consultar dados de uma equipa (nome, cidade, estádio, treinador).
- Consultar lista de jogadores de uma equipa.
- Ver resultados de jogos e estatísticas básicas.
- Consultar produtos de merchandising de cada equipa.

### Requisitos não funcionais
- A base de dados deve ser relacional.
- A aplicação deve permitir inserções e consultas rápidas.

### Entidades identificadas
- Clube
- Plantel (11 inicial)
- Jogador
- Jogo
- Temporada
- Classificação
- Loja Online
- Estádio
- Treinador
- Estatísticas do clube
- Estatísticas de jogador
- Pessoa
- Produto


### Principais relações
- Um clube participa em várias temporadas (via classificação).
- Um clube tem vários jogadores e um treinador associado.
- Uma temporada tem muitos jogos; cada jogo pertence a uma temporada.
- Cada jogo envolve dois clubes (casa e fora).
- Um clube tem uma classificação por temporada.
- Em cada jogo, cada clube define um plantel (11 inicial/suplentes) e cada plantel inclui vários jogadores.
- Um clube está associado a um estádio.
- Um clube tem uma loja online e a loja vende vários produtos.






## DER


![DER Diagram!](der.jpg "AnImage")

## ER

![ER Diagram!](er.jpg "AnImage")