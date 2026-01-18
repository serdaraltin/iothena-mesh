```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/bad-words'
sortWeight = 3000000
id = '0165bfd8-55e8-46cc-9c9b-4272c19ed64c'

[body]
type = 'JSON'
raw = '''
{
  "priority": "low",
  "word": "test",
  "match": "{test,test,tessss}",
}'''
```
