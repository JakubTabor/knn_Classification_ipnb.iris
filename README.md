# knn_Classification_ipnb.iris
# First i save my iris data "iris = load_iris()", then I check "feature_names" """iris.feature_names"""
# Next I load my data into columns and save it as "df" """df = pd.DataFrame(iris.data, columns=iris.feature_names)""" and I check the shape """df.shape"""
# Then I create new column "target" """df['target']= iris.target""" and I check how my "target1" look like and also "target2"
# I have my "target" column, so I can create column "flower_name" using my "target" """df['flower_name'] = df.target.apply(lambda x : iris.target_names[x])"""
# I create (3) "df" with my different "flower_name" (form 0 to 50, from 50 to 100, form 100 to 150) 
# Next I visualize my data use "%matplotlib inline", using "df0" and "df1" and column "sepal length " and "sepal width"
