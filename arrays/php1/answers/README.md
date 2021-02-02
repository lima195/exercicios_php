# Respostas exercícios php array 1 (https://github.com/lima195/exercicios_php/blob/main/arrays/php1/README.md)

## Exercício *1* 
#### - Dado o array com idades, implemente a solução na função `calculaMediaIdade($idade)` que recebe o array $idade como parâmetro e retornará um valor numérico (int, double ou float) e exiba na tela:

### Solução:

```php
    // Função a ser utilizada:
    /**
    * Função calculaMediaIdade, recebe um array como parâmetro e retorna um valor numérico
    * @param $idades array
    * @return int | float
    */
    function calculaMediaIdade($idades) {
        $resultado = 0;

        $totalIdades = count($idades);

        foreach($idades as $idade) {
            $resultado += $idade;
        }

        $resultado = $resultado/$totalIdades;

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $media;
    $media = calculaMediaIdade($idades);
    // Exibindo a variável $media
    var_dump($media);
```

### Respostas 1
---

### 1 - *a)*
```php
    35
```

### 1 - *b)*
```php
    37.833333333333
```

### 1 - *c)* 
```php
    32.333333333333
```

### 1 - *d)*
```php
    37.833333333333
```


## Exercício *2* 
#### – Dado o array de cada exercício, retorne qual é o maior número de todos implementando a solução na função `calcularMaiorNumero($numeros)` que recebe $numeros como parâmetro de entrada e retornará um valor numérico(int, double ou float) e exiba na tela.

### Solução:

```php
    // Função a ser utilizada:
    /**
    * Função calcularMaiorNumero, recebe um array como parâmetro e retorna um valor numérico
    * @param $numeros array
    * @return int | float
    */
    function calcularMaiorNumero($numeros) {
        $resultado = 0;
        
        foreach($numeros as $numero) {
            if($resultado < $numero) {
                $resultado = $numero;
            }
        }

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $maiorNumero;
    $maiorNumero = calcularMaiorNumero($numeros);
    // Exibindo a variável $maiorNumero
    var_dump($maiorNumero);
```

### Res 2
---

### 2 - *a)*
```php
    57
```

### 2 - *b)*
```php
    96
```

### 2 - *c)*
```php
    72
```

### 2 - *d)*
```php
    441
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

#### Solução:

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

        $i = 0;
        foreach($nomes as $nome) {
            if($i == 0) {
                $resultado = $nome;
            } else {
                $resultado = $resultado . ' ' . $nome;
            }

            $i++;
        }

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $nomesInvertido;
    $nomesInvertido = juntaNomes($nomes);
    // Exibindo a variável $nomesInvertido
    var_dump($nomesInvertido);
```

### Respostas 3
---

### 3 - *a)*
```php
    'João da Silva'
```

### 3 - *b)*
```php
    'Mauro Taka Kara No Muro'
```

### 3 - *c)*
```php
    'Naruto Uzumaki Mama Aki'
```

### 3 - *d)*
```php
    'Will Smith da Silva'
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

### Solução:

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

        $totalCarros = count($carros);
    
        foreach($carros as $key => $carro) {
            $totalCarros--;
            $resultado[] = $carros[$totalCarros]; 
        }

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $carrosInvertido;
    $carrosInvertido = inverterCarros($carros);
    // Exibindo a variável $carrosInvertido
    var_dump($carrosInvertido);
```

### Respostas 4
---

### 4 - *a)*
```php
    [
        'gol',
        'camaro',
        'fusca',
        'corsa',
    ];
```

### 4 - *b)*
```php
    [
        'gol',
        'camaro',
        'focus',
        'fusca',
        'corsa',
        'uno',
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

### Solução:

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

        foreach($idades as $idade) {
            if($idade >= 18) {
                $resultado[$idade] = true;
            } else {
                $resultado[$idade] = false;
            }
        }

        return $resultado;
    }

    // Chamada da função, onde o retorno é armazenado na variável $novasIdades;
    $novasIdades = listarIdades($idades);
    // Exibindo a variável $novasIdades
    var_dump($novasIdades);
```

### Respostas 5
---

### 5 - *a)*
```php
    $idades = [
        25 => true,
        15 => false,
        30 => true,
    ];
```

### 5 - *b)*
```php
    $idades = [
        35 => true,
        41 => true,
        15 => false,
        44 => true,
        33 => true,
        22 => true,
    ];
```

### 5 - *c)*
```php
    $idades = [
        15 => false,
        40 => true,
        72 => true,
        13 => false,
        60 => true,
        20 => true,
        11 => false,
        66 => true,
        14 => false,
        6 => false,
        22 => true,
        36 => true,
        30 => true,
    ];
```

### 5 - *d)*
```php
    $idades = [
        35 => true,
        41 => true,
        52 => true,
        44 => true,
        33 => true,
        22 => true,
    ];
```