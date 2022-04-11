[Back to Portfolio](./)

Assembly Lab 1 - Lab 6
===============

-   **Class:  Computer Archetecture CSCI 330** 
-   **Grade:  TBA** 
-   **Language(s):  Assembly** 
-   **Source Code Repository:** [features/mastering-markdown](https://github.com/kilikwhite/csci-330-spring-2022)  
    (Please [email me](mailto:kilikwhite@outlook.com?subject=GitHub%20Access) to request access.)

## Project description

This project is more of a compilation of labs 1 though 6 of programming through assembly.  In lab 1, it was an introduction to assembly code.  Labs 2 and 3 worked on summing the values in an array.  And labs 4, 5, and 6 are about making functions via assembly that mirror C.

## How to compile and run the program

To compile the project, first go to the directory of the lab you want to compile.  Next type nasm -felf64 lab0(lab *).asm && gcc -no-pie -fPIC lab0(lab *).o && ./a.out.  If you are compileing lab01 then you need to type this: nasm -felf64 hello-printf.asm && gcc -no-pie -fPIC hello-printf.o && ./a.out.

```bash
cd ./lab0(lab *)
nasm -felf64 lab0(lab *).asm && gcc -no-pie -fPIC lab0(lab *).o && ./a.out
```


## UI Design

Almost every program requires user interaction, even command-line programs. Include in this section the tasks the user can complete and what the program does. You don't need to include how it works here; that information may go in the project description or in an additional section, depending on its significance.

Lorem ipsum dolor sit amet (see Fig 1), consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat (see Fig 2). Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum (see Fig 3).

![Asm Lab01 code example](images/Project_2_screenshots/Lab_1EX.png)  
Fig 1. Lab01 Code

![screenshot](images/dummy_thumbnail.jpg)  
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)  
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

To be able to run this, it will require the machine to be able to compile Assembly code so make sure that the machine can run assembly before you can use the website. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
