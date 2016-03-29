# 已经编译的 dblib 和 pdo_dblib

这些DLL是从php源码中的ext/mssql和ext/pdo_dblib编译而来。使用freetds库(http://www.freetds.org/ )，这和官方发布的版本有所区别：对于ntext和nchar等类型字段，可以取得UTF-8编码的字符串，只要在c:\freetds.conf设置client charset=UTF-8
