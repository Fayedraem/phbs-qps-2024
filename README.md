# PHBS QPS 2024

本仓库包含工具和脚本，用于获取美国消费者价格指数 (CPI) 数据并计算最近四个季度的通胀率。

## 仓库结构
- `data`：用于存储原始和处理后的数据。
- `notebooks`：用于分析和可视化的 Jupyter 笔记本。
- `scripts`：用于获取和处理数据的 Python 脚本。
- `src`：可重用的辅助模块。

## 仓库地址
[GitHub Repository Link](https://github.com/Fayedream/phbs-qps-2024)

## 运行代码的方法
按照以下步骤设置环境并运行代码：

### 1. 克隆仓库
```bash
git clone https://github.com/YOUR_USERNAME/phbs-qps-2024.git
cd phbs-qps-2024

### 2. 设置 Python 环境
在 macOS/Linux 上：
bash
python3 -m venv venv
source venv/bin/activate
```
在 Windows 上：
```bash
python -m venv venv
venv\Scripts\activate
```
### 3. 安装依赖
运行以下命令安装所需的 Python 库：
```bash
pip install pandas pandas-datareader
```
### 4.进入scripts
进入 scripts 文件夹并运行脚本：
python scripts/CPI-America.ipynb

注意事项
脚本从美国联邦储备经济数据库（FRED）获取数据，请确保网络连接正常。
数据来源为消费者价格指数 (CPI)。

### 5.将文件提交到 GitHub
将所有更改提交并推送到 GitHub：
```bash
git add .
git commit -m "添加 CPI 获取脚本和 README 文件"
git push origin main
```
