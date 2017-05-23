# Barramento
#### Lucca Sukman de Mello
**Ignorar este texto porfavore**

![Barramento](http://producao.virtual.ufpb.br/books/camyle/introducao-a-computacao-livro/livro/livro.chunked/images/organizacao-computador/barramentos.png)

## O que é
Barramento (*“Bus”*, em inglês) é o sistema de fios que transmite informação entre as partes de um computador, ou entre computadores. O Barramento realiza 3 tipos de comunicação: 
* de dados (auto-explicativo),
* de endereços (indicar à CPU o endereço dos bytes para leitura e escrita) e
* de controle (controlar as ações dos Barramentos anteriores e pedidos de dados).

## Como funciona
Barramentos modernos podem realizar 2 tipos de transmissão: serial, com um bit sendo transmitido por vez em sequência, e paralela, com vários bits sendo transmitido ao mesmo tempo, em múltiplos fios paralelos. O valor do bit é determinado pela força elétrica passando pelo fio.
O desempenho do Barramento é medido em função de 2 propriedades: largura de banda, que  indica quantos bits o sistema pode transmitir paralelamente e simultaneamente, e velocidade de transmissão, que é quanto de informação o sistema consegue transmitir por segundo.

## Pra quê serve
A função do Barramento é a de conexão. Ele conecta:
* A CPU à memória
* A Unidade de Lógica e Aritmética (ALU) ao resto da CPU
* Uma CPU à outra (em computadores que têm mais de uma CPU)
* A Placa de Vídeo, o Disco, e outros componentes periféricos, ao sistema principal
O Barramento também pode fazer a ligação entre diferentes computadores, possibilitando que eles se comuniquem de forma rápida e bilateral, como é o caso de quando você conecta um iPhone num Mac, e pode ficar passando arquivos e dados de um pra outro. Nesse caso, o Barramento também vai desempenhar uma função secundária dele: a de transmissão de energia. O Lightning, por exemplo, é um tipo de Barramento no padrão USB.

#### Curiosidade: o que é USB?
O termo “USB” é popularmente conhecido, mas seu significado, nem tanto. Universal Serial Bus é um padrão que define como devem ser os fios do Barramento, desenvolvido nos anos 90 com o objetivo de estandardizar a comunicação entre o computador e os aparelhos externos a este (mouse, monitor, impressora, etc).
