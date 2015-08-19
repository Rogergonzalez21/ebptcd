# Escuela Bíblica para Todos - CD Version
A small interface made for the "Escuela Bíblica para Todos" CD for "Editorial Bautista de Venezuela.

Using:
*   Bootstrap 3.3.5
*   Jade Template Engine

## How to run it?
You need to install npm and Jade. Here are the instructions:

First, clone the repo to your pc:

    $ git clone https://github.com/Rogergonzalez21/ebptcd.git

Then, install npm:

    $ sudo apt-get install npm

After installing npm, you need to install Jade globaly:    

    $ sudo npm install -g jade

To compile the sources you must:

    $ cd ebptcd/src
    $ jade *.jade -o ../
    
This will compile every .jade into html inside ebptcd/src folder to the ebptcd/ folder.

And that's it.