```toml
name = 'update'
method = 'PUT'
url = 'http://0.0.0.0:8000/api/v1/devices/notifications'
sortWeight = 3000000
id = '0c20562e-4e20-438e-be5d-d9257ed1de2d'

[body]
type = 'JSON'
raw = '''
{
  "id": 20,
  "device_id": 1,
  "type": "warning",
  "priority": "high",
  "title": "test",
  "message": "test2",
  "delivered": false,
}'''
```
