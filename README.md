# LOUDONGWAJUE 🔍 漏洞挖掘

> 漏洞挖掘 / 渗透测试 / 安全研究项目仓库
> Vulnerability Research, Penetration Testing & Security Audit

---

## 项目结构

```
loudongwajue/
├── pocs/          # 漏洞验证脚本 (Proof of Concept)
├── notes/         # 漏洞分析笔记 / Writeup
├── targets/       # 审计目标源码 (靶场/测试应用)
├── scripts/       # 自动化工具脚本
├── reports/       # 审计报告
├── config/        # 配置文件
└── README.md
```

## 目录说明

| 目录 | 用途 |
|------|------|
| `pocs/` | 存放漏洞验证 PoC 脚本，按漏洞编号或名称组织 |
| `notes/` | Markdown 格式的漏洞分析笔记、审计思路、学习记录 |
| `targets/` | 待审计的靶场项目或测试应用源代码 |
| `scripts/` | 自动化扫描、信息收集、辅助工具脚本 |
| `reports/` | 完整的审计报告（PDF/Markdown） |
| `config/` | 工具配置、字典文件、Burp 配置等 |

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/HoulinGu0/LOUDONGWAJUE.git
cd LOUDONGWAJUE

# (可选) 创建 Python 虚拟环境
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## 配合 DeepAudit 使用

1. 在 DeepAudit 中创建项目 → 选择"Git 仓库"
2. 填入仓库 URL: `https://github.com/HoulinGu0/LOUDONGWAJUE.git`
3. 选择需要审计的目录（如 `targets/`）
4. 运行 Agent 审计

## 许可

本项目仅供安全研究和学习使用。
