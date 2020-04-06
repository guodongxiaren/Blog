## 1. C++是什么？

C++是一个多功能的编程语言，并且偏向于系统编程，它：

- 比C语言更好
- 支持数据抽象（例如：类class）
- 支持面向对象编程（例如：继承）
- 支持泛型编程（例如：可复用的泛型容器和算法）
- 支持函数式编程（例如：模板元编程、lambda函数、`constexpr`）

C++被ISO标准委员会稳定支持了几十年，并且还拥有一个庞大且活跃的用户社区。您可以阅读[《The C++ Programming Language》](http://stroustrup.com/4th.html)和[《Evolving a language in and for the real world: C++ 1991-2006》](http://stroustrup.com/hopl-almost-final.pdf)了解更多。

或者阅读C++[什么时间](#20-c何时被发明)以及[为什么](#21-为什么发明c)被发明。

## 2. C++是一门实用的语言吗？

是的。

C++是一个实用的工具，尽管它不完美，但是它有用。

在工业软件的世界里，C++被视作是一个成熟、稳固且主流的工具。它拥有广泛的工业界的支持，使得它从全面的商业出发变得越来越好。

## 3. C++是一门完美的语言吗？

不是。

C++被设计出来的目的不是用以表现一个完美的编程语言应有的样子。设计它的目的是作为一个接机实际问题的工具。

作为实用型编程工具，它有一些瑕疵。但是继续去打磨语言去达到学术界纯粹的完美，这不是C++的目标！

## 4. 什么是零开销（zero-overhea）原则？

零开销（zero-overhea）原则是**设计C++**的指导方针。它是说：凡是你不使用的，你不要为之付出（时间或空间）。引申出来是：你所能使用的，都是最好的（你不可能自己写的更好）。

换句话说：如果一个新特性会使得C++任何已存在的代码变得更大或者更慢，那么这个新特性就不应该被加入标准；如果新特性使得编译器生成的代码还不如程序员在不使用这个特性时手写的代码，那么这个新特性也不应该被加入标准！

> 译者注：
>
> 这个其实是C++持续演化的原则，要动态看待。就是C++不停修订增加新特性，到低要选择哪些进入标准之中。满足零开销是准入门槛！

## 5. What’s so great about classes?
## 6. What’s the big deal with OO?
## 7. What’s the big deal with generic programming?
## 8. What is multiparadigm programming?
## 9. Is C++ better than Java? (or C#, C, Objective-C, JavaScript, Ruby, Perl, PHP, Haskell, FORTRAN, Pascal, Ada, Smalltalk, or any other language?)
## 10. Why is C++ so big?
## 11. Who uses C++?
## 12. How long does it take to learn C++?
## 13. What’s the best way to improve my C++ programs?
## 14. Does it matter which programming language I use?
## 15. What are some features of C++ from a business perspective?
## 16. Are virtual functions (dynamic binding) central to OO/C++?
## 17. I’m from Missouri. Can you give me a simple reason why virtual functions (dynamic binding, dynamic polymorphism) and templates (static polymorphism) make a big difference?
## 18. Is C++ backward compatible with ANSI/ISO C?
## 19. Why is C++ (almost) compatible with C?
## 20. C++何时被发明？
## 21. 为什么发明C++?
## 22. Where did the name C++ come from?
## 23. Why does C++ allow unsafe code?
## 24. Why are some things left undefined in C++?
## 25. Why is portability considered so important?
## 26. Is C++ standardized?
## 27. Who is on the standardization committee?
## 28. Where can I get a copy of the C++ standard?
## 29. What is the difference between C++98 and C++03?
## 30. What is the difference between C++98 and C++0x?
## 31. What is the difference between C++98 and C++11?
## 32. What is the difference between C++11 and C++14?
## 33. What are some “interview questions” I could ask that would let me know if candidates really know their stuff?
## 34. What does the FAQ mean by “such and such is evil”?
## 35. Will I sometimes use any so-called “evil” constructs?
## 36. Is it important to know the technical definition of “good OO”? Of “good class design”?
## 37. What should I tell people who complain that the word “FAQ” is misleading, that it emphasizes the questions rather than the answers, and that we should all start using a different acronym?
## 38. How can I help make the C++ FAQ even better??!??
