# Criandoarray
public class CriandoArray {
    public static void main(String[] args) {
        // Declarar um array de inteiros com 5 elementos
        int[] array = new int[5];

        // Inicializar o array com valores
        array[0] = 10;
        array[1] = 20;
        array[2] = 30;
        array[3] = 40;
        array[4] = 50;

        // Imprimir o array
        System.out.println("Array:");
        for (int i = 0; i < array.length; i++) {
            System.out.print(array[i] + " ");
        }

        // Outra forma de criar e inicializar um array
        int[] array2 = {1, 2, 3, 4, 5
