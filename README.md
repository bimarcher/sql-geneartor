# sql-geneartor
根据模板和表配置生成sql语句

schema.json为数据库表的配置
template中的文件为模板

数据库名称 # 数据库注释

  表名称 # 表注释 # 唯一性约束字段名
    字段名 # 字段注释
      字段类型 | 是否是not null，[y n] | 默认值，无 [n '默认值']
