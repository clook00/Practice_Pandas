# Practice_Pandas

df = pd.DataFrame(dict)

df.index = ["BR", "RU", "IN", "CH", "SA"]
df

df['country']

df[['country']]

df[['country', 'area']]

df[0:4]

df[3:5]

df.iloc[2]

df.loc[['IN','CH'],['area','population']]

grades=pd.read_csv("Lectures/15_Grades.csv")
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
