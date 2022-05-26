# Yamini Ecosystem

The Yamini ecosystem consists of a collection of tools and libraries for building compiled and interpreted languages easily. It consists of the following components:

1) [Yamini-VM](https://github.com/yamini-vm/yamini.git) - A virtual machine with simple bytecode IR that allows you to plug your language (interpreted/compiled) front-ends to.
2) [YamASM](https://github.com/yamini-vm/yamasm.git) - An assembler that compiles down to machine code for the Yamini VM.
3) [YDB](https://github.com/yamini-vm/ydb.git) - A debugger that helps you as a contributor of YaminiVM/YamASM to debug your code and check the intermediate tokens and generated code from these two tools.
4) [YamSH](https://github.com/yamini-vm/yamsh.git) - A shell that runs the YamASM assembler and machine code for the Yamini VM, and contains some features that most modern shells don't offer.