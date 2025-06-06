# Libft - 42's First Project of the Common Core

## 📚 Project Overview

**Libft** is the first project of the 42 school Common Core curriculum. The objective is to create a personal C library that reimplements many standard C functions, such as those found in `<ctype.h>`, `<string.h>`, and `<stdlib.h>`, along with additional utilities. This library serves as a foundation for future projects and helps build an understanding of C, memory handling, and good coding practices.

## 📁 What’s Included

The project is divided into three main parts:

* **Part 1: Standard libc Functions**
  Reimplementing functions like `ft_strlen`, `ft_memcpy`, `ft_strdup`, etc., without using the originals.

* **Part 2: Additional Useful Functions**
  Includes functions like `ft_split`, `ft_itoa`, `ft_strtrim`, and others that go beyond standard C.

* **Bonus: Linked List Utilities**
  Implementation of a full linked list API using a custom `t_list` structure (e.g., `ft_lstnew`, `ft_lstmap`, etc.).

## 🧠 What I’ve Learned

* **Deep Understanding of C Fundamentals**
  Memory allocation, pointer manipulation, buffer overflows, and handling strings without built-in safeguards.

* **Strict Norm Compliance**
  Writing clean and consistent code that complies with the 42 norm, which emphasizes readability and maintainability.

* **Robust Error Handling**
  Avoiding segmentation faults and leaks was a major focus. I learned to use tools like `valgrind` for leak checking.

* **Creating a Makefile**
  Writing a complete Makefile with all required rules (`all`, `clean`, `fclean`, `re`, `bonus`).

## 😓 Difficulties Encountered

### ft\_split

* **Challenge:** This function was the most difficult due to dynamic memory allocation and the need to handle edge cases (e.g., multiple delimiters, memory cleanup on failure).
* **Lesson:** I learned the importance of careful memory management and writing helper functions to keep the logic clean.

### ft\_itoa

* **Challenge:** Handling negative numbers and the minimum integer value (`INT_MIN`) correctly.
* **Lesson:** Reinforced the understanding of integer limits and conversion logic.

### ft\_memmove

* **Challenge:** Correctly managing overlapping memory regions without corrupting data.
* **Lesson:** Required careful ordering of copying bytes, depending on pointer position.

### Bonus - ft\_lstmap

* **Challenge:** Combining dynamic memory allocation with error handling in linked lists was tricky.
* **Lesson:** Understanding how to prevent memory leaks in case of partial list creation or allocation failure was crucial.

## ✅ Final Thoughts

This project taught me how essential foundational knowledge is in systems programming. It gave me tools and habits that will be valuable in all future 42 projects and beyond. Although challenging, especially without access to standard functions, the learning experience was worth the effort.
