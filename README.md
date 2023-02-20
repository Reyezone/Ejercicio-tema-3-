public class Main {
    public static void main(String[] args) {
        Carro miCarro = new Carro(4);
        miCarro.Aumentarnumpuertas();
        miCarro.Aumentarnumpuertas();

        System.out.println(" El numero de puertas de mi coche es " + miCarro.getNumpuertas());
        }
    }
class Carro{
    private int numpuertas;

    public Carro(int numpuertas){
        this.numpuertas=numpuertas;
    }
    public void Aumentarnumpuertas(){
        this.numpuertas++;
    }
    public int getNumpuertas(){
        return this.numpuertas;
    }

}


// aqui empieza la parte 2 

public class Main {
    public static void main(String[] args) {
        suma(4, 3, 7);
    }

    public static void suma(int a, int b, int c) {
        int resultado;
        resultado = (a + b + c);
        System.out.println(resultado);
    }
}
