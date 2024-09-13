# DataStructures-Algorithm
Data is actually the value and algorithm is the logic or relation for storing the data
Data strucure is an efficient way of storing the data so that they can be used effectively
Data structures are classified as Primitive and non primitive
Primitive>Define.Intg ,Boolean,Char
Non Primitive>
    Linear       NonLinear
Algorithm:Computed procedure ha take input and produce output
An Algorithm is said to be correct if we get the correct output
    
Imp of Algorithm
  >Time
  >Rescources(Storage)
  >Efficency
  >Shortest Pathh
----------------------------------------------------------------------------->
Code:Code is actually a set of rules that we give the computer to perform a particular task
------------------------------------------------------------------------------>
>C++ is a progimming language which is object oriented
>Powerful and fast
>Platform dependent
>simple
>Memory Management
>Rich Library

Code for HELLO WORLD
#include<iostream>
using namespace std;
int main(){
cout<<"HELLO WORLD"<<endl;
return0;
}

--------------------------------------------------------------------------------->
Input and outputs in c++
Inputs are mainly reffered to the bytes given from devices like printers,keyboard,display to the memory
Outputr are the bytes given from the memory to te devices like printers,keyboard,display


Main header files in c++
iostream-->input output stream-->cout,cin,clog,cerr
iomanip-->input output manipulator-->setw,setprecision
filestream
cout-->Output command,<<,Insertion
cin-->Input command,>>Extraction
clog-->Buffer stream
cerr-->Nonbuffer stream(display error messgaes)

------------------------------------------------------------------------------------->
Datatypes
They are usually saying a  compiler how the user wants the data to be used by the compiler

                                                        DataType
        Primitive                                   Derived                                                   UserDefined
    Int,Float,Char,Bool                   Arrays,Function,Poiner,Reference                              Class,Structures,Union

   Datatype Modifiers
   Signed,Unsigned,Short,Long

   ---------------------------------------------------------------------------------------->
   Variables:Variables are actually name that we assigned to particular values
   Variables are of different types like int,char,float,double,bool
   Variable declaration usaully says about name and type
   Variable definition usually says about assign value ang provide certain memory location

   #include<iostream>
   using namespace std;
   int h=10(Global variable)
   int main(){
     int h=20;
     cout<<h;
     return 0;
   }
   ------------------------------------------------------------------------------------------->
   Operators in C++
   Operators are just like used for performing certain functions using operands
   Arithmetic Operators+,-,/,*,%
   Assignment Operator =
   Comparison Operaor ==
   Compound Assignment Operator +=,-=,%=,/=,*=
   Relational Operators ==,!=,<=,>=,<,>
   Logic Operaors ||,&&,!
   Oth operators-size,conditional(?:),coma
   Precedence PUMDRPM
   ---------------------------------------------------------------------------------------------->]
   Complexity of algthm
   The complexity of an algorithm is usually a measure of its efficiency
   Time Complexity:The time taken for executing a particular algorithm
   Space Complexity:The space taken for exceution of a particular programm

   Order of growth of alghtm
   Te order of growth of an algorithm is computed in terms of
   .Ignore low order constants
   .Ignor he constant preceding to higher valu component

   Eg:n+3n^2
   n^2 is the order of growth

  Asymptoic analysis
  Omega -lower bond-Best Case
  eg:f(n)<=c.g(n)
  consider
  f(n)=2n+1
  so,c=2+1=3
  2n+1<=3.n
  1<=n
     
  BigO-Upperbound-Worst Case
  c.g(n)<=f(n)
  f(n)=2n+1
  so,c=2-1=1
  1.n<=2n+1
  -1<=n

  
  Theta-between upper and lower bound-Average Case
  c1.g(n)<=f(n)<=c2.g(n)
  3.n<=2n+1<=1.n
  c1=1,c2=3
  considering the hisher value n0=3

  Space Complexit=Auxillary Space+Input Space
  Input space is te space taken by he variables & Auxillary space is the space that is required or used during execution of a programme 
  







   
