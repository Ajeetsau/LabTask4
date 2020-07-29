* Created by Intelli J IDEA.
 *  Author : Ajeet Shukla (dbc2201)
 *  date: 7/29/2020
 *  Time: 10:50 PM
 *  File: LabTask4.java
 */
import java.util.Scanner;
public class LabTask4 {
    
        System.out.println(message);
    }

    public static void main(String args[]) {
    byte st=0;
    while(st<=100){
        System.out.println("Total Ticket Left: "+(100-st));
        System.out.println("Please Enter Your Name: ");
        Scanner A=new Scanner(System.in);
        String s=A.next(); //nextLine();
        sellTicket(s);
        st+=1;
        if(st==100){
            System.out.println("Sorry, The Tickets Are Sold Out");
            break;}}
        }
    }


