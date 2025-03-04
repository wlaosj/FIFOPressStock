# 仓库管理系统

基于 Tkinter 的仓库管理系统，支持产品入库、出库和查询功能，遵循先进先出（FIFO）原则。

## 功能
- 产品入库：录入产品型号、数量、入库日期、库存位置、入库人和备注。
- 产品出库：按产品型号查询库存，按入库时间排序出库。
- 最近发货记录：按型号和日期范围查询出库记录。
- 数据管理：使用 Excel 文件存储库存和出库数据。

## 运行环境
- Python 3.x
- 依赖库：`pandas`, `portalocker`, `openpyxl`

## 安装
```bash
pip install pandas portalocker openpyxl
