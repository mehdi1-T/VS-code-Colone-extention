# Lazy C - Advanced C Coding Assistant

> **Supercharge your C programming** with intelligent automation, real-time safety analysis, and instant compilation in VSCode.

[![VSCode](https://img.shields.io/badge/VSCode-1.80+-blue.svg)](https://code.visualstudio.com/) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

## 🎯 What It Does

Eliminates C programming tedium with:
- ✅ **Auto semicolons** - Smart insertion (skips control structures & comments)
- ✅ **Auto headers** - Includes required files automatically (50+ functions)
- ✅ **Auto prototypes** - Function declarations generated automatically
- ✅ **Safety warnings** - Detects unsafe functions (gets, strcpy, sprintf, etc.)
- ✅ **Memory checks** - Reminds about malloc/free and NULL checks
- ✅ **One-click compile** - Ctrl+Shift+B to compile, Ctrl+Shift+R to run
- ✅ **Code templates** - Ctrl+Shift+M for main(), Ctrl+Shift+D for docs

## 🚀 Quick Start

1. Install from [VSCode Marketplace](https://marketplace.visualstudio.com)
2. Create a `.c` file → auto-template loads
3. Start typing → features work automatically

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+Shift+B` | Compile current file |
| `Ctrl+Shift+R` | Compile and run |
| `Ctrl+Shift+M` | Insert main function |
| `Ctrl+Shift+D` | Generate function documentation |

## ⚙️ Configuration

```json
{
  "c-helper.autoSemicolon": true,      // Auto semicolon insertion
  "c-helper.autoHeaders": true,        // Auto header inclusion
  "c-helper.warningLevel": "medium",   // Warning sensitivity
  "c-helper.compilerPath": "gcc"       // Compiler (gcc/clang)
}
```

## 📋 Features Explained

### Auto Semicolon
```c
int x = 5       // Press Enter
int x = 5;      // ✓ Auto semicolon added
```

### Auto Headers
```c
printf("test");  // ✓ #include <stdio.h> added
malloc(100);     // ✓ #include <stdlib.h> added
strlen("hi");    // ✓ #include <string.h> added
```

### Safety Warnings
```c
strcpy(dst, src);     // ⚠️ Use strncpy instead
if (x = 5) { }        // ⚠️ Assignment in conditional?
malloc(10);           // ℹ️ Remember to free
fopen("file", "r");   // ℹ️ Check if NULL
```

## 📊 Stats

- **50+ Library Functions** detected automatically
- **4 Real-time Safety Checks** running
- **Zero Configuration** required
- **100% Free & Open Source** (MIT License)

## 💻 Requirements

- VSCode 1.80 or higher
- GCC or Clang compiler

## 🔧 Building from Source

```bash
git clone https://github.com/mehdi1-T/Lazy-C-vscode-extension.git
cd lazy-C
npm install
npm run compile
# Press F5 to test in Extension Development Host
```

## 🤝 Contributing

- **Report bugs**: [GitHub Issues](https://github.com/mehdi1-T/Lazy-C-vscode-extension/issues)
- **Suggest features**: Open a GitHub issue
- **Submit PRs**: Fork → Branch → Commit → Push → PR

## 📜 License

MIT - See [LICENSE](LICENSE) file. Free to use commercially and modify.

## 👨‍💻 Author

**Mehdi Talalha** - [GitHub](https://github.com/mehdi1-T/Lazy-C-vscode-extension)

---

<div align="center">

⭐ **If you find Lazy C useful, star us on GitHub!**

</div>