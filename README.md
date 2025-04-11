# calc-chars

Quantitative investment workflow package

## 环境要求

- Python >= 3.12
- uv (Python包管理工具)

## 安装指南

### 1. 安装uv

首先需要安装uv包管理工具：

```bash
# 使用pip安装uv
pip install uv

# 或者使用curl安装
curl -LsSf https://astral.sh/uv/install.sh | sh
```

### 2. 创建虚拟环境（可选但推荐）

```bash
# 创建虚拟环境
uv venv

# 激活虚拟环境
# Windows:
.venv\Scripts\activate
# Linux/MacOS:
source .venv/bin/activate
```

### 3. 安装项目依赖

```bash
# 安装项目依赖
uv pip install .

```

## 项目依赖

- pandas
- numpy
- ipykernel
- PyYAML
- sqlalchemy

## 作者

Weiguan-group (weiguanwang@shu.edu.cn)
