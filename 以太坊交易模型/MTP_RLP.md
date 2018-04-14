### mtp与rlp
MTP 结构包含了Merkle Tree和Patricia Tree
![mtp_rlp](./images/mtp_rlp.png)
Merkle Tree 的好处是当要证明一个交易是否存在块中时，不重新计算所有交易的hash值


![mpt](./images/mpt.png)

MPT Tree 中用到的三种编码
![hex](./images/hex.png)

![mpt](./images/mptexample.png)

![rlp](./images/rlp.png)
RLP（递归长度前缀） 将内存中的数值表达成在数据库中存储的数据，及把数据库的数值表达成能在网络上传输的数值
