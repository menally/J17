public class Main {
    public static void main(String[] args) {

        // Inicialización directa con valores
        double[] precios = {34,22,51, 2.25};
        double total = 0;

        System.out.println("--- Lista de precios ---");
        for (int i = 0; i < precios.length; i++) {
            System.out.println("Producto " + i + ": $" + precios[i]);
            total += precios[i];
        }

        double promedio = total / precios.length;
        System.out.println("\nTotal: $" + total);
        System.out.println("Promedio por producto: $" + promedio);
    }
}