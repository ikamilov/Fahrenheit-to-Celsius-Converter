//
//  Author: Islam Kamilov
//  HW(3)_Assignment(3)_Islam_Kamilov
//  Date: 02/23/2015
//  Created by Islam Kamilov on 2/23/15.
//  Copyright (c) 2015 Islam Kamilov. All rights reserved.
//  That is converter program)))


#include <stdio.h>
#include <math.h>

//Function Declarations
float celsius_to_fahrenheit(float fahrenheit);
float fahrenheit_to_celsius(float celsius);


int main() {
    //Local Declarations
    
    float F;         //Fahrenheit
    float C;         //Celsius
    float resf;      //Result of Fahrenheit
    float resc;      //Result of Celsius
    
    printf("Please Enter Celsius to Convert Fahrenheit: \t\t\n");
    scanf("%f", &C);
    
    resf = fahrenheit_to_celsius(C);
    printf("Your Entered Celsius is:\t(%.2f) and your Fahrenheit is: \t%.2f\n", C, resf);
    
    printf("Please Enter Fahrenheit to Convert Celsius: \t\t\n");
    scanf("%f", &F);
    
    resc = celsius_to_fahrenheit(F);
    printf("Your Entered Fahrenheit is:\t(%.2f) and your Celsius is: \t%.2f\n", F, resc);
    
    
    return 0;
}//main


float fahrenheit_to_celsius(float celsius) {
  
    return 32 + ( celsius * 180.0) / 100.0;    //Print Out Fahrenheit

}//Fahrenheit

float celsius_to_fahrenheit(float fahrenheit) {
    
    return ((fahrenheit - 32) * 100.0) / 180.0; // Print Out Celsiues

}//Celsius
