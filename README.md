# Titanic_machine_learning
**使用机器学习方法对泰坦尼克号数据进行训练与预测**  
- 根据人名Name，使用正则表达式提取称呼Title  
- 利用SibSp和Parch，创建新的变量FamilySize和IsAlone  
- 从Cabin中提取第一个字符为Cabin_id  
- 使用随机森林方法，对缺失的Embarked、Cabin_id和Age进行填充  
- 对Age和Fare分bin  
- 对Category特征(Embarked, Cabin_id, Sex, Title)进行factorize(使用pandas的get_dummies)  
- 利用上述特征使用决策树进行训练与预测  
