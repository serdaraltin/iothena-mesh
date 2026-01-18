```toml
name = 'store'
method = 'POST'
url = 'http://0.0.0.0:8000/api/v1/devices/notifications'
sortWeight = 2500000
id = '623d9617-f6dd-4def-a672-14520d33fe6a'

[body]
type = 'JSON'
raw = '''
{
  "device_id": 1,
  "type": "info",
  "priority": "low",
  "title": "Device Started",
  "message": "The device has been successfully started.",
  "delivered": false,
}'''
```
