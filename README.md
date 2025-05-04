# blog_create
it is my first time to create a blog...
# 如何利用hugo创建个人博客 - 完整指南

## 🛠️ 准备工作
- 安装Git：[下载地址](https://git-scm.com/)
  ```powershell
  choco install git -y
  ```
- 代码编辑器推荐：VS Code

## ⚙️ 技术栈选择
| 方案 | 技术 | 难度 |
|------|------|------|
| 1    | Hugo + GitHub Pages | ★★☆ |
| 2    | Jekyll | ★★★ |
| 3    | 手动HTML/CSS | ★☆☆ |

根据一番调研，好像hugo建立博客，写博客的速度比较快，所以选择Hugo + GitHub page的方式

## 🚀 快速开始
# Hugo安装
1.win + x 选择终端管理员，打开powershell  

2.执行安装命令：
```powershell
choco install hugo-extended -y
```
3.验证hugo安装：
```powershell
hugo version
#应该显示类似：hugo v0.127......
```
如果是失败，可能是未安装Chocolatey导致，可执行以下命令安装：
```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
然后安装完后，进行验证：
```powershell
choco -v
```
# Git安装
1.安装命令：
```powershell
choco install git -y
```
2.首次配置：





