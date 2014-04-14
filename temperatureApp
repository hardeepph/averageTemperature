package javaapplication;

/**
 *
 * @author Hardeep
 */

import java.util.Scanner;

class temperatureApp
{

public static void main(String[] args){

//call scanner
    
Scanner reader = new Scanner(System.in);
Scanner repeat = new Scanner (System.in);

//declare int variables for monday to friday
    
    double Mtemp;
    double Ttemp;
    double Wtemp;
    double THtemp;
    double Ftemp;
    char response = 'y';
    double avg;

    
    //only executes while response = yes, and executes at least once
        do
        {

//asks user for input            
System.out.println("Please enter the temperature for Monday through Friday");

//gets input and stores temperature in variable:
   
System.out.println("Monday's temp?");
Mtemp =reader.nextInt();    

System.out.println("Tuesday's temp?");
Ttemp =reader.nextInt();

System.out.println("Wednesday's temp?");
Wtemp =reader.nextInt();     

System.out.println("Thursday's temp?");
THtemp = reader.nextInt();

System.out.println("Friday's temp?");
Ftemp = reader.nextInt();
     
//add all variables and divide by 5, store this value in double average

avg = ((Mtemp + Ttemp + Wtemp + THtemp + Ftemp)/ 5.0);    
                
//prints the average + a conditional message
if (avg > 100){
    System.out.println("The average temp was " + avg ); 
    System.out.println("Too hot!");
}
else if (avg < 0){
    System.out.println("The average temp was " + avg);
    System.out.println("Too cold!");
} 
else
    System.out.println("The average temp was" + avg); 


System.out.println("would you like to calculate agin for another week? (y or n)");
response = repeat.nextLine().charAt(0);


        }while(response == 'y');            
//ask user if they would like to calculate another week



System.out.println("All done!");

}   

}
