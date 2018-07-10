This has further been modified to ensure the Clang-NACL does not break ABI compatibility with non NACL binaries when compiling for NACL
The LLVM back end that accompanies this is located here https://github.com/shravanrn/nacl-llvm.git

Build both LLVM and Clang by following instructions from the below link but using the nacl-llvm.git and nacl-clang.git repos
https://clang.llvm.org/get_started.html

NACL-Clang
==========
This is the modified Clang that supports the NACL backend.

//===----------------------------------------------------------------------===//
// C Language Family Front-end
//===----------------------------------------------------------------------===//

Welcome to Clang.  This is a compiler front-end for the C family of languages
(C, C++, Objective-C, and Objective-C++) which is built as part of the LLVM
compiler infrastructure project.

Unlike many other compiler frontends, Clang is useful for a number of things
beyond just compiling code: we intend for Clang to be host to a number of
different source-level tools.  One example of this is the Clang Static Analyzer.

If you're interested in more (including how to build Clang) it is best to read
the relevant web sites.  Here are some pointers:

Information on Clang:              http://clang.llvm.org/
Building and using Clang:          http://clang.llvm.org/get_started.html
Clang Static Analyzer:             http://clang-analyzer.llvm.org/
Information on the LLVM project:   http://llvm.org/

If you have questions or comments about Clang, a great place to discuss them is
on the Clang development mailing list:
  http://lists.cs.uiuc.edu/mailman/listinfo/cfe-dev

If you find a bug in Clang, please file it in the LLVM bug tracker:
  http://llvm.org/bugs/
