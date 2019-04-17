# Titanic_machine_learning
**使用机器学习方法对泰坦尼克号数据进行训练与预测**  
## Load and read the data
## Define exploratory data analysis functions (free to skip this lengthy paragraph at first)
## Define transformer objects (free to skip this lengthy paragraph at first)
## Use these transformers to preprocess the data
- 根据人名Name，使用正则表达式提取称呼Title  
- 利用SibSp和Parch，创建新的变量FamilySize和IsAlone  
- 从Cabin中提取第一个字符为Cabin_id  
- 使用随机森林方法，对缺失的Embarked、Cabin_id和Age进行填充  
- 对Age和Fare分bin  
- 对Category特征(Embarked, Cabin_id, Sex, Title)进行factorize(使用pandas的get_dummies)  
## Use preprocessing and Ridge regression, gridsearch and crossvalidation to estimate the generalization performance
## Under the assumption, that the gridsearch parameters are stable between cross validation folds, retrain a model using gridsearch on all of the training data
## Further comments on additional transformers, next steps and references
