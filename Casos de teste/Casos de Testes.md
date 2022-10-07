<h1> Casos de teste <b>Tela de Busca</b> </h1>

## <b> ``Funcionalidade:`` </b> Realizar buscas

- **Eu** como usuário de testes
- **Quero** ter acesso a página inicial do pokemon test
- **Para** realizar buscas por cidade e visualizar o pokémon de acordo com o clima

<br>

## <b> ``Cenário:``</b> Buscando por cidade
**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro o nome da cidade desejada no campo de cidade

**E** pressiono o botão "Buscar"

**Então** abaixo do botão "Buscar", deve ser apresentado o resultado com informações relacionadas ao pokemon e a cidade inserida na busca

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas menores que 5°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura esteja abaixo dos 5°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo GELO (ICE) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas maior ou igual a 5°C e menor que 10°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura esteja maior ou igual a 5°C e menor que 10°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo ÁGUA (WATER) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas maior ou igual a 12°C e menor que 15°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura esteja maior ou igual a 12°C e menor que 15°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo GRAMA (GRASS) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas maior ou igual a 15°C e menor que 21°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura esteja maior ou igual a 15°C e menor que 21°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo TERRA (GROUND) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas maior ou igual a 23°C e menor que 27°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura esteja maior ou igual a 23°C e menor que 27°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo INSETO (BUG) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas maior ou igual a 27°C e menor que 33°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura esteja maior ou igual a 27°C e menor que 33°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo PEDRA (ROCK) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas maiores que 33°C

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade cuja temperatura seja maior que 33°C

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo FOGO (FIRE) deve ser apresentado

<br>

## <b> ``Cenário:``</b> Buscando por cidades com temperaturas fora das condições do critério

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade aleatória onde a temperatura não esteja listada nos critérios anteriores

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo NORMAL deve ser apresentado

<br>

## <b> ``Cenário:``</b> Cidade cujo clima esteja como "Chovendo"

**Dado que** me encontro com a tela do weather-pokemon-test aberta

**E** insiro uma cidade aleatória onde o resultado obtido no clima é "Chovendo"

**E** pressiono o botão "Buscar"

**Então** um pokemon do tipo ELÉTRICO (ELETRIC) deve ser apresentado

<br>
