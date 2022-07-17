# This embedded the hdfs into the RocksDB system, but when the db_bench tends to exit, it will cause segment fault.

# Also, I updated the cmake file, which append the hdfs into the plugin list.