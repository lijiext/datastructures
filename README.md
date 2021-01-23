# 数据结构
本仓库用于存储学习数据结构的代码及笔记

## 线性表
### ADT List

|      Function Name       |                       Description                        |
| :----------------------: | :------------------------------------------------------: |
|       InitList(&L)       |                   构造一个空的线性表L                    |
|     DestoryList(&L)      |                          销毁L                           |
|        IsEmpty(L)        |                      判断L是否为空                       |
|       GetLength(L)       |                  获取L的长度即元素个数                   |
|   GetElement(L, i, &e)   |                   用e返回L中第i个元素                    |
|    FindElement(L, e)     | 在L中查找元素e，返回第一个与e相同元素的位置，未找到返回0 |
| InsertElement(&L, i, e)  |                在L的第i个元素前插入元素e                 |
| DeleteElement(&L, i, &e) |             删除L的第i个元素，将其值用e返回              |

