# 3B. Modern C++: Templates, STL Containers, Compile-Time Evaluation & Type Systems

**Area of Study:** 03\. Systems Programming, Modern C++, Rust & Computer Science Algorithms  
**Provider:** Learn C++ (`learncpp.com`)  
**Email Digest Coverage:** August 1, 2026 – November 15, 2026

---

## 1\. Generic Programming, Templates & Compile-Time Execution (`constexpr`)

### \[SYS-CPP-09\] Function Templates & Generic Programming

* **Dates Recommended:** October 25, 2026; November 12, 2026  
* **Direct Link:** [Function Templates \- Learn C++](https://www.learncpp.com/cpp-tutorial/function-templates/)  
* **Expected Learning Outcome:** Master parameterized types, template type deduction, explicit template instantiation, and building type-safe reusable algorithms without code bloat in C++.  
* **Search Tags:** `#Cpp` `#FunctionTemplates` `#GenericProgramming` `#TypeDeduction`

### \[SYS-CPP-10\] Class Templates & Generic Containers

* **Dates Recommended:** October 26, 2026  
* **Direct Link:** [Template Classes \- Learn C++](https://www.learncpp.com/cpp-tutorial/template-classes/)  
* **Expected Learning Outcome:** Master defining generic class templates, managing template member functions, non-type template parameters, and header-only template instantiation rules in C++.  
* **Search Tags:** `#Cpp` `#ClassTemplates` `#GenericContainers` `#Templates`

### \[SYS-CPP-11\] Constexpr Variables & Compile-Time Constants

* **Dates Recommended:** November 7, 2026  
* **Direct Link:** [Constexpr Variables \- Learn C++](https://www.learncpp.com/cpp-tutorial/constexpr-variables/)  
* **Expected Learning Outcome:** Master declaring symbolic compile-time constants with `constexpr`, understanding constant expression evaluation rules, and eliminating runtime initialization overhead in C++.  
* **Search Tags:** `#Cpp` `#constexpr` `#CompileTimeConstants` `#Optimization`

### \[SYS-CPP-12\] Constexpr Functions & Compile-Time Evaluation

* **Dates Recommended:** October 31, 2026  
* **Direct Link:** [Constexpr Functions \- Learn C++](https://www.learncpp.com/cpp-tutorial/constexpr-functions/)  
* **Expected Learning Outcome:** Master writing `constexpr` and `consteval` functions, compile-time argument evaluation rules, and shifting expensive runtime computations into compile-time execution.  
* **Search Tags:** `#Cpp` `#constexprFunctions` `#consteval` `#CompileTimeEvaluation`

---

## 2\. Polymorphism, Overloading, Lambdas & Type Safety

### \[SYS-CPP-13\] Virtual Functions & Runtime Polymorphism

* **Dates Recommended:** October 27, 2026  
* **Direct Link:** [Virtual Functions \- Learn C++](https://www.learncpp.com/cpp-tutorial/virtual-functions/)  
* **Expected Learning Outcome:** Master virtual method tables (`vtable`), virtual destructors, the `override` and `final` specifiers, and dynamic dispatch mechanics in C++ object-oriented architectures.  
* **Search Tags:** `#Cpp` `#VirtualFunctions` `#vtable` `#Polymorphism` `#DynamicDispatch`

### \[SYS-CPP-14\] Operator Overloading Mechanics

* **Dates Recommended:** October 28, 2026  
* **Direct Link:** [Introduction to Operator Overloading \- Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-operator-overloading/)  
* **Expected Learning Outcome:** Master overloading arithmetic, relational, and stream I/O operators for custom classes using friend functions and member functions with intuitive value semantics.  
* **Search Tags:** `#Cpp` `#OperatorOverloading` `#FriendFunctions` `#ValueSemantics`

### \[SYS-CPP-15\] Function Overload Resolution & Ambiguity Handling

* **Dates Recommended:** November 5, 2026  
* **Direct Link:** [Function Overload Resolution and Ambiguous Matches \- Learn C++](https://www.learncpp.com/cpp-tutorial/function-overload-resolution-and-ambiguous-matches/)  
* **Expected Learning Outcome:** Understand compiler overload resolution matching sequences, exact matches, numeric promotions, implicit standard conversions, and resolving ambiguous function calls.  
* **Search Tags:** `#Cpp` `#OverloadResolution` `#FunctionOverloading` `#TypePromotion`

### \[SYS-CPP-16\] Explicit Type Conversion & static\_cast Mechanics

* **Dates Recommended:** November 6, 2026  
* **Direct Link:** [Explicit Type Conversion (Casting) and static\_cast \- Learn C++](https://www.learncpp.com/cpp-tutorial/explicit-type-conversion-casting-and-static-cast/)  
* **Expected Learning Outcome:** Master named casts in C++, compiler type-checking rules for `static_cast`, avoiding dangerous implicit narrowing conversions, and eliminating unsafe C-style type casts.  
* **Search Tags:** `#Cpp` `#static_cast` `#TypeConversion` `#TypeSafety`

### \[SYS-CPP-17\] Lambda Expressions & Anonymous Closures

* **Dates Recommended:** November 8, 2026  
* **Direct Link:** [Introduction to Lambdas (Anonymous Functions) \- Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-lambdas-anonymous-functions/)  
* **Expected Learning Outcome:** Master declaring inline anonymous functions, capture clauses, generic lambda parameters with `auto`, and passing closures to Standard Library algorithms.  
* **Search Tags:** `#Cpp` `#Lambdas` `#Closures` `#CaptureClauses` `#FunctionalCpp`

### \[SYS-CPP-18\] std::optional & Value-Semantics Error Handling

* **Dates Recommended:** August 15, 2026; November 3, 2026  
* **Direct Link:** [std::optional \- Learn C++](https://www.learncpp.com/cpp-tutorial/stdoptional/)  
* **Expected Learning Outcome:** Master using `std::optional<T>` to express nullable return values with value semantics, avoiding sentinel values, and preventing null pointer dereference bugs in C++.  
* **Search Tags:** `#Cpp` `#std_optional` `#ErrorHandling` `#NullableTypes`

### \[SYS-CPP-19\] std::string\_view & Zero-Allocation String Handling

* **Dates Recommended:** August 14, 2026; November 2, 2026  
* **Direct Link:** [Introduction to std::string\_view \- Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-stdstring_view/)  
* **Expected Learning Outcome:** Master non-owning string view parameters, avoiding heap allocations from temporary copies, understanding lifetime management, and preventing dangling view pointer bugs in C++.  
* **Search Tags:** `#Cpp` `#std_string_view` `#ZeroAllocation` `#StringOptimization`

---

## 3\. Containers, Iterators, STL Algorithms & Core Language Rules

### \[SYS-CPP-20\] Passing and Returning std::array

* **Dates Recommended:** November 13, 2026  
* **Direct Link:** [Passing and Returning std::array \- Learn C++](https://www.learncpp.com/cpp-tutorial/passing-and-returning-stdarray/)  
* **Expected Learning Outcome:** Understand why `std::array` is not move-capable unlike `std::vector`, how to pass fixed-size arrays efficiently by `const` reference, and when to use out-parameters or `std::vector` instead.  
* **Search Tags:** `#Cpp` `#std_array` `#Containers` `#StackAllocation`

### \[SYS-CPP-21\] Array Indexing & Signed vs Unsigned Types

* **Dates Recommended:** August 3, 2026  
* **Direct Link:** [Arrays, Loops, and Sign Challenge Solutions \- Learn C++](https://www.learncpp.com/cpp-tutorial/arrays-loops-and-sign-challenge-solutions/)  
* **Expected Learning Outcome:** Understand safe array traversal, `std::ptrdiff_t` vs `std::size_t`, signed vs unsigned implicit conversions, and preventing buffer overruns in C++.  
* **Search Tags:** `#Cpp` `#ArrayIndexing` `#size_t` `#ptrdiff_t` `#SignedUnsigned`

### \[SYS-CPP-22\] Introduction to Iterators & Iterator Invalidation

* **Dates Recommended:** November 14, 2026  
* **Direct Link:** [Introduction to Iterators \- Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-iterators/)  
* **Expected Learning Outcome:** Master C++ container iteration (`begin()`/`end()`), range-based `for` loop mechanics, STL algorithm integration, and avoiding undefined behavior from iterator invalidation.  
* **Search Tags:** `#Cpp` `#Iterators` `#IteratorInvalidation` `#STL`

### \[SYS-CPP-23\] Standard Library Container Iterators Overview

* **Dates Recommended:** August 1, 2026  
* **Direct Link:** [Learn C++ Iterators & STL Archive](https://www.learncpp.com/author/Alex/page/21/)  
* **Expected Learning Outcome:** Understand iterator categories (input, output, forward, random-access), pointer abstraction mechanics, and bridging containers with STL algorithms.  
* **Search Tags:** `#Cpp` `#IteratorCategories` `#RandomAccessIterators` `#STL`

### \[SYS-CPP-24\] Standard Library Algorithms Guide

* **Dates Recommended:** August 2, 2026  
* **Direct Link:** [Introduction to Standard Library Algorithms \- Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-standard-library-algorithms/)  
* **Expected Learning Outcome:** Master `std::find`, `std::count_if`, `std::for_each`, and predicate functions to write clean, loop-free data processing logic using C++ STL algorithms.  
* **Search Tags:** `#Cpp` `#STLAlgorithms` `#std_find` `#std_count_if` `#std_for_each`

### \[SYS-CPP-25\] Language Keywords & Expression Evaluation

* **Dates Recommended:** August 4, 2026 – August 13, 2026 (10 daily issues)  
* **Direct Link:** [Keywords and Naming Identifiers \- Learn C++](https://www.learncpp.com/cpp-tutorial/keywords-and-naming-identifiers/)  
* **Expected Learning Outcome:** Understand C++ keywords, identifier naming rules, memory alignment keywords (`alignas`/`alignof`), and compile-time type qualification mechanics.  
* **Search Tags:** `#Cpp` `#Keywords` `#alignas` `#alignof` `#MemoryAlignment`