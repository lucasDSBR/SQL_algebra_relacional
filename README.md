# SQL_algebra_relacional


### Seleção: σ
A seleção é utilizada para realizar uma seleção de elementos(como o nome já diz). Tal feito pode ser realizado por meio de uma condição<br>
<b>σ</b> nome='lucas'<b>(funcionario)</b>

Resumo:
- σ = operação(Seleção);
- "nome='lucas'" = condição;
- (funcionario) = tabela em que a ação será realizada
### Projeção: π
Utilizamos a projeção quando queremos quando temos a necessidade de selecionar colunas que nos interessa em uma determinada tabela em uma relação.
<b>π</b> idade<b>(funcionario)</b>
Resumo:
- π = operação(Projeção);
- idade = coluna da tabela;
- (funcionario) = tabela em que a ação será realizada

### União: ⋃
Como o próprio nome já diz, tal operação realiza a união de dados

### Interseção: ∩
A Interseção realiza uma "seleção" de todos os elementos que sejam comuns entre determinadas tabelas

### Diferença de conjuntos: −
Vamos supor que possuimos duas tableas: A e B. Ao realizarmos aa Diferença de conjuntos da seguinte maneira: A - B, vamos obter um segundo resultado C com todos o elementos que possuem em A mas não existem em B. Se fizermos o inverso, obtemos valores que contem em B que não estão em A.


## Outras operações

### Divisão: ÷
A operação de divisão traz campos em comuns entre duas relações.
