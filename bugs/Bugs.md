<h1> <b>Bugs encontrados</b> </h1>

## <b> ``Bug:``</b> Cidade já informada

**Na tela inicial, o campo referente a "Cidade" já está preenchido com "Campinas".**

- Navegador: Google Chrome
- Prioridade: Alta

<br>

    Sugestão: Limpar o campo e adicionar um placeholder. "Digite aqui sua cidade".

![Logo do Markdown](img/cidadejainformada.jpeg)

<br>

## <b> ``Bug:``</b> Buscar por cidade que não existe

**Ao buscar por uma cidade que não existe, não há uma tratativa do erro. Uma tela contendo uma mensagem de erro no servidor é apresentada**

- Navegador: Google Chrome
- Prioridade: Média

![Logo do Markdown](img/cidadequenaoexiste.jpeg)

<br>

## <b> ``Bug:``</b> Buscar por cidade que contém acentos

**Ao buscar cidades que contém acentos, não há uma tratativa do erro. Uma tela contendo uma mensagem de erro no servidor é apresentada**

- Navegador: Google Chrome
- Prioridade: Média

![Logo do Markdown](img/errobuscaracento.jpeg)

<br>

## <b> ``Bug:``</b> Erro ortográfico

**Após realizar a busca por uma cidade válida, o campo "Clima" está com a ortografia "clma"**

- Navegador: Google Chrome
- Prioridade: Baixa

![Logo do Markdown](img/erroortografiaclima.jpeg)

<br>

## <b> ``Bug:``</b> Falta de padrão no resultado

**Após realizar a busca por uma cidade válida, dependendo do tipo do pokemon, a primeira letra vem maiúscula ou minúscula**

- Navegador: Google Chrome
- Prioridade: Baixa

![Logo do Markdown](img/faltapadrao.jpeg)

<br>

## <b> ``Bug:``</b> Pokemons do tipo "normais" não são apresentados

**Após realizar a busca por uma cidade válida, cidades com temperaturas entre 10/11C° e 21/22C°**

    Condição: Para qualquer outra temperatura, deve-se retornar um pokémon do tipo normal.

- Navegador: Google Chrome
- Prioridade: Alta

<br>

## <b> ``Bug:``</b> Cidades com chuva não trás pokemon correto

**Após realizar a busca por uma cidade válida, se a cidade apresentada estiver chovendo, não é apresentado o pokemon de acordo com a condição proposta.**

    Condição: E, caso esteja chovendo, deve-se retornar um pokémon do tipo elétrico (electric), independente da temperatura.

- Navegador: Google Chrome
- Prioridade: Alta

<br>



