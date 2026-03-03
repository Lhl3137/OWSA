# OWSA

## 项目简介

OWSA 是一个由多个大模型协同驱动，针对光学遥感图像中的油井场景的安全评估系统，可以自动检测油井位置并生成安全分析报告。

## 数据集OWTD及预训练权重下载
### 百度网盘下载
- 链接：https://pan.baidu.com/s/1GYiCO5FMMrdgBR6AyH68pw?pwd=fa6q

## 安装步骤

1. 克隆项目到本地
2. 安装依赖包：
```bash
pip install -r requirements.txt
```

## 使用方法

1. 确保`best.pt`模型权重文件在项目根目录
2. 将要分析的图片放在`images`文件夹中
3. 运行程序：
```bash
python main.py
```
4. 分析报告将保存在`analysis_report.html`文件中
