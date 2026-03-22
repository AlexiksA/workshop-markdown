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
```
Build with:  
```console
gcc -Wall -o helloworld helloworld.c
```
Run with:  
```console
./helloworld
```
# C++
```C++
#include <iostream>
int main()
{
	std::cout << "Hello, World!" << std::endl;
	return 0;
}
```
Build with:  
```console
g++ -Wall -o helloworld helloworld.cpp
```
Run with:  
```console
./helloworld
```
# D
```Dlang
import std.stdio;
void main()
{
	writeln("Hello, World!");
}
```
Build with:  
```console
gdc -Wall -o helloworld helloworld.cpp
```
Run with:  
```console
./helloworld
```
# Go
```Go
package main
import "fmt"
func main() {
	fmt.Println("Hello, World!")
}
```
Build and run with:  
```console
go run helloworld.go
```
# Rust
```Rust
fn main() {
	println!("Hello, World");
}
```
Build with:  
```console
rustc hello.rs
```
Run with:  
```console
./helloworld
```
# Java
```Java
public class HelloWorld {
	public static void main(String[] args) {
		System.out.println("Hello, World!");
	}
}
```
Build with:  
```console
javac HelloWorld.java
```
Run with:  
```console
java HelloWorld
```
# x86_64 Assembly

Build with:
```console
TODO
```
Run with:  
```console
./helloworld
```
TODO

# ARM64 Assembly

Build with:
```console
TODO
```
Run with:
```console
./helloworld
```
# Bash
```console
echo "Hello, World!"
```
Run with:
```console
bash helloworld.sh
```
# Python
```Python
print("Hello, World!")
```
Run with:
```console
python helloworld.py
```
# Ruby
```Ruby
puts "Hello, World!"
```
Run with:
```console
ruby helloworld.rb
```
# PHP
```PHP
<?php
echo "Hello, World!"
?>
```
Run with:
```console
./helloworld
```
