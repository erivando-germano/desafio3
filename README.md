﻿# desafio-felipao3

# Projeto Heróis da Aventura

Este é um projeto simples que implementa uma classe em JavaScript para representar heróis em uma aventura. Cada herói possui um nome, idade e tipo, e pode executar a ação de atacar com base no seu tipo.

## Estrutura do Projeto

O projeto consiste em um arquivo JavaScript que define a classe `Heroi` e demonstra seu uso.

### Arquivos do Projeto

- `heroi.js`: Contém a definição da classe `Heroi` e exemplos de instâncias e chamadas de método.

## Como Executar

### Navegador

1. Abra o console do desenvolvedor no seu navegador.
2. Cole o conteúdo de `heroi.js` no console.
3. Pressione Enter para executar o código.

### Node.js

1. Abra o terminal no diretório do projeto.
2. Execute o comando `node heroi.js`.

## Exemplo de Uso

```javascript
// Criação de heróis
const heroi1 = new Heroi("Redgar", 30, "guerreiro");
const heroi2 = new Heroi("Yennefer", 100, "mago");

// Chamada do método atacar
heroi1.atacar(); // Saída esperada: O guerreiro Redgar atacou usando espada
heroi2.atacar(); // Saída esperada: O mago Yennefer atacou usando magia
