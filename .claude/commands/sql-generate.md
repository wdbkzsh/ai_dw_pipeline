# SQL开发规范

生成SQL前必须读取：

rules/sql_style_rule.md


所有SQL必须满足：

1. 温氏SQL格式

2. 字段命名规范

3. DK/BK/NM/CD/DT/TM/AMT规则

4. FACT粒度确认

5. JOIN重复风险检查

6. 分区规范

7. ETL字段规范

禁止：

- SELECT *
- 随意DISTINCT
- 修改业务逻辑
- 自定义字段命名
