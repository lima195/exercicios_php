## Exercício *1* 
#### - Dado o array com idades, implemente a solução na função `calculaMediaIdade($idade)` que recebe o array $idade como parâmetro e retornará um valor numérico (int, double ou float) e exiba na tela:

### Modelo:

```php
    // Função a ser utilizada:
    /**
    * Função calculaMediaIdade, recebe um array como parâmetro e retorna um valor numérico
    * @param $idades array
    * @return int | float
    */
    function calculaMediaIdade($idades) {
        $resultado = 0;

        // Seu código

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $media;
    $media = calculaMediaIdade($idades);
    // Exibindo a variável $media
    var_dump($media);
```

#### Exemplo:

```php
    $nomes = [
        25,
        'pessoa_c' => 25,
        35,
    ];
```

 Ao passar pela função `calculaMediaIdade($idades)`, deverá retornar: 
 
```php
    61.666666667
```

### Exercícios 1
---

### 1 - *a)*
```php
    $idades = [
        25,
        50,
        30
    ];
```

### 1 - *b)*
```php
    $idades = [
        35,
        41,
        52,
        44,
        33,
        22,
    ];
```

### 1 - *c)* 
```php
    $idades = [
        15,
        20,
        60,
        40,
        72,
        13,
        60,
        20,
        11,
        66,
        14,
        6,
        22,
        36,
        30,
    ];
```

### 1 - *d)*
```php
    $idades = [
        35,
        41,
        'pessoa_c' => 52,
        44,
        'idade' => 33,
        'pessoa_a' => 22,
    ];
```

#
#
#
---
#
#
#

## Exercício *2* 
#### – Dado o array de cada exercício, retorne qual é o maior número de todos implementando a solução na função `calcularMaiorNumero($numeros)` que recebe $numeros como parâmetro de entrada e retornará um valor numérico(int, double ou float) e exiba na tela.

#### Modelo:

```php
    // Função a ser utilizada:
    /**
    * Função calcularMaiorNumero, recebe um array como parâmetro e retorna um valor numérico
    * @param $numeros array
    * @return int | float
    */
    function calcularMaiorNumero($numeros) {
        $resultado = 0;

        // Seu código

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $maiorNumero;
    $maiorNumero = calcularMaiorNumero($numeros);
    // Exibindo a variável $maiorNumero
    var_dump($maiorNumero);
```

#### Exemplo:

```php
    $nomes = [
        85,
        'pessoa_c' => 25,
        35,
    ];
```

 Ao passar pela função `calcularMaiorNumero($numeros)`, deverá retornar: 
 
```php
    85
```

### Exercícios 2
---

### 2 - *a)*
```php
    $numeros = [
        35,
        57,
        22
    ];
```

### 2 - *b)*
```php
    $numeros = [
        22,
        95,
        52,
        41,
        33,
        44,
    ];
```

### 2 - *c)*
```php
    $numeros = [
        11,
        20,
        60,
        15,
        72,
        13,
        60,
        40,
        66,
        14,
        0,
        11.5,
        36,
        30,
        20,
    ];
```

### 2 - *d)*
```php
    $numeros = [
        350,
        421,
        'x' => 152,
        441,
        'y' => 311,
        'z' => 22,
    ];
```

#
#
#
---
#
#
#

## Exercício *3* 
#### – Dado o array de cada exercício, retorne uma string com a junção dos nomes, separados por um espaço implementando a solução na função `juntaNomes($nomes)` que recebe o array $nomes como parâmetro de entrada e retornará uma string e exiba na tela.

#### Modelo:

```php
    // Função a ser utilizada:
    /**
    * Função juntaNomes, recebe um array como parâmetro e retorna uma string
    * @param $nomes array
    * @return string
    */
    function juntaNomes($nomes) {
        // Definindo uma string vazia
        $resultado = '';

        // Seu código

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $nomesInvertido;
    $nomesInvertido = juntaNomes($nomes);
    // Exibindo a variável $nomesInvertido
    var_dump($nomesInvertido);
```

#### Exemplo:
```php
    $nomes = [
        'Gabriela',
        'de',
        'gm' => 'Lucas',
    ];
```

 Ao passar pela função `juntaNomes($nomes)`, deverá retornar: 
 
```php
    'Gabriela de Lucas'
```

### Exercícios 3
---

### 3 - *a)*
```php
    $nomes = [
        'João',
        'da',
        'Silva'
    ];
```

### 3 - *b)*
```php
    $nomes = [
        'Mauro',
        'Taka',
        'Kara',
        'No',
        'Muro',
    ];
```

### 3 - *c)*
```php
    $nomes = [
        'Naruto',
        'Uzumaki',
        8 => 'Mama',
        'Aki',
    ];
```

### 3 - *d)*
```php
    $nomes = [
        'smith' => 'Will',
        'will' => 'Smith',
        4 => 'da',
        'Silva',
    ];
```

#
#
#
---
#
#
#

## Exercício *4* 
#### – Dado o array de cada exercício, retorne outro array com a ordem invertida implementando a solução na função `inverterCarros($carros)` que recebe $carros como parâmetro de entrada e retornará um array com a ordem invertida e exiba na tela.

### Modelo:

```php
    // Função a ser utilizada:
    /**
    * Função inverterCarros, recebe um array como parâmetro e retorna outro array
    * @param $carros array
    * @return array
    */
    function inverterCarros($carros) {
        // Definindo array vazio
        $resultado = [];

        // Seu código

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $carrosInvertido;
    $carrosInvertido = inverterCarros($carros);
    // Exibindo a variável $carrosInvertido
    var_dump($carrosInvertido);
```

### Exemplo:
```php
    $carros = [
        'corsa',
        'fusca',
        'gm' => 'camaro',
        'gol',
    ];
```

Ao passar pela função `inverterArray($idades)`, deverá retornar:
    
```php
    [
        'gol',
        'camaro',
        'fusca',
        'corsa',
    ];
```

### Exercícios 4
---

### 4 - *a)*
```php
    $carros = [
        'corsa',
        'fusca',
        'gm' => 'camaro',
        'gol',
    ];
```

### 4 - *b)*
```php
    $carros = [
        'uno',
        5 => 'corsa',
        'fusca',
        'focus',
        'gm' => 'camaro',
        'gol',
    ];
```

#
#
#
---
#
#
#

## Exercício *5* 
#### – Dado array com idades, crie um novo array onde para cada item do array $idades tenha como key a idade e como value um valor booleano (true ou false), para idades iguais ou maiores a 18, defina como true, ou então defina como false. Implemente a sua solução na função `listarIdades($idades)` onde retornará um array e exiba na tela.

### Modelo:

```php
    // Função a ser utilizada:
    /**
    * Função listarIdades, recebe um array como parâmetro e retorna outro array
    * @param $idades array
    * @return array
    */
    function listarIdades($idades) {
        // Definindo array vazio
        $resultado = [];

        // Seu código

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $novasIdades;
    $novasIdades = listarIdades($idades);
    // Exibindo a variável $novasIdades
    var_dump($novasIdades);
```

### Exemplo:

```php
    $idades = [
        11,
        25,
        18,
        'pessoa_x' => 31,
    ];
```

Ao passar pela função `listarIdades($idades)`, deverá retornar:

```php
    [
        11 => false,
        25 => true,
        18 => true,
        31 => true
    ];
```

### Exercícios 5
---

### 5 - *a)*
```php
    $idades = [
        25,
        50,
        30
    ];
```

### 5 - *b)*
```php
    $idades = [
        35,
        41,
        52,
        44,
        33,
        22,
    ];
```

### 5 - *c)*
```php
    $idades = [
        15,
        40,
        72,
        13,
        60,
        20,
        11,
        66,
        14,
        6,
        22,
        36,
        30,
    ];
```

### 5 - *d)*
```php
    $idades = [
        35,
        41,
        'pessoa_c' => 52,
        44,
        'idade' => 33,
        'pessoa_a' => 22,
    ];
```