# CI/CD 实操 Demo

一个用来学习 GitHub Actions + Release 的最小 C++ 项目。

## 功能

- 编译输出 "Hello, CI/CD!"
- 每次 push 自动编译（CI）
- 打 tag 自动发布 Release（CD）

## 构建

```bash
cmake -B build
cmake --build build
./build/ci_demo
```
