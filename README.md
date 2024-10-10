import pandas as pd
import seaborn as sns

path=('/content/drive/MyDrive/Data set/Data_set.csv')
df=pd.read_csv(path)
df

df_null=df.isnull()
df_null

df_drop=df.dropna()
df_drop
