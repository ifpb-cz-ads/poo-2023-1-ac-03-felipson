Questões de POO - Programação Orientada a Objetos
Felipe Saraiva Tavares
Livro Batista & Moraes (2013), p.23

1 - A JVM (Máquina Virtual Java) possibilita a execução de códigos Java em uma vasta gama de máquinas, com diferentes sistemas operacionais e arquiteturas, ao fazer a interpretação do código ao converter bytecode em código de máquina.

2 - O JRE é uma parte do ambiente de execução Java utilizada para executar as aplicações Java, mas não inclui ferramentas de desenvolvimento. Já o JDK é um pacote de desenvolvimento Java, que inclui o JRE e os compiladores e interpretadores necessários para execução das aplicações Java.

3 - public class PrimeiraAula {
    public static void main(String[] args) {
        System.out.println("Terminei a primeira aula com um programa Java!");
    }
}

4 - Não é possível executar a aplicação, pois o bytecode dela está presente no arquivo .class, então recebo um erro de execução.

5 - Obtém-se um erro de execução, pois não foi possível encontrar o método de entrada esperado pelo compilador.
  error: can't find main(String[]) method in class: atvd.Main

6 - public class Saudacoes {
    public static void main(String[] args) {
        System.out.println("Meu nome é [Seu Nome]");     
        System.out.println("Eu torço para o [Seu Time]");
    }
}


7 - A aplicação tem erro de compilação, pois o Java diferencia letras maiúsculas e minúsculas.

8 - Obtém-se erro ao tentar compilar e executar, pois o Java espera que o nome do arquivo e da classe coincidam.
  error: class Main is public, should be declared in a file named Main.java public class Main
