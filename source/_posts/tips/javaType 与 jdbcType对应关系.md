---
title: javaType 与 jdbcType对应关系：
date: 2023-06-26 
tags: springboot
categories: 环境配置
---
    jdbcType 与 javaType 的类型对应
    jdbcType	javaType
    CHAR	String
    VARCHAR	String
    LONGVARCHAR	String
    NUMERIC	java.math.BigDecimal
    DECIMAL	java.math.BigDecimal
    BIT	boolean
    BOOLEAN	boolean
    TINYINT	byte
    SMALLINT	short
    INTEGER	INTEGER
    BIGINT	long
    REAL	float
    FLOAT	double
    DOUBLE	double
    BINARY	byte[]
    VARBINARY	byte[]
    LONGVARBINARY	byte[]
    DATE	java.sql.Date
    TIME	java.sql.Time
    TIMESTAMP	java.sql.Timestamp
    CLOB	Clob
    BLOB	Blob
    ARRAY	Array
    DISTINCT	mapping of underlying type
    STRUCT	Struct
    REF	Ref
    DATALINK	java.net.URL
