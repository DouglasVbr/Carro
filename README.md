# Carro


PARTE.1

// Arquivo: Carro.java
package carro;

public class Carro {
    private String marca;
    private String modelo;
    private int ano;
    private double preco;
    
    // Construtor
    public Carro(String marca, String modelo, int ano, double preco) {
        this.marca = "Toyota";
        this.modelo = "Corolla";
        this.ano = 2022;
        this.preco = 75000.00;
    }
    
    // Métodos acessores
    public String getMarca() {
        return marca;
    }
    
    public String getModelo() {
        return modelo;
    }
    
    public int getAno() {
        return ano;
    }
    
    // Método para exibir informações do carro
    public void exibirInformacoes() {
        System.out.println("Marca: " + marca);
        System.out.println("Modelo: " + modelo);
        System.out.println("Ano: " + ano);
        System.out.println("Preço: " + preco);
    }
}



PARTE.2



// Arquivo: Main.java
package carro;

public class Main {
    public static void main(String[] args) {
        // Criando um objeto Carro
        Carro carro1 = new Carro("Toyota", "Corolla", 2022, 75000.00);
        
        // Exibindo informações do carro
        carro1.exibirInformacoes();
    }
}
