# CSV文件分析器 📊

一个基于 Streamlit 开发的 CSV 文件分析工具，支持数据可视化和基本统计分析。

## 功能特点

- 📈 支持多种文件编码（UTF-8、Big5、GBK）
- 📊 自动处理百分比等特殊格式数据
- 📉 提供多种可视化方式（直方图、箱型图、散点图）
- 📋 显示基本统计信息和数据预览
- 🎨 美观的用户界面

## 安装方法

1. 克隆仓库：
```bash
git clone https://github.com/Edneylin/csv-analyzer.git
cd csv-analyzer
```

2. 安装依赖：
```bash
pip install -r requirements.txt
```

3. 运行应用：
```bash
streamlit run app.py
```

## 使用方法

1. 上传 CSV 文件（支持 UTF-8、Big5、GBK 编码）
2. 查看数据基本信息和统计分析
3. 使用不同图表类型进行数据可视化

## 部署

### Zeabur 部署
1. 在 Zeabur 创建新项目
2. 选择 "Deploy New Service"
3. 选择 "Git Repository"
4. 选择此仓库
5. 选择 "Docker" 作为部署方式
6. 等待部署完成

### Streamlit Cloud 部署
1. 访问 https://share.streamlit.io/
2. 连接您的 GitHub 仓库
3. 选择此项目
4. 点击 "Deploy"

## 依赖包

- streamlit==1.32.0
- pandas==2.2.0
- plotly==5.18.0
- matplotlib==3.8.3
- seaborn==0.13.2

## 许可证

MIT License 