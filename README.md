
/*
Program - single inheritance
@author - Nishita
@date - 29-09-2022
*/

class Parent
{
 
// creating constructor

Parent();
System.out.println(" ABC");

// creating method  sing

void sing();
System.out.println("Singing");
}

class Child inherits Parent
{

// creating method speak 

void speak();
System.out.println("Speaking");

//creating method dance

void dance();
System.out.println("Dancing");
}


class Inheritance
{
public static void main (String[] args)
{
Child obj = new Child();
obj.sing();
obj.speak();
obj.dance();
}
}
