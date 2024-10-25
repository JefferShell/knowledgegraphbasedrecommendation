## Diseases Knowledge Graph Visualization System

### 项目简介

疾病知识图谱展示系统是一个基于Neo4j图数据库和Django框架开发的知识图谱应用。该系统整合了丰富的疾病相关数据，并通过直观的图谱展示方式，帮助用户更好地理解和探索疾病之间的复杂关系。

### 主要功能

* **数据导入与初始化:** 以简易方式从文件中导入疾病相关数据，并自动进行数据初始化，确保数据的完整性和准确性。
* **知识图谱展示:** 通过ECharts等前端技术实现直观且交互性强的知识图谱展示，并支持节点关系查询。
* **节点关系查询:** 支持关键词或特定节点进行查询，快速检索并展示相关信息，以发现疾病之间的潜在联系和规律。


### 技术架构

* **后端:** Django框架、py2neo
* **前端:** HTML5、CSS3、JavaScript、ECharts
* **数据库:** Neo4j

### 使用说明

1. 环境安装：
    - Python版本：3.7+
    - Django版本：3.2.7
2. 安装依赖: `pip install -r requirements.txt -i httpspypi.tuna.tsinghua.edu.cnsimple`
3. 运行Django服务器：`python manage.py runserver`
4. 在浏览器中打开地址：`http://127.0.0.1:8000` 进行系统访问
5. 首次使用时需进行Neo4j数据库账号密码设置并初始化数据：`http://127.0.0.1:8000/init_data`

### 联系方式

**微信号：zt745324325**