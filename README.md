# rust-quick-start-guide

rust 快速入门 
by 普若哥们儿

https://github.com/wu-hongbing/rust-quick-start-guide

Rust 语法规则比较复杂，rust 组织也发明了很多术语，使得学习 Rust 相比其它语言要困难得多。多数 Rust 资料篇幅很大，让人望而生畏。几乎**没有人**会将 Rust 作为第一门编程语言来学习，学习者通常**已经具有其它语言的经验**，需要一份**精简**而**完整**的资料，放在案头随时查阅。

本教程按照概念和语法项组织内容，每个章节内容尽可能系统而完整，这对于有其它语言经验的读者是有好处的，知识分类更清晰，反复查阅更方便，但是带来的负面问题是造成一些知识点的循环依赖。教程尽力减少前面的内容对后面的内容的依赖，对于具有其它高级语言的先验知识的读者不会造成太大的困扰。建议阅读时保持耐心，顺序阅读，暂时抑制完全明白每一句话的欲望。

实际上，有些教程为了减少没有其它语言经验者的学习难度，将同一类内容分割离散到各处，也仍难以完全避免前面的内容依赖后面内容的问题，根本原因在于语言要素本身就是相互依赖的。

总体上，不需要记住所有的语法细节，Rust 编译器的错误提示非常明确，给出的建议也非常准确，在实践中慢慢就熟练了。Rust 创新的术语非常多，要理解这些术语才能看懂 Rust 的错误提示和建议，另外再保存这篇目录结构清晰的教程，随时查阅。

学习一门编程语言，首先需要了解它的设计思想和目的，Rust 也不例外。如果理解了 Rust 的目的和思想，就会对它的复杂性理解和宽容了。

很多教程介绍语法内容时涉及了标准库，附件中的关键字列表和运算符列表，可以明确哪些是语法规范，哪些是标准库提供的功能。

与其它高级语言不同，Rust 语言规范不限于关键字和运算符的语法逻辑，还包括一些特定的 Trait，比如 Sized、Drop、Copy，……等，这些 Trait 是内嵌于语言中的。在特定的情形下，编译器会自动调用变量类型所实现的特定的 Trait，编译器也会通过查看变量类型是否支持特定的 Trait 而判断是否存在错误。
