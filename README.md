import pandas as pd
df = pd.read_csv('fake_news.csv')
df.info()
df.isnull().sum()
df.duplicated().sum()
