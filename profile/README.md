# Yamini Ecosystem

The Yamini ecosystem consists of a collection of tools and libraries for building compiled and interpreted languages easily. It consists of the following components:

1) [Yamini-VM](https://github.com/yamini-vm/yamini.git) - A virtual machine with simple bytecode IR that allows you to plug your language (interpreted/compiled) front-ends to.
2) [YamASM](https://github.com/yamini-vm/yamasm.git) - An assembler that compiles down to machine code for the Yamini VM.
3) [YDB](https://github.com/yamini-vm/ydb.git) - A debugger that helps you as a contributor of YaminiVM/YamASM to debug your code and check the intermediate tokens and generated code from these two tools.
4) [YamSH](https://github.com/yamini-vm/yamsh.git) - A shell that runs the YamASM assembler and machine code for the Yamini VM, and contains some features that most modern shells don't offer.
5) [Yamtests](https://github.com/yamini-vm/yamtests.git) - Collection of programs written in YamASM assembly that serves as code tests for both YamASM and YaminiVM.
6) [YamLang](https://github.com/yamini-vm/yamlang.git) - A compiled languages that compiles down to YamASM assembly code which can then be compiled down to YaminiVM machine code using YamASM and run using YaminiVM. This project has been paused currently in favour of others and will be resumed soon.

## Languages used

- For the core systems (the virtual machine, assembler, compiled language, and the shell) are written in Rust because they require performance.

- The code test is written in python and is made into a python package which can be installed using pip to make the testing easier.

- The debugger is written in javascript with a jQuery front end and Node.js backend.

## Contributing

- All the projects are open sourced under MIT license and are open to contributions, more documentations will be added soon to each of the repositories to make it easier for new contributors to onboard on the project.