# Ejercicios-U4E2-al-U4E11
public class Principal {

    public static void main(String[] args) {
        Arbol A = new Arbol();
        A.add(A.getRaiz(), "Ana", 1997);
        //Nodos Izquierdos
        A.add(A.getRaiz(), "Roberto", 1982);
        A.add(A.getRaiz(), "Cristal", 1993);
        A.add(A.getRaiz(), "Gustavo", 1986);
        A.add(A.getRaiz(), "Martha", 1990);
        A.add(A.getRaiz(), "Fernando", 1981);
        A.add(A.getRaiz(), "Carmen", 1970);
        //Nodos Derechos
        A.add(A.getRaiz(), "Joseline", 2003);
        A.add(A.getRaiz(), "Alicia", 2009);
        A.add(A.getRaiz(), "Cesar", 2005);
        A.add(A.getRaiz(), "Ramiro", 2001);
        A.add(A.getRaiz(), "Lalo", 2002);

        System.out.println("1.- PERSONA CON LA EDAD PEQUEÑA:\n"
                + A.EdadMin() + "\n");
        System.out.println("2.- PERSONA CON LA EDAD GRANDE:\n"
                + A.EdadMax() + "\n");
        System.out.println("3.- DIFERENCIA EN LA EDAD ENTRE LA PERSONA GRANDE"
                + "\ny la mas pequeña: " + A.Diferencia() + "\n");
        System.out.println("4.- NUMERO DE PERSONAS ACTUAL" + A.getNoNodos() + "\n");
        System.out.println("5.- SUMA DE ALTURAS: " + A.Suma() + "\n");
        System.out.println("6.- PROMEDIO DE EDAD: " + A.Promedio() + "\n");
        System.out.println("7.- ALTURA DE ARBOL: " + A.Altura(A.getRaiz()) + "\n");
        System.out.println("8.- preOrden");
        A.preOrden(A.getRaiz());
        System.out.println("\n9.- inOrden");
        A.inOrden(A.getRaiz());
        System.out.println("\n10.- postOrden");
        A.postOrden(A.getRaiz());
        System.out.println("");
    }
}
