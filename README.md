# OPPS_C-
# Name: TARIQ AKHLAK
# PRN: 22070123124

# Overloading
Function overloading is a feature of object-oriented programming where two or more functions can have the same name but different parameters. 
When a function name is overloaded with different jobs it is called Function Overloading.
f multiple functions having same name but parameters of the functions should be different is known as Function Overloading.
If we have to perform only one operation and having same name of the functions increases the readability of the program.

# EXPERIMENT NO: 1
AIM: Basic operation using function overloading
Algorithm:

--> STEP 1: START
--> STEP 2: Take input from the user and create a class
--> STEP 3:  
    int a;
    overload(){
        a = 10;
    }
    overload(int x){
        a=x;
    }
    overload(overload &aa){
        a = aa.a;
    }
    void display(){
        cout<<"Display output: "<<a<<endl;
    }
--> STEP 4: Instantiation of object in main function
--> STEP 5: Print the output
--> STEP 6: STOP

OUTPUT
Display output: 10
Display output: 20
Display output: 10

# EXPERIMENT NO: 2
AIM: Add, subtract and multiple using overloading
Algorithm:

--> STEP 1: START
--> STEP 2: Take input from the user and create a class
--> STEP 3:  
    int a, b, c, d;
    multiple(int a, int b){
        c = a+b;
    }
    multiple(float a, float b, float d){
        c = a-b-d;
    }
    multiple(int a ){
        c = a*a;
    }
    void display(){
        cout<<"Output is: "<<c<<endl;
    }
--> STEP 4: Instantiation of object in main function
--> STEP 5: Print the output
--> STEP 6: STOP

OUTPUT
Output is: 30
Output is: -13
Output is: 81
