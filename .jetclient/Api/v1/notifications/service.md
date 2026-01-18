```toml
name = 'service'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/notifications/service'
sortWeight = 3000000
id = '2d62a394-a65a-43ae-a7fb-b7cfcd554eaf'

[body]
type = 'JSON'
raw = '''
{
  "slug": "database",
  "type": "info",
  "priority": "low",
  "title": "Database cache cleaned",
  "message": "Database service cache data cleaned"
}
'''
```
