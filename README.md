# Blog OS

## Overview

This repository is my personal learning project, based on the **Writing an OS in Rust** series hosted at [os.phil-opp.com](https://os.phil-opp.com). It serves as a sandbox for understanding operating system development and the Rust programming language.

## Learning Objectives

- To delve into the internals of operating system design.
- To enhance my Rust programming skills through practical OS development.
- To chronicle my journey and learning experiences step by step.

## Posts

The goal of this project is to provide step-by-step tutorials in individual blog posts. The original project currently have the following set of posts:

**Bare Bones:**

- [A Freestanding Rust Binary](https://os.phil-opp.com/freestanding-rust-binary/) [[source code](https://github.com/phil-opp/blog_os/tree/post-01)]
- [A Minimal Rust Kernel](https://os.phil-opp.com/minimal-rust-kernel/) [[source code](https://github.com/phil-opp/blog_os/tree/post-02)]
- [VGA Text Mode](https://os.phil-opp.com/vga-text-mode/) [[source code](https://github.com/phil-opp/blog_os/tree/post-03)]
- [Testing](https://os.phil-opp.com/testing/) [[source code](https://github.com/phil-opp/blog_os/tree/post-04)]

**Interrupts:**

- [CPU Exceptions](https://os.phil-opp.com/cpu-exceptions/) [[source code](https://github.com/phil-opp/blog_os/tree/post-05)]
- [Double Faults](https://os.phil-opp.com/double-fault-exceptions/) [[source code](https://github.com/phil-opp/blog_os/tree/post-06)]
- [Hardware Interrupts](https://os.phil-opp.com/hardware-interrupts/) [[source code](https://github.com/phil-opp/blog_os/tree/post-07)]

**Memory Management:**

- [Introduction to Paging](https://os.phil-opp.com/paging-introduction/) [[source code](https://github.com/phil-opp/blog_os/tree/post-08)]
- [Paging Implementation](https://os.phil-opp.com/paging-implementation/) [[source code](https://github.com/phil-opp/blog_os/tree/post-09)]
- [Heap Allocation](https://os.phil-opp.com/heap-allocation/) [[source code](https://github.com/phil-opp/blog_os/tree/post-10)]
- [Allocator Designs](https://os.phil-opp.com/allocator-designs/) [[source code](https://github.com/phil-opp/blog_os/tree/post-11)]

**Multitasking**:

- [Async/Await](https://os.phil-opp.com/async-await/) [[source code](https://github.com/phil-opp/blog_os/tree/post-12)]


## First Edition Posts

The current version of the blog is already the second edition. The first edition is outdated and no longer maintained, but might still be useful. The posts of the first edition are:

<details><summary><i>Click to expand</i></summary>

**Bare Bones:**

- [A Minimal x86 Kernel](https://os.phil-opp.com/multiboot-kernel.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_1)]
- [Entering Long Mode](https://os.phil-opp.com/entering-longmode.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_2)]
- [Set Up Rust](https://os.phil-opp.com/set-up-rust.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_3)]
- [Printing to Screen](https://os.phil-opp.com/printing-to-screen.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_4)]

**Memory Management:**

- [Allocating Frames](https://os.phil-opp.com/allocating-frames.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_5)]
- [Page Tables](https://os.phil-opp.com/modifying-page-tables.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_6)]
- [Remap the Kernel](https://os.phil-opp.com/remap-the-kernel.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_7)]
- [Kernel Heap](https://os.phil-opp.com/kernel-heap.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_8)]

**Exceptions:**

- [Handling Exceptions](https://os.phil-opp.com/handling-exceptions.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_9)]
- [Double Faults](https://os.phil-opp.com/double-faults.html) [[source code](https://github.com/phil-opp/blog_os/tree/first_edition_post_10)]

**Additional Resources:**

- [Cross Compile Binutils](https://os.phil-opp.com/cross-compile-binutils.html)
- [Cross Compile libcore](https://os.phil-opp.com/cross-compile-libcore.html)
- [Set Up GDB](https://os.phil-opp.com/set-up-gdb)
- [Handling Exceptions using Naked Functions](https://os.phil-opp.com/handling-exceptions-with-naked-fns.html)
    - [Catching Exceptions](https://os.phil-opp.com/catching-exceptions.html) [[source code](https://github.com/phil-opp/blog_os/tree/catching_exceptions)]
    - [Better Exception Messages](https://os.phil-opp.com/better-exception-messages.html) [[source code](https://github.com/phil-opp/blog_os/tree/better_exception_messages)]
    - [Returning from Exceptions](https://os.phil-opp.com/returning-from-exceptions.html) [[source code](https://github.com/phil-opp/blog_os/tree/returning_from_exceptions)]

</details>


