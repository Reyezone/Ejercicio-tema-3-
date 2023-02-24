public class Main {

    public static void main(String[] args) {
        Carro miCarro = new Carro(4);
        miCarro.Aumentarnumpuertas();
        miCarro.Aumentarnumpuertas();

        System.out.println(" El numero de puertas de mi coche es " + miCarro.getNumpuertas());

        int resultado;
        resultado= suma(4, 3, 7);
        System.out.println(resultado);


    }
    public static int suma(int a, int b, int c) {
        return (a + b + c);

    }
    static class Carro {
        private int numpuertas;

        public Carro(int numpuertas) {
            this.numpuertas = numpuertas;
        }

        public void Aumentarnumpuertas() {
            this.numpuertas++;
        }

        public int getNumpuertas() {
            return this.numpuertas;
        }

    }

}
