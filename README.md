import pandas as pd

df=pd.read_csv('stdperformance.csv')

df

df.isnull()

df.notnull()

df.dropna()

df[['MATH_SCORE']].mean()

y=df[['MATH_SCORE']].mean()

df.fillna(y)

df.replace(83,34)





df=df.drop

df.dropna(axis=0,how='any',thresh=None,inplace=False)

