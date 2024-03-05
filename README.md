# Carro


PARTE.1

package carro;


public class Carro {
    
    

    
    public static void main(String[] args) {
        
      // exibir  informação do carro
      
      CarroOutro c1 = new CarroOutro("Toyota", "Corolla", 2022, 75000.00);
      c1.exibir();
        
    }
    
    
    
 
    
}


PARTE.2

package carro;

public class CarroOutro {

    private String marca;
    private String modelo;
    private int ano;
    private double preco;

    // metodo contrutor 
    public CarroOutro(String marca, String modelo, int ano, double preco) {

        this.marca = marca;
        this.modelo = modelo;
        this.ano = ano;
        this.preco = preco;
    }

    // metodo acessores
    public String setmarca(String marca) {

        this.marca = marca;
        return marca;
    }

    public String getmarca() {
        return marca;
    }

   public String setmodelo(String modelo){
   
       this.modelo = modelo;
       return modelo;
   } 
   
   public String getmodelo(){
   return modelo;
   }
   
   public int setmarca(int ano) {

        this.ano = ano;
        return ano;
    }

    public int getano() {
        return ano;
    }
    
    public double setpreco(double preco) {

        this.preco = preco;
        return preco;
    }

    public double getpreco() {
        return preco;
    }
   
    public void exibir(){
        System.out.println("marca: " + getmarca());
        System.out.println("modelo: " + getmodelo());
        System.out.println("ano: " + getano());
        System.out.println("preço: " + getpreco());
    }
   
    
}





