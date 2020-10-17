public class Help {
    public static void main(String args[])
        throws java.io.IOException {

        char choice;

        System.out.println(" Info :");
        System.out.println(" 1. if" );
        System.out.println(" 2. switch");
        System.out.println("choice: ");
        choice = (char) System.in.read();

        System.out.println("\n");

        switch (choice) {
            case '1' :
                System.out.println(" Insruction if: \n");
                System.out.println(" if (condition of) insruction if: \n");
                System.out.println(" else insruction ;");
                break;
            case '2' :
                System.out.println ( " Инcтpyкция switch:\n" ) ;
                System.out.println ( " switch ( выpaжeниe ) {") ;
                System.out.println (" case константа : " );
                System.out.println (" последовательность инструкций " );
                System.out.println (" break; " ) ;
                System.out.println (" // ... " ) ;
                System.out.println (")") ;
                break;

            default :
                System.out.print ( " Зaпpoc не найден.") ;
        }
    }
}
