# java03
class on 03-07-2023

reference variables holds the properties of the class

public class TeacherUse {
    public static void main(String[]args){
     //teacher object has created
     Teacher t1=new TEacher();
     //set the properties
     t1.tid=101;
     t1.name="Mahima";
     System.out.println("Teacher id: ",+t1.id);
     System.out.println("Teacher name: ",+t1.name);

     o/p:Teacher id:101
         Teacher name:Mahima

         //the above is the basic code of java to understand the reference variable and how we create the objects


         in java we are not allowed to add the duplicate methods
         when we are decalring the parameterized comnstructor we have to pass the values in the object 

    like:
    Teacher t1=new Teacherr(102,"Samiksha")

to read the values from the use r then we use the scanner class that will be imported from the package claeed java.util.Scanner

code:
import java.util.scanner;
public classTacherUSe{
     public static void main(String[] args)

          Scanner sc=new Scanner(Scanner . in);
          System.out.println("Enter Integer String and Float values:")
          int n = sc.next();
          String s=sc.next();
          System.out.println("Number: ",+n)
          System.out.println("String: ",+s)
          
          
}

o/p:
Enter integer and string values
 Number:100
String1:Hello


we have created class print() is a function that is goin to print in which name ,id has to print
t1,t2 are reference variables which have name,id so that we can access the as t1.name,t2.name,t2.id,t2.id

//
//if we declared the varibaleeds as a private then we make use of GETTER AND SETTER METHODS
            --------------------------

            OOPS COMPONENTS:
            =--------------=

      4 TYPES OF COMPONENTS:
      1.encapsulation: this prevents  we can not acces the data outside the class 
      by declaring the all the variables as a private
      defination: wrapping up of data and its functionality in a single unit is known as encapsulaation
      
      
      
      2.Inheritance
      3.Polymorphism
      4.Abstaraction

Inheritance: to inheri the properties from the parent
package vehicle;                              \   \\all the peoperties inside the car has the properies also have the properties of vehicle as well
public class VehicleUSe{                      \   public class Car extends Vehicle 
    public static void main(Srtring[] args){  \
    vehicle v=new Vehicle()                    \
    v.color="black"                             \
    v.maxspeed=100;                             \
    system.out.println(v.color)                 \
    system.out.println(v.maxspeed)              \
    }  
  \  o/p:Black                                     
      100
    


  
     



}
























    
