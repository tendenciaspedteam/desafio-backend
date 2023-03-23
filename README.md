<h1 align="center">
  <img alt="Logo" src="./doc/img/logo.png" alt="Logo Tendencias">
</h1>

<h1 align="center">Desafios de Backend</h1>
<p align = "center">Lista de desafios para o processo seletivo para backend</p>

## Um programa para popular um banco de dados com milhares de filmes
### Problema
Nesse desafio você deve criar um programa de linha de comando (cli) que lê um arquivo csv de filmes e popula um banco de dados pensando em performance e esperando que o arquivo pode crescer muito.
### Requisitos

* Cada linha do csv contém colunas que deverm ser salvas em colunas/campos separados no banco de dados:
* ID - número inteiro que identifica o filme encontrado
* title - título do filme encontrado na 2a coluna do csv. Com o valor "Jumanji (1995)" o title é Jumanji
* Year - ano do filme encontrado na 2a coluna do csv. Com o valor "Jumanji (1995)" o year é 1995
* Genres - múltiplos valores com os gêneros do filme separados por |. Encontrado na 3a coluna. O script deve pensar em performance e tirar proveito de concorrência/paralelismo para popular o banco de dados.

### Observações
* **O programa tem que ser em escrito em python**
* A partir do problema descrito acima, você pode fazer uma solução muito básica ou adicionar recursos opcionais que não foram descritos. Use seu tempo com sabedoria. Portanto, seria melhor se você apresentasse a melhor solução possível que durasse o menor tempo possível e ainda pudesse mostrar suas habilidades para provar seu valor;
* Só aceitamos soluções que implementem TODAS AS CARACTERÍSTICAS descritas acima. Testes incompletos ou com erro não serão considerados;
* Devemos ser capazes de executar sua solução com configuração mínima (documente no README).
* O banco de Dados deve ser um banco de dados relacional (Postgres, MySQL, MariaDB, etc)

## 2. Implemente uma Documentação
### Problema
Neste desafio, você terá que criar uma documentação a partir de um código fornecido. O código em questão contém uma classe com métodos e atributos que precisam ser explicados. Sendo assim, sua tarefa consiste em descrever o que cada método faz e como eles funcionam.

### Requistos

* A documentação não tem padrão, sinta livre para escrever do jeito que você achar melhor, mas lembre que outra pessoa terá que entender.
* Explicar de maneira clara e concisa o que pode ser feito.
* Certificar-se de que cada método e atributo da classe sejam devidamente documentados.
* Fornecer exemplos de uso sempre que possível, para ilustrar como cada método pode ser utilizado na prática.
* Verificar se todas as informações fornecidas são relevantes e úteis para o usuário final.
* Refatore o código para melhor legibilidade do mesmo.

O código se encontra [aqui](https://github.com/tendenciaspedteam/desafio-backend/blob/main/desafio-2/main.py).