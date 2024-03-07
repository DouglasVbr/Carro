# Carro


PARTE.1

// Arquivo: Main.java
package carro;

public class Carro {

    public static void main(String[] args) {
        // Criando um objeto Carro
        Carro2 Carro2 = new Carro2("fiat", "uno", 2010, 14000.00);

        // Exibindo informações do carro
        Carro2.exibir();

    }
}



PARTE.2

// Arquivo: Carro.java
package carro;

public class Carro2 {

    //atributos e variaveis
    private String marca;
    private String modelo;
    private int ano;
    private double preco;

    //metodo construtor
    public Carro2(String marca, String modelo, int ano, double preco) {

        this.marca = marca;
        this.modelo = modelo;
        this.ano = ano;
        this.preco = preco;

    }

    // metodo set marca
    public String setmarca(String marca) {

        this.marca = marca;
        return marca;
    }

    // metodo get marca
    public String getmarca() {

        return marca;

    }

    //metodo set modelo
    public String setmodelo(String modelo) {

        this.modelo = modelo;
        return modelo;

    }

    // metodo get modelo
    public String getmodelo() {

        return modelo;

    }

    // metodo set ano 
    public int setano(int ano) {
        this.ano = ano;
        return ano;
    }

    // metodo get ano
    public int getano() {
        return ano;
    }

    //metodo set preço
    public double setpreco(double preco) {
        this.preco = preco;
        return preco;
    }

    // metodo get preço
    public double getpreco() {
        return preco;
    }

    public void exibir() {

        System.out.println("marca: " + getmarca());
        System.out.println("modelo: " + getmodelo());
        System.out.println("ano: " + getano());
        System.out.println("preço:" + getpreco());
    }
}





