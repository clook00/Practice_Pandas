# Practice_Pandas

1) df = pd.DataFrame(dict)

2) df.index = ["BR", "RU", "IN", "CH", "SA"]
df

3) df['country']

4) df[['country']]

5) df[['country', 'area']]

6) df[0:4]

7) df[3:5]

8) df.iloc[2]

9) df.loc[['IN','CH'],['area','population']]

10) grades=pd.read_csv("Lectures/15_Grades.csv")
grades.head()
list(grades.columns)
list(grades.index)
grades.shape
grades.dtypes
grades['Grade'].unique()
grades['Grade'].nunique()
grades_grouped = grades.groupby('Grade')
grades_grouped.mean()
grades_grouped.min()
grades_grouped.max()
grades_grouped.describe()
