# **Simple Bash Utils - Project Overview**  

**Simple Bash Utils** is a project focused on developing basic Bash text-processing utilities: **cat** and **grep**, using the **C11 standard**. These utilities are essential command-line tools in Unix-like operating systems.  

## **Project Objectives**  
- Implement **s21_cat** and **s21_grep** with support for various command-line flags.  
- Follow the **POSIX.1-2017 standard** and **Google coding style**.  
- Ensure structured programming and avoid code duplication by reusing common modules.  
- Use **Makefile** for building executable files.  
- Conduct **integration testing** to verify correct behavior.  

## **Project Tasks**  

### **1. cat Utility (`s21_cat`)**  
- Implement `cat` with support for standard and GNU-specific flags (`-b, -e, -n, -s, -t`).  

### **2. grep Utility (`s21_grep`)**  
- Implement `grep` with support for essential flags (`-e, -i, -v, -c, -l, -n`).  
- Use **pcre** or **regex** libraries for regular expressions.  

### **3. Bonus Features**  
- Additional `grep` flags (`-h, -s, -f, -o`).  
- Support for **flag combinations** (e.g., `-iv`, `-in`).  

This project helps reinforce knowledge of Bash utilities, structured programming, and low-level C development. 🚀
