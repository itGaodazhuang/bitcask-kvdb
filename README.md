基于Bitcask模型，兼容Redis数据结构和协议的KV存储引擎
- 采用Key、Value的数据模型，实现数据检索的快速、稳定、高效
- 存储模型：采用Bitcask存储模型，对于顺序写作了优化
- 持久化：实现了数据的持久化，确保数据的可靠性和可恢复性                  
- 索引：采用了分片B+树的实现，减弱了锁的粒度，提升了并发处理性能
- 并发控制：采用锁机制，确保数据一致性和并发访问的正确性
