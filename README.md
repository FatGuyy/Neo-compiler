# Neo Online Compiler

### Overview

Neo Online Compiler is a web-based tool designed for compiling NEO3 C# smart contracts into NEO VM bytecode. It simplifies the development process by integrating **NEP11** and **NEP17** templates, allowing developers to save time and focus on their code.

### Features

- **C# Smart Contract Compilation**: Convert NEO3 C# contracts to NEO VM bytecode.
- **Error Handling**: Provides detailed error messages for incorrect contract code.
- **Integrated Templates**: Pre-built **NEP11** and **NEP17** templates for quick use.
- **Output**: Generates `.nef` script, `.nef` image, and manifest in Base64 format.

### Tech Stack

- **.NET Core**: Manages communication with NEO developer tools and handles compilation.
- **Neo Developer Tools**: For smart contract compilation and deployment.

### Usage

1. **Authenticate** using your API key.
2. **Select task-type** as `C#`.
3. **Input contract source code** (Base64 format) and compile.
4. Get the compiled **.nef script**, **nef image**, and **manifest** as outputs.

### Demo

Watch a demo [here].
