# Lazy C - Advanced C Coding Assistant

## How Lazy C make your code easier with out using AI

Eliminates C programming tedium with:
- ✅ **Auto semicolons** - Smart insertion (skips control structures & comments)
- ✅ **Auto headers** - Includes required files automatically (50+ functions)
- ✅ **Auto prototypes** - Function declarations generated automatically
- ✅ **Safety warnings** - Detects unsafe functions (gets, strcpy, sprintf, etc.)
- ✅ **Memory checks** - Reminds about malloc/free and NULL checks
- ✅ **One-click compile** - Ctrl+Shift+B to compile, Ctrl+Shift+R to run
- ✅ **Code templates** - Ctrl+Shift+M for main(), Ctrl+Shift+D for docs


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


## 👨‍💻 Author

**Mehdi Talalha** - [GitHub](https://github.com/mehdi1-T/Lazy-C-vscode-extension)

---

<div align="center">

⭐ **If you like Lazy C, star me on GitHub!**
</div>