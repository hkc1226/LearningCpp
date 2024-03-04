# **`LearningCpp :`**

## **Introduction to _`C++`_ programming:**

- Developed by **_Bjarne Stroustrup_** as an extension to **C language.**

- **_C++_** is a **cross-platform** and **object-oriented** programming language.

- It is used to **create high-performance applications.**

- Provides **high-level of control over system resources** and **memory**.

## **Main differences between _`C++`_ & _`C`_:**

- **_<u>`C++`</u> :_**

  - Supports both **procedural** & **object-oriented programming**.

  - Encapsulate both **Data** & **Functions** together as an object.

  - Supports both **Built-in** & **User-defined** data types.

  - **Object driven** language beacause of **OOPs**.

  - **_Namespace_** features are present in **_`C++ programming`_** to **avoid name collisions**.

  - **Standard IO** header is **_`#include <iostream.h>`_** or **_`#include <iostream>`_**.

- **_<u>`C`</u> :_**

  - Supports **procedural programming** but not **OOPs.**

  - **Data** & **Functions** are separated because of **procedural programming**.

  - Supports only **Built-in** data types but not **User-defined** data types.

  - **Function driven** language because it is **procedural programming.**

  - **_Namespace_** features are not present in **_`C-programming`_**.

  - **Standard IO** header is **_`#include <stdio.h>`_** or **_`#include <stdio>`_**.

  > [**_<u>`Learn more`</u>_**](https://www.geeksforgeeks.org/difference-between-c-and-c/) about differences between **_`C++`_** & **_`C`._**

## **Minimal requirements to run a _`C++`_ code:**

- A **_`C++`_ compiler** installed on your system to compile **_`C++`_** code into machine readable format. Most widely used **_`C++`_** compilers are:

  - **GNU Compiler Collection (GCC):** [**_<u>`download here`</u>_**](https://sourceforge.net/projects/mingw-w64/)

  - **Clang**

  - **Microsoft Visual C++ Compiler** (For Microsoft VS code user)

- A **Text-editor** or an **Integrated Development Environment (IDE).**

  - **_Text-editor :_** Notepad++, Sublime text, Atom.

  - **_IDE :_** Turbo C/C++, Visual Studio Code, Code::Blocks, Eclipse, Xcode.

  ### **Follow the steps to run your code:**

  After complete installation of an **IDE** and a **text-editor.**

  - Write your code in the text-editor and save it with **_`.cpp`_** / **_`.cc`_** / **_`.cxx`_** / **_`.c++`_** extension.

  - Once **_`.cpp`_** file is saved, open any terminal or command prompt.

  - Navigate to the folder where **_`.cpp`_** files are saved.

  - Now **Compile** and **Run** with the following command:

    - **_To <u>Build / Compile</u> :_** Write command **_`g++ -o filename filename.cpp`_** in command line **Hit Enter.**

      ![command to compile cpp code](./Images/compile-cpp-code.png)

    - **_To <u>Run</u> :_** Write command **_`filename.exe`_** in command line and **Hit Enter.**

      ![command to run cpp code](./Images/run-cpp-code.png)

## **Basic Structure of _`C++`_ programming:**

- Here is the **basic structure** of **_`C++`_** code.

  ![Basic Structure of Cpp](./Images/basic-structure-of-cpp-code.png)

### **_Explanation:_**

- **_Line 1:_** consists of a **_<u>Preprocessor Directives</u>_** & **_<u>Header File Liberary</u>._**

  - **_Preprocessor directives: <u>`#include`</u>, <u>`#define`</u>_ etc.**

    - It instructs the compiler and processed before code compilation. It starts with **hash _( `#` )_** character.

    - **_`#include`:_** Used to **include _header file liberary._**

      ![Preprocessor directive > include](./Images/preprocessor-directives-include.png)

    - **_`#define`:_** Used for **defining _constant_** or **_macros._**

      ![img1](./Images/preprocessor-directives-const-definition.png)

      ![img2](./Images/preprocessor-directives-macros-definition.png)

  - **_Header file liberary: <u>`<iostream>`</u>, <u>`<cmath>`</u>, <u>`<ctime>`</u>, <u>`<fstream>`</u>, <u>`<string>`</u>_ etc.**
    - Each header file liberary offers a wide range of functionalities to use within the **_`C++`_** code.
      <br>
      <br>

<hr style="background:linear-gradient(to right,violet,indigo,blue,green,yellow, orange, red);border-radius:50px; height:10px;border:2px solid black;">

## **Some standard liberary objects:**

- **_`cout` :_** used with **_`<<`_** to **output values / print** text on console or display. By default **_`cout`_** does not insert any new line automatically after the completion of **_`cout`_** statement(S).

  - **e.g:-**

    ![cout-example](./Images/cout-example.png)

- **_`endl` :_** Terminate the current line and jump into a **new-line.**

  - **e.g:-**

    ![endl-example](./Images/endl-example.png)

<hr style="background:linear-gradient(to right,violet,indigo,blue,green,yellow, orange, red);border-radius:50px; height:10px;border:2px solid black;">

## **Escape Sequence:**

- **_newline character (`\n`) :_** Terminate the current line and jump into a **new-line.**

- **_tabspace character (`\t`) :_** Insert a **tabspace** (that is equivalent to **_4-space character_**) **between current-line and new-line** or **within a line.**

- **_backslash character (`\\`) :_** Insert a **backslash** character.

- **_double quote character (`\"`) :_** Insert a **double quote** character.

  - **e.g:-**

    ![2-esc-seq](./Images/2-esc-seq-example.png)

<hr style="background:linear-gradient(to right,violet,indigo,blue,green,yellow, orange, red);border-radius:50px; height:10px;border:2px solid black;">

## **Comment style in _`Cpp` :_**

- There are two ways to write comment in _`Cpp`_.

  ![comment-style](./Images/comment-style.png)

<hr style="background:linear-gradient(to right,violet,indigo,blue,green,yellow, orange, red);border-radius:50px; height:10px;border:2px solid black;">
