# COMPSCI 377 Operating Systems

In this course we examine the important problems in operating system design and implementation. The operating system provides a well-known, convenient, and efficient interface between user programs and the bare hardware of the computer on which they run. The operating system is responsible for allowing resources (e.g., disks, networks, and processors) to be shared, providing common services needed by many different programs (e.g., file service, the ability to start or stop processes, and access to the printer), and protecting individual programs from one another. The course will start with a brief historical perspective of the evolution of operating systems over the last fifty years, and then cover the major components of most operating systems. This discussion will cover the tradeoffs that can be made between performance and functionality during the design and implementation of an operating system. Particular emphasis will be given to three major OS subsystems: process management (processes, threads, CPU scheduling, synchronization, and deadlock), memory management (segmentation, paging, swapping), file systems, and operating system support for distributed systems.

*FALL 2022*

- [Syllabus](syllabus/syllabus.md)
- [Schedule](syllabus/schedule.md)
- [Important Dates](syllabus/dates.md)

## Usage

Make sure you have [git](https://git-scm.com/downloads) installed on your local machine before proceeding.

You can easily access all the course material from this GitHub repository. We recommend that you clone this repository to your local computer and do frequent pulls to get the latest changes. You can do this in several ways. We recommend the [`gh` command line tool](https://github.com/cli/cli) as it easy to use and provides useful GitHub related tasks. If you choose to use `gh`, you can clone this repository by running the following command:

```bash
gh repo clone umass-cs-377/377-F22
```

Otherwise, you can use `https`:

```bash
git clone https://github.com/umass-cs-377/377-F22.git
```

Lastly, you can use `ssh`:

```bash
git clone git@github.com:umass-cs-377/377-F22.git
```

## VSCode and Markdown

If you clone this repository to your local computer, you may prefer to preview the markdown files, rather than read them directly. Use the [command palette](https://code.visualstudio.com/docs/getstarted/userinterface#_command-palette) in VScode and select `Markdown: Open Preview to the Side`. If you want to get fancy, I recommend the [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) VSCode extension.

## VSCode Extensions

We will be using C/C++ in this course as part of the programming assignments. You will be completing projects in the Edlab environment. We recommend you install the following VSCode extensions to enhance your coding experience. You can follow the links below or simply search for them in the VSCode extension manager.

### Name: Better C++ Syntax

- Description: The bleeding edge of the C++ syntax
- Publisher: Jeff Hykin
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=jeff-hykin.better-cpp-syntax

### Name: C/C++ Extension Pack

- Description: Popular extensions for C++ development in Visual Studio Code.
- Publisher: Microsoft
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools-extension-pack

### Name: Makefile Tools

- Description: Provide makefile support in VS Code: C/C++ IntelliSense, build, debug/run.
- Publisher: Microsoft
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode.makefile-tools

### Name: Prettier - Code formatter

- Description: Code formatter using prettier
- Publisher: Prettier
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode

### Name: Remote - SSH

- Description: Open any folder on a remote machine using SSH and take advantage of VS Code's full feature set.
- Publisher: Microsoft
- VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh