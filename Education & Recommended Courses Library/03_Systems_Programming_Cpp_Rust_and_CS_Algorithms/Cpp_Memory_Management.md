# 3A. Modern C++: Memory Management, Move Semantics & Smart Pointers

**Area of Study:** 03\. Systems Programming, Modern C++, Rust & Computer Science Algorithms  
**Provider:** Learn C++ (`learncpp.com`)  
**Email Digest Coverage:** August 1, 2026 – November 15, 2026

---

## 1\. Value Categories, Rvalue References & Move Semantics

### \[SYS-CPP-01\] Rvalue References & Value Categories

* **Dates Recommended:** October 30, 2026  
* **Direct Link:** [Rvalue References \- Learn C++](https://www.learncpp.com/cpp-tutorial/rvalue-references/)  
* **Expected Learning Outcome:** Understand expressions with identity vs ephemeral temporaries (prvalues/xvalues), binding rules for `Type&&`, and leveraging rvalue references to implement zero-copy move semantics.  
* **Search Tags:** `#Cpp` `#RvalueReferences` `#ValueCategories` `#MoveSemantics`

### \[SYS-CPP-02\] std::move & Rvalue Reference Mechanics

* **Dates Recommended:** October 24, 2026  
* **Direct Link:** [std::move \- Learn C++](https://www.learncpp.com/cpp-tutorial/stdmove/)  
* **Expected Learning Outcome:** Understand lvalues vs rvalues, casting with `std::move`, move constructors, transferring expensive heap-allocated resources, and avoiding post-move dangling object states in C++.  
* **Search Tags:** `#Cpp` `#std_move` `#MoveSemantics` `#ResourceTransfer`

### \[SYS-CPP-03\] Move Constructors & Move Assignment Operators

* **Dates Recommended:** November 1, 2026  
* **Direct Link:** [Move Constructors and Move Assignment \- Learn C++](https://www.learncpp.com/cpp-tutorial/move-constructors-and-move-assignment/)  
* **Expected Learning Outcome:** Master implementing `noexcept` move constructors and move assignment operators, transferring resource ownership from rvalues, eliminating deep heap copy overhead, and adhering to the Rule of Five.  
* **Search Tags:** `#Cpp` `#MoveConstructor` `#MoveAssignment` `#RuleOfFive` `#noexcept`

### \[SYS-CPP-04\] std::move\_if\_noexcept & Exception Safety Guarantees

* **Dates Recommended:** November 4, 2026  
* **Direct Link:** [std::move\_if\_noexcept \- Learn C++](https://www.learncpp.com/cpp-tutorial/stdmove_if_noexcept/)  
* **Expected Learning Outcome:** Master conditional move semantics, checking `noexcept` specifications, preserving the strong exception safety guarantee in container reallocations, and avoiding partially moved states.  
* **Search Tags:** `#Cpp` `#std_move_if_noexcept` `#ExceptionSafety` `#noexcept`

### \[SYS-CPP-05\] Copy Constructors & Copy Initialization

* **Dates Recommended:** October 29, 2026  
* **Direct Link:** [Introduction to the Copy Constructor \- Learn C++](https://www.learncpp.com/cpp-tutorial/introduction-to-the-copy-constructor/)  
* **Expected Learning Outcome:** Master memberwise copy initialization, designing explicit copy constructors, preventing double-free memory bugs, and passing objects by `const` reference in C++.  
* **Search Tags:** `#Cpp` `#CopyConstructor` `#DeepCopy` `#ConstReference`

---

## 2\. Smart Pointers & Ownership Semantics (`std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`)

### \[SYS-CPP-06\] std::unique\_ptr & Exclusive-Ownership Memory Management

* **Dates Recommended:** October 21, 2026; November 10, 2026  
* **Direct Link:** [std::unique\_ptr \- Learn C++](https://www.learncpp.com/cpp-tutorial/stdunique_ptr/)  
* **Expected Learning Outcome:** Master managing dynamically allocated memory with exclusive ownership semantics, automatic scope-based heap deallocation, custom deleters, and eliminating memory leaks without runtime overhead.  
* **Search Tags:** `#Cpp` `#std_unique_ptr` `#SmartPointers` `#RAII` `#ExclusiveOwnership`

### \[SYS-CPP-07\] std::shared\_ptr & Reference Counting Internals

* **Dates Recommended:** October 22, 2026; November 11, 2026  
* **Direct Link:** [std::shared\_ptr \- Learn C++](https://www.learncpp.com/cpp-tutorial/stdshared_ptr/)  
* **Expected Learning Outcome:** Master shared ownership semantics, reference counting control blocks, `std::make_shared` allocation optimization, and avoiding cyclic reference memory leaks in C++.  
* **Search Tags:** `#Cpp` `#std_shared_ptr` `#ReferenceCounting` `#ControlBlocks` `#make_shared`

### \[SYS-CPP-08\] std::weak\_ptr & Breaking Cyclic References

* **Dates Recommended:** October 23, 2026; November 9, 2026  
* **Direct Link:** [Circular Dependency Issues with std::shared\_ptr and std::weak\_ptr \- Learn C++](https://www.learncpp.com/cpp-tutorial/circular-dependency-issues-with-stdshared_ptr-and-stdweak_ptr/)  
* **Expected Learning Outcome:** Master resolving circular dependency deadlocks with `std::weak_ptr`, temporary ownership elevation via `.lock()`, and safe observer pointer semantics in C++.  
* **Search Tags:** `#Cpp` `#std_weak_ptr` `#CircularDependencies` `#MemoryLeaks` `#ObserverPointers`