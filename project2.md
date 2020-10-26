[Back to Portfolio](./)

Project 1 Title
===============

-   **Class:** CSCI 315
-   **Grade:** B
-   **Language(s):** C++
-   **Source Code Repository:** [MattYanzer/Project2_HTML_Tag_Checker](https://guides.github.com/MattYanzer/Project2_HTML_Tag_Checker)  
    (Please [email me](mailto:mcyanzer@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

The purpose of this project is to check HTML files to ensure that all tags used are in proper order and determines what the longest stream of non-repeating pages that can be accessed are.

## How to compiles / run the program

In order to properly run the program, execute the below commands inside the project2 folder.
Make sure that you list the address of the file if it's not in the same file as project2.
For example, in order to run the index.html file in the pages folder, run the below code.

```bash
make
./html-test pages/index.html
```
The general format for running the program is as follows.

```bash
make
./html-test <file name here>
```

## UI Design

As afore-mentioned, this project has two purposes. The first purpose is to parse through html files and ensure that the file's tags are balanced, and the second purpose is to find how many unique pages that file can access. For the first purpose, the program utilizes a stack and pushes copies of the names of the tags into the stack. Any time an end tag is found, it is pushed onto the stack and the top two elements of the stack are compared to see if the top element (aka the end tag) matches the element beneath it (aka its supposed start tag). If the tags match, the two elements are popped off of the stack and the parsing continues until the end of the file. The file will be properly balanced if the stack is empty once the parsing finishes since every beginning tag will have been matched with its cooresponding end tag in the proper order. The program will then display a message stating that the file is balanced (see Figure 1). After that, the program will then parse through 

![screenshot](images/dummy_thumbnail.jpg)
Fig 1. The launch screen

![screenshot](images/dummy_thumbnail.jpg)
Fig 2. Example output after input is processed.

![screenshot](images/dummy_thumbnail.jpg)
Fig 3. Feedback when an error occurs.

## 3. Additional Considerations

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. 

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

[Back to Portfolio](./)
