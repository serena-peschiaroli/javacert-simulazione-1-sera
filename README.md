- 1. 


Which of the following are correct about random number generation?

The are 2 correct answers

x A. Math.random gives a random value that is greater than or equal to 0.0 and less than 1.0
B. Random numbers cannot be generated within a specific range using java.util.Random
x C. The ints() method of java.util.Random class can be used to generate random numbers within a range
D. In java.util.Random class, there is no support for random numbers other than for int datatype

___________________________________________________________________________


- 2. 
Which of these options can be replaced in “//Condition” to print true?

The are 3 correct answers

public class DecisionMakingTest {

public static void main(String[] args) {

boolean var1 = true;

boolean var2 = true;

if (//Condition) {

System.out.println("true");

} else {

System.out.println("false");

}

}
}

 A. var1==”true”
B. var1!==true
C. var1!=true && var1!=false
x D. var1==var2
E. var1=var2
F. var1=var2=true



___________________________________________________________________________

3 / 45
What will be the result?

try {

int a = 0;

int b = 0;

System.out.print(a / b);

} catch (Exception e) {

System.out.print("E");

} catch (ArithmeticException e) {

System.out.print("AE");

} finally {

System.out.print("F");

}

The are 1 correct answers

A. Prints “E”
x B. Does not compile
C. Prints “FAE”
D. Prints “FE”
E. Prints “AEF”








___________________________________________________________________________



- 4. 

Which of the following constructors can be used to create objects of the class Employee from external code?

The are 2 correct answers

public class Employee {

private int employeeId;

private String designation;

//Constructors

}


x A. public Employee() {
}
x B. public Employee(int employeeId, String designation) {
this.employeeId=employeeId;
this.designation=designation;
}
C. private Employee(int employeeId) {
this.employeeId=employeeId;
}
D. private Employee() {
}
E. public String Employee() { 
return designation;
}






___________________________________________________________________________

- 5. 


How many references and objects are created in the given program?

The are 1 correct answers


public class JavaBasicTest {

public static void main(String[] args) {

BasicClass a,b,c,d;

a = b = new BasicClass("a"); // Line 1

C = new BasicClass("b"); // Line 2

d=new BasicClass(c); // Line 3

}

}

class BasicClass {

public BasicClass(String val) {

}

public BasicClass(BasicClass basicClass) {

}

}

A. 4 references and 4 objects
x B. 3 references and 4 objects
C. 4 references and 3 objects
D. 3 references and 3 objects


___________________________________________________________________________

- 6. 

public class OperatorPrecedenceTest {

public static void main(String[] args) {

int n1 = 10, n2 = 5, n3 = 1, result;

result= (n1 + -- n3 - ++n2) * 2;

System.out.println(result);

}

}


A. 6
B. -2
C. 10
x D. 8



___________________________________________________________________________

- 7. 

What are the different ways to get a list from an array?

 

String[] games = {“Cricket”, “Football”, “Volleyball”, “Basketball”, “Tennis”};

The are 2 correct answers
x A. List list = Arrays.asList(games); 
x B. List list = new ArrayList();

Collections.addAll(list, games);
C. List list=new ArrayList( games);
D. ArrayList list=new ArrayList( games);


___________________________________________________________________________


- 8. 

In the below code, which option will cause a compilation error if inserted in line 3?

public class InitializationTest {

            String employeeName;

            static int  employeeId;

            public static void main(String args[]) {

                        int  employeeId; // line 1

                        Employee employee=new Employee(); // line 2

                        // line 3           

            }

}

class Employee {

            String employeeName;

            int employeeId;

            public static int MINAGE;

            public int getEmployeeId() {

                        return employeeId;

            }

            public void setEmployeeId(int employeeId) {

                        this.employeeId = employeeId;

            }                      

}

The are 1 correct answers

A. System.out.println(employee.getEmployeeId());
x B. System.out.println(employeeId);
C. System.out.println(InitializationTest.employeeId);
D. System.out.println(Employee.MINAGE);





___________________________________________________________________________

- 9. 

What will be the output of the following program?

public class StringTest {

            public static void main(String[] args) {

                        String s1="hello";

                        String s2="hello";

                        String s3=new String("hello");

                        System.out.print(s1==s2);

                        System.out.print(s1==s3);

                        System.out.print(s1.equals(s2));

                        System.out.print(s1.equals(s3));

            }

}

The are 1 correct answers

A. truefalsefalsetrue
x B. truefalsetruetrue
C. truetruefalsetrue
D. truetruetruetrue
E. falsefalsefalsefalse




___________________________________________________________________________

- 10. 

In the given code, how many times will the loop get iterated?

public class LoopTest {

            public static void main(String args[]) {

                        // Loop 1

                        for (int i = 0; i > 5; i++) {

                                    System.out.println(i);

                        }

                        // Loop 2

                        int i = 0;

                        while (i > 5) {

                                    System.out.println(i);

                                    i++;

                        }

                        // Loop 3

                        i = 0;

                        do {

                                    System.out.println(i);

                                    i++;

                        } while (i > 5);

            }

}

The are 1 correct answers

A. Loop 1 = 5, Loop 2 = 5, Loop 3=5;
x B. Loop 1 = 0, Loop 2 = 0, Loop 3=0;
C. Loop 1 = 5, Loop 2 = 5, Loop 3=1;
D. Loop 1 = 1, Loop 2 = 1, Loop 3=0;
E. Loop 1 = 0, Loop 2 = 0, Loop 3=1;




___________________________________________________________________________

- 11. 

What is the output?

The are 1 correct answers

A. 36
x B. 35
C. 37
D. 34

A. 36
x B. 35
C. 37
D. 34






___________________________________________________________________________


- 12. 

Which of the following are valid constructors for the class Student?

 

class Student {    int studentId;}
The are 2 correct answers
x A.    public Student() {
             studentId=0;
             super();
    }
B.  public Student(Student student) {
             studentId = student.studentId;
}
x C. public Student(int studentId, String studentName) {
             this();
             this.studentId = studentId;
}
D. public Student(int studentId) {
             this();
             super();
             this.studentId = studentId;
    }




___________________________________________________________________________

- 13. 

Which of the following statements are correct about Java source files?

The are 3 correct answers

x A. A Java source file can have any number of classes
B. A Java source file can have any number of public classes
x C. If a Java source file contains a public class, the class name and file name should be the same
x D. The number of .class files generated against a source file will be the same as the number of classes in the source file
E. Package statements are always mandatory
F. One or more import statements should be there in all source files





___________________________________________________________________________

- 14. 

Analyze the following output and pick the correct statements.

public class CompareToTest {

            public static void main(String[] args) {

                        Scanner sc = new Scanner(System.in);

                        System.out.print("Enter first String ");

                        String s1 = sc.next();

                        System.out.print("Enter second String ");

                        String s2 = sc.next();

                        System.out.println(s1.compareTo(s2));

            }

}

The are 3 correct answers

x A. If s1 equal to s2 prints 0
B. If s1 equal to s2 prints true
x C. If s1 greater than s2 prints a positive number
D. If s1 greater than s2 prints 1(Always)
x E. If s1 lesser than s2 prints a negative number
F. If s1 lesser than s2 prints -1(Always)

___________________________________________________________________________

- 15. 

Which of the following options will print “true” when placed at line 2?

The are 3 correct answers

public class LogicalOperatorTest {

public static void main(String[] args) {

int a = 10, b = 15, c = 5;
// Line 1

// Line 2

}

}


A. System.out.println(a>b && a>c && true);
x B. System.out.println((a>b && a>c) || c<a);
x C. System.out.println((a>b || a>c) || c<a);
D. System.out.println((a>b || a>c) && c<a && !true);
x E. System.out.println(a<b && c<a );
F. System.out.println((a<b && !(a!=c)) || false );


___________________________________________________________________________

- 16. 

Which of the following package import is mandatory to execute the below program?

public class TestClass{

 public static void main(String[] args){

     double num  = Math.random();

     System.out.println(num);

  }

}

The are 1 correct answers

A. import java.lang.*;
x B. import java.util.*;
C. import java.io.*;
D. No package import required


___________________________________________________________________________

- 17. 

Which of the following lines will compile without any issue?

The are 4 correct answers

public class TypePromotion {

public static void main(String[] args) {

float floatVal=12;

int intVal;

short shortVal;

byte numByte;

double doubleVal;

long longVal;

char c;

numByte = 27; // line 1

shortVal = numByte; // line 2

/ line 3

longVal = intVal; // line 4

// line 5

c = floatVal; // line 6

}

intVal = floatVal;

floatVal = longVal;

}


x A. Line 1
x B. Line 2
C. Line 3
x D. Line 4
x E. Line 5
F. Line 6


___________________________________________________________________________


- 18. 
Assume that the contents of the file ‘C://myfile.txt’ are as follows.

Hello

What will be the output when the below code executes?

The are 1 correct answers

public class ExceptionTest {
public static void main(String[] args) {
readFile("C://myfile.txt");

}

public static void readFile(String path) throws IOException {
File file = new File(path);
FileInputStream in = new FileInputStream(file);
int content;
while ((content = in.read()) != -1) {
System.out.print((char) content);

}

}

}


A. Prints Hello
B. Prints Nothing
x C. Compilation Error
D. Runtime Error




___________________________________________________________________________

- 19. 

What will be printed when the program runs?

The are 1 correct answers


import java.util.ArrayList;
import java.util.List;

public class ArrayListTest {
public static void main(String[] args) {
List<Integer> al= new ArrayList<>();
al.add(5); al.add(10); al.add(15); al.add(20);
al.remove(Integer.value0f(10));
al.remove("15");
System.out.println(al);

}

}


A. [5, 10, 15, 20]
B. [5, 15, 20]
C. [5, 20]
D. Prints Nothing






___________________________________________________________________________

- 20. 

What is the output of the following program?

The are 1 correct answers


public class ForLoopTest {

public static void main(String[] args) {

int total = 0;

int num = 10;

for (int i = num; i >= 1; -- i) {

total += i;

}

System.out.println(total +" "+i);

}

}


A. 50
B. 53
C. 52
D. 56
x E. Compilation error


______________________________________

- 21. 

Which of the following terms are related to inheritance?

The are 2 correct answers

x A. Superclass
x B. Extends
C. Data Abstraction
D. Wrapper Classes
E. Singleton

_________________________________________________

-  22. 


import java.util.ArrayList;
import java.util.Arrays;

public class LoopTest {

public static void main(String args[]) {

ArrayList<String> counties = new ArrayList<String>(
Arrays. asList("India", "China", "Sri Lanka", "USA", "UAE"));

for (String country : counties) {

System.out.println(country);

if (country.contains("China")) {
break;
}

}

}
}

A. Only first element in the list;
x B. First two elements in the list
C. All elements except last
D. All elements
E. Nothing

_______________________________________________

- 23. 

What of the following are the parts of the method signature?

The are 2 correct answers

A. Modifiers
B. Return type
x C. Method name
x D. Parameter list
E. Exception list
F. Method body


___________________________________________________-

- 24. 


What will be the output of the following program?

The are 1 correct answers

public class StringFormatTest {

public static void main(String args[]) {

int num = 1947;

String str = String.format("%08d", num);

System.out.println(str);

}

}

A. 00001947
B. 000000001947
x C. 000019470000
D. 19470000
E. 00000000


________________________________________________

- 25. 

What will be the output of the following program?

The are 1 correct answers

public class SwitchTest {

static int a;

public static void main(String[] args) {

switch (a) {

case 0:

System.out.print("Zero ");

case 1:

System.out.print("One ");

case 2:

System.out.print("Two ");

case 3:

System.out.print("Three ");

default:

System.out.print("Default ");

}

}
}

A. Zero Default
B. Zero One Two Three
C. Zero
x D. Zero One Two Three Default
E. Does not compile

_______________________________________________----

What happens when the below program compiles and runs?

public class ArrayTest {

public static void main(String[] args) {

            int myArr[] = new int[]{1,2,3,4,5,6};

            System.out.print(myArr);

 }

}

The are 1 correct answers

A. Prints 1,2,3,4,5,6
B. Prints 123456
x   C. Prints some value that does not make sense
D. Exception at runtime
E. Code doesn’t compile Successfully


________________________________________________

- 27. 

What will be the output of the following program?

public class OperatorTest {

            public static void main(String[] args) {

                        int a = 40;

                        int b = 5;

                        a -= b++;

                        System.out.print(a + " ");

                        System.out.println(b);

            }

}

The are 1 correct answers

A. 36 6
B. 36 5
C. 35 5
x D. 35 6

_____________________________________________________

- 28. 

What will be the output of the following program?

The are 1 correct answers

public class LabeledTest {

public static void main(String[] args) {

outer:
for (int i = 0; i < 3; i++) {

System.out.print(i); // Line1

inner:
for (int j = 0; j < 3; j++) {
if (j >1) {
break outer;

}

System.out.print(" " + i + " " + j); // Line 2

}

}

}

}


A. Compilation Error
B. Runtime Error
C. 0 0 0 1
D. 1 0 0 0 0
E. 0 0 0 0 1

_____________________________________________________


- 29. 

Which of the following are true about method overloading?

The are 3 correct answers

A. Overloaded methods cannot  be static
x B. The main() method can be overloaded
x C. Subclasses can overload superclass methods
D. Overloaded methods cannot be final
x E. Overloaded methods can be synchronized



_____________________________________________________
- 30. 


What will be printed when the below program runs?

The are 1 correct answers


public class ExceptionHandlingTest {

int getNum() {
try {
int x= 10 / 0;
return x;
} catch (ArithmeticException ae) {
return 20;
} finally {
return 30;

}

}

public static void main(String[] args) {
ExceptionHandlingTest obj = new ExceptionHandlingTest();
System.out.println(obj.getNum());

}

}



_____________________________________________________

- 31. 


Which of the following significance is found in the following code?

public class ReverseTest {

    public static void main(String[] args)

    {

        int numToReverse = 6985;

        int numReversed = 0;

        int mod;

        while (numToReverse != 0) {

            mod = numToReverse / 10;

            numReversed

                = numReversed * 10

                  + mod;

            numToReverse /= 10;

        }

        System.out.println("Reversed number :  "

                           + numReversed);

    }

}

The are 1 correct answers

A. Reversing of given no
x B. A logical Error
C. A syntax Error
D. Exception Handling
E. A runtime Error


_____________________________________________________

- 32. 

Which statements are correct about primitive data type and wrapper classes?

The are 3 correct answers

A. Primitive types can have null values
x B. Wrapper classes can be used with collections
x C. Primitive data types are predefined data types
D. Wrapper classes cannot be used with arrays
x E. Primitive types can be converted to object wrapper class types


_____________________________________________________

- 33. 

What is the output of the following program?

public class IteratorTest {

            public static void main(String args[]) {

                        ArrayList countries = new ArrayList();

                        countries.add("India");

                        countries.add("China");

                        countries.add("America");

                        Iterator it = countries.iterator(); // line 1

                        countries.add("Sri Lanka");  // line 2

                        while (it.hasNext()) {

                                    String obj = (String) it.next();

                                    System.out.print(obj+" ");

                        }

            }

}

The are 1 correct answers

A. Compilation error
B. Prints India China America Sri Lanka
x C. Causes an exception at runtime
D. Prints India China America



_____________________________________________________

- 34. 
What will be the result?

public class TypeCastingTest {

    public static void main(String[] args)

    {

        char c = "C";       //line 1

        int n = 5;              //line 2

        c = n;                   //line 3

       System.out.println(c);

    }

}

The are 1 correct answers

A. Compilation Error in lines 1, 2 and 3
B. Compilation Error in lines 2 and 3
x C. Compilation Error in lines 1 and 3
D. Compiles and prints 5
E. Runtime Error



_____________________________________________________

- 35. 

Which of the following are OOPS concepts?

The are 3 correct answers

x A. Inheritance
B. Exception Handling
x C. Encapsulation
D. Multi-threading
x E. Abstraction
F. Platform independence

__________________________________________________-

- 36. 
What is the output of the following program?

 

The are 1 correct answers


public class MethodOverloadingTest {

public void overLoad(Object object) {

System.out.println("Object method called");

}

public void overLoad() {

System.out.println("No argument method called");

}

public void overLoad(String object) {

System.out.println("String method called");

}

public static void main(String args[]) {

MethodOverloadingTest moe = new MethodOverloadingTest();

moe.overLoad(null);

}
}

A. Print “No argument method called”
B. Print “Object method called”
x C. Print “String method called”
D. Compilation Error
E. Runtime Error


_____________________________________________________

- 37. 


What is true about comments in java?

The are 2 correct answers

x A. Forward slashes (//) is used for single-line comments
x B. /* is used to start multi-line comments and */ is used to end the comments area
C. Backward slashes () are used for single-line comments
D. */ is used to start multi-line comments and */ is used to end the comments area
E. */ is used to start multi-line comments and /* is used to end the comments area



_____________________________________________________

- 38. 

What will be the output?

public class DoWhileLoopTest {

    public static void main(String[] args) {   

        int i=1;

        do

        {

            if(i%2==0)

                System.out.print(" "+i);

            i++;

        }while(i%5!=0);

    }

}

The are 1 correct answers

x A. 2 4
B. 1 2 3 4 5
C. 0 2 4
D. 4 2


_____________________________________________________

- 39. 

Which statements are correct?

The are 3 correct answers

public class CompareToTest {

public static void main(String args[]) {

String str1;

String str2;

Scanner sc= new Scanner(System.in);

System.out.println("Enter string 1");

str1 = sc.nextLine();

System.out.println("Enter string 2");

str2 = sc.nextLine();

System.out.println(str1.compareTo(str2));

}

}

x A. if str1 > str2, it prints a positive number 
B. if str1 > str2, it prints ‘true’
x C. if str1 < str2, it prints a negative number 
D. if str1 < str2, it prints ‘false’ 
x E. if str1 == str2, it prints 0
F. if str1 == str2, it prints nothing 





_____________________________________________________

- 40. 

Which operators have been used in the following expression in ‘if’ condition?

The are 4 correct answers

int a = 1, b = 2, c = 5;

if((!(a == b) && ((b+5)> c)) || (!((c - 3) == 0)))
{

System.out.println("Hello");

}


x A. Arithmetic Operator
B. Shift Operator
x C. Relational Operator
D. Ternary Operator
E. Bitwise Operator
x F. Logical Operator
x G. Unary Operator
_____________________________________________________

- 41. 


What will be the result?

public class OperatorTest {

            public static void main(String args[])

               {

                  int num = 9;

                  int result=0;

                  switch(num)

                  {

                     default :

                     if( num>10) {result=num*10; }

                     else

                     {

                         result = num*5;

                        break;

                     }

                     case 0 : result = 0;

                  }

                  System.out.println(result);

               }

}

The are 1 correct answers

x A. 45
B. 0
C. 9
D. Does Not compile
E. Runtime Exception




_____________________________________________________

- 42. 

Which of the following is NOT true about using import in Java?

The are 1 correct answers

A. It can be used to make a class in a package visible in the current Java source file
x B. It can be used to make a subset of classes in a package visible in the current Java source file
C. Imported classes do not have to be referenced using fully qualified type names
D. When an entire package is imported, the sub packages are not imported




_____________________________________________________

- 43. 

The given program will cause an exception. Which one is that?

public class Example {

public static void main(String args[]) {

List countries = new ArrayList<>();

countries.add("India");

countries.add("China");

countries.add("UK");

Iterator iterator = countries.iterator();

if (iterator.hasNext()) {

iterator.remove();

}
}
}


 A. ConcurrentModificationException
x B. IllegalStateException
C. IllegalArgumentException
D. ArrayIndexOutOfBoundsException
E. UnsupportedOperationException


_____________________________________________________

- 44. 

Find the output of the following program.

The are 1 correct answers

public class MathClassTest {

public static void main(String[] args) {

int randomNum = (int) (Math.random() * 101);

System.out.print(randomNum) ;

}

}

x A. Prints a number between 0 and 100
  B. Gets a random number and multiplies it by 101 and prints
C. Prints a number between 0 and 101
D. Gets a random number between 0 and 100 and multiplies it by 101 and prints





_____________________________________________________

- 45. 

Which of the following are the right statements?

The are 3 correct answers

A. Java supports operator overloading
x B. Java doesn’t support ‘goto’ statement
x C. Java does not support pointers
D. Java is platform dependant
x E. Java converts source code to bytecode at compilation time




_____________________________________________________





_____________________________________________________