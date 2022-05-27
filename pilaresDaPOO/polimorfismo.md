# Polimorfismo

No pilar do polimorfismo temos o principio de que podemos invocar um mesmo método para mais de uma classe, porém suas respostas serão diferentes.

Um exemplo disso seria um método *Comunicar()* que pode ser utilizado por Pessoa, Cachorro, Pato ou Gato, porém suas respostas serão diferentes.

Também ajuda no reaproveitamento do código e torna as funcionalidades do programa dinamicas no decorrer da execução.

~~~~Java

public class Main {
    public static void main(String[] args) {
        Automovel moto = new Moto("Yamaha XPTO-100", new MecanismoDeAceleracaoDeMotos())
        Automovel carro = new Carro("Honda Fit", new MecanismoDeAceleracaoDeCarros())
        List<Automovel> listaAutomoveis = Arrays.asList(moto, carro);
        for (Automovel automovel : listaAutomoveis) {
            automovel.acelerar();
            automovel.acenderFarol();
        }
    }
}

~~~

~~~PHP
Class Main {
    public function main(...args) {
        $Automovel = new Moto("Yamaha XPTO-100", MecanismoDeAceleracaoDeMotos())
        $Automovel = new Carro("Honda Fit", MecanismoDeAceleracaoDeCarros())
        foreach ($Auto as $automovel) {
            $Automovel->acelerar();
            $Automovel->acenderFarol();
        }
    }
}

~~~

![comunicar](img/comunicar.png)

[Próximo capítulo](../tiposDeRelacionamento/tiposDeRelacionamento.md)