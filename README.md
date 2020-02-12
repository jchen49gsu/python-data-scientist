# python-data-scientist
## use python to handle data related

1. The format of JSON file is with double quotes
2. validate JSON can use website:  https://jsonlint.com/
```
Valid JSON format: 
  test1 = {"a":"tex't1", "b": "text2"}
  test2 = {"a":"tex\"t1", "b": "text2"}  #not valid if not using backspace test2 = {"a":"tex"t1", "b": "text2"}
```
3. from str to dict json.loads(), from dict to str json.dumps()
4.  

```python
#https://dataideas.blog/2018/10/09/loading-json-it-looks-simple-part-1/ 
#can use json.loads() change str to dict
test1 = {"a":"tex't1", "b": "text2"}
test2 = {'a':'tex\"t1', 'b': 'text2'}
import pandas
from pandas.io.json import json_normalize
json_normalize(test1)
json_normalize(test2)
```


