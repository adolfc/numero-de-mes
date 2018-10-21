# numero-de-mes

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package diadesemana;

import java.util.Scanner;

/**
 *
 * @author Adolf
 */
public class DiadeMes {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String Mes[]={"Enero","Febrero","Marzo","Abril","Mayo","Junio","Julio","Agosto","Septiembre","Octubre","Noviembre","Diciembre"};
        System.out.println("Ingresa Numero");
        int d= sc.nextInt();
        if(d >= 1 && d <= 12){
            System.out.println("El Numero " +d+ " Equivale al mes de " +Mes[d-1]);
        }else{
            System.out.println("No existe ese Número de Mes");
        }
    }
    
}
