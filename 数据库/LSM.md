

SSTable 基于顺序写磁盘速度很快的原理，将key/value对写入文件；为了实现快速的随机读，引入了LSM tree。



------

[1]: https://www.igvita.com/2012/02/06/sstable-and-log-structured-storage-leveldb/	"LSM Tree"
[2]: https://blog.csdn.net/anderscloud/article/details/7182165	"LevelDb 实现原理解析"

