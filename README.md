# 用于深度哈希图像检索和深度哈希跨模态检索的性能评估算法的计算脚本
## MAT文件命名的key命名规则
**使用scipy库的savemat方法来保存mat文件，以下是两个模态的命名键值命名方式**
### 单模态
![图片](https://github.com/user-attachments/assets/cb14a032-5850-47eb-a648-0508fe2304f0)

### 跨模态
![图片](https://github.com/user-attachments/assets/88a1cea1-2284-4779-8146-e9ef8d84a0b8)


A script on eval Image Retrieval Model
* [2023-11-30]-automatic script dealing with the CSV file will be released
* [2023-11-25]-fix the bug in saving result for csv file in PH@2 computing and fix the top @ K list index

### 一个简单的自动脚本
## 一个用于评估图像检索模型性能的算法总结
* PH@2 基于汉明半径的检索系统的精确率
* TopK-Precison 计算前K精确度
* TopK-Recall 计算前K召回率
* PRcurve 计算精确度-召回率曲线
* NDCG 评估检索的顺序性能
### RUN
```shell
python run.py --arg's parameter
```
# 文件结构和效果展示
![2023-09-14 20-04-41 的屏幕截图](https://github.com/Mahiro2211/Eval_Image_Retrieval/assets/130811701/5bafc9c9-a2e0-486d-a94f-21f3a6378c1e)
