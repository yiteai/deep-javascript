# Deep JavaScript: ECMAScript Principles

> Not a how-to guide — a why-it-works guide. From Brendan Eich's 10-day design decisions to V8 JIT deoptimization, covering all core ECMAScript mechanisms: type system, prototype chain, execution contexts, closures, event loop, Promise resolution algorithm, ESM module linking. Four-layer structure per chapter serves developers at every level. 35 chapters — the most in-depth ECMAScript internals guide in Chinese.

**📖 Read the full book online (free): [https://tools.yiteai.com/en/books/ecmascript](https://tools.yiteai.com/en/books/ecmascript)**

*A deep-dive technical book by [YiteAI](https://tools.yiteai.com). This repo is the companion index — every chapter links to the full text on the site.*

---
## Table of Contents

- [Built in 10 Days: Brendan Eich's Design Trade-offs and JavaScript's Historical Debt](https://tools.yiteai.com/en/books/ecmascript/ch01)
- [ES1 to ES2027: What Each Version Fixed and the TC39 Stage 0-4 Process](https://tools.yiteai.com/en/books/ecmascript/ch02)
- [How to Read the ECMAScript Spec: Notation, Abstract Operations, Algorithm Steps](https://tools.yiteai.com/en/books/ecmascript/ch03)
- [Source to Execution: The Complete V8 Engine Pipeline](https://tools.yiteai.com/en/books/ecmascript/ch04)
- [8 Language Types and Their Internal Representations](https://tools.yiteai.com/en/books/ecmascript/ch05)
- [ToPrimitive: The Complete Object-to-Primitive Conversion Algorithm](https://tools.yiteai.com/en/books/ecmascript/ch06)
- [Abstract Equality: Deriving All 12 Rules of ==](https://tools.yiteai.com/en/books/ecmascript/ch07)
- [IEEE 754 and Number Precision: The Real Reason 0.1+0.2 Fails](https://tools.yiteai.com/en/books/ecmascript/ch08)
- [BigInt and Symbol: The Design Philosophy Behind Two Special Types](https://tools.yiteai.com/en/books/ecmascript/ch09)
- [String and Unicode: UTF-16, Surrogate Pairs, and Code Point Traps](https://tools.yiteai.com/en/books/ecmascript/ch10)
- [Operator Algorithms: +, delete, in, instanceof, typeof, ?. and ??](https://tools.yiteai.com/en/books/ecmascript/ch11)
- [Property Descriptors: 4 Internal Slots and Object.defineProperty](https://tools.yiteai.com/en/books/ecmascript/ch12)
- [The Prototype Chain: Complete [[Prototype]] Lookup Algorithm](https://tools.yiteai.com/en/books/ecmascript/ch13)
- [Ordinary and Exotic Objects: [[Get]], [[Set]], [[Call]] Internal Methods](https://tools.yiteai.com/en/books/ecmascript/ch14)
- [Proxy and Reflect: 13 Traps and Complete Metaprogramming](https://tools.yiteai.com/en/books/ecmascript/ch15)
- [Execution Context Stack and Realm: Call Stack Structure and Cross-Realm Traps](https://tools.yiteai.com/en/books/ecmascript/ch16)
- [Environment Records and Reference Records: The Complete Scope Chain](https://tools.yiteai.com/en/books/ecmascript/ch17)
- [var, let, const: Spec-Level Differences and the Temporal Dead Zone](https://tools.yiteai.com/en/books/ecmascript/ch18)
- [Closures: The Precise Definition of Function + Lexical Environment](https://tools.yiteai.com/en/books/ecmascript/ch19)
- [this: 5 Binding Rules, Priority Order, and ResolveThisBinding](https://tools.yiteai.com/en/books/ecmascript/ch20)
- [Function Object Internals: [[Call]] vs [[Construct]], arguments, bind, Tail Calls](https://tools.yiteai.com/en/books/ecmascript/ch21)
- [Generators and the Iteration Protocol: Complete Symbol.iterator Implementation](https://tools.yiteai.com/en/books/ecmascript/ch22)
- [Under the Hood of class: ClassDefinitionEvaluation and Private Fields](https://tools.yiteai.com/en/books/ecmascript/ch23)
- [async/await: The Complete Desugaring to Generator Form](https://tools.yiteai.com/en/books/ecmascript/ch24)
- [The Event Loop: Spec-Level Definitions of Job Queue and Task Queue](https://tools.yiteai.com/en/books/ecmascript/ch25)
- [Promises: PromiseCapability and the Resolution Algorithm](https://tools.yiteai.com/en/books/ecmascript/ch26)
- [The Microtask Queue: A Complete Proof of Execution Order](https://tools.yiteai.com/en/books/ecmascript/ch27)
- [Error and Completion Record: Spec Semantics of try/catch/finally](https://tools.yiteai.com/en/books/ecmascript/ch28)
- [SharedArrayBuffer and Atomics: The Memory Model for Multi-threaded JS](https://tools.yiteai.com/en/books/ecmascript/ch29)
- [ESM: Linking, Instantiation, Evaluation Phases and Circular Dependencies](https://tools.yiteai.com/en/books/ecmascript/ch30)
- [Automatic Semicolon Insertion: 7 Rules and Classic Traps](https://tools.yiteai.com/en/books/ecmascript/ch31)
- [Destructuring and Spread: Spec Semantics and Edge Behaviors](https://tools.yiteai.com/en/books/ecmascript/ch32)
- [Iterators and the Iterable Protocol: How for...of Really Works](https://tools.yiteai.com/en/books/ecmascript/ch33)
- [V8 Internals: Hidden Classes, Inline Caches, and JIT Deoptimization](https://tools.yiteai.com/en/books/ecmascript/ch34)
- [Memory Management: Generational GC, WeakRef, and DevTools Memory Profiling](https://tools.yiteai.com/en/books/ecmascript/ch35)

---
## 中文版

# 深入理解 JavaScript：ECMAScript 原理

> 不教你怎么写 JS，教你 JS 为什么这样运行。从 Brendan Eich 的10天设计决策到 V8 引擎 JIT 反优化，覆盖 ECMAScript 规范全部核心机制：类型系统、原型链、执行上下文、闭包、事件循环、Promise 解析算法、ESM 模块链接……每章四层结构，同时服务1-3年、3-5年和资深 JavaScript 开发者。35章，中文最深度的 ECMAScript 原理完全指南。

**📖 在线免费阅读全文:[https://tools.yiteai.com/books/ecmascript](https://tools.yiteai.com/books/ecmascript)**

### 目录

- [10天造出的语言：Brendan Eich 的设计取舍与历史债务](https://tools.yiteai.com/books/ecmascript/ch01)
- [ES1 到 ES2027：每个版本解决了什么，TC39 提案 Stage 0-4](https://tools.yiteai.com/books/ecmascript/ch02)
- [如何读 ECMAScript 规范：符号、抽象操作、算法步骤](https://tools.yiteai.com/books/ecmascript/ch03)
- [从源码到执行：V8 引擎的完整链路](https://tools.yiteai.com/books/ecmascript/ch04)
- [8种语言类型与内部表示](https://tools.yiteai.com/books/ecmascript/ch05)
- [ToPrimitive：对象转基础类型的完整算法](https://tools.yiteai.com/books/ecmascript/ch06)
- [抽象相等比较：== 的12条规则完整推导](https://tools.yiteai.com/books/ecmascript/ch07)
- [IEEE 754 与 Number 精度：0.1+0.2 的底层真相](https://tools.yiteai.com/books/ecmascript/ch08)
- [BigInt 与 Symbol：两个特殊类型的设计哲学](https://tools.yiteai.com/books/ecmascript/ch09)
- [String 与 Unicode：UTF-16、代理对与码点陷阱](https://tools.yiteai.com/books/ecmascript/ch10)
- [运算符的规范算法：+、delete、in、instanceof、typeof、?.、??](https://tools.yiteai.com/books/ecmascript/ch11)
- [属性描述符：4个内部槽与 Object.defineProperty](https://tools.yiteai.com/books/ecmascript/ch12)
- [原型链：[[Prototype]] 查找算法的完整机制](https://tools.yiteai.com/books/ecmascript/ch13)
- [普通对象与异质对象：[[Get]][[Set]][[Call]] 内部方法](https://tools.yiteai.com/books/ecmascript/ch14)
- [Proxy 与 Reflect：13个陷阱与元编程完整实现](https://tools.yiteai.com/books/ecmascript/ch15)
- [执行上下文栈与 Realm：调用栈结构与跨领域陷阱](https://tools.yiteai.com/books/ecmascript/ch16)
- [环境记录与 Reference Record：作用域链的完整机制](https://tools.yiteai.com/books/ecmascript/ch17)
- [var/let/const：三种绑定的规范级差异与 TDZ](https://tools.yiteai.com/books/ecmascript/ch18)
- [闭包：函数 + 词法环境的精确定义](https://tools.yiteai.com/books/ecmascript/ch19)
- [this：5种绑定规则、优先级与 ResolveThisBinding](https://tools.yiteai.com/books/ecmascript/ch20)
- [函数对象内部结构：[[Call]] vs [[Construct]]、arguments、bind、尾调用](https://tools.yiteai.com/books/ecmascript/ch21)
- [生成器与迭代协议：Symbol.iterator 的完整实现](https://tools.yiteai.com/books/ecmascript/ch22)
- [class 的底层：ClassDefinitionEvaluation 与私有字段](https://tools.yiteai.com/books/ecmascript/ch23)
- [async/await：Generator 语法糖的完整脱糖形态](https://tools.yiteai.com/books/ecmascript/ch24)
- [事件循环：Job Queue 与 Task Queue 的规范定义](https://tools.yiteai.com/books/ecmascript/ch25)
- [Promise：PromiseCapability 与解析算法](https://tools.yiteai.com/books/ecmascript/ch26)
- [微任务队列：执行顺序的完整证明](https://tools.yiteai.com/books/ecmascript/ch27)
- [Error 与 Completion Record：try/catch/finally 规范语义](https://tools.yiteai.com/books/ecmascript/ch28)
- [SharedArrayBuffer 与 Atomics：多线程 JS 的内存模型](https://tools.yiteai.com/books/ecmascript/ch29)
- [ESM：链接、实例化、求值三阶段与循环依赖处理](https://tools.yiteai.com/books/ecmascript/ch30)
- [ASI 自动分号插入：7条规则与经典陷阱](https://tools.yiteai.com/books/ecmascript/ch31)
- [解构与展开：规范语义与边界行为](https://tools.yiteai.com/books/ecmascript/ch32)
- [迭代器与可迭代协议：for...of 的完整内部机制](https://tools.yiteai.com/books/ecmascript/ch33)
- [V8 内部：Hidden Class、内联缓存与 JIT 反优化](https://tools.yiteai.com/books/ecmascript/ch34)
- [内存管理：分代回收、WeakRef 与 DevTools 内存分析](https://tools.yiteai.com/books/ecmascript/ch35)

---
## About YiteAI

[YiteAI](https://tools.yiteai.com) 是面向开发者的 AI 工具箱 + 技术书库 + AI Agent Skills 市场。更多免费技术书:[https://tools.yiteai.com/books](https://tools.yiteai.com/books)

> ⚖️ Content © YiteAI. This repo indexes the book; the full text is hosted on the site. Please link back rather than mirror.
