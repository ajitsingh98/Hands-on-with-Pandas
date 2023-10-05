# Hands-On-With-Pandas
`Begineer Friendly Pandas Tutorial`

## Contents

Introduction
---
Creating and Viewing DataFrames and Series:
--
  - pd.DataFrame()
  - pd.Series()
  - df.head()
  - df.tail()
  - df.shape
  - df.dtypes
  - df.sample()

Data Aggregation and Statistics:
---
  - df.sum()
  - df.mean()
  - df.median()
  - df.max()
  - df.min()
  - df.count()
  - df.nunique()
  - df.info()
  - df.describe()
  - df.value_counts()

Indexing and Selection:
---
  - df['column_name']
  - df.column_name
  - df[['column_name']]
  - df.loc[row_label]
  - df.iloc[row_index]
  - df[df['column'] > value]
  - df[mask]
  - df.ix[]
  - df.where()
  - df.query()
  - df.isin()

Data Manipulation:
---
  - df.drop()
  - df.rename()
  - df.sort_values()
  - df.groupby()
  - df.get_group()
  - df['a'].astype('data_type')
  - df.set_index()
  - df.reset_index()
  - del df['col']
  - df.agg()
  - df.map()
  - df.rank()

Missing Data Handling:
---
  - df.isna()
  - df.dropna()
  - df.fillna()
  - df.isnull()
  - df.notnull()
    
Data Cleaning and Transformation:
---
  - df.apply()
  - df.replace()
  - df.duplicated()
  - df.drop_duplicates()

Merging and Joining DataFrames:
---
  - pd.concat()
  - pd.merge()
  - pd.join()

Working with Dates and Times:
---
  - pd.to_datetime()
  - df.resample()

Data Visualization:
---
  - df.plot()
  - df.hist()
  - df.boxplot()

IO Operations:
---
  - pd.read_csv()
  - pd.read_excel()
  - df.to_csv()
  - df.to_excel()
