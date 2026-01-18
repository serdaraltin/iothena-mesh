```toml
name = 'device'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/notifications/device'
sortWeight = 1000000
id = '2e90132e-096c-4c6c-b56d-c99d516c2cb1'

[body]
type = 'JSON'
raw = '''
{
  "device_uuid": "4f5b8c6b-cde9-42ab-9e24-e30336a59b56",
  "type": "warning",
  "priority": "medium",
  "title": "Device low batterry!",
  "message": "Device battery service stopped.",
}'''
```
