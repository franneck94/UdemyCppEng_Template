# Tooling

## Compiler

Any GCC, Clang or MSVC compiler

## IDE: Visual Studio Code

- [Visual Studio Code](https://code.visualstudio.com/)

### VSCode Extensions

- Coding Tools Extension Pack (franneck94)
- C/C++ Extension Pack (franneck94)

### Extra settings (for local .vscode/settings.json file)

#### Windows

```json
  "C_Cpp_Runner.warnings": [
    "/W4"
  ],
  "C_Cpp_Runner.compilerArgs": [],
  "C_Cpp_Runner.includePaths": [],
  "C_Cpp_Runner.linkerArgs": [],
  "C_Cpp_Runner.cStandard": "c11",
  "C_Cpp_Runner.cppStandard": "latest",
  "C_Cpp_Runner.excludeSearch": [],
  "C_Cpp_Runner.enableWarnings": true,
  "C_Cpp_Runner.warningsAsError": false
```

#### Linux/Mac

```json
  "C_Cpp_Runner.warnings": [
    "-Wall",
    "-Wextra",
    "-Wpedantic",
    "-Wshadow",
    "-Wconversion",
    "-Woverflow",
    "-Wformat=2",
    "-Wsign-conversion"
  ],
  "C_Cpp_Runner.compilerArgs": [],
  "C_Cpp_Runner.includePaths": [],
  "C_Cpp_Runner.linkerArgs": [],
  "C_Cpp_Runner.cStandard": "c99",
  "C_Cpp_Runner.cppStandard": "c++20",
  "C_Cpp_Runner.excludeSearch": [],
  "C_Cpp_Runner.enableWarnings": true,
  "C_Cpp_Runner.warningsAsError": false
```
