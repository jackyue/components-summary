
|模块|名称|功能|代码路径|
|----|----|----|----|
|0.数据协议|protobuf|结构化数据的传输与存储、通讯框架实现等，如广告物料、广告系统日志、rpc协议等|https://github.com/google/protobuf|
||thrift||https://github.com/apache/thrift|
|1.web服务器|nginx|web服务器、负载均衡、反向代理等，用于用户产品后台，如网页/app等应用的后台|https://github.com/nginx/nginx|
||apache||https://github.com/apache/httpd|
|2.网络应用程序框架|netty|用于广告系统后台，如播放，检索等后台服务|https://github.com/netty/netty|
||grpc||https://github.com/grpc/grpc|
||sofa-pbrpc||https://github.com/baidu/sofa-pbrpc|
||brpc||https://github.com/brpc/brpc|
||iris||https://github.com/kataras/iris|
||muduo||https://github.com/chenshuo/muduo|
||mars||https://github.com/Tencent/mars|
|3.负载均衡|nginx|用于集群扩展，动态分配等分发策略|https://github.com/nginx/nginx|
||seesaw||https://github.com/google/seesaw|
|4.日志系统|glog|用于后台服务记录日志，日志记录是否合理会影响系统整体性能|https://github.com/google/glog|
||log4j||https://github.com/apache/log4j|
|5.日志采集|kafka|用户业务日志的上报落地等，业务日志将在日志分析，算法等模块应用|https://github.com/apache/kafka|
||flume||https://github.com/apache/flume|
||rabbitmq||https://github.com/rabbitmq/rabbitmq-server|
||scribe||https://github.com/facebookarchive/scribe|
||LogDevice||https://github.com/facebookincubator/LogDevice|
|6.分布式文件系统|hdfs|用于存储业务日志文件等|https://github.com/apache/hadoop-hdfs|
|7.分布式计算框架|mapreduce|用于大数据业务分布式计算|https://github.com/apache/hadoop-mapreduce|
||spark||https://github.com/apache/spark|
||storm||https://github.com/apache/storm|
||pig||https://github.com/apache/pig|
|8.协调服务|zookeeper|集群高可用组件|https://github.com/apache/zookeeper|
||yarn||https://github.com/yarnpkg/yarn|
|9.数据仓库|mysql|SQL、NOSQL等数据库|https://github.com/mysql/mysql-server|
||postgresql||https://github.com/postgres/postgres|
||hive||https://github.com/apache/hive|
||hbase|                                                              |https://github.com/apache/hbase|
||leveldb||https://github.com/google/leveldb|
||phxsql||https://github.com/Tencent/phxsql|
||canal||https://github.com/alibaba/canal|
|10.缓存|redis|基于内存的键值数据库|https://github.com/antirez/redis|
||memcached||https://github.com/memcached/memcached|
|11.OLAP查询引擎|druid|分布式大数据查询引擎|https://github.com/druid-io/druid|
||presto||https://github.com/prestodb/presto|
||Kylin||https://github.com/apache/kylin|
|12.检索引擎|lucene|用于广告检索等|https://github.com/apache/lucene-solr|
||elasticsearch||https://github.com/elastic/elasticsearch|
|13.机器学习|tensorflow||https://github.com/tensorfow/tensorflow|
||xgboost||https://github.com/dmlc/xgboost|
||caffe||https://github.com/BVLC/caffe|
|14.单元测试|gtest||https://github.com/google/googletest|
||gmock||https://github.com/google/googlemock|
||junit||https://github.com/junit-team/junit5|
|15.语言|c++||http://www.cplusplus.com/doc/tutorial/|
||java||https://docs.oracle.com/javase/tutorial/|
||go||https://golang.org/|
||python||https://www.python.org/|
|16.构建工具|bazel||https://github.com/bazelbuild/bazel|
||blade||https://github.com/chen3feng/typhoon-blade|
|17.性能分析工具|gperftools||https://github.com/gperftools/gperftools|
||Valgrind||https://github.com/mozilla-b2g/valgrind|
||pprof||https://github.com/google/pprof|
|18.性能优化|jemalloc||https://github.com/jemalloc/jemalloc|
||tcmalloc||https://github.com/gperftools/gperftools|
|19.持续集成工具|jenkins||https://github.com/jenkinsci/jenkins|
|20.系统可靠性|chaosmonkey||https://github.com/Netflix/chaosmonkey|
|21.监控|elk||https://github.com/deviantony/docker-elk|
