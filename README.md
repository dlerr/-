# CTR预测
  本项目旨在进行智能推荐的ctr预测模块，由最原始的埋点数据开始，经过数据清洗、特征构造、特征工程、数据建模等一系列操作从而达到对ctr的预估。
## 代码结构
——project（项目根目录）<br>
&emsp;——data（数据路径）<br>
&emsp;&emsp;——原始数据（原始埋点数据）<br>
&emsp;&emsp;——tabel_u_f（用户表、特征表）<br>
&emsp;&emsp;——训练数据.csv（最终训练数据）<br>
&emsp;——dataloader（特征构造入口、用户表特征表构造入口等其他表基础操作）<br>
&emsp;——utils（具体特征的构造、序列特征提取以及基础数据操作）<br>
&emsp;——train_data.py（特征构造主程序）<br>
