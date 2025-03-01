本项目的目的是学习Raft的原理，并实现一个简单的k-v存储数据库。
## 分支说明
- main：最新内容，已经实现一个简单的clerk
- rpc：基于muduo和rpc框架相关内容
- raft_DB：基于Raft的k-v存储数据库，主要用于观察选举过程`


## Docs
- 如果你想创建自己的rpc，请参考example中rpc的md文件和friendRPC相关代码.此外可以见rpc分支
- 各个文件夹文件内容说明：[这里](./docs/目录导览.md)
> notice:在代码编写过程中可能有一些bug改进，其他分支可能并没有修复这些bug以及相应的改进。注意甄别
>同时欢迎issue提出这些bug或者pr改进。

## todoList

- [x] 完成raft节点的集群功能
- [ ] 去除冗余的库：muduo、boost 
- [ ] 代码精简优化
- [x] code format
- [ ] 代码解读 maybe
- [ ] 完成ReadIndex功能
- [ ] 完成leader lease 和 check quorum

