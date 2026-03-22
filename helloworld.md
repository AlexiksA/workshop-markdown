# Helloworld Programs
![helloworld](helloworld.png)  
We list below Helloworld programs for different programming languages, i.e. programs that print "Hello, World!".  
Thespecified compiler or interpreter is required for each programming languages.  
The table below summarizes the programs:  

| Language | Language (Spec) Site | Section | Build / RunDebian / Ubuntu | ToolchainPackages |
|----------|----------------------|---------|----------------------------|-------------------|
| C | [The Standard - C]() | [C](#C) | GCC | `build-essential` |
| C++ | [The Standard - C++]() | [C++](#C++) | GCC / G++ | `build-essential` , `g++` |
| Dlang | [D Programming Language:Home]() | [Dlang](#D) | GCC / GDC | `build-essential` , `gdc` |
| Go | [The Go Programming Language]() | [Go](#Go) | Go | `golang` |
| Rust | [Rust Programming Language]() | [Rust](#Rust) | Rust | `(Crate)rustlang` |
| Java | [Java Programming Language]() | [Java](#Java) | JDK | `openjdk-17-jdk` |
| x86_64 assembly | [x86 and amd64 instructionreferencex]() | [86_64 Assembly](#Asm) | GCC / GAS | `build-essential` | 
| ARM64 assembly | [Arm A64 Instruction Set Architecture]() | [ARM64 Assembly](#ARM64) | GCC / GAS(AArch64) | `build-essential` |
| Bash | [Bash Reference Manual]() | [Bash](#Bash) | Bash | `bash` |
| Python | [Welcome to Python.org]() | [Python](#Python) | Python | `python` |
| Ruby | [Ruby Programming Language]() | [Ruby](#Ruby) | Ruby | `ruby` |
| PHP | [PHP: Hypertext Preprocessor]() | [PHP](#PHP) | PHP | `php` |

## C
```C
#include <stdio.h>
int main(void)
{
puts("Hello, World!");
return 0;
}
Build with:
gcc -Wall -o helloworld helloworld.c
Run with:
./helloworld
```
C++
#include <iostream>
int main()
{
std::cout << "Hello, World!" << std::endl;
return 0;
}
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md
3/910/26/24, 10:32 AM
workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
Build with:
g++ -Wall -o helloworld helloworld.cpp
Run with:
./helloworld
Dlang
import std.stdio;
void main()
{
writeln("Hello, World!");
}
Build with:
gdc -Wall -o helloworld helloworld.cpp
Run with:
./helloworld
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md
4/910/26/24, 10:32 AM
workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
Go
package main
import "fmt"
func main() {
fmt.Println("Hello, World!")
}
Build and run with:
go run helloworld.go
Rust
fn main() {
println!("Hello, World");
}
Build with:
rustc hello.rs
Run with:
./helloworld
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md
5/910/26/24, 10:32 AM
workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
Java
public class HelloWorld {
public static void main(String[] args) {
System.out.println("Hello, World!");
}
}
Build with:
javac HelloWorld.java
Run with:
java HelloWorld
x86_64 Assembly
Build with:
TODO
Run with:
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md
6/910/26/24, 10:32 AM
workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
./helloworld
TODO
ARM64 Assembly
Build with:
TODO
Run with:
./helloworld
Bash
echo "Hello, World!"
Run with:
bash helloworld.sh
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md
7/910/26/24, 10:32 AM
workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
Python
print("Hello, World!")
Run with:
python helloworld.py
Ruby
puts "Hello, World!"
Run with:
ruby helloworld.rb
PHP
<?php
echo "Hello, World!"
?>
Run with:
./helloworld
https://github.com/rosedu/workshop-markdown/blob/solution/helloworld.md
8/910/26/24, 10:32 AM
workshop-markdown/helloworld.md at solution · rosedu/workshop-markdown
Perl
print("Hello, World!\n")
Run with:
perl helloworld.pl
Lua
print("Hello, World!")
Run with:
lua helloworld.lua
