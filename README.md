# Decoder-by-Ayush-Kumar-
 Binary number Decoder by java developer Ayush Kumar


 import java.util.*;
import java.math.*;//(C)Ayush Kumar

public class Program
{
    public static void main(String[] args) {
        Scanner s= new Scanner(System.in);
              String[]lines = s.nextLine().split(" ");
             for(String line:lines){
                   BigInteger i = new BigInteger(line,2);
                   System.out.println(i.toString()+ "|" +((char) Integer.parseInt( i.toString())));
             }
    }
}
