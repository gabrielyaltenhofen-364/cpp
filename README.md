# Getting started with C++

This repository was created for students interested in learning and working with C++. Below are the steps to execute the C++ program:
GABRIELY MOURA ALTENHOFEN-580034
## 1. Clone the repository
````
  $ git clone https://github.com/jstoquica/getting-started-with-cpp.git
````
```cpp
#include <iostream>

int main() {
    std::cout << "Olá, GitHub!" << std::endl;
    return 0;
}



## 2. Compile the *.cpp file
````
  $ g++ application.cpp -o application.o
````
## 3. Execute the output file (*.o)
````
  $ ./application.o
````
#include <iostream>
#include "myheader.h"

int main()
{
	int a = 0;
	std::cin >> a;
	std::cout << myfunc(a);
       
	return 0;
}


## 4. The result of the program is the sum of two or more integers, defined in the *.h file as "myfunc()".

It is worth mentioning that the procedures described are based on the G++ compiler for Linux, version 11.4.0. It is also possible to use online C++ compilers, such as https://www.onlinegdb.com/online_c++_compiler.

## Good coding!

