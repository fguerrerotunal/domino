# domino
hola perras



import java.util.*;
public class Main {
    public static void random(int rang){
        
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        String ln = System.getProperty("line.separator");
        String msj_bienvenida = "BIENBENIDO A ASDASD "
                + ln + "A continuacion se daran a conocer diferentes comandos que, usted como"
                + ln + "jugador podra usar para interactuar y disfrutar el juego"
                + ln + "al terminar de leer, por favor ingresar el numero de jugadores"
                + ln + "el juego comenzara autamaticamente despues de eso.";
        System.out.println(msj_bienvenida);
        int players = sc.nextInt();
        Vector<int[]> Tiles = new Vector<>();
        for(int i = 6;i>=0;i--){
            for(int j=i;j>=0;j--){
                int[] tile = new int[2];
                tile[0] = i;
                tile[1] = j;
                Tiles.add(tile);
            }
        }    
        System.out.println("["+ Tiles.get(10)[0] + "," + Tiles.get(10)[0] + "]");
        random(players);
    }
    
}
