# QuestionsML
百面机器学习所有问题带答案整理
  参考资料：
    第1章 特征工程
1.为什么需要对数值类型的特征做归一化？
https://blog.csdn.net/qq_34604224/article/details/118002756
https://zhuanlan.zhihu.com/p/265411459
https://www.zhihu.com/question/594487822#:~:text=%E5%9C%A8%E6%95%B0%E6%8D%AE%E6%8C%96%E6%8E%98%E4%B8%AD%EF%BC%8C%E5%AF%B9%E6%95%B0%E5%80%BC%E5%9E%8B%E7%89%B9%E5%BE%81%E8%BF%9B%E8%A1%8C%E5%BD%92%E4%B8%80%E5%8C%96%E6%98%AF%E4%B8%80%E4%B8%AA%E5%BE%88%E5%B8%B8%E8%A7%81%E7%9A%84%E6%95%B0%E6%8D%AE%E9%A2%84%E5%A4%84%E7%90%86%E6%AD%A5%E9%AA%A4%E3%80%82%20%E8%BF%99%E6%98%AF%E5%9B%A0%E4%B8%BA%E4%B8%8D%E5%90%8C%E7%9A%84%E7%89%B9%E5%BE%81%E5%BE%80%E5%BE%80%E5%85%B7%E6%9C%89%E4%B8%8D%E5%90%8C%E7%9A%84%E5%BA%A6%E9%87%8F%E5%8D%95%E4%BD%8D%E5%92%8C%E5%B0%BA%E5%BA%A6%E8%8C%83%E5%9B%B4%EF%BC%8C%E5%A6%82%E6%9E%9C%E4%B8%8D%E8%BF%9B%E8%A1%8C%E5%BD%92%E4%B8%80%E5%8C%96%E5%A4%84%E7%90%86%EF%BC%8C%E5%8F%AF%E8%83%BD%E4%BC%9A%E5%AF%BC%E8%87%B4%E4%BB%A5%E4%B8%8B%E9%97%AE%E9%A2%98%EF%BC%9A%20%E7%89%B9%E5%BE%81%E7%9A%84%E5%B0%BA%E5%BA%A6%E4%B8%8D%E5%90%8C%EF%BC%8C%E5%AF%BC%E8%87%B4%E7%AE%97%E6%B3%95%E5%8F%97%E5%88%B0%E5%B0%BA%E5%BA%A6%E5%B7%AE%E5%BC%82%E7%9A%84%E5%BD%B1%E5%93%8D%EF%BC%8C%E4%B8%8D%E8%83%BD%E5%87%86%E7%A1%AE%E5%9C%B0%E8%AF%84%E4%BC%B0%E7%89%B9%E5%BE%81%E4%B9%8B%E9%97%B4%E7%9A%84%E6%9D%83%E9%87%8D%E3%80%82,%E5%9C%A8%E6%9F%90%E4%BA%9B%E7%AE%97%E6%B3%95%E4%B8%AD%EF%BC%8C%E4%B8%8D%E5%90%8C%E7%9A%84%E7%89%B9%E5%BE%81%E6%9D%83%E9%87%8D%E8%A2%AB%E8%A7%86%E4%B8%BA%E7%9B%B8%E7%AD%89%EF%BC%8C%E4%BD%86%E6%98%AF%E8%BF%99%E7%A7%8D%E6%9D%83%E9%87%8D%E7%9A%84%E5%81%87%E8%AE%BE%E5%8F%AA%E6%9C%89%E5%9C%A8%E6%89%80%E6%9C%89%E7%89%B9%E5%BE%81%E5%85%B7%E6%9C%89%E7%9B%B8%E5%90%8C%E7%9A%84%E5%B0%BA%E5%BA%A6%E6%97%B6%E6%89%8D%E6%98%AF%E6%AD%A3%E7%A1%AE%E7%9A%84%E3%80%82%20%E5%A6%82%E6%9E%9C%E4%B8%8D%E5%AF%B9%E7%89%B9%E5%BE%81%E8%BF%9B%E8%A1%8C%E5%BD%92%E4%B8%80%E5%8C%96%EF%BC%8C%E5%8F%AF%E8%83%BD%E4%BC%9A%E5%AF%BC%E8%87%B4%E4%B8%8D%E6%AD%A3%E7%A1%AE%E7%9A%84%E6%9D%83%E9%87%8D%E5%81%87%E8%AE%BE%E3%80%82%20%E5%9C%A8%E4%BD%BF%E7%94%A8%E6%9F%90%E4%BA%9B%E8%B7%9D%E7%A6%BB%E5%BA%A6%E9%87%8F%E7%AE%97%E6%B3%95%E6%97%B6%EF%BC%8C%E5%A6%82KNN%EF%BC%8C%E6%AC%A7%E5%87%A0%E9%87%8C%E5%BE%97%E8%B7%9D%E7%A6%BB%E5%92%8C%E6%9B%BC%E5%93%88%E9%A1%BF%E8%B7%9D%E7%A6%BB%E7%AD%89%EF%BC%8C%E5%9B%A0%E4%B8%BA%E7%89%B9%E5%BE%81%E5%B0%BA%E5%BA%A6%E7%9A%84%E4%B8%8D%E5%90%8C%EF%BC%8C%E5%8F%AF%E8%83%BD%E4%BC%9A%E5%AF%BC%E8%87%B4%E6%9F%90%E4%BA%9B%E7%89%B9%E5%BE%81%E5%AF%B9%E8%B7%9D%E7%A6%BB%E7%9A%84%E8%B4%A1%E7%8C%AE%E6%9B%B4%E5%A4%A7%EF%BC%8C%E4%BB%8E%E8%80%8C%E5%BD%B1%E5%93%8D%E5%88%86%E7%B1%BB%E7%BB%93%E6%9E%9C%E3%80%82
2.怎么处理类别特征？
https://zhuanlan.zhihu.com/p/349592092
https://zhuanlan.zhihu.com/p/560004588
3.什么是组合特征？如何处理高维组合特征？
https://blog.csdn.net/qq_34170700/article/details/106255063
https://juejin.cn/post/7199137002948542501
https://zhuanlan.zhihu.com/p/78502978
4.怎么有效地找到组合特征？
https://blog.csdn.net/youif/article/details/106784024
https://blog.csdn.net/m0_62128864/article/details/124536606
https://zhuanlan.zhihu.com/p/78502978
5.有哪些文本表示模型？它们各有什么优缺点？
https://www.zhihu.com/question/357033470
https://blog.csdn.net/qq_15698613/article/details/96172128
6.如何缓解图像分类任务中训练数据不足带来的问题？
https://hellozhaozheng.github.io/z_post/%E6%B7%B1%E5%BA%A6%E5%AD%A6%E4%B9%A0-%E8%AE%AD%E7%BB%83%E9%97%AE%E9%A2%98/#:~:text=%E5%9C%A8%E5%9B%BE%E5%83%8F%E5%88%86%E7%B1%BB%E4%BB%BB%E5%8A%A1%E4%B8%AD%2C%20%E8%AE%AD%E7%BB%83%E6%95%B0%E6%8D%AE%E4%B8%8D%E8%B6%B3%E4%BC%9A%E5%B8%A6%E6%9D%A5%E4%BB%80%E4%B9%88%E9%97%AE%E9%A2%98%2C%20%E5%A6%82%E4%BD%95%E7%BC%93%E8%A7%A3%E6%95%B0%E6%8D%AE%E9%87%8F%E4%B8%8D%E8%B6%B3%E5%B8%A6%E6%9D%A5%E7%9A%84%E9%97%AE%E9%A2%98%3F%201%20%E5%9F%BA%E4%BA%8E%E6%A8%A1%E5%9E%8B%E7%9A%84%E6%96%B9%E6%B3%95%3A%20%E9%87%87%E7%94%A8%E9%99%8D%E4%BD%8E%E8%BF%87%E6%8B%9F%E5%90%88%E9%A3%8E%E9%99%A9%E7%9A%84%E6%8E%AA%E6%96%BD%2C%E5%8C%85%E6%8B%AC%E7%AE%80%E5%8C%96%E6%A8%A1%E5%9E%8B%28%E5%A6%82%E5%B0%86%E9%9D%9E%E7%BA%BF%E6%80%A7%E7%AE%80%E5%8C%96%E6%88%90%E7%BA%BF%E6%80%A7%29%2C%20%E6%B7%BB%E5%8A%A0%E7%BA%A6%E6%9D%9F%E9%A1%B9%E4%BB%A5%E7%BC%A9%E5%B0%8F%E5%81%87%E8%AE%BE%E7%A9%BA%E9%97%B4%28%E5%A6%82L1%E5%92%8CL2%E6%AD%A3%E5%88%99%E5%8C%96%29%2C%20%E9%9B%86%E6%88%90%E5%AD%A6%E4%B9%A0%2C,Dropout%E8%B6%85%E5%8F%82%E6%95%B0%E7%AD%89.%202%20%E5%9F%BA%E4%BA%8E%E6%95%B0%E6%8D%AE%E7%9A%84%E6%96%B9%E6%B3%95%2C%20%E4%B8%BB%E8%A6%81%E9%80%9A%E8%BF%87%E6%95%B0%E6%8D%AE%E6%89%A9%E5%85%85%28Data%20Augmentation%29%2C%20%E5%8D%B3%E6%A0%B9%E6%8D%AE%E4%B8%80%E4%BA%9B%E5%85%88%E9%AA%8C%E7%9F%A5%E8%AF%86%2C%20%E5%9C%A8%E4%BF%9D%E6%8C%81%E7%89%B9%E5%AE%9A%E4%BF%A1%E6%81%AF%E7%9A%84%E5%89%8D%E6%8F%90%E4%B8%8B%2C%20%E5%AF%B9%E5%8E%9F%E5%A7%8B%E6%95%B0%E6%8D%AE%E8%BF%9B%E8%A1%8C%E9%80%82%E5%90%88%E5%8F%98%E6%8D%A2%E4%BB%A5%E8%BE%BE%E5%88%B0%E6%89%A9%E5%85%85%E6%95%B0%E6%8D%AE%E9%9B%86%E7%9A%84%E6%95%88%E6%9E%9C.
7.word2vec是如何工作的？它和隐狄利克雷模型有什么联系和区别？
https://blog.csdn.net/qq_29678299/article/details/88727380
https://zhuanlan.zhihu.com/p/133876076
第2章 模型评估
8.准确率的局限性
https://blog.csdn.net/qq_29678299/article/details/88732290
https://blog.csdn.net/weixin_42080490/article/details/108897318?spm=1001.2101.3001.6650.2&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-2-108897318-blog-88732290.235%5Ev38%5Epc_relevant_sort_base1&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-2-108897318-blog-88732290.235%5Ev38%5Epc_relevant_sort_base1&utm_relevant_index=5
https://zhuanlan.zhihu.com/p/425652214
9.精确率与召回率的权衡
https://zhuanlan.zhihu.com/p/369936908#:~:text=%E7%B2%BE%E7%A1%AE%E7%8E%87%E5%92%8C%E5%8F%AC%E5%9B%9E%E7%8E%87%E4%BA%92%E7%9B%B8%E5%BD%B1%E5%93%8D%EF%BC%8C%E7%90%86%E6%83%B3%E7%8A%B6%E6%80%81%E4%B8%8B%E8%82%AF%E5%AE%9A%E8%BF%BD%E6%B1%82%E4%B8%A4%E4%B8%AA%E9%83%BD%E9%AB%98%EF%BC%8C%E4%BD%86%E6%98%AF%E5%AE%9E%E9%99%85%E6%83%85%E5%86%B5%E6%98%AF%E4%B8%A4%E8%80%85%E7%9B%B8%E4%BA%92%E2%80%9C%E5%88%B6%E7%BA%A6%E2%80%9D%EF%BC%9A%20%E8%BF%BD%E6%B1%82%E7%B2%BE%E7%A1%AE%E7%8E%87%E9%AB%98%EF%BC%8C%E5%88%99%E5%8F%AC%E5%9B%9E%E7%8E%87%E5%B0%B1%E4%BD%8E%EF%BC%9B%E8%BF%BD%E6%B1%82%E5%8F%AC%E5%9B%9E%E7%8E%87%E9%AB%98%EF%BC%8C%E5%88%99%E9%80%9A%E5%B8%B8%E4%BC%9A%E5%BD%B1%E5%93%8D%E7%B2%BE%E7%A1%AE%E7%8E%87%20%E3%80%82%20%E6%88%91%E4%BB%AC%E5%BD%93%E7%84%B6%E5%B8%8C%E6%9C%9B%E9%A2%84%E6%B5%8B%E7%9A%84%E7%BB%93%E6%9E%9C%E7%B2%BE%E7%A1%AE%E7%8E%87%E8%B6%8A%E9%AB%98%E8%B6%8A%E5%A5%BD%EF%BC%8C%E5%8F%AC%E5%9B%9E%E7%8E%87%E8%B6%8A%E9%AB%98%E8%B6%8A%E5%A5%BD%EF%BC%8C%20%E4%BD%86%E4%BA%8B%E5%AE%9E%E4%B8%8A%E8%BF%99%E4%B8%A4%E8%80%85%E5%9C%A8%E6%9F%90%E4%BA%9B%E6%83%85%E5%86%B5%E4%B8%8B%E6%98%AF%E7%9F%9B%E7%9B%BE%E7%9A%84%E3%80%82%20%E8%BF%99%E6%A0%B7%E5%B0%B1%E9%9C%80%E8%A6%81%E7%BB%BC%E5%90%88%E8%80%83%E8%99%91%E5%AE%83%E4%BB%AC%EF%BC%8C%E6%9C%80%E5%B8%B8%E8%A7%81%E7%9A%84%E6%96%B9%E6%B3%95%E5%B0%B1%E6%98%AFF-score%E3%80%82%20%E4%B9%9F%E5%8F%AF%E4%BB%A5%E7%BB%98%E5%88%B6%E5%87%BAP-R%E6%9B%B2%E7%BA%BF%E5%9B%BE%EF%BC%8C%E8%A7%82%E5%AF%9F%E5%AE%83%E4%BB%AC%E7%9A%84%E5%88%86%E5%B8%83%E6%83%85%E5%86%B5%E3%80%82%20F_,%281%2Bbeta%5E2%29frac%20%7BPrecision%20cdot%20Recall%7D%20%7Bbeta%5E2%20cdot%20Precision%2BRecall%7D%20F-Score%EF%BC%9A%E6%9D%83%E8%A1%A1%E7%B2%BE%E7%A1%AE%E7%8E%87%EF%BC%88Precision%EF%BC%89%E5%92%8C%E5%8F%AC%E5%9B%9E%E7%8E%87%EF%BC%88Recall%EF%BC%89%EF%BC%8C%E4%B8%80%E8%88%AC%E6%9D%A5%E8%AF%B4%E5%87%86%E7%A1%AE%E7%8E%87%E5%92%8C%E5%8F%AC%E5%9B%9E%E7%8E%87%E5%91%88%E8%B4%9F%E7%9B%B8%E5%85%B3%EF%BC%8C%E4%B8%80%E4%B8%AA%E9%AB%98%EF%BC%8C%E4%B8%80%E4%B8%AA%E5%B0%B1%E4%BD%8E%EF%BC%8C%E5%A6%82%E6%9E%9C%E4%B8%A4%E4%B8%AA%E9%83%BD%E4%BD%8E%EF%BC%8C%E4%B8%80%E5%AE%9A%E6%98%AF%E6%9C%89%E9%97%AE%E9%A2%98%E7%9A%84%E3%80%82
https://blog.csdn.net/qq_15698613/article/details/97791756
10.平方根误差的“意外”
https://blog.csdn.net/qq_29678299/article/details/88741966
https://qq1244180262.blog.csdn.net/article/details/100831604?spm=1001.2101.3001.6650.9&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-9-100831604-blog-88741966.235%5Ev38%5Epc_relevant_sort_base1&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7ERate-9-100831604-blog-88741966.235%5Ev38%5Epc_relevant_sort_base1&utm_relevant_index=18
11.什么是ROC曲线？
https://zhuanlan.zhihu.com/p/26293316
https://www.zhihu.com/question/390923141
https://zhuanlan.zhihu.com/p/616190701
https://zhuanlan.zhihu.com/p/53015815
12.为什么要进行在线A/B测试
  .......
