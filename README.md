# insert_dylib

`insert_dylib` 是一个用于将动态库（dylib）注入到 macOS 目标进程中的工具。它利用低级的系统调用来实现动态库的注入，通常用于调试、测试或修改正在运行的应用程序。

## 编译

### 1. 下载源码

下载 `insert_dylib` 工具的源代码，文件夹内包含 `main.c` 

### 2. 编译

在终端中进入源码文件夹，并使用 `clang` 或 `gcc` 编译 `main.c` 文件生成可执行文件。

```bash
cd insert_dylib
```
```bash
clang -o insert_dylib main.c
```

或者

```bash
gcc -o insert_dylib main.c
```


成功！生成了 insert.dylib 的可执行文件
