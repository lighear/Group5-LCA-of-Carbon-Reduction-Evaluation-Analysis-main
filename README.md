# 秸秆资源化利用方式生命周期碳减排效果评价

## 概述

本项目旨在使用生命周期评价（LCA）方法，评估六种不同秸秆资源化利用技术（直接还田、饲料化、直燃发电、厌氧发酵、与煤共燃、生产甲醇）的碳减排效果。通过对不同技术的生命周期环境影响进行详细分析，帮助实现秸秆的有效资源化利用，推动可持续农业与能源管理。

## 研究背景

随着全球人口增长和经济发展，能源需求日益增加，生物质资源，特别是秸秆，作为一种可再生资源，具有替代化石燃料的潜力。本研究评估了秸秆资源化利用的技术路线，目标是通过生命周期评价为相关部门提供科学参考，推动秸秆的可持续利用。

## 项目目标

- 评估不同秸秆利用技术的环境效益，尤其是碳减排潜力。
- 基于不同省份的实际数据，分析技术在不同地区的适用性。
- 为各相关决策提供支持，帮助制定科学的秸秆资源化利用规划。

## 研究方法

- **软件工具**：使用 `efootprint` 软件进行环境负荷的计算，使用 `RStudio` 进行数据分析和可视化。
- **数据来源**：
  - **文献数据**：收集相关学术文献中的秸秆资源化技术参数。
  - **生命周期评价数据库**：利用中国生命周期基础数据库（CLCD）进行CO₂排放量的计算。
  - **实景数据**：部分数据来源于企业和部门提供的实地生产数据。

## 结果与讨论

### 六种秸秆资源化技术的碳减排效果：

1. **生产甲醇**：最高碳减排效果，-1082.07 kgCO₂eq/t
2. **直接还田**：较高的碳减排效果，-554.1 kgCO₂eq/t
3. **直燃发电**：-448.58 kgCO₂eq/t
4. **厌氧发酵**：-345.89 kgCO₂eq/t
5. **饲料化**：-67.095 kgCO₂eq/t
6. **与煤共燃**：碳减排效果最差，-7.6 kgCO₂eq/t

### 不同技术的省级异质性：
- 秸秆直燃发电在一些省份（如河北、山西）有显著碳减排效果，而在一些省份（如云南、四川）效果不明显。
- 秸秆与煤共燃的碳减排效果在部分省份较好（如贵州、重庆），但在北方部分地区可能增加排放。

## 安装与使用

### 安装依赖

本项目依赖于 `R` 和 `efootprint` 软件。

- **安装 R**：请参考 [R 官网](https://cran.r-project.org/) 进行安装。
- **安装 efootprint 软件**：具体安装步骤请参考该软件的文档。

### 运行分析

1. 使用 `RStudio` 打开项目文件夹。
2. 运行 `LCA_analysis.R` 脚本以进行生命周期评价分析。

### 结果展示

<img width="2400" height="1800" alt="图1 秸秆直接还田的环境影响" src="https://github.com/user-attachments/assets/d2a414b2-4511-45d7-8729-2eb512cb556d" />
<img width="2400" height="1800" alt="图2 秸秆饲料化的环境影响" src="https://github.com/user-attachments/assets/04701927-415c-4418-9f51-47e07d53e4a4" />
<img width="2400" height="1800" alt="图3 秸秆直燃发电的环境影响" src="https://github.com/user-attachments/assets/61e7cfe4-c8bc-4126-af4b-4b5344c17ad2" />
<img width="2400" height="1800" alt="图4 秸秆厌氧发酵的环境影响" src="https://github.com/user-attachments/assets/29cb12a7-f882-47f9-9591-33b594eb7949" />
<img width="2400" height="1800" alt="图5 秸秆与煤共燃的环境影响" src="https://github.com/user-attachments/assets/2a4ed826-ad68-4153-ad62-cf3c9980731f" />
<img width="2400" height="1800" alt="图6  秸秆生产甲醇的环境影响" src="https://github.com/user-attachments/assets/c5993715-db95-4c64-8ef5-6ead864c7f63" />
<img width="2400" height="1800" alt="图7 六种技术路线的环境影响比较" src="https://github.com/user-attachments/assets/4ec3df6a-33fd-4e40-a8f7-77daa1ae7b51" />
<img width="1200" height="876" alt="图8 不同省份秸秆与煤共燃的环境影响" src="https://github.com/user-attachments/assets/cb94d31a-9441-4cea-a1ac-82812525fc2e" />
<img width="1200" height="878" alt="图9 不同省份秸秆直燃发电的环境影响" src="https://github.com/user-attachments/assets/f14e76b6-b447-49f0-a473-f2faf0d3056d" />

## 团队成员

- [童卓琳] 2501212931			
- [李筱] 2501212900
- [李昊] 2501212898

