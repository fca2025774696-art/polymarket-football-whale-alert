# 🎯 Polymarket Football Whale Alert

[![Python 3.12+](https://img.shields.io/badge/python-3.12+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/你的用户名/仓库名?style=social)](https://github.com/你的用户名/仓库名)

一个实时监控 Polymarket 足球预测市场大额交易的工具，帮助识别"聪明钱"和鲸鱼交易。

## 🌟 特性

- **实时监控**：监听 Polygon 链上 Polymarket 合约的足球市场交易
- **大额交易警报**：自定义阈值（默认 $5,000+）
- **数据存储**：SQLite 本地数据库存储历史交易
- **交易者分析**：识别"聪明钱"、鲸鱼等标签
- **简单查询**：命令行工具查看统计数据
- **支持测试网**：可在 Mumbai 测试网安全测试

## 📦 快速开始

### 环境要求
- Python 3.12+
- WSL (Windows) 或 Linux/Mac 终端

### 安装步骤

```bash
# 1. 克隆仓库
git clone https://github.com/你的用户名/polymarket-football-whale-alert.git
cd polymarket-football-whale-alert

# 2. 创建虚拟环境
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3. 安装依赖
pip install -r requirements.txt

# 4. 复制环境变量模板
cp .env.example .env
# 编辑 .env 文件，填入你的配置

# 5. 运行监控
python main.py
