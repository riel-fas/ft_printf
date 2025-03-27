<p align="center"> 
<img src="https://img.shields.io/badge/42-Network-black?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAABiElEQVQ4y2NgGFQggv//CSgoKCgqKioqKSkpKSkpffz48f///f8P0tjR0VHe3t5e29zcXNLc3FzS2NhY0tDQUNLQ0FDS1NRc0traurS1tXVpW1vb0tbW1qVtbW1L29vbl7a3ty9tb29f2tHRsbSjo2Npe3v70s7OzqWdnZ1LBwYGlw4ODi4dGhpaOjQ0tHRkZGTp6Ojo0rGxsaVjY2NLx8fHl46Pjy8dHx9fOjExsXRycnLpzMzM0llg8D8K//37R/Dv3z+Cv3//Evz//5/g+/cfBP/+/Sf4/v0nwe/fvwm+ff9F8OfPX4Kf\n P34T/Pz5i+Dnz98Ev3//Ifj9+y/Bn/2/gAr+ATX+hCr+AVWAqQAW+APU8Aeo4R9Qw19QDf+BGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBr+ATX8A2r4B9TwD6jhH1DDH6CGf0AN/4Aa/gE1/ANq+AfU8A+o4R9Qwz+ghn9ADf+AGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBoYAABhKkjR0SIEzwAAAABJRU5ErkJggg==" alt="42 Network"> 
<img src="https://img.shields.io/badge/1337-Coding-green?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAAACXBIWXMAAAsTAAALEwEAmpwYAAABiElEQVQ4y2NgGFQggv//CSgoKCgqKioqKSkpKSkpffz48f///f8P0tjR0VHe3t5e29zcXNLc3FzS2NhY0tDQUNLQ0FDS1NRc0traurS1tXVpW1vb0tbW1qVtbW1L29vbl7a3ty9tb29f2tHRsbSjo2Npe3v70s7OzqWdnZ1LBwYGlw4ODi4dGhpaOjQ0tHRkZGTp6Ojo0rGxsaVjY2NLx8fHl46Pjy8dHx9fOjExsXRycnLpzMzM0llg8D8K//37R/Dv3z+Cv3//Evz//5/g+/cfBP/+/Sf4/v0nwe/fvwm+ff9F8OfPX4Kf\n P34T/Pz5i+Dnz98Ev3//Ifj9+y/Bn/2/gAr+ATX+hCr+AVWAqQAW+APU8Aeo4R9Qw19QDf+BGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBr+ATX8A2r4B9TwD6jhH1DDH6CGf0AN/4Aa/gE1/ANq+AfU8A+o4R9Qwz+ghn9ADf+AGv4BNfwDavgH1PAPqOEfUMM/oIZ/QA3/gBoYAABhKkjR0SIEzwAAAABJRU5ErkJggg==" alt="1337 Coding"> 
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
