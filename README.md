# tools

SimpleXX 统一使用的一些配置文件

## 代码格式

要求在每个源文件开始处保留以下信息

```cpp
(blank line)
// This file is a part of Simple-XX/SimpleExample
// (https://github.com/Simple-XX/SimpleExample).
//
// example.cpp for Simple-XX/SimpleExample.
(blank line)
```

- C/C++

    clang-format_c_cxx

## git commit 要求

Git Commit 规范.md

## gitignore

需要注意不要把系统文件传上来，比如 osx 系统的 `.DS_Store` 文件

## 提交代码

**禁止直接向 repo 推送**

需要以 pr 形式推送代码，除了需要通过 github action 外，对于 main/master 分支，需要经过至少一位同学的 review。

