# LaunchLab Fresher's Training 2ed

This repository contains all the materials related to the basic MOSFET theory, CMOS technology, circuit and layout design, and basic PDK design.

# Introduction to Linux, Scripting and Python

This is the first module required by all trainees to introduce them to basic fundamentals of working on a Linux System, basic scripting skills in Linux and Python programming.

- **LINUX OS** access is the first and foremost thing everyone should get setup with. Although, you have access to **CentOS** Linux in the Lab., it is very easy to setup a Linux distribution on your own laptop or desktop running windows.
  - The preferred and recommneded method for it is **Windows Subsystem for Linux 2 (WSL2)**.  [Windows Subsytem for Linux (WSL2)](https://github.com/silicon-vlsi-org/eda-wsl2) provides detail instructions on how to enable WSL and then install the Linux distribution **Ubuntu 24.04** on it. Then you can install **iverilog** and **gtkwave** to start doing difital design. **NOTE** Please follow these instructions carefully and don't use other guides on the internet.
  - The other _alternative_ is **Virutal Box** from Oracle. If you already have Virtual Box installed and **Ubunut 24.04** installed, then you can use it as well. Rememeber, this is much more resource hungry than WSL. [This module on Virtual Box](https://github.com/silicon-vlsi-org/eda-virtualmachine) provides instructions on how to install it.

- **LINUX COMMANDS**: For those who are new to Linux or rusty in it, [these set of 8 modules](https://github.com/silicon-vlsi-org/module-cs3-301) introduces the candidate from basic to expert commands in Linux.
  - [LINUX CHEAT SHEET](docs/linux-cheat-sheet-plexAI.md)

- **VIM TEXT EDITOR** is a de-facto text editor for VLSI engineers. There are some excellent tutorials documented [[here](docs/vim-tutorial-plexAI.md)]
  - **Interactive Built-in Tutorial:** Run `vimtutor` in your terminal. This is Vim’s official, interactive, step-by-step tutorial and is widely recommended as the best starting point for new users. It teaches you practical navigation, editing, and command-line basics directly in Vim itself.
  - [VIM QUICK REFERENCE](docs/VimQuickReferenceGuide.md)

- **BASIC LINUX SCRIPTING** is an essential productivity skill for any VLSI engineer. [Intro to Linux Shell Scripting](https://www.udemy.com/course/linux-shell-scripting-free/) is an excellent free course on Udemy which intorduces basic linux scripting to begineers. [This module](https://github.com/VLSI-LaunchLab/Intro-to-Linux-Scripting) is based on the course that will be helpful when repeating or refreshing the course.

- **PYTHON PROGRAMMING** is another essential productivity tool. [AI Python for Beginners](https://www.deeplearning.ai/short-courses/ai-python-for-beginners/) is an excellent short from deepLearning.ai that not only introduces Python programming but it teaches how to use modern AI chatbots to increase your efficiency in programming. [This module](https://github.com/VLSI-LaunchLab/AI-Python-for-Beginners) is based on the course that will be helpful when repeating or refreshing the course.

- **HELPFUL RESOURCES**:
  - [Git on Linux](https://www.linuxjournal.com/content/git-linux-beginners-guide-version-control-and-project-management): _A Beginner’s Guide to Version Control and Project Management_ by George Whittaker, Linux Journal, April 2025
  - [Mastering Linux File Permissions and Ownership](https://www.linuxjournal.com/content/mastering-linux-file-permissions-and-ownership) by George Whittaker, Linux Journal, April 2025
  - [The Power of Linux Shell Environment Variables](https://www.linuxjournal.com/content/power-linux-shell-environment-variables) by George Whittaker, Linux Journal, April 2025
  - [LINUX CHEAT SHEET](docs/linux-cheat-sheet-plexAI.md)
  
# Introduction to Digital Logic

**PREREQ/ASSESSMENT** : Check your digital logic proficiency by taking [this test](docs/Digital-Circuits-Assignment.pdf)

- **Logic Gates**: Understanding of basic (NOT, AND, OR), universal (NAND, NOR) and special logic gates (X-OR,X-NOR). 
- **Truth Table & K-Map**: Draw the truth table and find out the logic circuit using K-Map (up to 5 variable). 
- **Combinational Circuit**: Draw the following circuits: Adders, Subtractors, Multiplexers, De-multiplexers, Decoders, Encoders and Code converters.
- **Sequential Circuits**: Draw the following circuits: Latches, Flip-Flops, Resisters, Counters and FSM.
  - Understanding the concept of setup time. hold time, removal time, recovery time etc.
- **Misc.**: Multiplexer and Decoder based logic circuit design, Edge detector circuit design.
- **Logic States**: Understanding the loging states and their relevances: 1, 0, X, Z.
- **Timing Diagram**: Understanding the timing diagram of all the combi and sequential logic circuits.
- **Resources**:
  - [Other Advanced Topics](https://github.com/silicon-vlsi/LaunchLab-Freshers-Training/blob/main/README.md#week-7-other-combinational-and-sequential-circuit-design): Notes from old notes covering FSM, STA, etc.
  - Digital Logic and Computer Design by M. Morris Mano. [[Link]](https://ia800607.us.archive.org/3/items/DigitalLogicAndComputerDesignByM.MorrisMano2ndEdition/Digital%20Logic%20And%20Computer%20Design%20By%20M.%20Morris%20Mano%20%282nd%20Edition%29.pdf)
