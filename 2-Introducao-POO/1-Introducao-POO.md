# Introdução a Programação Orientada a Objetos

![keep calm and programe orientado a objetos](img/programe-orientado-a-objetos.png)

Na programação orientada a objetos (POO), os objetos são organizados de acordo com características em comum, ou seja: classes, métodos e atributos. Dessa forma é mais fácil localizar, reutilizar e realizar a comunicação entre objetos.

Ela foi desenvolvida como uma tentativa de aproximar o mundo real do mundo virtual.

Na POO é implementado um conjunto de classes que definem os objetos presentes no sistema de software. Cada classe determina o comportamento (métodos) e os estados possíveis (atributos) de seus objetos, bem como seu relacionamento com os outros objetos.

## Principais conceitos

Mas para entendermos o que de fato é a programação orientada a objetos, temos que responder a pergunta primordial: o que é um objeto?
 
Em definição um objeto seria coisa material ou abstrata que pode ser percebida pelos sentidos e descrita por meio de suas características, comportamentos e estado atual. No caso da programação, essas características levam o nome de atributos, os comportamentos de método, e o estado continua sendo o estado.

Um objeto não pode ser simplesmente criado, ele precisa de um modelo para ser seguido. A esse modelo nós damos o nome de classe. Nós dizemos que o objeto é uma instancia da classe. Em sua definição seria um conjunto de características de um determinado "objeto" que pode ser utilizada de modelo para criar os objetos.

~~~Java
public class Carro {
    Double velocidade;
    String modelo;

    public Carro(String modelo) {
        this.modelo = modelo;
        this.velocidade = 0;
    }

    public void acelerar() {
        /* código do carro para acelerar */
    }

    public void frear() {
        /* código do carro para frear */
    }

    public void acenderFarol() {
        /* código do carro para acender o farol */
    }
}
~~~

~~~PHP
Class Carro {
    $velocidade;
    $modelo;

    public Carro($modelo) {
        $this->modelo = modelo;
        $this->velocidade = 0;
    }

    public function acelerar() {
        /* código do carro para acelerar */
    }

    public function frear() {
        /* código do carro para frear */
    }

    public function acenderFarol() {
        /* código do carro para acender o farol */
    }
}
~~~

Outro conceito importante que vai nos auxiliar no entendimento da POO é o de evento. Eventos são interações (parâmetros) internas e externas que auxiliam na execução de um programa.

![paradigma orientado a objetos](img/POO.jpg)

## [História](https://pt.wikipedia.org/wiki/Programa%C3%A7%C3%A3o_orientada_a_objetos)
 
 Apesar de ter surgido na década de 1970, acabou se popularizando em meados de 1990. Os principais conceitos da POO tem origem na Simula 67, uma linguagem de programação desenhada para fazer simulações.

 Atualmente o principal paradigma utilizado, e tem entre as linguagens de programação que o suportam:
 - Java
 - Python
 - Javascript
 - C
 - C#
 - PHP
 - entre outros


[Próximo capítulo](2-Poo-estruturada.md)
