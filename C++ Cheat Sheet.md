C++ Cheat Sheet By Joab Martinez
-----------------------------------------------------------------

C++ is a very powerful language which extends from the C language and is used for multiple systems/application softwares,drivers, client-server applications, and embedded firmware. It is developed by Bjarne Stroustrup. 

![C++](https://upload.wikimedia.org/wikipedia/commons/thumb/1/18/ISO_C%2B%2B_Logo.svg/1200px-ISO_C%2B%2B_Logo.svg.png)

You will need to have two different softwares installed in your computer
A text editor and a C++ Compiler
                - For MacOS
                    -Download the GCC Xcode from Apple’s website and follow the 
                     instructions provided
                        - developer.apple.com/technologies/tools
                - For Windows
				    - You need to install MinGw
					   - www.mingw.org
				    - While installing MinGW, you must select gcc-core, gcc-g++, 
                  binutils, and MinGW runtime
                  
C++ Structure for a basic Hello World script
    #include <iostream>
    using namespace std;

    // main() is where program execution begins.
    int main() {
    cout << "Hello World"; // prints Hello World
    return 0;
    }
    
Execute C++
       1. Save the file as : helloWorld.cpp
       2. Open the command prompt and locate the file
       3. Type in ‘g++ helloWorld.cpp’ and press enter
       4. Once the command prompt generates a.out file, type in a.out to run the
          program
       5. Success!
       
Common Headers  - | Iostream | fstream | math | cctype | string |

Data Types - | Int | char | float | double | void | bool |

Basic Syntax
Object : Objects have states and behaviors.

Class :  A class can be defined as a template/blueprint that describe the behaviors/states that objects of its type support.

Methods : A method is a behavior. A class can maintain multiple methods. It is in methods where the logics are written, data is manipulated and all the actions are executed.

Instance Variables - Each object has its own unique set of instance variables. An object’s state is created by the values assigned to these instance variables

Built-in Types:
    1. Boolean                            bool              Stores either value
                                                            true or false
    2. Character                          char              Typically a single
                                                            octect
    3. Integer                            int               The most natural size
                                                            of integer 
    4. Floating Point                     float             A single-precision
                                                            floating point value
    5. Double Floating Point              double            A double-precision
                                                            floating point value
    6. Valueless                          void              Represents the
                                                            absence of type
    7. Wide Character                     wchar_t           A wide character type
    

        
        
        
        
        asm                                      extern
        else                                     public
        new                                      typedef
        this                                     catch
        auto                                     false
        enum                                     register
        operator                                 typeid
        throw                                    char
        bool                                     float
        explicit                                 reinterpret_cast
        private                                  typename
        true                                     class
        break                                    for
        export                                   return
        protected                                union
        try                                      const
        case                                     friend
        short                                    sizeof
        unsigned                                 virtual
        const_cast                               default
        goto                                     inline
        signed                                   static
        using                                    void
        continue                                 delete
        if                                       int
        static_cast                              double
        volatile                                 mutable
        do                                       switch
        long                                     while
        struct                                   dynamic_cast
        wchar_t                                  namespace                               
        template







Link for Tutorial - https://www.youtube.com/watch?v=Rub-JsjMhWY



