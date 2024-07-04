# java-notes

`important`

```java
System.out.println("Hi");
sout
```
```java
public static void main(String{} args)
psvm
```
```java
arithmetic operators

a(any operator)=b is a = a (operator) b
```
```java
anything written after // has no effect on the code
```
```java
relational operators always return boolean values
```
```java
&& and          || or           ! not 
```
```java
import java.util.scanner;
Scanner sc= new Scanner(system.in);
sc.next*type*();
```
```java
if(expression) {
} else{
}
```
```java
if (expression) {
} else if(expression) {
} else{
}
```
```java
int max=0 can be used when giving condition
```
```java
max = a > b ? a : b ;

this works as

if (a>b) {
   max = a;
} else{
   max = b;
}
```
```java
max = a > b ? a > c ? a : c : b > c ? b : c ;                nested if else statement 
```
```java
switch(day i.e any variable) {
    case 1 :                                                 here cases are the values that can be assigned to the variable 
    System.out.println( "sunday" );                                
    break;
    case 2: case 3:                                         this type is also possible for cases with similar outcomes
                  ..........so on.........

    default :                                               for any type of value that can't be assigned to the variable
    System.out.println ("invalid value");
} 
```
```java
for(int i=0 ;i<=10 ; i++){                                 for loop
     System.out.println(i);
}

while( i<=5 ) {
    System.out.println(i);
     i++;
}                                                          WHILE LOOP    

boolean status = false;
while( !status ) {
     System.out.println("keep trying");
     System.out.println("did you get the answer?");
     status = sc.nextBoolean();
}

int i=8                                                   DO-WHILE LOOP (it runs atleast one time before terminating)
do{
   System.out.println(i);
   i++;
} while (i<=5) ;
   System.out.println("out of the loop");

```
```java
break statement

while(test expression){                                                  do{
//codw                                                                   //code
    if (condition to break) {                                            if (condition to break) {
     break;                                                               break;
    }                                                                     }
//code                                                                   //code
}      [ BREAKS OUT OF THE BRACKETS TO HERE ]                            while ( test expression );   
                                                                           [ BREAKS HERE ]
for ( int ; testExpression; update ) {
   //code
   if (condition to break) {
   break;
   }
//code
}     [ BREAKS HERE ]








