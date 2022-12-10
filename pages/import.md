---
layout: default
title: Import data
nav_order: 2
child_nav_order: desc
---

# How do I import data?

Well, pandas gives us several different ways to import our data.
In this tutorial we will focus on the `read_json` method. But there are several more.

```py
import pandas as pd

df = pd.read_json('tagesschau.json')
```

`df` stands for data frame which is a pandas object. When we want to view or manipulate our data we will use this `df` object.

Additional ways to import data

```py
# import csv file
pd.read_csv('file.csv')

# import html file
pd.read_html('file.csv')

# import excel file
pd.read_excel('file.xlsx')
```

These are additional methods to import data. For more information follow the link.

(`read_csv`)[https://pandas.pydata.org/docs/reference/api/pandas.read_excel.html]
