<p align="center"> 
<img src="https://img.shields.io/badge/-000000?style=for-the-badge&logo=42&logoColor=white)](https://42.fr))"> 
<img src="https://img.shields.io/badge/1337-000000?style=for-the-badge&logo=1337&logoColor=white)](https://1337.ma))">  
<img src="https://img.shields.io/badge/Language-C-blue?style=for-the-badge&logo=c)">
</p> 
<h1 align="center">🚀 ft_printf 🚀</h1> 


## 📘 Project Description
This project involves creating a custom implementation of the standard C library function `printf()`. The goal is to recreate the functionality of `printf()` with a focus on understanding variadic functions, parsing format specifiers, and creating a robust output formatting library.

## 🎯 Project Objectives
- Reproduce the behavior of the standard `printf()` function
- Handle multiple format specifiers
- Implement flexible argument parsing
- Create a reusable library function
- Comply with 42 School's coding norms (Norminette)

## 📋 Mandatory Format Specifiers
- `%c`: Character output
- `%s`: String output
- `%p`: Pointer address
- `%d`: Decimal integer
- `%i`: Integer
- `%u`: Unsigned integer
- `%x`: Hexadecimal (lowercase)
- `%X`: Hexadecimal (uppercase)
- `%%`: Percent sign literal

## 🔍 Technical Challenges
### 1. Variadic Function Handling
- Use of `va_list`, `va_start()`, `va_arg()`, and `va_end()`
- Dynamic argument processing
- Type-safe argument parsing

### 2. Format Specifier Parsing
- Creating a robust parsing mechanism
- Handling edge cases
- Implementing type conversion logic

### 3. Memory Management
- Efficient memory allocation
- Avoiding memory leaks
- Minimizing system resource usage

## 🛠️ Implementation Considerations
- Use of `write()` instead of standard output functions
- Custom buffer management
- Precise error handling
- Performance optimization

## 📚 Learning Outcomes
- Deep understanding of C variadic functions
- Advanced string manipulation
- Low-level system programming concepts
- Parsing and type conversion techniques
