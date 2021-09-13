# Haywood-cop3330-ex02
/*
 *  UCF COP3330 Fall 2021 Assignment 1 Solution
 *  Copyright 2021 Kaylah Haywood
 *  Exercise 2 - Counting the Number of Characters
 */

public class CountCharacter    
{    
    public static void main(String[] args) {    
        String string = "Strawberry";    
        int count = 0;    
          
        for(int i = 0; i < string.length(); i++) {    
            if(string.charAt(i) != ' ')    
                count++;    
        }    
           
        System.out.println("Total number of characters in a string: " + count);    
    }    
}     
