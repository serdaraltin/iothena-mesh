```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/bad-words'
sortWeight = 4000000
id = '6b7dfa18-3bc3-468c-9a86-124040dc581b'

[body]
type = 'JSON'
raw = '''
{
  "priority": "medium",
  "word": "test",
  "match": "{test2,test3,tessss4}",
}'''
```
