# BitcoinUTXOSlicer
比特币区块链UTXO切片程序
本项目主要功能为从区块链原始文件中顺序查找比特币区块链上的下一个合法区块并解析，然后根据UTXO切片时间间隔程序保存切片文件、OpReturn数据和区块处理程序中间状态文件。
本程序可以从创世区块开始启动程序进行切片也可以从中断处启动程序对比特币区块链程序进行时间切片处理。本项目的主要目的是对UTXO区块链进行增量式切片分析。此外，本项目的
应用场景也包括为比特币区块链的交易流分析和地址追踪提供切片分析功能。
