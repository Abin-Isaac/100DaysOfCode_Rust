# 100 Days Of Code in Rust

## Learning Source : https://www.w3adda.com/rust-tutorial

## First day 
We are using a main function here, seems like every rust program has this Referee here 

Remember, <b> println </b> is macro and ! is required to invoke it. 

Semi_colon is needed to end a statement.

After this interacton it seems like entering naughty student caged in strict Teachers class. Cursor brackets shows the cage {cage or performance ?}

If you are pythonista please remember println doesn't know 2+2 so you need to provide needed string formatting Okay!! 

Run the code here :- https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=d65d1e138a9b3ae060da7d10a5aa172d

## Second day 

Lets dive into 3 easy peasy comments of rust..probably you may be knowning them 

Single line comments should start with  //

Multi line comments should start with  /* and end with */

Doc comment should start and end with ///

Thats it..

Run the code here 
https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=26441c7be90bc0de62c2fad881e895ba

## Third day 

Variables are a vital point in every prg. language. Here we have some of them like : Numbers, Text and Boolean etc

Here you can define type or Rust will take it automatically and Rust has lot of size options with the type like in Numpy...felt like I reached numpy :)

Overflow will happen if you put more things than space...so just keep that in mind !

 4 ways to declare variable in Rust:-
1) let a; // Declaration without type
2) let b : i32; // Declaration with  type
3) let c: i32 = 10; // Declaration with initialization with type
4) let d = 20; // Declaration with initialization with type inference
    
Run the code here 
https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=ac1c30534ff8f6c2d8b9add960a08096

## Fourth day 

Every variable in Rust is immutable. never dare to change any one !

If you want you can created mutable varaibles using mut keyword

and if you reassign any mutable variables without usage then Rust can give you a warning...so dont waste resources..OKAY ?

Run the code here 
https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=581ded6c9c86f4db38abb3945529f5bf

## Fifth day 

You need to use {} to print variables and this is called "String Interpolation"

In String interpolation the compiler understands by {} and after the comma come the argument which is interpolated

Run the code here 
https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=652b62c4d811dc10ea4dfd8a76d50647

## Sixth day 
Using Const keyword - Lets create constants
1) const A : i32 = 20 // Capitals and data type are required otherwise you will get a warning
2) No fixed address for a constant variable
3) Lives for entire life time of program
4) Finally unchangable as we all know

Run the code here 
https://play.rust-lang.org/?version=stable&mode=debug&edition=2021&gist=e7ccbccaf6e19aa17bd34336dc27c6b1

