# Getting-Started-with-Programming-in-Java-11
Plural Course
Just some Supplements

Difference between float and double:

        Float - 32 bits; Double - 64 bits
        Float is generally used when speed is more important than accuracy.

1. Create my first java app

        public class Main {
            public static void main(String[] args) {
                System.out.println("Hello world!");
                System.out.println("First Hello world!");
                System.out.println("Second Hello world!");
            }
        }
    
    Only ONE class; static void; System.out.println("...");
      // println = print line
       
           JRE = Java Runtime Environment - enbale executive
           JDK = Java Development Kit - provide tools to create Java apps
           IDE = Integrated Development Environment - edit, build, run, debug
   
   ternimal: cmd --> java Main
        // different from python, python should have Python3 new.py [the postfix]
    
    windows + i = Windows Settings; locate the file
    
            SYNTAX and COMMENTS same as those in Introduction to Java Coursera
            
            package com.pluralsight.search
                // All lowercase; reverse domain name(com.); qualifiers to assure uniqueness
                // New version in intelliJ is to 
                        1. right click src
                        2. new --> class
                        3. com.pluralsight.letsgetlogical(...).Main
                        //4. Main would be the Main.class

4. Block Statement 

        package com.pluralsight.letsgetlogical;
        public class Main {
            public static void main(String[] args) {
                int v1 = 2, v2 = 12;
                final int diff;
                diff =  v1 - v2;

                if (diff > 0)
                    System.out.println(" v1 is greater than v2, diff = " + diff);
                else
                    System.out.println(" v1 is not greater than v2, diff = " + diff);

              System.out.println();
              System.out.println("*** end of program ***");
             }
         }
         
    Quite Python style; each time, remember to clarify the data type;  PRINT just use indentation. 
         
    Block statement, have a braket can keep the variables inside the scope
         
         
        package com.pluralsight.letsgetlogical;
        
        public class Main {
            public static void main(String[] args) {
                double students = 30.0d, rooms = 4.0d;
                if (rooms > 0.0d){
                    System.out.println(students);
                    System.out.println(rooms);
                    double avg = students / rooms;
        //            System.out.println("Average is " + avg); - PRINT
                }

              System.out.println();
              System.out.println("Average is " + avg); - NOT PRINT,  Since its outside the brackets
              System.out.println("*** end of program ***");
            }
        }

   
   
   4 statements: 4m17 TO BE CONTINUE
   
   
   https://www.w3schools.com/java/java_data_types.asp
   W3school - Java - Datatype:
   
                Data Type	Size	Description
                byte	1 byte	Stores whole numbers from -128 to 127
                short	2 bytes	Stores whole numbers from -32,768 to 32,767
                int	4 bytes	Stores whole numbers from -2,147,483,648 to 2,147,483,647
                long	8 bytes	Stores whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807
                float	4 bytes	Stores fractional numbers. Sufficient for storing 6 to 7 decimal digits
                double	8 bytes	Stores fractional numbers. Sufficient for storing 15 decimal digits
                boolean	1 bit	Stores true or false values
                char	2 bytes	Stores a single character/letter or ASCII values
