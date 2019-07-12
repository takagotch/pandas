### pandas
---
https://pandas.pydata.org/
http://pandas.pydata.org/

https://github.com/pandas-dev/pandas

```sh
conda intall pandas
pip install pandas

pip install cython
python setup.py install
python setup.py develop
pip install -e .
```

```py
index = pd.date_range('1/1/2000', periods=8)

s = pd.Series(np.random.randh(5), index=['a', 'b', 'c', 'd', 'e'])

df = pd.DataFrame(np.random.randh(8, 3), index=index,
  columns=['A', 'B', 'C'])
  
wp = pd.Panel(np.random.randh(2, 5, 4), items=['Item1', 'Item2'],
  major_axis=pd.date_range('1/1/2000', periods=5),
  minor_axis=['A', 'B', 'C', 'D'])

```

```
```


