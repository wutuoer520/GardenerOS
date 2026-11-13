# GardenerOS

《操作系统》课程实验代码仓库。

- 姓名：冯彰庭
- 学号：24301088
- 开发环境：openEuler 24.03 (LTS-SP4) 容器 + Rust nightly + QEMU 11.0.0

## 目录说明

| 路径 | 说明 |
| --- | --- |
| `rust-toolchain` | 锁定实验使用的 Rust nightly 版本 |
| `.gitignore` | 忽略构建产物与编辑器临时文件 |

## 分支约定

仓库按实验划分分支，每次实验在对应分支上完成，后续实验可在前一次实验的基础上迭代：

- `main`：实验 0 环境配置
- `ex1` ~ `ex7`：第 1 ~ 7 次实验

## 环境使用方式

本地目录通过 Docker 绑定挂载到容器的 `/mnt`，容器内直接在该目录下编译与运行：

```bash
docker exec -it openeuler-dev bash
cd /mnt
```
